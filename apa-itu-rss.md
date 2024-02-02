---
createdAt: 2022-04-03T18:00:00Z
description: "RSS adalah singkatan dari Really simple syndication. RSS merupakan file yang berisi informasi perwakilan dari sebuah website tentang hal baru di kontennya.  Pelajari Apa itu RSS disini."
tags: ["website"]
title: "Apa itu RSS?"
---
RSS adalah singkatan dari Really simple syndication. RSS merupakan file yang berisi informasi perwakilan dari sebuah website tentang hal baru di kontennya.

## Dasar masalah RSS

Website atau blog punya struktur yang berbeda-beda. Mulai dari desain, tata letak, di halaman mana sebuah konten berada, setiap situs punya prefrensi yang berbeda. Karena itu sulit jika "mesin" mau mengetahui apa konten terbaru di situs tersebut, karena tidak ada pola untuk membacanya.

Karena itu lahirlah RSS. RSS merupakan file berformal .xml yang menjadi perwakilan sebuah situs untuk konten-kontennya. Bukan hanya blog, playlist video seperti youtube pun punya RSS.

## Apa manfaat RSS

Manfaat RSS adalah memudahkan mesin untuk membaca konten terbarunya. Sehingga, ketika seseorang menggunakan sebuah aplikasi "RSS Feed reader" dimana seseorang  ingin punya satu tempat untuk melihat beberapa update konten dari berbagai situs sekaligus bisa di sini.

Bayangkan kamu suka membaca blog ini, suka sebuah playlist youtube dan membaca beberapa blog lain. Tentu untuk update berbagai konten ini kamu perlu membuka situsnya satu per satu. Nah sekarang tidak lagi, dengan aplikasi RSS-reader, kamu bisa menampilkan semua konten terbaru dari berbagai link ini dalam satu tempat. RSS-reader tidak bisa melakukannya jika sebuah situs tidak mempunyai RSS.

## Bagaimana cara membuat RSS

Tergantung dengan website yang kamu gunakan. Kamu bisa lebih spesifik mencari "bagaimana cara membuat RSS dengan wordpress" misalnya. Atau jika kamu seorang developer, kamu bisa mencari sesuai framework yang kamu gunakan. Sebagai contoh "how to create RSS with django" (untuk pengguna framework django).

Jika kamu tidak tahu cara membuatnya, bisa juga dengan bantual tool rss-generator seperti ini: [fetchrss](http://fetchrss.com/#:\~:text=Creating%20RSS%20feed%20from%20social,click%20on%20Generate%20RSS%20button.)

## Contoh RSS

Berikut contoh file RSS dari website ini.

    <rss xmlns:atom="http://www.w3.org/2005/Atom" version="2.0">
    <channel>
    <title>Bikin Space</title>
    <link>https://bikin.space/</link>
    <description>Recent content on Bikin Space</description>
    <generator>Hugo -- gohugo.io</generator>
    <language>id</language>
    <lastBuildDate>Sun, 03 Apr 2022 17:05:00 +0000</lastBuildDate>
    <atom:link href="https://bikin.space/index.xml" rel="self" type="application/rss+xml"/>
    <item>
    <title>Belajar marketing lewat contoh</title>
    <link>https://bikin.space/link/belajar-marketing-lewat-contoh/</link>
    <pubDate>Sun, 03 Apr 2022 17:05:00 +0000</pubDate>
    <guid>https://bikin.space/link/belajar-marketing-lewat-contoh/</guid>
    <description/>
    </item>
    <item>
    <title>Channel youtube Rio Purba</title>
    <link>https://bikin.space/link/channel-youtube-rio-purba/</link>
    <pubDate>Sun, 03 Apr 2022 17:02:00 +0000</pubDate>
    <guid>https://bikin.space/link/channel-youtube-rio-purba/</guid>
    <description/>
    </item>
    </channel>
    </rss>

Berisi tag rss, dibungkus dengan tag channel. Lalu satu blok untuk informasi situs sebelum diikuti setiap potongan informasi konten.