---
id: cara-membuat-chatbot-yang-disukai-orang
title: Bagian 1 - Menambah Wawasan Tentang Chatbot
sidebar_label: Cara Membuat Chatbot Yang Disukai Orang
hide_title: false
---
## Cara Membuat Chatbot Yang Disukai Orang

Mendesain chatbot adalah pekerjaan yang tidak mudah, apalagi kalau Anda tipe orang yang jarang berbicara dengan orang lain atau malas berkomunikasi basa-basi. Karakter seperti ini biasanya adalah salah satu ciri seorang introvert. Tapi menurut saya, ilmu komunikasi itu itu bisa dipelajari siapapun asalkan ada kemauan dan aksi yang dilakukan untuk mewudujkannya.

Mari kita mulai dengan melihat profesi AI Interaction Designer.

![AI Interaction Designer](../assets/bagian-1/gambar-1-28-ai-interaction-designer.png)
*Gambar-1.28 Role AI Interaction Designer*

Dengan semakin berkembangnya teknologi chatbot, maka diperlukan keterlibatan disiplin ilmu yang lainnya.

Sebagai seorang AI Interaction Designer, harus memiliki keahlian berkomunikasi yang luar biasa dan biasanya dicari yang memiliki gelar dibidang Seni, Teater, Psikologi, atau Komunikasi.

Dalam contoh lowongan kerja ini, kita bisa lihat bahwa seorang kandidat harus menguasai komunikasi baik verbal maupun tertulis. Dan bahkan tau kapan harus melanggar aturan dalam penggunaan grammar.
Selain itu perhatikan point ke-3, kandidat harus memiliki latar belakang yang kuat dalam pengembangan karakter dan ahli dalam menulis dialog.

Dari sini bisa kita simpulkan, bahwa untuk mendesain percakapan yang baik diperlukan pengetahuan tersebut.
Tapi ga usah khawatir jika sebagai seorang chatbot developer tidak memiliki skill tersebut.

Anda bisa mulai mencari teman yang setidaknya memiliki latar belakang dibidang seni, teater, psikologi dan komunikasi.
Mulailah join ke grup di facebook yang relevan dengan bidang tersebut, dan mulai bersosialisasi mencari teman.

Atau jika Anda hanya ingin sekedar belajar membuat chatbot, bisa menggunakan template percakapan yang sudah tersedia, bisa cari Google atau ambil gaya percakapan dari film yang Anda sukai.

## Membangun Tim

Membuat chatbot secara professional biasanya dibutuhkan tim. Contohnya diluar negeri sudah ada perusahaan yang membuat tim pengembang chatbot. Salah satunya bernama botscrew. Mari kita lihat komposisi tim chatbot diperusahaan tersebut.

![Software Development Team](../assets/bagian-1/gambar-1-29-chatbot-team.png)
*Gambar-1.29 Chatbot Development Team*

Jika dilihat disini, tidak ada yang menggunakan title chatbot developer, melainkan menggunakan title Software Engineer. Penggunaan title sepenuhnya diatur oleh masing-masing perusahaan. Karena ada juga perusahaan yang dengan jelas mencatumkan title Chatbot Developer.

Jadi dalam satu tim pengembang chatbot terdiri dari, Software Engineer, Content Manager, QA Engineer, Designer, Sales & Marketing Manager, Project Manager dan UI/UX Designer.

Sama seperti project software pada umumnya, namun bedanya ada di skillset personilnya, yang difokuskan untuk mengembangkan chatbot.
Lalu bagaimana jika ingin menjadi seorang single-fighter atau freelancer chatbot developer?

Tentunya hal tersebut tidak ada masalah, selama sanggup dan selalu belajar untuk meningkatkan keahlian di bidang tersebut.

Untuk memulai membuat chatbot sama halnya dengan membuat software, yaitu dimulai dari perencanaan terlebih dahulu.

## Perencanaan Membuat Chatbot

Dalam proses lifecycle chatbot, perencanaan adalah hal yang kritikal, tanpa perencanaan yang baik dan jelas, project chatbot akan memiliki tingkat kegagalan yang tinggi. Maka dari itu jangan menyepelakan fase perencanaan diawal.

### Tentukan tujuan chatbot

Yang pertama adalah tentukan tujuan chatbot, seperti di sesi sebelumnya, banyak use cases yang bisa diimplementasikan menggunakan chatbot, contohnya chatbot travel, yang dapat membantu dalam memberikan informasi akun, bisa booking kamar, bisa akses direktori hotel dan peta, ataupun chatbot banking yang bisa memberikan informasi mutasi rekening, dan sisa saldo atau chatbot rumah sakit, yang bisa memberikan informasi histori rawat Jalan, rawat inap, asuransi, obat dan informasi dokter.

