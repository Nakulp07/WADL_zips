apt update -y
apt upgrade -y 
apt install curl gnupg2 gnupg git wget -y
apt install nodejs
node --version
npm install -g @angular/cli

ng version
ng new myapp
cd myapp
ng serve

