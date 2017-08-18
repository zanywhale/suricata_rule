# suricata_rule
suricata.rules

* "http://www." rules
* "http://" rules
* "http://~~~/[PATH]" rules
* "https://" rules
* "https://~~~/[PATH]" cannot make rule...

http://
```sh
08/17/2017-23:00:22.034754  [**] [1:1001:1] hitomi.la rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:34180 -> 88.80.20.11:80
08/17/2017-23:00:31.214687  [**] [1:1002:1] kass.org.kp rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:37980 -> 175.45.176.81:80
08/17/2017-23:00:31.529334  [**] [1:1002:1] kass.org.kp rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:37982 -> 175.45.176.81:80
08/17/2017-23:00:39.982082  [**] [1:1004:1] ks8282.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:39878 -> 54.65.82.252:80
08/17/2017-23:00:59.024222  [**] [1:1005:1] naevr.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:56696 -> 67.227.226.241:80
08/17/2017-23:01:07.894665  [**] [1:1006:1] naver6.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:37806 -> 185.53.178.9:80
08/17/2017-23:02:20.041331  [**] [1:1009:1] rodong.rep.kp rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:46158 -> 175.45.176.68:80
08/17/2017-23:04:04.338929  [**] [1:1020:1] sk386.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:60572 -> 222.231.2.128:80
08/17/2017-23:04:44.049276  [**] [1:1011:1] 4shared.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:52064 -> 204.155.149.43:80
08/17/2017-23:04:51.879925  [**] [1:1014:1] kimmadam.net rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:39204 -> 175.125.23.115:80
08/17/2017-23:05:01.694572  [**] [1:1015:1] minjok.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:35312 -> 74.208.236.254:80
08/17/2017-23:05:07.271842  [**] [1:1016:1] narutoxxx.com rule! [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:42518 -> 208.91.197.194:80
...
```

http://~~~/[PATH]
```sh
08/17/2017-23:14:17.824946  [**] [1:1025:1] linoit.com/users/men1212/canvases/19%EA%B8%88%20 rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:53880 -> 52.8.206.111:80
08/17/2017-23:19:44.493375  [**] [1:1026:1] named.com/game/ladder/v2_index.php rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:51284 -> 198.41.208.129:80
08/17/2017-23:23:34.297483  [**] [1:1027:1] kitribob.wiki/wiki rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:47268 -> 104.28.27.243:80
08/17/2017-23:23:45.273524  [**] [1:1028:1] snoopspy.com/download rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:42190 -> 61.73.111.238:80
08/17/2017-23:24:11.460203  [**] [1:1029:1] test.gilgil.net & .mp4 fitest.gilgille rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:42202 -> 61.73.111.238:80
08/17/2017-23:27:28.444678  [**] [1:1030:1] www.ilbe.com/ilbe [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:43770 -> 141.101.121.208:80
08/17/2017-23:24:39.764884  [**] [1:1031:1] www.winclub88.net/my/4D.html [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:58372 -> 104.27.184.156:80
```

https://
```sh
08/17/2017-23:33:26.676172  [**] [1:1032:1] mujige53770.wixsite.com rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181
.170:37054 -> 52.20.141.132:80
08/17/2017-23:33:39.878807  [**] [1:1033:1] graphgame.net rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:58510
 -> 104.18.38.97:80
08/17/2017-23:33:44.204033  [**] [1:1034:1] sex.com rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:39318 -> 20
6.125.164.82:80
08/17/2017-23:34:07.345236  [**] [1:1036:1] torrentkim10.net rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:57170 -> 104.27.145.154:80
08/17/2017-23:34:17.218940  [**] [1:1037:1] webtoon.bamtoki.com rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:55748 -> 104.20.188.49:80
08/17/2017-23:34:28.004154  [**] [1:1038:1] www.mtbucks.com rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:40250 -> 104.27.150.234:80
08/17/2017-23:34:36.604791  [**] [1:1039:1] www.phishtank.com rule [**] [Classification: (null)] [Priority: 3] {TCP} 192.168.181.170:59878 -> 146.112.225.22:80
```

https://~~~/[PATH]
```sh
......
```
