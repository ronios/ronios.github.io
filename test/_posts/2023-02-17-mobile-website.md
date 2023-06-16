---
layout: single
title:  "Mobile Website Development"
tags:
  - Development
---
### How I did it
After setting up my Proxmox Based home network lab with Cloudflare Tunnels, I decided to, out of boredom, see if I can code a website from an ssh session on my phone during my bus ride home!

Firstly, I connected to my ssh shell using Cloudflare's Tunnel technology. This feature requires a domain, but I had a few from [Freenom](https://freenom.com), so I was good with that. Through my phone I connected to Cloudflare Tunnels under the domain " sshkali.domain.com " (not mine for privacy reasons). Under this website I had access to a mobile supported shell which ran great. NOTE: to access this website, I required Cloudflare to use email 2FA, meaning I didn't have to worry about any intruders.

While inside of my Ubuntu Container, I simply downloaded the nginx software package, and created a simple website in the /var/www/html directory with the commands:

$ apt install nginx

$ nano /var/www/html/index.html

Once inside of nano, I typed the following text and succesfully created a simple web server on a bus ride home!

<img src="{{ site.url }}{{ site.baseurl }}/images/mobileshell.png" alt="" class="full" style="width:450px;">

>Here is the code without being cut off:
>
><img src="{{ site.url }}{{ site.baseurl }}/images/mobilehtmlcode.png" alt="" class="full">