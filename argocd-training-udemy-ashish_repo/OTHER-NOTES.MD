# Reset GIT user and password
git config --global credential.helper osxkeychain

# In case repo in GITHUB is changes - please update
  source:
    path: argocd-training-udemy-ashish_repo/0-Demo_Files/Nginx_Deployment
    repoURL: 'https://github.com/hello2ashu/My-repo.git'


 # How to change a branch
 ARGOCD picks the config from commit where HEAD is pointing
  targetRevision: test1

In sync settings on GUI  if branch is mentioned ARGOCD will sync from the branch (last status will be sync but SYNC status may be out of sync)
Change the target revision to branch and if HEAD is also pointing to commit in brach argocd will changes from branch.
