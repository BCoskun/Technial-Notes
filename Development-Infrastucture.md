# Network Tunniling from Dev Enviroments

SSH tunelling can be used to tunnel TCP traffic between systems but require proper network design and and not always easy. *ngrok* service can be used for quick local system tunnelling.
- https://ngrok.com/

When you need magic DNS Service without setup anything 

`scoop install bind`

`dig @ns-gce.sslip.io. 169-254-169-254.xip.example.com +short` 

`dig 169.254.169.254.nip.io +short`

- https://sslip.io/
- https://nip.io/

For local deployment localtls

https://github.com/Corollarium/localtls