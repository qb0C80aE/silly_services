# DocherHub Image Downloader

It enables you to download archived docker images from dockerhub. 

ex.

```
$ curl https://imgdl.mybluemix.net/ubuntu:latest > ubuntu.tgz
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 24.6M    0 24.6M    0     0  24.1M      0 --:--:--  0:00:01 --:--:-- 24.2M
$ tar ztvf ubuntu.tgz
drwxr-xr-x root/root         0 2020-01-13 06:10 bin/
-rwxr-xr-x root/root   1113504 2019-06-07 07:28 bin/bash
-rwxr-xr-x root/root     34888 2019-07-04 21:35 bin/bunzip2
hrwxr-xr-x root/root         0 2019-07-04 21:35 bin/bzcat link to bin/bunzip2
lrwxrwxrwx root/root         0 2019-07-04 21:35 bin/bzcmp -> bzdiff
-rwxr-xr-x root/root      2140 2019-07-04 21:35 bin/bzdiff
lrwxrwxrwx root/root         0 2019-07-04 21:35 bin/bzegrep -> bzgrep
-rwxr-xr-x root/root      4877 2019-07-04 21:35 bin/bzexe
lrwxrwxrwx root/root         0 2019-07-04 21:35 bin/bzfgrep -> bzgrep
-rwxr-xr-x root/root      3642 2019-07-04 21:35 bin/bzgrep
hrwxr-xr-x root/root         0 2019-07-04 21:35 bin/bzip2 link to bin/bunzip2
-rwxr-xr-x root/root     14328 2019-07-04 21:35 bin/bzip2recover
lrwxrwxrwx root/root         0 2019-07-04 21:35 bin/bzless -> bzmore
-- snip --
```

It's running on IBM Cloud. Because the account used there is Lite, it might reach the monthly limit, and also the at first use time it will take a little while to download.

# Text to Binary

```
$ curl "https://texttobinary.herokuapp.com/proxyart?bg=0&fg=1&size=10&text=JOBHUNTING"
00000000000000000000000000000000000000000000000000
00000000000000000000000000000000000000000000000000
00010011001110010010100101001011111001001001001100
00010100101001010010100101101000100001001101010010
00010100101001010010100101101000100001001101010000
00010100101110011110100101101000100001001101010110
10010100101001010010100101011000100001001011010010
10010100101001010010100101011000100001001011010010
01100011001110010010011001001000100001001001001110
00000000000000000000000000000000000000000000000000
00000000000000000000000000000000000000000000000000
```

