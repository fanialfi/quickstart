+++
date = '2026-11-15T15:26:54+07:00'
draft = false
title = 'postingan pertama saya : sebagai uji coba'
+++

## Introduction

Ini adalah paragraf pertama saya
jangan sampai bosan belajar.

### Add Content

untuk menambahkan sebuah kontent baru

```
hugo new content content/posts/my-first-post.md
```

hugo akan membuat file di directory `content/posts` dan didalamnya berisi

```markdown
+++
date = '2026-11-15T15:26:54+07:00'
draft = true
title = 'My First Post'
+++
```

Untuk menjalankan Hugo develompent server, ada 2 cara yang bisa kamu lakukan, dari kedua cara ini kamu boleh memilihnya salah satu

```
hugo server --buildDrafts
hugo server -D
```

ketika sudah selesai dan sudah matang dengan content yang baru dibuat, ubah parameter _front matter_ **draft** menjadi **false**

pastikan juga ketika mengupload repository project hugo, folder _public/_ jangan sampai diupload ke repository, karena isi dari folder tersebut adalah hasil dari kompilasi content hugo
