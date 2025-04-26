+++
title = 'How to install Nginx on Ubuntu Server'
date = 2025-04-26T21:25:50+03:00
draft = false
description = ""
image = "https://nginxblog-8de1046ff5a84f2c-endpoint.azureedge.net/blobnginxbloga72cde487e/wp-content/uploads/2024/10/Celebrating-20-Years-of-NGINX.png"
imageBig = "https://nginxblog-8de1046ff5a84f2c-endpoint.azureedge.net/blobnginxbloga72cde487e/wp-content/uploads/2024/10/Celebrating-20-Years-of-NGINX.png"
categories = ["HowTO","Nginx", "Coding"]
authors = ["Martin Negin"]
avatar = "/images/avatar.jpg"
+++

## Introduction

Nginx is one of the most popular web servers in the world and is responsible for hosting some of the largest and highest-traffic sites on the internet. It is a lightweight choice that can be used as either a web server or reverse proxy.

In this guide, we’ll discuss how to install Nginx on your Ubuntu server, adjust the firewall, manage the Nginx process, and set up server blocks for hosting more than one domain from a single server.

## Step 1 – Installing Nginx

Because Nginx is available in Ubuntu’s default repositories, it is possible to install it from these repositories using the apt packaging system.

Since this is our first interaction with the apt packaging system in this session, we will update our local package index so that we have access to the most recent package listings. Afterwards, we can install nginx:

```sh
sudo apt update
sudo apt install nginx

Nginx image by blog.nginx.org 