### Memutuskan menggunakan rule-based atau NLP platform

Putuskan apakah akan menggunakan rules-based atau NLP atau bahkan keduanya. Untuk menentukan pilihan tersebut sederhana saja.

Jika tujuan dari chatbot sangat spesifik dan sederhana cukup gunakan rules-based, contohnya chatbot yang dapat memberikan informasi tentang cuaca hari ini, besok atau lusa. Karena percapakan yang dilakukan tentunya akan spesifik dan tidak perlu memiliki basa-basi hal lainnya.
Sedangkan jika chatbot harus menangani berbagai macam percakapan termasuk percakapan sehari-hari maka diperlukan NLP.

Contohnya chatbot dapat merespon dengan baik ketika ditanya mengenai nama, umur, alamat, ataupun hal basa-basi lainnya. Dan selain itu chatbot harus bisa mengenali unsur sentiment dari percakapan, misalnya ingin mengetahui apakah lawan bicaranya kesal atau tidak.

Chatbot dengan kriteria tersebut memerlukan teknologi NLP.
Atau bisa juga menggunakan rule-based dan NLP, misal layer pertama akan dihandle oleh logic rule-based ketika logic rule-based tidak bis memahami percapakan dengan spesifik maka akan diproses di layer kedua menggunakan NLP

### Ketahui limitasi dari platform

Ketahuilah limitasi dari platform messaging seperti Facebook Messenger, Line, Telegram dan WhatsApp

Contohnya, di telegram dan line support inline bot dan di facebook whatsapp tidak support, lalu contoh lainnya, di facebook tidak boleh mengirim pesan jika percakapan telah lewat dari 24 jam, lalu di telegram ada Batasan mengirim pesan secara beruntun dengan ketentuan 30 pesan per detik, jadi kalau mengirimkan pesan 40 pesan per detik, maka 10 pesan tidak akan terkirim ke lawan bicaranya.
Dan lain sebagainya, semua itu bisa dibaca di dokumentasi masing-masing platform messenger.

Ingat bahwa semua platform memiliki limitasi, ingat kata kunci ini, dan galilah lebih dalam tentang limitasi dimasing-masing platform.
Jangan sampai salah menentukan teknologi, bisa-bisa projek akan gagal, dan reputasi bisa jatuh.

### Tentukan kepribadian dan nada

Tentukan kepribadian dan nada. Maksudnya adalah buatlah chatbot seakan-akan memiliki karakter yang hidup, memiliki nama, gambar avatar dan biography sederhana. Ini akan di bahas lebih lanjut di bagian selanjutnya.

Dan untuk nada, jika chatbot bisa merespon dengan suara, maka diperlukan karakter atau tone khusus sebagai ciri dari karakter chatbot yang akan membuat orang senang berinteraksi dengan chatbot.

### Menulis pesan seperti manusia

Menulis pesan haruslah senatural mungkin, jangan pakai gaya robotic, pikirkan sesuatu yang menunjukan empati layaknya manusia. Jadi ketika mendesain percakapan, Anda harus membayangkan dari dua sudut pandang, yaitu dari sisi  chatbot, dan dari sisi lawan bicara chatbot. Intinya harus senatural mungkin kata-katanya. Memang tidak mudah, mulailah berkomunikasi atau banyak ngobrol hal non-teknis dengan teman-teman Anda, supaya bisa merasakan percakapan dan menambah inspirasi.

### Mendesain alur percakapan

Berkaitan dengan yang kelima, desain alur percakapan senatural mungkin, jika ada yang belum bisa di handle, berikan pesan general yang memberikan informasi tentang apa yang bisa dilakukan oleh chatbot.

Contohya chatbot yang hanya mengerti tentang cuaca. Ketika ditanya dimana saya bisa pesan makanan enak, makan chatbot bisa membalas pesan tersebut dengan "Maaf saya tidak mengerti, saya hanya mengetahui tentang cuaca, dan Anda bisa bertanya tentang cuaca hari ini, besok atau lusa".

Untuk mendesain percakapan Anda bisa menggunakan tools brain storming seperti Xmind atau Draw.io

### Memberikan pesan sisipan (teks / gambar)

Memberikan pesan sisipan berupa teks atau gambar, agar percakapan terkesan lebih natural.

### Memanfaatkan visualisasi (gambar / video)

