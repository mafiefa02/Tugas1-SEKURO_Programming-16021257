# **Rangkuman Video 3 - "*[#3 GITHUB:BRANCH](https://www.youtube.com/watch?v=k1QXd-8VbPY&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=3&ab_channel=WebProgrammingUNPAS)*"**

## **Branching**

- Membuat Git branch
- Membuat snapshot tanpa mengganggu jalur utama (*Master branch*)
- Bisa digunakan untuk membuat fitur eksperimental
- Jika ada dua orang yang mengerjakan repo yang sama, setelah itu kedua branch dapat di merge

### **#1**

Biasanya setiap repository ada file **README.md**, yang berisi penjelasan lengkap mengenai repository tersebut.

### **#2**

Setiap kali melakukan commit, kita bisa memilih di branch mana kita akan melakukan commit, ini dilakukan dengan memilih atau membuat branch di halaman utama repo GitHub kita. ![GitHub Branch](/images/branches.png "GitHub Branches")

### **#3**

Kita bisa melakukan edit pada suatu file langsung dari halaman web GitHub, lalu melakukan *commit changes* sehingga perubahan pada file tersebut tersimpan di history commit.

### **#4**

Jika kita merasa bahwa pada suatu branch tertentu, ada fitur yang dapat digunakan pada aplikasi yang kita kembangkan. Kita dapat mengimplementasikan fitur yang sudah di-*develop* pada branch tersebut, dengan melakukan *merge* kepada branch utama. Ini dilakukan dengan melakukan *pull request*, *pull request* adalah permintaan khusus dari suatu branch untuk menggabungkan diri/mengambil suatu perubahan ke branch utama kepada pemilik/master repo.

### **#5**

Jika seseorang melakukan pull request, seorang master dari repo bisa melakukan merge repo dengan mengklik *merge pull request*, dan branch yang sudah dimerge ke branch utama bisa dihapus namun tidak akan mengubah perubahan pada branch utama.

### **#6**

Terkadang kita tidak bisa melakukan merging secara otomatis, karena ada suatu konflik pada file yang akan kita merge. Jika demikian, kita harus melakukan edit pada file tersebut secara manual, sehingga konflik tersebut terselesaikan, setelah itu baru kita bisa melakukan merging.
