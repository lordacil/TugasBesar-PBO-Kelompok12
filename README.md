<p align="center">
  <a name="top" href="#octocat-hi-there-thanks-for-visiting-">
     <img alt="lordacil/tugas-besar-pbo" height="60%" width="100%" src="https://i.ibb.co/KD0r577/ico.png"/>
  </a>
</p>

## :rice_scene: Pendahuluan
Assalamualikum wr.wb, Perkenalkan kami dari Kelompok-12 yang beranggotakan :
| Nama | NIM | Kelas |
| -- | -- | -- |
| :boy: : **Rizky Nugraha Herliyanto** | 19104014 | SE03A |
| :boy: : **Fawwaz Muhammad Zulfikar** | 19104007 | SE03A |
| :woman: : **Renna Nur Injayani** | 19104001 | SE03A |

Disini kami membuat program e-bank sederhana dengan nama e-bank sejahtera guna untuk menyelesaikan tugas besar pada mata kuliah pemrograman berorientasi objek yang diampu oleh bapak dosen <em>Ariq Cahya Wardhana, S.Kom., M.Kom</em> dan juga dibantu oleh asisten praktikumnya yaitu Kak <em> Bagus Bayu Sasongko </em> dan <em> Kak Ajeng Fitria </em>, berkat semuanya akhirnya kami menyelesaikan tugas ini, walapun masih banyak kekurangannya.

**Powered by:**

<a href="https://nodejs.org/en/">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
</a>
<a href="https://manjaro.org/">
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white">
</a>
<a href="https://www.microsoft.com/id-id/">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
</a>

## :cyclone: Cara Penggunaan

### Cara Running Program

untuk merunning/menjalankan program ini yaitu bisa dengan ***2*** cara, yaitu :

1. **Memakai IDE Online**

untuk memakai IDE Online contohnya bisa menggunakan website dari <em>Repl.it</em>, jika ingin menjalankannya anda bisa langsung mengcopy program filenya lalu paste ke <em>Repl.it</em> atau jika anda tidak mau yang ribet anda bisa langsung klik icon di bawah ini:

![https://repl.it/@lordacil/tubes-PBO](images/chalk.svg)

2. **Memakai IDE/Text Editor Offline(berbentuk software)**

cara yang kedua ini cukup ribet ya karena kita diharuskan sudah menginstall beberapa package terlebih dahulu agar program bisa di jalankan, berikut caranya :

### Install Node JS

 <details>
  <summary>install di <kbd>Windows</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
  <details>
  <summary>install di <kbd>Arch Linux</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>

### Install NPM

 <details>
  <summary>install di <kbd>Windows</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
  <details>
  <summary>install di <kbd>Arch Linux</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
  ### Install Package Prompt-sync

 <details>
  <summary>install di <kbd>Windows</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
   <details>
  <summary>install di <kbd>Arch Linux</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
   ### Install Package Chalk
  
  <details>
  <summary>install di <kbd>Windows</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>
  
  <details>
  <summary>install di <kbd>Arch Linux</kbd></summary>
  
  - ```bash
    $ sudo apt install zsh
    ```
  - ```bash
    $ chsh -s `which zsh` # Change default shell to zsh for current user
    ```
  - ```bash
    $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
  - ```bash
    $ git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
  - [zsh-completions](https://software.opensuse.org/download.html?project=shells%3Azsh-users%3Azsh-completions&package=zsh-completions)
  
  </details>

## :bookmark_tabs: Class Diagram

## :star2: Fitur Program

### Login

![](images/login.gif)

### Register

![](images/registers.gif)

### Logout

![](images/logout.gif)

### Cek Saldo

![](images/ceksaldo.gif)

### Transfer Saldo

### Ambil Saldo

![](images/ambiluang.gif)

### Tambah Saldo

![](images/tambahuang.gif)

## Menu Lainnya

### Pembelian Pulsa

![](images/pulsa.gif)

### Pembayaran Listrik

![](images/listrik.gif)

## :video_camera: Video Penjelasan Coding, Class Diagram, dan Running Aplikasinya

berikut link video youtube tentang penjelasan coding, class diagram, dan running aplikasi bisa di klik pada icon di bawah ini:

<a href="https://www.youtube.com/channel/UChDIv8GsgR2JUc9_q_EoVqA">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
</a>

## :inbox_tray: Package yang digunakan
  1. [Prompt-Sync](https://www.npmjs.com/package/prompt-sync) - Digunakan untuk menginput di node.js  
  2. [Chalk](https://www.npmjs.com/package/chalk) - Digunakan untuk memberi warna pada text.
