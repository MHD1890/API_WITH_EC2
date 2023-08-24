# BUILD_API_WITH_EC2
- Create index.js
- touch index.js .gitignore
- npm init -y
- npm i express
- isi di .gitignore (node_modules)
- di bagian package.json di bawah main ketiikan ( "type": "module",)
- Jalankan perintah nodemon . (jika tidak ada dapat diinstall dgn code "npm install -g nodemon" lalu chechk dgn "nodemon --version"
- Jalankan perintah nodemon . di GITBASH sehingga muncul "API LISTERNING 5001"
- Jika sudah input semua file ke github menggunakan kode berikut
_______________________________________________________________________
git init
git add .
git commit -m 'first commit'
git remote add origin https://github.com/MHD1890/API_WITH_EC2.git
git branch -M main
git push -u origin main
_______________________________________________________________________
#cloud-config
package_update: true
package_upgrade: true
runcmd:
- sudo yum -y update
- sudo yum install -y gcc-c++ make
- curl -o- https://nodejs.org/dist/v16.8.0/node-v16.8.0.tar.gz | tar -xz

