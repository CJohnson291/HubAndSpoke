Hub - sotrage account for Terraform backend, Linux VM acting as the firewall
Production spoke - storage account containing write up, Private Endpoint to connect SA to CDN
Non-Production spoke - storage account containing write up (pre-prod)
GitHub repo - local write up, including changes, pushed to repo. Repo will then provide Non-Prod SA with site contents


