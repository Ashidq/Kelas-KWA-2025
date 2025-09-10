Nama: Login Admin
Type: Injection

- Masuk ke dalam page login

<img width="553" height="832" alt="Image" src="https://github.com/user-attachments/assets/9409313b-5a6b-4553-93bf-8cc3f548481b" />

- Intercept Login Request menggunakan burp suite

<img width="1202" height="541" alt="Image" src="https://github.com/user-attachments/assets/c02b3f39-8b8c-45ec-a82c-0ea2e70c75ab" />

- Ubah SQL Query
Ubah kolom email di payload JSON menggunakan ' OR true-- yang akan mengubah perintah SQL menjadi pernyataan yang selalu mengembalikan nilai true, sehingga tidak perlu kata sandi.

<img width="1180" height="564" alt="Image" src="https://github.com/user-attachments/assets/ccfe69f3-96da-45af-910b-4665c82a4504" />

- Selanjutnya send to repeater diburp suite lalu liat responnya

<img width="1420" height="656" alt="Image" src="https://github.com/user-attachments/assets/a8441522-ad12-4df3-9dfe-970c6b50c2a6" />
