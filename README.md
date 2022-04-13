| HERLIYANSYAH          |       312010387       |
|---------------------- |-----------------------|
|       TI.20.A.2       |   PEMROGRAMAN WEB     |
| PERTEMUAN 7           |   PRAKTIKUM 6         |

## PERTEMUAN 7

## LAB 6 WEB

Dipertemuan kali ini kita akan mempelajari **Web FrameWork** dengan ***Bootstrap*** dalam membuat **layout**

## WEB FRAMEWORK BOOTSTRAP

## 1). BUAT STRUKTUR DASAR DOKUMEN HTML

**PENJELASAN**

Dibawah adalah struktur Dasar Html menggunakan **Framework Bootstrap** Untuk menggunakan **Framework bootstrap** agar terhubung dengan Dokumen Html memerlukan **Link** yang sudah disediakan **bootstrap** dengan **link CDN** atau melalui **Online link** Seperti contoh salinan code dibawah.

**code html dan link bootstrap**

```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Web Framework</title>
  </head>
  <body>


    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```

## 2). MEMBUAT CONTAINER

**PENJELASAN**

Disini Saya membuat **Container** dengan **class container** **container** ini adalah container biasa di akan secara default hanya selebar **url** di atas layar atau tidak ukuran full **width** sementara untuk **class container-fluid** dia **full width 100%** itu perbedaan jenis **container** *dibootstrap* sudah terdesain otomatis hanya tinggal bagaiman kita membutuhkan nya,namun disini saya menggunakan **container** jenis biasa yang tidak **full width**.

**code html**

```html
 <!-- Container -->
    <div class="container">

    </div>
```

Di atas adalah contoh *class container* atau container yang saya gunakan sebagai wadah

## 3). MEMBUAT CARD HEADER



