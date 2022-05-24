## Bash Completion
```bash
# As root:
argocd completion bash >> /etc/bash_completion.d/argocd
# As Non-root and current terminal:
source <(argocd completion bash)
```

## Login to argo server
```bash
# argocd login <URL_WITHOUT_PREFIX>:443
argocd login wow.wow.wowww:443
argocd cluster list
```

