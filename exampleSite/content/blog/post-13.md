---
title: 'apache2.service: Control process exited, code=exited, status=139/n/a'
date: 2022-10-21T04:07:47+00:00
image: images/post/post-3.jpg
description: this is meta description
categories:
- Apache2
- " PHP"
tags:
- New
- Apache2
type: post

---
# After ubuntu upgrade to 22.04 apache2 was broken

### Error - apache2.service: Control process exited, code=exited, status=139/n/a

## Solution - 

### $ cd /etc/apache2/  
  
$ l mods-*/php*

#### The "status=139" error must have something to do with having multiple, conflicting versions of PHP enabled.

  
In my case, it was showing php7.4 and php8.1 both.

### $ sudo a2dismod php7.4

### $ systemctl restart apache2

![apache2 issue](/uploads/screenshot-from-2022-10-21-18-25-06.png "fixing broken apache2")