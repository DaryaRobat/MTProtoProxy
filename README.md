# PHP-MTProtoProxy
[![Telegram Channel](https://img.shields.io/badge/Channel-Telegram-blue.svg)](https://t.me/VPN_And_Proxies)

High Performance PHP MTProto Proxy

# How To Use
Assign execute permissions

        chmod +x mtpproxy.php
 
Start the proxy, specifiying a secret seed and a port

        ./mtproxyd pony 6666
        
This will print the Secret text

Share the proxy, using the port, your IP and generated secret

Host: 163.172.167.189

Port: 6666

Secret: 4b3e3c2f99046f92a61bab6775848577

Quick link: https://t.me/proxy?server=163.172.167.189&port=6666&secret=4b3e3c2f99046f92a61bab6775848577

Protip: start the proxy in a screen session to keep it always running

# If have error on centos

Exception:

MadelineProto requires the xml extension to run. Try running sudo apt-get install php5.6-xml. in MadelineProto:1

PHP Fatal error:

Uncaught MadelineProto requires the xml extension to run. Try running sudo apt-get install php5.6-xml.

thrown in MadelineProto on line 1
  
Run:

        yum --enablerepo remi install php-xml
        service httpd restart

if can not run on php 5.6 change the php version

## License

MIT License

Copyright (c) 2018 PHP-MTPProxy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

