# OCP-CLI
Introduction to ocp cli

We can manage an OpenShift cluster from the web console or by using the kubectl or oc command-line interfaces (CLI).
* The "kubectl" commands are native to Kubernetes, and  "oc" commands are a superset of the kubectl commands, and add commands for the OpenShift-specific features

* The main method of interacting with an RHOCP cluster is by using the "oc command".

* oc CLI is a superset of the kubectl CLI, the version, --help, and explain commands are the same for both CLIs. However, the oc CLI includes additional commands that are not included in the kubectl CLI, such as the oc login and oc new-project commands.



Yes, that's correct. Namespaces are used to differentiate resources that have the same names within a cluster.


Operators : -
* Operators are important components of Red Hat OpenShift Container Platform (RHOCP).
* Operators automate the required tasks to maintain a healthy RHOCP cluster.
* Operators are the preferred method of packaging, deploying, and managing services on the control plane.
* Operators provide the means of monitoring applications, performing health checks, managing over-the-air (OTA) updates, and ensuring that 
  applications remain in your specified state.
