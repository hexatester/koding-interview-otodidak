# [title buku]

[![Creative Commons Attribution-NonCommercial 4.0 International License](https://i.creativecommons.org/l/by-nc/4.0/80x15.png)](http://creativecommons.org/licenses/by-nc/4.0/ ":crossorgin")

Ini adalah template buku open source (non komersial) yang dapat dideploy ke [github pages](https://pages.github.com/) dengan bantuan [docsify.js](https://docsify.js.org/)

## Mulai

Silahkan buat buku dari repo ini dengan [generate](https://github.com/hexatester/template-buku/generate).

## Favicon

Merubah favicon dengan mengganti file favicon.ico, generate favicon di [favicon.io](https://favicon.io/ ":crossorgin").

## Bantuan

### Konten Penting

```md
!> **Semangat** belajar!
```

Menjadi

!> **Semangat** belajar!

### Tips Umum

```md
?> _TODO_ unit test
```

Menjadi

?> _TODO_ unit test

### Mengatur Gambar

```md
![logo](https://docsify.js.org/_media/icon.svg ":size=WIDTHxHEIGHT")
![logo](https://docsify.js.org/_media/icon.svg ":size=50x100")
![logo](https://docsify.js.org/_media/icon.svg ":size=100")

<!-- Support percentage -->

![logo](https://docsify.js.org/_media/icon.svg ":size=10%")

<!-- Support css class -->
![logo](https://docsify.js.org/_media/icon.svg ":class=someCssClass")

<!-- Support css id -->
![logo](https://docsify.js.org/_media/icon.svg ":id=someCssId")
```

### ID Header Kustom

```md
### Hello, world! :id=hello-world
```

### Markdown di html tag

```md
<details>
<summary>Tugas Mandiri (Klik untuk melihat)</summary>

- Abc
- Abc

</details>
```

<details>
<summary>Tugas Mandiri (Klik untuk melihat)</summary>

- Abc
- Abc

</details>

### Link Cross-Origin

Menunjukkan link pada website yang berbeda

```md
[example.com](https://example.com/ ":crossorgin")
```

## Sampul

Rubah sampul dengan merubah file `_coverpage.md`

### Background Kustom

```md
<!-- _coverpage.md -->

# docsify <small>3.5</small>

[GitHub](https://github.com/docsifyjs/docsify/)
[Get Started](#quick-start)

<!-- background image -->

![](_media/bg.png)

<!-- background color -->

![color](#f0f0f0)
```
