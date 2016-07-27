.. danyProject documentation master file, created by
   sphinx-quickstart on Mon Nov 24 16:21:23 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


*******************************
 	PPIDS Academy Tutorial Book
*******************************

-------------------------------------------------------
*(Or how to be a geospatial web developer in 10 days)*
-------------------------------------------------------

.. raw:: html

   <hr></br>


Buku (*online*) ini adalah panduan resmi untuk mahasiswa anggota PPIDS Academy yang diselenggarakan oleh Pusat Pengembangan
Infrastruktur Data Spasial (PPIDS) UGM Yogyakarta. Buku ini berperan sebagai panduan pada saat pelatihan maupun sebagai bahan
pembelajaran mandiri di luar pelatihan.

.. _konten-workshop:

Daftar Materi
================

.. toctree::
   :maxdepth: 4

   hari_1.rst
   hari_2.rst
   lisensi.rst


.. _tentang-kami:

Tentang Kami
=================

Pusat Pengembangan Infrastruktur Data Spasial (PPIDS) didirikan berdasarkan
pada Perjanjian Kerjasama antara Deputi Infrastruktur Data Spasial
(IDS) Bakosurtanal (sekarang bernama Badan Informasi Geospasial/BIG)
dengan Dekan Fakultas Teknik Universitas Gadjah Mada pada tanggal 29 Juli
2011. Kepengurusan PPIDS sendiri baru ditetapkan oleh Dekan Fakultas Teknik
pada tanggal 28 September 2012. Pengurus PPIDS ini terdiri dari beberapa
peneliti dan asisten peneliti yang bekerja di lingkungan Universitas Gadjah
Mada Yogyakarta. Sejak awal berdirinya, PPIDS telah terlibat dalam berbagai
kegiatan terkait dengan pengembangan infrastruktur data spasial di Indonesia
melalui kegiatan penelitian, pelatihan dan pengabdian masyarakat.

Beberapa kegiatan yang telah dilaksanakan oleh PPIDS-UGM antara lain:

* Evaluasi data OpenStreetMap di Padang, Jakarta, Bandung, Yogyakarta,
  Surabaya, dan Dompu
* Pelatihan QGIS dan InaSAFE di berbagai kota di Indonesia (Kerjasama dengan
  HOT-OSM Indonesia)
* Pelatihan perangkat lunak OpenSource untuk penanggulangan bencana Jawa Barat
* Adaptasi seri ISO 19100 untuk Standar Nasional Indonesia (SNI) bidang
  geospasial
* Evaluasi Kesiapan Penerapan IDS pada pemerintah daerah di Indonesia
* Pengembangan Geoportal pada berbagai Kementrian/Lembaga/Pemda
* dan lain-lain


.. _tentang-academy:

Tentang PPIDS-Academy
=====================

Untuk mengantisipasi tingginya permintaan pasar atas pengembangan infrastruktur data spasial
baik dalam bentuk penyiapan SDM maupun pengembangan teknologi, pada tahun 2016 PPIDS-UGM
membentuk PPIDS-Academy yang terdiri dari lebih-kurang 20 orang mahasiswa yang dilatih
dan dipersiapkan secara khusus untuk membantu PPIDS dalam melaksanakan tugas yang dibebankan.

Tujuan utama dari PPIDS-Academy adalah untuk mempersiapkan tenaga professional muda yang
mampu bekerja di bidang informasi geospasial untuk meningkatkan kapasitas mahasiswa
dalam memenuhi permintaan pasar yang kian tinggi. PPIDS-Academy berlangsung selama satu semester dengan
jumlah pertemuan sekurang-kurangnya 10 kali. PPIDS memberikan sertifikat kelulusan bagi mahasiswa peserta
PPIDS-Academy yang dapat menghadiri 80% dari total pertemuan yang diselenggarakan. Sebagai catatan, peserta
PPIDS-Academy tidak dipungut biaya sama sekali.

Beberapa materi pokok yang disampaikan pada **PPIDS-Academy** adalah sebagai berikut:

* Teknologi Internet dan Web
* Dasar-dasar WebGIS
* Client-side dan Server-side scripting
* Webmap APIs (OpenLayers, Gmap API, ArcGIS API dan Leaflet)
* Cloud WebGIS (GISCloud, Mapbox dan TileMill, serta CartoDB)
* Server Data Spasial (ArcGIS Server, Geoserver)
* Manajemen Geoportal (Geonode dan OpenGeo Suite)
* Pemetaan web tiga dimensi (Cessium, ThreeJS, X3DOM dan CityGML)
* Location Based Service (LBS) dan WebGIS dengan Android
* Fullstack WebGIS development (MongoDB, ExpressJS, AngularJS dan NodeJS)
* Cloud-computing WebGIS


.. _sistematika:

Sistematika Penulisan Buku
===========================


Buku ini dibagi menjadi 10 bagian sesuai dengan jumlah pertemuan minimal yang diselenggarakan dalam
PPIDS-Academy. Tiap bagian (satu hari pertemuan) membahas mengenai satu topik secara global dengan materi praktek yang
dapat langsung diterapkan untuk memudahkan pemahaman. Kesepakatan mengenai notasi dan penulisan merujuk pada penulisan dokumen
dengan ReST (*reStructuredText*). Sebagai contoh, ``tulisan seperti ini`` menunjukkan nama file, perintah atau tombol. Penulisan
kode dilakukan seperti ini:

.. highlight:: python

.. code-block:: python
   :caption: **hello-def.py**
   :linenos:

    def hello():
        #Greetings!
        return "Hello World"


.. raw:: html

        </br>

.. highlight:: javascript

atau seperti ini::

      function hello(): {
        return "Hello World";
      }

.. raw:: html

      </br>

Selain itu, beberapa tanda khusus seperti berikut diberikan untuk menandai hal-hal penting:

.. note:: Bagian seperti ini menunjukkan catatan

.. warning:: Bagian seperti ini adalah peringatan

.. danger:: Bahaya! perhatikan dengan seksama


Panduan ini mengasumsikan anda menggunakan Sistem Operasi berbasis Windows. Meskipun demikian
materi utama dari panduan ini tetap dapat digunakan pada berbagai sistem operasi lain dengan sedikit penyesuaian.

.. _masukan-saran:

Masukan dan Saran
===================

Untuk perbaikan dan masukan terkait dokumen ini anda dapat mengubungi kami
di alamat email ``ppids@ugm.ac.id`` atau ``laksono.dany@gmail.ugm.ac.id``.


.. _lisensi:

Lisensi Dokumen
=================
Copyright (c) 2016 Pusat Pengembangan Infrastruktur Data Spasial UGM

Pembaca diijinkan untuk mengkopi, membagikan dan atau memodifikasi dokumen
ini sesuai dengan persyaratan yang diijinkan oleh GNU Free Documentation
License, Versi 1.3 atau seterusnya. Lisensi lengkap dapat dilihat pada bagian
`Lisensi Dokumen <lisensi.html>`_.



.. raw:: latex

   \pagebreak[4]
