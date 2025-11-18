# commands-
sudo su
yum update -y
yum install -y httpd
cd /var/www/html
wget https://github.com/azeezsalu/techmax/archive/refs/heads/main.zip
unzip main.zip
cp -r techmax-main/* /var/www/html/
rm -rf techmax-main main.zip
systemctl enable httpd 
systemctl start httpd

https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa052clZ6aTVFYWZwZjVZdG4zdUZaT0xNZFk3UXxBQ3Jtc0tubU1KLVFpek56VE5BX0w4TmdSUG54RXVKanpaUjlQeHBJZEZQcUoxNGUxWC0wa3BodUNQMjJOQzY3Ny1PQThQYTVRanRRQ1dhYVVfMHlSZXhIdTVnR2RoeTdxdzhkaGd6X1lnelBsWlVfU094RFJWWQ&q=https%3A%2F%2Fgithub.com%2Fazeezsalu%2Ftechmax&v=7jFLGdu62jM

https://github.com/azeezsalu/techmax.git
