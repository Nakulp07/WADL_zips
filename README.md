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



mongodb://127.0.0.1:27017/art


res.setHeader('Access-Control-Allow-Origin', '*');

fetch('http://localhost:3000/artGallery/getArts')
