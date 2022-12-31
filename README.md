# odo-demo
How to use odo for rapid application development

**Tools**

 1. A Kubernetes Environment (e.g., Local Kube, AKS, EKS, OpenShift, Rancher)

*You'll need a Kubernetes cluster of some kind. In the demo, I use the free OpenShift Developer's Sanbox. You can create a free Red Hat account at developers.redhat.com. Alternatively, you can also use [OpenShift Local](https://developers.redhat.com/products/openshift-local/overview) is a terrific development environment, as is KIND ([Kubernetes In Docker](https://kind.sigs.k8s.io/))* 

 2. Command line tools

You'll need to download the latest version of odo to your system.
https://odo.dev/docs/overview/installation Finally, you'll also need kubectl ***and or*** the OpenShift oc tool. You can download these tools together through the OpenShift Developer Sandbox console by clicking on the [Help and clicking Command Line tools.](https://cookbook.openshift.org/accessing-an-openshift-cluster/where-can-i-download-the-openshift-command-line-tool.html)


3. A sample application

In my demo I use a [sample Java Springboot application](https://spring.io/guides/gs/spring-boot/). However, `odo`supports [many modern frameworks](https://odo.dev/docs/user-guides/advanced/deploy/) such as [Node.js](https://odo.dev/docs/user-guides/advanced/deploy/nodejs), [Java](https://odo.dev/docs/user-guides/advanced/deploy/java), [.Net](https://odo.dev/docs/user-guides/advanced/deploy/dotnet), [Go](https://odo.dev/docs/user-guides/advanced/deploy/go), PHP, etc.
