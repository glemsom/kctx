# kctx
Simple BASH Kubernetes context switcher - used as a builtin BASH function.
Adjust variables like `KUBECONFIGDIR` and `GEN_EXTRA_OPTS` as needed

### Setup
Copy the content of `bashrc-kctx` to your local ~/.bashrc file  
Optional: Set KUBECONFIGDIR variable to folder with kubeconfig to automatically populate KUBECONFIG

### Usage
`kctx`  
Select the desired context by searching (just start typing), or use arrow-keys
