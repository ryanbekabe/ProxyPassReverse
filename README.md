# ProxyPassReverse
Laragon Apache and Nginx - Ryan Bekabe - bekabeipa@gmail.com

Port Forward Work: ssh -i ec2sgneo.pem -g -R 8000:127.0.0.1:8000 ubuntu@52.221.190.108

ssh -i ec2sgneo.pem ubuntu@3.1.202.230
ssh -i ec2sgneo.pem -R 8000:127.0.0.1:8000 ubuntu@3.1.202.230
ssh -i ec2sgneo.pem -L 8080:127.0.0.1:80 bitnami@18.139.227.196
ssh -i ec2sgneo.pem -g -R 8000:127.0.0.1:8000 ubuntu@52.221.190.108
ssh -N -L 8090:127.0.0.1:8080 usbigdata@123.72.214.65
ssh -R 8000:127.0.0.1:8000 rootdebian@52.163.51.108
ssh -v -R 8000:localhost:8000 ubuntu@52.221.190.108 -i ec2sgneo.pem
ssh rootdebian@52.187.146.136

/etc/ssh/sshd_config
GatewayPorts yes
ForwardAgent yes
ForwardX11 yes
