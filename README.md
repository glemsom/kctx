# kctx
Simple BASH Kubernetes context switcher - used as a builtin BASH function.
Adjust variables like `KUBECONFIG` and `GEN_EXTRA_OPTS` as needed

### Setup
Copy the content of `bashrc-kctx` to your local ~/.bashrc file - and adjust variables as needed.

Ensure you have the requirements kubectl, sed, awk and fzf installed.

### Usage
`kctx`  
Select the desired context by searching (just start typing), or use arrow-keys