Memanfaatkan visualisasi berupa gambar atau video untuk menunjukan ekspresi dari chatbot, inipun bertujuan agar percakapan terkesan lebih natural dan menyenangkan.

### Mempermudah pemindahan percakapan dari bot ke manusia

Mempermudah pemindahan percakapan dari bot ke manusia. Hal ini dilakukan jika lawan bicara secara manual ingin berbicara dengan operator manusia ataupun bisa dilakukan otomatis jika chatbot tidak bisa menjawab pertanyaan dengan spesifik sebanyak beberapa kali maka system backend akan mengalihkan percakapan dari chatbot ke customer service manusia.

![Chatbot sisipan gambar](../assets/bagian-1/gambar-1-30-chatbot-image.png)
*Gambar-1.30 Chatbot Merespon Dengan Gambar*

Contoh: Memberikan pesan sisipan (teks / gambar)

## Membangun Personality Chatbot

Secanggih apapun chatbot yang Anda buat, belum tentu bisa engage dengan pengguna. Chatbot memerlukan personality layaknya manusia, karena suatu percakapan akan terasa lebih hidup.

![Microsoft Project Personality Chat](../assets/bagian-1/gambar-1-31-chatbot-personality.png)
*Gambar-1.31 Microsoft: Project Personality Chat*

Microsoft research telah mempublikasikan hasil risetnya, yaitu Project Personality Chat. Tujuan dari riset ini adalah untuk membantu chatbot developer mendesain chatbot agar mudah engage dengan lawan bicaranya. Ada beberapa jenis personality yaitu, professional, enthusiastic, caring, witty dan friendly. Silahkan coba [https://www.microsoft.com/en-us/research/project/personality-chat/#!get-it-now](https://www.microsoft.com/en-us/research/project/personality-chat/#!get-it-now)

## 8 Langkah Membangun Personality Chatbot

### Tentukan role

Yang pertama adalah menentukan role dari chatbot, contohnya chatbot informasi cuaca, atau chatbot HR yang menjadi assisten pegawai dan manajemen HR

### Uraikan role

Contohnya chatbot dapat memberikan informasi cuaca pada hari ini, besok ataupun lusa. Chatbot dapat memberikan informasi cuaca di berbagai tempat ataupun negara.

### Tentukan gender

Tentukan gender dari chatbot, missal perempuan atau laki-laki, karena akan menentukan gaya bicara atau gaya penulisan pesannya.

### Tentukan umur “activation date”

Tentukan umurnya, bias disesuaikan dengan rata-rata umur lawan bicaranya, atau berdasarkan tanggal chatbot dipublish pertama kali

### Membuat biografi

Membuat biografi sederhana, contohnya chatbot lahir di suatu tempat dan dikembangkan oleh orang bernama X, buat senatural mungkin namun tidak berlebihan, tetap harus memperlihatkan bahwa ini adalah chatbot

### Beri nama yang humanis “identitas kultur”

Berikan nama yang humanis, contohnya, jika gender chatbot adalah perempuan bisa memberikan nama seperti Mira, Lucy, dan lain sebagainya, disesuaikan dengan kepribadian dan role dari chatbotnya.

### Visualisasikan

Buatlah avatar dari chatbot, dan juga buatlah gambar-gambar ekspresi chatbot, seperti senang, senyum, kesal, dan lain sebagainya, disesuaikan dengan role chatbot.

### Persona (psikologi) “topeng social” “karakter”

Berikan suatu karakter atau kepribadian tertentu, bisa menggunakan personality chat dari Microsoft. Ataupun bias menggunakan beberapa model yang sering digunakan untuk tes kepribadian, seperti MBTI dan FFM.

Mari kita lihat beberapa chatbot yang sudah dibuat menggunakan personality, beberapa chatbot ini, dibuatkan website atau landing page khusus yang berisi profile dari chatbot. Sehingga pengguna bisa mengetahui profil chatbot, apa yang bisa dilakukan chatbot dan bagaimana cara memulai percakapan dengan chatbot tersebut. Berikut adalah beberapa contoh implementasi Personality Chatbot

- https://shandong.evocreations.com/
- https://www.rinna.id/profile
- https://www.bca.co.id/individu/inovasi/vira
- https://kata.ai/story/jemma
- https://kata.ai/story/veronika
- https://kata.ai/story/Shalma
- https://kata.ai/story/sabrina

![Chatbot stickers](../assets/bagian-1/gambar-1-32-chatbot-stickers.png)
*Gambar-1.32 Chatbot Stickers*

Stiker Animasi didukung suara, akan menambah keakraban percapakan
secara personal. Ini adalah bagian dari personality chatbot.
