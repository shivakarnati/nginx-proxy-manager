# NGINX PROXY MANAGER

This repository is to create the custom URL proxy using NGINX.

## STEPS
1. Create an account in `https://www.duckdns.org/`
2. Login using GitHub/Google account credentials
3. ![image](https://github.com/user-attachments/assets/60966e2b-b669-4559-af4c-087739826c9f) Add a proxy domain
4. Create a docker compose file for Nginx-proxy, as shown in `https://nginxproxymanager.com/guide/`
5. Bring up the given compose file using `docker-compose up -d`
6. Check your `localhost`, and login using

     ```Email:    admin@example.com, Password: changeme```
7. Add proxy host in the given dashboard ![image](https://github.com/user-attachments/assets/75568cec-e548-4f63-b3ad-b68f6dedec03)

Here, we can select the SSL certificates to access our proxy URL within the network.

