---
icon: database
---

# Data Master

## Master Customer

### Master Customer Direct ( di ERP Netsuite )

Data master customer diambil dari Netsuite, di Netsuite telah disediakan laporan yang bisa di download kedalam format CSV untuk kemudian di upload kembali di applikasi SiskA.

#### Download Master Customer Netsuite

* Buka Netsuite,&#x20;
* Lalu ke menu **Analytics** > **Workbooks** dan pilih **ACP - Customer**,
* Klik pada icon bergambar kertas

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>Download data customer dari Netsuite</p></figcaption></figure>

* Yang selanjutnya akan terdownload file dengan ekstensi .CSV
* Setelah file terdownload lanjutkan dengan buka Applikasi SiskA, lalu buka menu **Data Warehouse**, pilih **Customer**
* Klik pada tombol **Upload Data**, lalu pilih file yg customer yang telah didownload sebelumnya

&#x20;

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Upload CSV dari Netsuite</p></figcaption></figure>

* Untuk Upload data customer ini juga bisa dilakukan dari menu **Applikasi** > **SFA** > **Upload Data Netsuite**



### Master Customer DAR

Master customer DAR adalah data yang digunakan oleh pengguna applikasi DAR dalam melakukan aktivitas baik itu kunjungan, ataupun aktivitas lainnya.&#x20;

Untuk mengelola data customer DAR dilakukan secara mandiri oleh user pada applikasi DAR, namun demikian pada DAR versi 3, telah pula ditambahkan fitur untuk data customer yang digunakan adalah data customer yg terdaftar dalam Customer Distributor, artinya user DAR tidak perlu lagi mengelola data Customernya.



## Master Item

Master item adalah data seluruh item product yang digunakan untuk transaksi dari mulai Sales Order, sampai dengan inventory. Data ini didapatkan dari Applikasi ERP Netsuite dengan cara di import

