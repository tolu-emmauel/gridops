# GridOps lab log

Newest entry at the top. Template and rules: Practice system tab of the curriculum.

## 2026-11-17 — Lab 0: workbench
**Goal:** set up Linux, Git, GitHub and a first CI pipeline
**What I did:** installed WSL Ubuntu + VS Code; created SSH key; made gridops repo; added a repo secret; wrote first workflow
**What broke:** 1) mkdir/cd showed no output  2) git clone: "not a valid repository name"  3) couldn't find Secrets  4) workflow didn't appear in Actions
**Why it broke:** 1) Linux is silent on success  2) pasted the full URL where only the username belonged  
3) was in account settings, not repo settings  4) file not saved and pushed
**Fix:** 1) pwd to confirm  2) copied the exact SSH address from GitHub  
3) repo → Settings → Secrets and variables  4) Ctrl+S, git push
**Break test:** none on purpose, but four real breaks above
**Electrical link:** SSH key and lock = a keyed isolator: only the holder of the key can operate it
**Proof:** commit link; Actions run showing the secret as ***
**STAR line:** This lab I had to setup my workbench, 
basically my Linux, git and Github, and my very first CI. 
I installed the WSL ubuntu and vS code, built my repository and wrote my first workflow. 
I was able to commit my work, use secrets to hide sensitive informatio that only I should have access to, and all systems were a go.
