# to removing sensitive data from git history
 **git filter-branch  --force --index-filter "git rm --cached --ignore-unmatch kubeconfig" --prune-empty --tag-name-filter cat -- --all**