Welcome to Tyler's Homelab docs!
===================================

My homelab is a place for me to try interesting pieces of technology. 
Currently it's a k8s cluster with 3 masters and 3 nodes. The platform uses gitops to deploy
all of the manifests using ArgoCD and the creation of the VMs in Proxmox and initial cluster bootstrapping
is automated by Ansible scripts.

Check out the :ref:`create an account section <create your account>` section if you're looking to use my services.

Otherwise for architecture/design docs refer to... (TODO)

.. note::

   This project is under active development and is not a production service.
   
   Some things may be a bit janky, I have much lower requirements at home.

Contents
--------

.. toctree::

   user