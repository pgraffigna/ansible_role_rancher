# ansible_role_rancher

Ansible Playbook para desplegar un Servidor Rancher.

Testeado con Virtualbox + Ubuntu 20.04

---

roles:
- docker
- rancher
- kubectl
- kubecolor

---

notas:

kubeconfig
- desde rancher dashboard copiar el kubeconfig en el servidor en ~/.kube/config
- editar server: "https://IP/k8s/clusters/local" con la ip del contenedor
