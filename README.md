# meowna
Uma aplicação web propositalmente vulnerável para você ownar

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/ismael0liveira/meowna/blob/main/LICENSE)

## Sobre o Projeto

meOwna foi desenvolvido pensando na comunidade de Cibersegurança, para contribuir com estudantes ou profissionais da área que desejam aprimorar suas habilidades em web hacking ou até mesmo utilizar este ambiente para fins didáticos. Neste laboratório de estudos você encontra livros, referências de aprendizagem, termos técnicos, tutoriais e muitas vulnerabilidades para explorar como XSS - Cross-Site Scripting, IDOR - Insecure Direct Object Reference, SSRF - Server-Side Request Forgery, CSRF - Cross-Site Request Forgery, LFI - Local File Inclusion, dentre outras.

![Página inicial de meOwna](https://github.com/ismael0liveira/meowna/blob/main/assets/owna1.png)

## Vulnerabilidades e ataques que você pode aprender e explorar neste laboratório:

* XSS - Cross-Site Scripting  
* CSRF - Cross-Site Request Forgery  
* SSRF - Server-Side Request Forgery  
* IDOR - Insecure Direct Object Reference  
* LFI - Local File Inclusion  
* RFI - Remote File Inclusion
* LFD - Local File Download
* BLH - Broken Link Hijacking
* No Rate Limit  
* OS Command Injection  
* Open Redirect
* Unrestricted File Upload
* Tabnabbing
* Clickjacking
* HTML Injection
* Information Disclosure
* Outros...

## Passos para Instalação:

```bash
apt install apache2
apt install php
nano php.ini #(configure allow_url_fopen = On  e allow_url_include = On)
cd /var/www/html
mv /home/user/Downloads/meowna.zip .
unzip meowna.zip
cd meOwna
service apache2 start
#acesse http://localhost  
```
## Sobre o autor

Ismael Oliveira

https://www.linkedin.com/in/ismaeloliveirapro/  
https://www.instagram.com/1smaeloliveira/  
https://www.facebook.com/Isma520liveira/  

Formming Hackers  
  
https://formminghackers.com  
https://www.instagram.com/formminghackers/  
https://www.facebook.com/formminghackers  
https://www.youtube.com/@FORMMINGHACKERS  


