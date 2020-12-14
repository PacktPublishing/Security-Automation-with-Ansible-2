## $5 Tech Unlocked 2021!
[Buy and download this Book for only $5 on PacktPub.com](https://www.packtpub.com/product/security-automation-with-ansible-2/9781788394512)
-----
*If you have read this book, please leave a review on [Amazon.com](https://www.amazon.com/gp/product/1788394518).     Potential readers can then use your unbiased opinion to help them make purchase decisions. Thank you. The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# Security Automation with Ansible 2
This is the code repository for [Security Automation with Ansible 2](https://www.packtpub.com/virtualization-and-cloud/security-automation-ansible-2?utm_source=github&utm_medium=repository&utm_campaign=9781788394512), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Security automation is one of the most interesting skills to have nowadays. Ansible allows you to write automation procedures once and use them across your entire infrastructure. This book will teach you the best way to use Ansible for seemingly complex tasks by using the various building blocks available and creating solutions that are easy to teach others, store for later, perform version control on, and repeat.

We’ll start by covering various popular modules and writing simple playbooks to showcase those modules. You’ll see how this can be applied over a variety of platforms and operating systems, whether they are Windows/Linux bare metal servers or containers on a cloud platform. Once the bare bones automation is in place, you’ll learn how to leverage tools such as Ansible Tower or even Jenkins to create scheduled repeatable processes around security patching, security hardening, compliance reports, monitoring of systems, and so on.

Moving on, you’ll delve into useful security automation techniques and approaches, and learn how to extend Ansible for enhanced security. While on the way, we will tackle topics like how to manage secrets, how to manage all the playbooks that we will create and how to enable collaboration using Ansible Galaxy. In the final stretch, we’ll tackle how to extend the modules of Ansible for our use, and do all the previous tasks in a programmatic manner to get even more powerful automation frameworks and rigs.

## Instructions and Navigation
All of the code is organized into folders. For example, Chapter02.



The code will look like the following:
```
- name: update the hardened nginx configuration changes
template:
src: "hardened-nginx-config.j2"
dest: "/etc/nginx/sites-available/default"
notify:
- restart nginx
```

Ansible is a tool written in Python2. For control machines, if Python2 is installed with the minimum version 2.6, you are good to go. Since Ansible 2.2 onwards, Python3 is supported as a tech preview.

## Related Products
* [Ansible 2: Advancements with Security Automation [Video]](https://www.packtpub.com/networking-and-servers/ansible-2-advancements-security-automation-video?utm_source=github&utm_medium=repository&utm_campaign=9781788478847)

* [Getting Started with Ansible 2 Security Automation [Video]](https://www.packtpub.com/virtualization-and-cloud/getting-started-ansible-2-security-automation-video?utm_source=github&utm_medium=repository&utm_campaign=9781788390378)

* [Containerization with Ansible 2](https://www.packtpub.com/virtualization-and-cloud/containerization-ansible-2?utm_source=github&utm_medium=repository&utm_campaign=9781788291910)

