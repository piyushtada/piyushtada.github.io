---
layout: post
title: github gpg failed to sign the data
---

I was having this problem with this for a long time tryed different things, but nothing worked but found some good posts that you can use:

[github gpg failed to sign the data](https://removeif.github.io/develop/github-gpg-failed-to-sign-the-data.html) this is a very good written example. 


If it does not work and it tells you that it cannot find the gpg2 program, then you need to setup the github config file.

git config --global gpg.program /usr/local/bin/gpg 

^^^^
here you need to make sure that when you install gpg2, you need to make note of path where it stored the program. Then you need to write this path.

[GPG2 (GnuGP 2) Guide](https://docs.releng.linuxfoundation.org/en/latest/gpg.html) this provide you with a detailed description of how to generate a gpg key and set up the program.

