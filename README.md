
# kctx

Simple BASH Kubernetes context switcher - used as a built-in BASH function.  
Adjust variables like `KUBECONFIGDIR` and `GEN_EXTRA_OPTS` as needed.

  

### Setup

1: Clone repository  
`git clone https://github.com/glemsom/kctx.git ~/.kctx`

2: Source kctx from your .bashrc  
`echo 'source ~/.kctx/bashrc-kctx' >> ~/.bashrc`

**Optional**: Set `KUBECONFIGDIR` variable to folder with kubeconfig files to automatically populate `KUBECONFIG`  
See https://kubernetes.io/docs/concepts/configuration/organize-cluster-access-kubeconfig/#the-kubeconfig-environment-variable for details

**NOTE**: By default, the script will try and source kubeconfig files from `~/kubeconfigs`

  

### Usage
`kctx`  
Select the desired context by searching (just start typing), or use arrow-keys
