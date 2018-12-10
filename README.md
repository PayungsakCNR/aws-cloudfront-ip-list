# aws-cloudfront-ip-list
This is AWS Cloudfront Edge Server IP list for nginx web server.

How to use

1.Download .conf file to /etc/nginx/
2.in your virtual server conf,please add 

include aws-cloudfront-ip-list.conf;

3.If you want to permit only Source ip from AWS Cloudfront please add

deny all;

to below include aws-cloudfront-ip-list.conf;

(I suggest you to permit only AWS Cloudfront Source IP)

Have a good day!

PaOv6
Payungsak Klinchampa
pao@paov6.network , pao@payungsakpk.xyz
www.payungsakpk.xyz
