
# Kubernetes Virtual filesystem for Midnight Commander

This extension to MC shows the API object as files. 
The main objective is to cut down on the time spent typing kubectl commands.

 1. Kubectl contexts
 ![k8s contexts](screenshots/Screenshot_20190506_095605.png)
 2. Namespaces 
 ![Namespaces](screenshots/Screenshot_20190506_095628.png)
 3. ConfigMaps, Deplooyents, Ingress, Pods, Replicasets, Secrets and Services ![k8s objects](screenshots/Screenshot_20190506_095639.png)
 4. Pod status 
 ![k8s objects](screenshots/Screenshot_20190506_095721.png)
 5. Pod Object description  
 ![Pod Object description](screenshots/Screenshot_20190506_095729.png) 


# Installation 

Copy k8sfs+ and k8sfs-context to
```shell
~/.local/share/mc/extfs.d
```

Add this:
```
regex/^\[k8s-context\]
	Open=%cd %p/k8sfs-context://
```

To the top of:
```shell
~/.config/mc/mc.ext
```

# Usage
Execute: cd k8sfs://
