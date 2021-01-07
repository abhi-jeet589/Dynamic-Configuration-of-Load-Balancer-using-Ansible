# Dynamic-Configuration-of-Load-Balancer-using-Ansible
The configuration of Load balancer is much of a tedious task. Making changes in the config file manually might lead to human errors. This playbook will help you to configure the load balancer dynamically when the instance joins the inventory. The load balancer used in this playbook is HAProxy.
<h2> How to use this Playbook </h2>
<p> To use this Playbook clone this repository to your directory <p>
<p> After cloning you have the ability to change the frontend port number , backend port number and the document root <p>
<h2>Note:</h2><p>I have used a iso file containing all the packages. You can use epel release to configure the yum</p>
