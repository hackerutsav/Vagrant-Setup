This repo contains all the initial requirements for getting started out Vagrant.

Vagrant provides easy to configure, reproducible, and portable work environments built on top of standard technology to provide a consistent environment for everybody in the team.


How to get started 

1)Install dependencies                                   

--->Download the latest virtualbox (http://goo.gl/jVyTwu)

--->Download the latest Vagrant (http://goo.gl/OKfM1T)

2)Clone the project to get started

---> git clone https://github.com/hackerutsav/Vagrant-Setup

----> cd Vagrant

3)Getting Started

3.1 For starting up vagrant.This triggers the downlaod of presetup Vagrant image first time and relaunching the setup next time  

---> Vagrant up

3.2 For connecting to the virtual machine

---> vagrant ssh

4)Sharing

---> To use HTTP sharing, simply run vagrant share

---> For sharing ssh, run vagrant share --ssh     (Anyone can then SSH directly to your Vagrant environment by running vagrant connect --ssh NAME where NAME is the name of the share outputted when running this command.)



This should get you up started with vagrant.

If any problem arises you can ...

1)Vagrant halt (for shutting down the environment)

2)Vagrant destroy (for totally removing the environment)

3)Vagrant suspend (For suspending the environment)

Any suggestion for improving  or contributing with the development is always welcome!

Have fun with Vagrant!
