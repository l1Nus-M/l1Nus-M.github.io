---
title: Seting up my Cloud Securrity Lab on GCP, Azure and AWS.
date: 2026-02-13 10:07:00 +03:00
categories: [Cloud, Lab-setup, Azure, AWS, GCP]
tags: [ubuntu, nginx, gcp, aws, azure]
image:
  path: /assets/images/AWS-vs-MS-vs-GCP.jpg
  alt: A feature image for awsgcpazure

---
## Why I Built This Lab
To trully understand **Network Security**. I decided to move away from local VMs and Deploy dedicated environment on **GCP Azure & AWS**.
![Desktop View](/assets/images/AWS-Azure-GCP.jpg)
_This is the caption that appears under the image_

## The Architechture
I am currently running on **Ubuntu 32.04** instance named *lab1*. My goals for this setup include:

1: Configuring hhardened *Nginx* Reverse Proxy.

2: Managing access via *Custom SSH Ports* to reduce bruteforce noise.

3: Hosting my technical documentation (this blog!) via GitHub Pages.

### Lessons Learned
During this setup, I encountered issues with **Bitlocker** encrypted devices on my machine.

---
*Stay tuned for my next post*
