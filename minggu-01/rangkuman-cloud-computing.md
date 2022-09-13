## Apa itu cloud computing

Cloud computing adalah _Computer system resources_, terutama media penyimpanan data dan infrastruktur komputasi tanpa pengelolaan langsung dari user. Layanan ini sering didistribusikan dari beberapa lokasi yang tiap lokasi diberi nama _Data Center_.

## Sejarah Awal

- masih belum banyak service yang ada di tahun 1960-an namun yang paling menonjol adalah RJE, dan beberapa fitur awal VPN (_virtual private network_)
- di tahun 2000-an sudah mulai bermunculan beberapa cloud provider seperti AWS (_Amazon web service_) yang menyediakan fitur storage dan cloud computingnya. kemudian Google juga mengeluarkan versi _beta_ dari _Google App Engine_ yang merupakan awal mula _PaaS_ yang digunakan untuk membuat aplikasi web dalam beberapa pilihan bahasa
- di tahun 2010-an beberapa provider sudah mulai bermunculan seperti, _Microsoft_ dengan _MS Azure_, _IBM_ dengan _SmartCloud_ dan _Oracle_ dengan _Oracle Cloud_, yang dimana penyedia jasa ini sering dianggap sebagai yang pertama dalam menyediakan jasa yang terintegrasi dari _IT Solutions_ termasuk _SaaS PaaS IaaS_

## Karakteristik

- Lebih fleksibel dalam pembuatan infrastruktur
- penurunan biaya dikarenakan kita hanya membayar apa yang kita butuhkan saja
- Kemududahan akses darimana saja asal kita memiliki akses internet
- _Maintenance Free_ dikarenakan sudah dilakukan oleh penyedia jasa
- Performa layanan selalu dimonitor oleh tim IT layanan secara konsisten
- Lebih aman karena sentralisasi data

## Service Model

secara umum cloud computing dibagi menjadi 3 cabang yaitu (_infrastructure_)-aaS, (_Platform_)-aaS, dan (_Software_)-aaS

### _Infrastructure as a service (IaaS)_

"Infrastruktur sebagai layanan" (IaaS) mengacu pada layanan online yang menyediakan *High-Level*tapi API yang digunakan untuk menyediakan berbagai detail tingkat rendah dari infrastruktur jaringan seperti sumber daya komputasi fisik, lokasi, partisi data, _scaling_, keamanan, dll. hypervisor menjalankan mesin virtual sebagai tamu. Kumpulan hypervisor dalam sistem operasional cloud dapat mendukung sejumlah besar mesin virtual dan kemampuan untuk meningkatkan dan menurunkan skala layanan sesuai dengan kebutuhan pelanggan yang bervariasi. Linux Container berjalan di partisi terisolasi dari satu kernel Linux yang berjalan langsung pada perangkat keras fisik. Cgroup dan namespace Linux adalah teknologi kernel Linux yang digunakan untuk mengisolasi, mengamankan, dan mengelola container. Kontainerisasi menawarkan kinerja yang lebih tinggi daripada virtualisasi karena tidak ada overhead hypervisor.

### _Platform as a service (PaaS)_

Vendor PaaS menawarkan lingkungan pengembangan untuk pengembang aplikasi. Penyedia biasanya mengembangkan toolkit dan standar untuk pengembangan dan saluran untuk distribusi dan pembayaran. Dalam model PaaS, penyedia cloud memberikan platform komputasi, biasanya termasuk sistem operasi, lingkungan eksekusi bahasa pemrograman, database, dan server web. Pengembang aplikasi mengembangkan dan menjalankan perangkat lunak mereka di platform cloud alih-alih langsung membeli dan mengelola lapisan perangkat keras dan perangkat lunak yang mendasarinya. Dengan beberapa PaaS, sumber daya komputer dan penyimpanan yang mendasarinya menskalakan secara otomatis untuk menyesuaikan permintaan aplikasi sehingga pengguna cloud tidak perlu mengalokasikan sumber daya secara manual

### _Software as a service (SaaS)_

Dalam model perangkat lunak sebagai layanan (SaaS), pengguna mendapatkan akses ke perangkat lunak aplikasi dan database. Penyedia cloud mengelola infrastruktur dan platform yang menjalankan aplikasi. SaaS kadang-kadang disebut sebagai "perangkat lunak sesuai permintaan" dan biasanya diberi harga berdasarkan bayar per penggunaan atau menggunakan biaya berlangganan.[78] Dalam model SaaS, penyedia cloud menginstal dan mengoperasikan perangkat lunak aplikasi di cloud dan pengguna cloud mengakses perangkat lunak dari klien cloud. Pengguna cloud tidak mengelola infrastruktur dan platform cloud tempat aplikasi berjalan. Ini menghilangkan kebutuhan untuk menginstal dan menjalankan aplikasi di komputer pengguna cloud sendiri, yang menyederhanakan pemeliharaan dan dukungan. Aplikasi cloud berbeda dari aplikasi lain dalam skalabilitasnya—yang dapat dicapai dengan mengkloning tugas ke beberapa mesin virtual saat run-time untuk memenuhi permintaan pekerjaan yang berubah.[79] Penyeimbang beban mendistribusikan pekerjaan melalui set mesin virtual. Proses ini transparan bagi pengguna cloud, yang hanya melihat satu titik akses. Untuk mengakomodasi sejumlah besar pengguna cloud, aplikasi cloud dapat bersifat multitenant, artinya setiap mesin dapat melayani lebih dari satu organisasi pengguna cloud.
