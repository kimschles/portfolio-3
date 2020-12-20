---
title:      Core Commands for Kubernetes 
date:       2019-03-08
description:    Basic Kubernetes commands for the CKAD Exam
author: Kim Schlesinger
---
{{< youtube qq7OV-Mz6B8 >}}

The [Certified Kubernetes Application Developer Exam](https://www.cncf.io/certification/ckad/) is a challenging, hands-on exam that requires you to configure and deploy applications and services in a real Kubernetes cluster. In this tutorial, I show how to run some basic `kubectl` commands that will get you started preparing for the CKAD. 


In this video, I show how to do the following in a Kubernetes cluster:

* View and switch contexts
* Setup your preferred text editor
    * vim is the default, but can be set to nano
* View pods in all namespaces
* View namespaces
* Create a namespace called `practice`
* Create a pod from yaml generated by the `--dry-run` flag
* Delete the pod
* Create the pod in the practice namespace
* Exec into the pod

To see the commands, checkout this github repo: 

[https://github.com/kimschles/CKAD-Prep/blob/master/01-Core-Concepts.md](https://github.com/kimschles/CKAD-Prep/blob/master/01-Core-Concepts.md).
