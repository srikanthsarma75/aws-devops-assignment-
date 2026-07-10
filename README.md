AWS Services Used
EC2: Launched Ubuntu EC2 instance, connected via SSH, installed and configured Nginx, hosted a
sample web page.
Linux Commands Used
pwd
ls -la
cd /var/www/html
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl restart nginx
sudo nginx -t
sudo ss -tulnp | grep :80
curl http://localhost
mv index.html /var/www/html/
git status
git add .
git commit -m "message"
git push origin main
Commands to Install Nginx
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
Problems Faced
1. GitHub 403 Forbidden while pushing changes.
2. Authentication issues with Personal Access Token.
3. Switched to SSH authentication.
4. Push rejected because remote branch contained commits not available locally
(non-fast-forward/diverged branches).
5. Nested Git repository caused 'does not have a commit checked out' error.
6. Initial difficulty accessing the Nginx web page due to troubleshooting networking and
configuration.
Learnings
• Learned to launch and connect to an EC2 instance.
• Installed, started, enabled and verified Nginx.
• Understood Security Groups, HTTP (80), SSH (22), and public IP usage.
• Learned Nginx document root (/var/www/html).
• Learned Git workflow: add, commit, push, pull, merge, SSH authentication, and resolving push
conflicts.
• Improved Linux command-line troubleshooting skills
