# pelatihan-praktikum-sisop
1. Membuat folder dan masuk ke folder
```bash
mkdir artists_who_can_sing
cd artists_who_can_sing
```
2. Mendownload file zip menggunakan wget
```bash
wget --no-check-certificate -p ~/artists_who_can_sing 'https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut' -O tutorial.zip
```
3. Membuat file baru bernama "singing_tutorials" dan melakukan unzip file kedalam folder "singing_tutorials"
```bash
mkdir singing_tuorials
cd singing_tutorials
unzip -d singing_tutorial tutorial.zip   
```
4. Menampilkan semua file dan menampilkan semua file yang tersembunyi
```bash
ls
ls -a
```
5. Mencari flag 
```bash
find . -type f -iname "*opera*NBAYoungboy*" -exec grep -i "FLAG" {} \;
```
