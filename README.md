# Bench-Test

Build assumes the presence of epel-release and Ansible. Not much was done in the way of system hardening since it varies dramatically between organizations.

I would have liked to have continued with the bonus section but didn't have an AWS account I could deploy several boxes to. My homelab runs vSphere and the work would not have been portable. I would have also liked to have explored using ELBs instead of HAProxy/Nginx.

I chose C because I haven't used it in a long time and my Bash & Python apps were too boring/simple to deploy.

Also, I was not clear on the purpose behind different repositories for the app and the playbook. If that is a requirement, I'm happy to break this out into two separate repositories.
