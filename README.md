# rpi-kube-wordpress
A Kubernetes Wordpress project for Raspberry PI

This project is to showcase how to setup MariaDB (https://mariadb.com/), Wordpress (https://wordpress.org/), RaspberryPi (https://www.raspberrypi.org/), *Metallb (https://metallb.universe.tf/), 
K3S (https://k3s.io/), and **Rancher (https://rancher.com/).

This is a work in effort to creating a Wordpress HA setup for my website, rolandcraddolph.com,  that I am hosting myself. :)

This work is following this guide from MariaDB as a base - https://mariadb.org/mariadb-k8s-deploy-mariadb-and-wordpress-using-persistent-volumes/

* Metallb is not really needed if you want to use the default tools for loadbalancers in Kubernetes, but using Metallb to use IPs on my local network is great and a good way to expose oneself to learning more about networking.
* Rancher is not really needed but useful when you are tired of typing kubectl .... and just want a visual of what is going on
