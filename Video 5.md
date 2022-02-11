# **Rangkuman Video 5 - [#5 BEKERJA DENGAN GIT](https://www.youtube.com/watch?v=e-6OkXRqWaE&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=5&ab_channel=WebProgrammingUNPAS)**

## **Download client Git**

Untuk mendownload client Git bisa dari link berikut. [Link download Git client](htpps://git-scm.com)

Jika kita belum menginstall Git, tampilan command prompt jika kita mengetik 'git' adalah sebagai berikut ![Belum install Git](/images/git_belum_install.png "Belum install Git")
Berikut adalah tampilan ketika Git sudah diinstall ![Sudah install Git](/images/git_sudah_install.png "Sudah install Git")

## **Git command (lokal)**

- `$ git init`
- `$ git add <file(s)>`
- `$ git status`
- `$ git commit`
- `$ git config`
- `$ git branch`
- `$ git help`
- `...`

## **3 area pada repo Git**

- Working tree
- Staging area
- History

## Percobaan di Git terminal

![Percobaan 1](/images/git_terminal_1.png)

- `pwd` untuk mengetahui *current working directory*.
- `cd desktop` untuk masuk ke directory desktop
- `cd test-sekuro` untuk masuk ke directory desktop/test-sekuro

![Percobaan 2](/images/git_terminal_2.png)

- `git init` untuk initialize repository git

![Percobaan 3](/images/git_terminal_3.png)

- `git status` untuk mengetahui status repo lokal kita

![Percobaan 4](/images/git_terminal_4.png)

- `git add` untuk mentrack suatu file

![Percobaan 5](/images/git_terminal_5.png)

- `git commit -m "first commit"` untuk commit file yang sudah di track

![Percobaan 6](/images/git_terminal_6.png)

- `git log -- file.txt` untuk mengetahui history commit file bernama file.txt
