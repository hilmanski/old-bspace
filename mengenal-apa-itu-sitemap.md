---
createdAt: "2022-04-03T19:00:00Z"
description: "Sitemap adalah file yang berisi informasi dari sebuah situs, mulai dari halaman, video, artikel dan lainnya, serta bagaimana mereka saling berhubungan satu sama lain."
tags: ["SEO", "website"]
title: "Mengenal apa itu Sitemap"
---
Mesin pencari sudah cukup pintar untuk mengetahui struktur sebuah website secara kasar, namun untuk membuatnya lebih powerful lagi, kita bisa membantunya dengan menyediakan peta situs alias "sitemap". Sitemap berisi informasi seperti waktu update, potongan deskripsi, judul, dan lainnya.

## Apa itu sitemap?

Sitemap adalah file yang berisi informasi dari sebuah situs, mulai dari halaman, video, artikel dan lainnya, serta bagaimana mereka saling berhubungan satu sama lain.

Sitemap berformal XML, dengan tag tag yang tersedia kita bisa membuat sitemap sendiri atau menggunakan tool-tool generator yang bertebaran di internet.

## Apakah situs kamu butuh sitemap?

JIka kamu ingin meningkatkan SEO dari situsmu dan ingin setiap detail yang ada disitusmu masuk dalam situs pencari, makan menyediakan Sitemap menjadi penting. Kamu bisa memberi informasi detail pada sitemap yang akan membantu mesin pencari. Seperti jika kontennya gambar, maka kamu bisa memasukkan informasi licence, type, ukuran dll. Begitu juga dengan konten berita, video dan lainnya.

Dengan informasi detail tersebut, mesin pencari seperti google akan semakin mudah untuk mengkategorikan dan menawarkan pencari dengan kontenmu secara relevan.

Kalau situs kamu tidak banyak halamannya, dan cukup jelas bisa diketahui lewat menu navigasi, kemungkinan kamu tidak perlu sitemap.

## Bagaimana cara membuat sitemap?

Jika kamu sudah menggunakan pembuat website seperti Wordpress, Wix atau Blogger, mereka sudah menyediakan sitemap secara otomatis untukmu. Tidak perlu khawatir lagi.

Jika kamu seorang developer atau membuat situsnya secara mandiri, ada banyak tool yang bisa kamu gunakan untuk membuat sitemap. Bisa menggunakan kata kunci "sitemap generator" ada banyak pilihannya.

Nanti, sitemap generator ini kamu beriklan link situsmu, setelah itu ia akan secara otomatis, menjelajahi websitemu dan membuat struktur sitemapnya. Kamu bisa menyertakala file dari hasil pencariannya nanti.

Untuk developer yang ingin membuatnya lebih jauh lagi (lebih detail) kamu bisa mempelajari [format sitemap di sini](https://developers.google.com/search/docs/advanced/sitemaps/build-sitemap)

## Contoh isi file sitemap

Kalau kamu mengunjung sitemap situs ini di [sitemap.xml](https://bikin.space/sitemap.xml) kamu bisa melihat contohnya. Berikut potongan contoh formal file sitemap

    <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9 http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd">
    <!--  created with Free Online Sitemap Generator www.xml-sitemaps.com  -->
    <url>
    <loc>https://bikin.club/</loc>
    <lastmod>2022-03-09T22:01:00+00:00</lastmod>
    <changefreq>daily</changefreq>
    <priority>1.00</priority>
    </url>
    <url>
    <loc>https://bikin.club/login</loc>
    <lastmod>2022-03-09T22:01:00+00:00</lastmod>
    <changefreq>daily</changefreq>
    <priority>0.80</priority>
    </url>
    <url>
    <loc>https://bikin.club/posts/tag/help</loc>
    <lastmod>2022-03-09T22:01:00+00:00</lastmod>
    <changefreq>daily</changefreq>
    <priority>0.80</priority>
    </url>
    </urlset>