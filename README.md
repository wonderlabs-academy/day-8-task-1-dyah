# Oh My Zsh
## Shell

Apa itu shell ? shell adalah program (penterjemah perintah) yang menjembatani user dengan sistem operasi dalam hal ini kernel (inti sistem operasi), umumnya shell menyediakan prompt sebagai user interface, tempat dimana user mengetikkan perintah-perintah yang diinginkan baik berupa perintah internal shell (internal command), ataupun perintah eksekusi suatu file progam (eksternal command), selain itu shell memungkinkan user menyusun sekumpulan perintah pada sebuah atau beberapa file untuk dieksekusi sebagai program.

## Zsh 
Zsh (Z shell) adalah salah satu shell untuk Unix/Linux yang merupakan pengembangan dari Bourne shell (sh). Beberapa peningkatan fiturnya antara lain _`cd completion`_ , _`git completion`_, _`path expansion`_, _`path replacement`_, dan _`right prompt`_.

### Zsh sudah ada di Mac

## Oh My Zsh
Robby Russel mengembangkan Oh My Zsh, sebuah framework untuk konfigurasi Zsh. Dengan Oh My Zsh, terminal yang menjalankan Zsh menjadi lebih keren karena dilengkapi dengan `functions`, `helpers`, `plugins`, dan `themes`. Pada saat artikel ini ditulis ada 200+ plugin, 900+ kontributor, dan 140 tema.


## Install Oh My Zsh

`sh` - "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

## Cara Ganti tema Oh My Zsh
Default theme Oh My Zsh menggunakan _robbyrussell_, dapat diganti dengan mengubah file **~/.zshrc**. Dengan command:

```
ls -a ~
```
```
nano .zshrc
```
 Cari baris kode `ZSH_THEME` dan ganti dengan nama theme yang diinginkan. Lihat nama theme dan screenshot-nya di GitHub.com. Setelah mengedit tema dan save file. 

 ```
 source .zshrc
 ```

 Tema akan berubah. Selesai 😊

## Fitur di Zsh yang tidak ada yang tidak ada di Bash


### zmv
 Untuk mengganti nama file secara massive. Misalkan file yang diganti .txt

 Run
```
zmv –C '(*)(#q.)' '$1.txt'
```

### Zsh enhancements
  
  Dengan menekan tab maka, command yang kita ketik akan otomatis di selesaikan dan dikoreksi. Misalkan :
```
  $ lls 
```

    akan otomatis menjadi
```
    $ ls
```

### zcalc
Calcular yang terdapat pada Command Line tanpa harus meninggalkan terminal.

Load dengan
```
autoload -Uz zcalc
```
Lalu run dengan 
```
zcalc
```

### Interactive path expansion: Type

Fitur yang memungkinkan kita dapat meringkas nama Path dengan hanya menuliskan huruf depannya, misalkan:

Sebelumnya kita akan menulis
```
cd /usr/local/bin
```
Kita dapat tulis dengan

```
cd /u/l/b
```
### Autopush Command

Autopushd command pada zsh membuat kita dapat kembali ke directory sebelumnya.
```
cd

```
### Alias

Menyediakan perintah yang lebih singkat. Misalkan :

```
ls -liah 
```
Menjadi

```
ls -ll
```


 

 





