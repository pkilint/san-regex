# san-regex
A regular expression to validate domainName &amp; wildcard &amp; iPAddress.


## Tests

| Sample        	| Reliality Valid or not 	| Assert 	|   	|   	|
|---------------	|------------------------	|--------	|---	|---	|
| www.baidu.com 	|  ![](/.docs/success.svg)	|        	|   	|   	|
| *.baidu.com       | ![](/.docs/success.svg)                       	|        	|   	|   	|
| 1.1.1.1           | ![](/.docs/success.svg)                       	|        	|   	|   	|
| ::1               | ![](/.docs/success.svg)                       	|        	|   	|   	|
| 1:2:3:4:5:6:7:8   | ![](/.docs/success.svg)                       	|        	|   	|   	|
| xn--6qq79v.xn--fiqs8s | ![](/.docs/success.svg)                       	|        	|   	|   	|
| *.xn--6qq79v.xn--fiqs8s   | ![](/.docs/success.svg)                       	|        	|   	|   	|
| a*.domain.com     |                        	|        	|   	|   	|
| a.*.domain.com    |                        	|        	|   	|   	|
| baidu.com.        |                        	|        	|   	|   	|
| .baidu.com        |                        	|        	|   	|   	|
| ::1:              |                        	|        	|   	|   	|
| :::1              |                        	|        	|   	|   	|
| 1:2:3:4:5:6:7:8*a.doamin.com               	|                        	|        	|   	|   	|
| 1:2:3:4:5:6:7:8:9 |                        	|        	|   	|   	|
| 你好.中国         |                        	|        	|   	|   	|
| http://www.baidu.com  |                        	|        	|   	|   	|
| .xn--6qq79v.xn--fiqs8s    |                        	|        	|   	|   	|
| *.xn--6qq79v.xn--fiqs8s.  |                        	|        	|   	|   	|
| *xn--6qq79v.xn--fiqs8s    |                        	|        	|   	|   	|
| www.*.xn--6qq79v.xn--fiqs8s   |                        	|        	|   	|   	|
