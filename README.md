
# kctx

Simple BASH Kubernetes context switcher - used as a built-in BASH function.  
Adjust configuration in `~/.config/kctx/kctx.conf` as needed.

  

### Setup

1: Clone repository  
`git clone https://github.com/glemsom/kctx.git ~/.kctx`

2: Source kctx from your .bashrc  
`echo 'source ~/.kctx/bashrc-kctx' >> ~/.bashrc`

**Recommended**: Place your kubeconfig files in `~/.config/kctx/kubeconfig.d` (By default the script will use those files to generate the `KUBECONFIG` variable)  
See https://kubernetes.io/docs/concepts/configuration/organize-cluster-access-kubeconfig/#the-kubeconfig-environment-variable for details

**Optional**
Adjust the GEN_EXTRA_OPTS variable in `~/.config/kctx/kctx.conf` as needed.

### Usage
`kctx`  
Select the desired context by searching (just start typing), or use arrow-keys
