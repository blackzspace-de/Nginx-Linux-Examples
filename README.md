# Nginx-Linux-Examples


```
Auhtor: BlackLeakz

Description: This are example nginx-sites configurations for different usages! This documentaion will growth with time. I hope you find Answeres for your Questions about how to configuring nginx-sites! If you have any questions, contact us/me on discord or e-mail!
All these examples arent converted by certbot. In the following Steps you will learn how to convert the nginx-sites into a SSL-Secured Site by using CERTBOT! 


Beschreibung; Dies sind beispielhafte NGINX-Seiten Konfigurationen für Standartnutzung , nutzung mit erweiterungen wie PHP oder Proxy_Pass nutzung! Ich/WIr hoffen diese Beispiele helfen euch weiter! Bei Fragen, kontaktier und/mich auf Discord oder per E-MAIL!
All diese Beispiele sind nich mit Certbot konvertiert und sind daher nicht mit SSL gesichert, wie dies funktioniert lernt ihr in den nächsten Schritten auf dieser Seite. Mit der Zeit wir dieses Nginx-Konfigurationshandbuch wachsen, bitte habt noch ein wenig gedult!
```


# How to convert nginx-sites to a ssl-secured site: || Wie konvertier ich eine Nginx-Seite in eine SSL- gesicherte Seite?!!

```
Use one of the unconverted examples comparing to this your usage!

in example, we use "default_primitve.conf".

create the config-file in /etc/nginx/sites-available/your_domain.conf with your personal details! (Edit the example)
Execute: ln -s /etc/nginx/sites-available/your_domain.conf /etc/nginx/sites-enabled
Execute: nginx -t  || to test if working!
Now Execute: certbot --nginx -d subdomain.domain.domainending || customize domain-name
```