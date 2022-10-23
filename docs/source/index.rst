Welcome to Tyler's Homelab docs!
===================================

My homelab is a place for me to try interesting pieces of technology. 
Currently it's a k8s cluster with 3 masters and 3 nodes. The platform uses gitops to deploy
all of the manifests using ArgoCD and the creation of the VMs in Proxmox and initial cluster bootstrapping
is automated by Ansible scripts.

Check out the :User Docs:`Getting Started` section if you're looking to use my services.
Otherwise for architecture/design docs refer to... (TODO)

.. note::

   This project is under active development and is not a production service.
   I take lots of short cuts here which I wouldn't do professionally. So please keep that in mind.

Contents
--------

.. toctree::
   user