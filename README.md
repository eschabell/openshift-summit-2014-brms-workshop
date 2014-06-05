Red Hat Summit 2014 JBoss BRMS Workshop
=======================================
This git repository helps you get up and running quickly with a 
Cloud hosted workshop on JBoss BRMS that gets you
started building your very own Cool Store retail webshop.

The web shop project will have you designing guided rules, technical rules, 
a decision table, a ruleflow, and deploying a Java WAR of the web shop.

Enjoy!

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a ruby application

    rhc app create summitworkshop -t ruby-1.9 --from-code git://github.com/eschabell/openshift-summit-2014-brms-workshop.git

That's it, you can now start your workshop at:

    http://brmsworkshop-$your_domain.rhcloud.com

![Cool Store Workshop](https://raw.githubusercontent.com/eschabell/openshift-summit-2014-brms-workshop/master/lib/images/brms_bpms_workshop/header.png)

![Cool Store App](https://raw.githubusercontent.com/eschabell/openshift-summit-2014-brms-workshop/master/lib/images/brms_bpms_workshop/image125.png)
