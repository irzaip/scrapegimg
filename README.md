# SCRAPE GOOGLE IMAGE

working 2020/08/27
ini adalah pengembangan kode dari 
sumber:
https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/


## INSTALASI DAN REQUIREMENT

menggunakan python3, baca requirements.txt untuk mengetahui library apa saja yang diperlukan
untuk menjalankan program ini.


cara menggunakan:

    git clone https://github.com/irzaip/scrapegimg
    cd scrapegimg
    1. buka chrome kamu,
    2. masuk ke google image
    3. cari gambar berdasarkan keyword kamu
    4. scroll terus untuk menambah gambar yang terdisplay
    5. buka console (developer tools)
    6. select semua + copy paste kode capurl.js ke console
    7. setelah ENTER akan membuat file url.txt untuk di donwload ke comp kamu
    8. download gambar mengunakan python3 ./scrape.py -u url.txt -o outputdir
    9. Susun dan atur gambar2 kamu.


