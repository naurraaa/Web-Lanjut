# vue-myproject

#### buat project baru
1. pastikan sudah install nodejs dan github desktop.
2. buka terminal dan pilih folder tempat project.
3. jalankan `npm create vue@latest`.
4. Project name isi dengan `vue-myproject`.
5. untuk feature pilih `Router` saja.

##### menjalankan project
1. buka folder `vue-myproject` di vscode.
2. buka terminal yang ada di vscode dengan ctrl + `.
3. install dependency project dengan menjalankan `npm install` di terminal.
4. jalankan project dengan menjalankan `npm run dev` di terminal.

#### setting github di vscode
1. buat repository di github dengan nama repo `vue-myproject`.
2. masuk ke menu source controle di github dan pilih `initialize repository`.
3. masukkan `README.md` ke stage dan commit.
4. tambahkan remote github.
5. publish/push/sync ke github.

#### setting cloudflare
1. install wrangler dan cloudflare/vite-plugin degan menjalankan `npm install -D @cloudflare/vite-plugin wrangler` di terminal.
2. setting cloudflare di `vite.config.js`.
3. buat dan setting `wrangler.jsonc`
4. buat file `index.js` di folder api untuk backend.
5. create worker di cloudflare dengan memilih `Import a repository` dan pilih `vue-myproject`.
6. biarkan setting standart pilih build.
