# _Decision Tree Analysis_



## Pendahuluan {#label1}

Analisis keputusan atau *Decision Analysis*(DA) secara sederhana didefinisikan sebagai sebuah proses dalam pemilihan alternatif yang paling sesuai dengan tujuan yang telah ditetapkan. Didalam literatur, Analisis keputusan dijelaskan sebagai sebuah prosedur yang sistematis dalam men-trasformasikan masalah-masalah pengambilan keputusan yang masih belum jelas menjadi sebuah keputusan yang lebih jelas dengan urutan langkah yang transparan.

Penggunaan analisis keputusan dalam penilaian kelayakan proyek memberikan gambaran yang lebih baik terhadap _opportunity_ yang dimiliki, mengevaluasi potensi risiko, memberikan gambaran Informasi apa saja yang diperlukan dan menilai kesiapan untuk melakukan pekerjaan tersebut. Dalam konteks pengambilan keputusan, _decision analysis_ sebaiknya dilihat sebagai sebuah komunikasi antara pengambil keputusan dengan _decision facilitator_ yang bertujuan memberikan _insight_, sehingga hasil dari analisis keputusan diharapkan memberikan gambaran terbaik terhadap opsi yang dimiliki. 

Adanya faktor _uncertainty_ baik yang disertakan maupun diluar dari batasannya, memungkinkan bahwa hasil terbaik dari _decision analysis_ bisa jadi tidak linier terhadap kesuksesan proyek. Untuk mengurangi akibat dari ketidakakuratan hasil analisis, diperlukan proses analisis keputusan secara bertahap dengan perubahan informasi baru yang dimiliki seiring perjalanan proyek.

Analisis Pohon Keputusan atau _Decision Tree Analysis_ (DTA) merupakan salah satu metode yang paling sering digunakan dalam proses pengambilan keputusan, implementasi penggunaan metode ini dalam teknik perminyakan sejauh ini sering ditujukan pada tahap eksplorasi [@Bratvold2010]. 

Modul *Decision Analyis* **PertaEOR** menggunakan metode DTA dalam melakukan evalusi sebuah proyek. Modul ini didesain secara khusus untuk proyek-proyek EOR. _Workflow_  pada modul DTA untuk **PertaEOR** telah diintegrasikan dengan modul lainnya yang telah ada, seperti: Modul _screening_, Modul _predictive model_, Modul keekonomian dan modul analisis monte carlo.

```
Istilah Decision Facilitator adalah untuk memberikan cakupan yang lebih luas 
dari individu-individu yang harus terlibat dalam proses pendefinisian pengambilan keputusan.  
``` [@Mcnamee2001]

## Stuktur Analisis Pohon Keputusan _(Decision Tree Analysis)_ {#label2}
Analisis pohon keputusan atau _Decision Tree Analysis (DTA)_ merupakan salah satu metode pengambilan keputusan yang menggunakan _tree-model_ dalam memvisualisasikan opsi dan kemungkinan yang berpotensi terjadi. DTA secara terstruktur akan memetakan opsi-opsi dan kemungkinan dari sebuah kejadian menjadi sebuah cabang-cabang pohon _(tree brach)_. Proses perhitungan di _tree brach_ sangat bergantung dari _tree node_ yang di pilih, dua jenis _tree node_ yang digunakan pada DTA adalah _option node_ dan _uncertainty node_. _Option node_ adalah titik yang akan memberikan cabang berupa opsi yang bisa di pilih dan disertakan, sedangkan _uncertainty node_ adalah titik yang menggambarkan variabel _uncertainty_ dalam sebuah kejadian. Selanjutnya _uncertainty_ akan direpresentasikan dalam sebuah nilai probabilitas, hal ini akan lebih detil dijelaskan pada seksi \@ref(label19) dan seksi \@ref(label20).

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/dtree2.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-2)_Decision Tree Analysis_</p>
</div>
Gambar [ref] merupakan sebuah contoh perumusan masalah pada DTA, bagian utama dari struktur _tree_ akan dijelaskan lebih detil pada seksi \@ref(label9). Perumusan bagian-bagian yang terkait dengan cabang-cabang yang akan disertakan merupakan hasil dari proses diskusi antara pengambil keputusan dengan _decision facilitator_. Beberapa hal yang perlu disimpulkan sebelum mebangun sebuah _tree_ adalah pendefinisian: _Objective function_, _alternatif_ / skenario, dan variabel-variabel yang berkaitan dengan  biaya dan ekspektasi yang akan didapatkan. Hal ini akan dijelaskan lebih detil pada seksi \@ref(label13).

### Elemen Analisis Pohon Keputusan {#label3}
Elemen _decision analysis_ merupakan variabel yang perlu dijelaskan sebelum melakukan evaluasi, variabel tersebut harus dipahami dengan baik oleh pengambil keputusan dan _decision facilitator_. Menurut [@Bratvold2010], ada lima elemen utama pada proses studi pengambilan keputusan yaitu: 

- _Alternatives_
- _Objectives_
- _Information_
- _Payoff_
- _Decision_

Tiga elemen teratas sering disebut _"decision basis"_ [@Howard1988].

#### _Alternatives_ {#label4}
Alternatif didefinisikan sebagai sebuah pilihan _(choices)_ yang dimiliki sebelum proses pengambilan keputusan, tidak ada keputusan yang diambil jika tidak memiliki opsi [@Bratvold2010]. Proses pendefinisian alternatif membutuhkan komunikasi antara _decision facilitator_ yang terlibat. Penilaian terhadap sebuah proses pengambilan keputusan apakah sudah menyertakan seluruh opsi yang dimiliki atau belum akan dilakukan pada seksi \@ref(dq2).

#### _Objectives_ {#label5}
Tujuan yang jelas dan dapat dicapai perlu untuk ditetapkan sebelum memulai proses pengambilan keputusan. 

#### _Information_ {#label6}
#### _Payoff_ {#label7}
#### _Decision_ {#label8}

### Notasi Baku Analisis Pohon Keputusan {#label9}

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/elm.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-3)_Decision Tree Analysis_</p>
</div>
-Notasi Node
-Notasi Tree
-Notasi Diagram

## Alur Kerja Pengambilan Keputusan {#label10}

## _Decision Tree Analysis Workflow_ {#label11}

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/flow.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-4)_Decision Tree Analysis_</p>
</div>

### _Framing The Problem_ {#label12}

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/fram1.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-5)_Decision Tree Analysis_</p>
</div>

_Framing_ adalah memastikan bahwa terdapat orang-orang yang tepat untuk mengatasi suatu masalah dengan perspektif yang tepat. Terdapat tiga dimensi kunci dalam melakukan _framing_ dengan tepat: tujuan, cakupan, dan perspektif. Ketika tim memulai pekerjaan dalam suatu keputusan, pada beberapa kesempatan terdapat beberapa anggota yang tidak setuju dengan apa yang dilakukan. Tujuan yang jelas harus ditetapkan dan disetujui sebelum tim memulai pekerjaan.
Dimensi cakupan dalam _framing_ biasanya mudah dilakukan dan dipahami. Cakupan bertujuan untuk menetapkan batasan masalah, jenis-jenis solusi, sumber informasi yang akan membantu dalam penentuan solusi, dan kriteria yang akan digunakan pada pilihan.

Dimensi perspektif pada _framing_ lebih sulit untuk dideskripsikan. Kita memiliki metode dalam menghadapi berbagai informasi yang kita terima. Analoginya bahwa setiap orang sudah memiliki saringan tersendiri: beberapa informasi diklasifikasikan tidak relevan dan tidak digunakan dari awal proses pembentukan persepsi. Analogi lain adalah suatu bingkai gambar: kita menaruh bingkai di sekeliling masalah, mengeluarkan beberapa hal pada gambar dan memasukkan beberapa hal ke dalamnya. Ketika masalah lintas displin terjadi, penyaringan masalah perlu direvisi dan _frame_ perlu diluaskan. Tidak mungkin tim dapat berpikir strategis atau dapat mengimplementasikan, kecuali jika seluruh anggota memiliki _frame_ yang sama. Kesuksesan dalam _framing_ telah terbukti sangat krusial dalam menentukan kualitas keputusan. Proses-proses utama dan produk-produk pada proses _framing_ adalah sebagi berikut:

1. __Issue Raising__: Kegiatan ini memiliki tiga tujuan: memunculkan materi yang akan dibahas sebanyak mungkin, menyoroti _frame_ antar sesama anggota tim, dan mengembangkan rasa kepemilikan tim terhadap keputusan yang akan diselesaikan.
2. __Project Vision Statement__: Dilakukan dengan menjawab empat pertanyaan mendasar: Apa yang akan kita lakukan? Kenapa kita melakukan ini? Bagaimana kita tahu bahwa kita akan berhasil? Bagaimana jika gagal?
3. __Decision Hierarchy__: Merupakan _tools_ yang digunakan untuk menjabarkan rangkaian keputusan yang kompleks seperti gambar di bawah ini.
<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/st.png" alt="_Strategy Table_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-6)_Strategy Table_</p>
</div>
5. __Influence Diagram__: Merupakan _tools_ yang dihunakan untuk melacak keputusan, ketidakpastian, dan keterhubungan di antara keduanya. _Influence diagram_ sangat penting untuk mengembangkan pemahaman tim proyek terhadap masalah dan dalam mengatur pekerjaan.
<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/id.png" alt="_Influence Diagram_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-7)_Influence Diagram_</p>
</div>
6. __Decision Criterion__: Sebelum keputusan dibuat, kriteria keputusan harus ditetapkan dan disetujui bersama. Kriteria terpenting dalam pengambilan keputusan biasanya adalah NPV. 

### _Deterministic Analysis_ {#label13}

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/sens.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-8)_Decision Tree Analysis_</p>
</div>
_Deterministic analysis_ digunakan untuk mengevaluasi keekonomian model dari setiap strategi yang telah didapat dari proses _framing_. Penilaian kecenderungan variabilitas dilakukan untuk setiap parameter untuk mengetahui parameter mana yang memiliki pengaruh besar terhadap keekonomian. Proses ini dilakukan dengan menggunakan _Tornado Chart_ arau _Spider Chart_ dengan melakukan variasi: nilai _low_, _base_, dan _high_ untuk setiap parameternya.

### _Probabilistic Analysis_ {#label14}
<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/forward.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-9)_Decision Tree Analysis_</p>
</div>
Bilamana _deterministic analysis_ berfokus untuk mengkuantifikasi pengaruh setiap parameter terhadap keekonomian proyek maka dalam _probabilistic analysis_, seluruh parameter divariasikan secara bersamaan dan pengaruh parameter ketidakpastian yang dikombinasikan dalam proyek dikuantifikasikan sebagai _economic value_ dengan probabilitas terkait yang terjadi. _Expected Value_ (EV) dan probabilitas hasil rata-rata beban juga dihitung. Model probabilistik dibangun dari _decision tree analysis_. Parameter-parameter yang mendominasi dalam _Tornado Chart_ digunakan untuk membangun _decision tree_. _Decision tree_ digunakan untuk mengevaluasi seluruh kombinasi kemungkinan hasil yang mungkin terjadi dengan setiap probabilitasnya dan NPV untuk setiap opsi pengembangan. Hasil dari _decision tree analysis_ digambarkan dalam bentuk _Cummulative Distribution Function_ atau _Expectation Curve_ dengan NPV berada di sumbu x dan probabilitas kumulatifnya berada di sumbu y.

### _Appraisal_ {#label15}

#### _Value of Information_ {#label16}

Kebanyakan kegiatan yang _petroleum engineer_ dan _geoscientist_ lakukan, melibatkan kegiatan memperoleh informasi dari satu kegiatan lain ke yang lain. Istilah "informasi" di sini bermakna luas yang mencakup pengambilan data, melakukan studi teknis, menyewa konsultan, melakukan tes diagnostik, dan seterusnya. Harapannya adalah bahwa mengurangi ketidakpastian meningkatkan kesempatan untuk mendapatkan hasil yang diinginkan. Namun nyatanya, alasan satu-satunya dilakukan kegiatan pengumpulan informasi atau analisis teknis adalah untuk memenuhi persyaratan peraturan. Pertanyaan mendasar untuk proses mendapatkan informasi adalah apakah pengurangan ketidakpastian itu sebanding dengan biaya untuk mendapatkan informasi. _Value of Information_ (VoI) dirancang untuk menjawab pertanyaan tersebut.

Tujuan dari perhitungan VoI, yakni untuk mengestimasi nilai dari kegiatan pengumpulan informasi sehingga suatu keputusan akan diimplementasikan atau tidaknya dibuat berdasarkan basis ekonomi. Agar informasi memiliki nilai, maka perlu adanya perhitungan probabilistik antara informasi dan hasil dari suatu kejadian ketidakpastian. Dalam perhitungan VoI diperlukan beberapa informasi sebagai berikut:

1. _Prior probability_, estimasi probabilitas dari kemungkinan hasil yang dapat diambil kuantitasnya (misalnya terdapat peluang 30% _recovery factor_ rendah dan peluang 70% _recovery factor_ tinggi).
2. _Reliaility(likelihood)_, estimasi probabilitias efisiensi suatu informasi dalam memprediksi hasil (misalnya saat _recovery factor_ diketahui tinggi, studi simulasi reservoir 3D mengindikasikan dengan benar sebesar 80%).
3. Nilai moneter proyek untuk setiap kombinasi hasil yang memungkinkan (contohnya NPV 600 USD jika _recovery factor_ tinggi dan NPV 100 USD jika rendah).

Dalam menghitung VoI, perhitungan biasanya dilakukan dengan menggunakan _decision tree_. Terdapat dua _decision tree_ yang dihitung, yaitu nilai proyek dengan estimasi probabilitas yang ada dan perkiraan nilai projek baru dengan probabilitas yang diperbarui setelah adanya kegiatan memperoleh informasi. Perbedaan kedua nilai tersebut disebut sebagi _expected VoI_. Nilai _expected VoI_ terbagi menjadi dua, yaitu:

1. EVPI (*Expected Value of Perfect Information*), nilai tersebut diperoleh ketika suatu kegiatan mampu memperoleh hasil informasi dengan tingkat akurasi 100%.
2. EVII (*Expected Value of Imperfect Information*), adapun terdapat kondisi dimana informasi yang didapat tidaklah selalu dapat memberikan kepastian (tingkat akurasi di abwah 100%).

Pada dua nilai tersebut, EVPI merupakan batas atas nilai suatu informasi. Di sisi lain bisa jadi kegiatan pengambilan informasi ini tidak mengakibatkan adanya perubahan probilitas. _Expected value_ ini dapat dijadikan acuan _decision maker_ untuk membuat keputusan apakah akan melakukan kegiatan untuk memperoleh informasi atau tidak. Ketika nilai _expected value_ berada di bawah biaya untuk memperoleh informasi maka jawabannya jelas, yaitu tidak perlu diproses. Namun, ketika _expected value_ nilainya ada di ata biaya untuk memperoleh informasi maka _decision maker_ dapat mempertimbangkannya. Terdapat beberapa langkah dalam menghitung VoI sebagai berikut:

1. Menghitung _expected value_ suatu keputusan yang akan dibuat pada kondisi belum terdapat informasi atau bisa disebut dengan istilah _base project_.
2. Mengformulasi struktur _decision tree_ untuk memasukkan informasi baru. Dimulai dengan menambahkan _branch_ baru pada _node_ pertama pada _decision tree_ untuk merepresentasikan pilihan untuk memperoleh informasi. _Branch_ ini harus mengarah pada _uncertainty node_, yaitu _event_ ketidakpastian yang menjadi hasil dari kegiatan memperoleh informasi. Setiap hasil yangn memungkinkan dari _event_ untuk memperoleh informasi ditambahkan _tree_ yang merepresestasikan _base project_. 
3. Menghitung EVPI.
4. Menghitung EVII, langkah ini memiliki beberapa turunan, yaitu:
   a. Mengestimasi probabilitas _reliability (likelihood)_, *P(info __says__ | real world __is__ )*
   b. Menghitung probabilitas _updated (posterior)_ 
   c. Memasukkan _posterior_ pada _decision tree_ 
   d. Menghitung nilai proyek
5. Menghitung EVII dengan nilai probabilitas _reliability (likelihood)_ yang berbeda-beda. 

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/voi.png" alt="_Decision Tree Analysis_" width="45%" />
<p class="caption">(\#fig:unnamed-chunk-10)_Decision Tree Analysis_</p>
</div>

#### _Decision Quality_ {#label17}

Terdapat suatu perbedaan definisi yang mendasar antara keputusan dan hasil. Hasil yang baik adalah apa yang kita inginkan sedangkan keputusan yang baik adalah apa yang dapat dilakukan untuk memaksimalkan kemungkinan hasil yang baik. Keputusan yang baik tidak menjamin hasil yang baik tapi pada umumnya keputusan yang baik akan mengarah pada hasil yang baik sehingga dari definisi ini maka yang dapat dilakukan adalah membuat keputusan yang baik, bukan hasil yang baik. Bagi _decision-maker_ tunggal, biasanya penentuan apakah keputusan itu "baik" dapat dilakukan dengan jelas. Di sisi lain, jika berada dalam suatu lingkungan yang terdiri dari beberapa _decision-maker_, maka penentuan organisasi itu siap mengambil keputusan menjadi cukup sulit. Dalam kondisi tersebut, perlu ada persetujuaan mengenai kualitas dari alternatif, informasi, dan _value_. _Decision Quality_ di sini berperan sebagai alat yang berfungsi untuk mengevaluasi kualitas dari keputusan.

Setelah mencapi tahap pendeklarasian keputusan, perlu dipastikan bahwa proses menentukan keputusan tersebut sudah mencapai keputusan yang berkualitas yang dilakukan dengan mengevaluasi keputusan tersebut berdasarkan 6 elemen _Decision Quality_. Matheson dan Matheson (1998) mensurvei sejumlah besar _decison-maker_ dan menggabungan tanggapan mereka dengan pemikiran akademisi untuk mengembangkan kerangka kerja yang mengevaluasi kualitas dari keputusan dalam 6 dimensi seperti Gambar di bawah ini.

<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/bagan.png" alt="Elemen _Decision Quality_" width="55%" />
<p class="caption">(\#fig:unnamed-chunk-11)Elemen _Decision Quality_</p>
</div>

Elemen-elemen tersebut direpresentasikan dalam sebagai hubungan dalam rantai keputusan akan hanya sekuat mata rantai yang paling lemah. Jika setiap elemen kuat, maka kualitas keputusan adalah tinggi. Jika salah satu elemen lemah, maka kualitas keputusan tidak lebih baik dari elemen yang lemah tersebut. Setiap elemen harus dipertimbangkan berdasarkan perspektif kepala dan hati karena keputusan harus masuk akal dan terasa benar. Setiap dari 6 elemen tersebut harus mencapai kualitas terbaiknya: _helpful frame_, _creative alternatives_, _useful information_, _clear values_, _sound reasoning_, dan _commitment to follow through_.

##### _1. Helpful Frame_ {#dq1}

Titik awal adalah mengidentifikasi keputusan yang akan dibuat secara jelas dan seberapa akurat keputusan itu untuk dinilai. _Helpful frame_ memperjelas situasi yang akan dipecahkan. Langkah pada tahap ini sangat penting. Mendapat pertanyaan yang baik dari kerangka masalah yang buruk adalah tidak berguna. Sebagai _engineer_ dan _geoscientists_, mereka cenderung untuk segera menghasilkan model (sebagai contoh, _tools_ simulasi, _spreadsheets_, model dan analisi geologi, dan lain-lain) saat menghadapi situasi keputusan yang baru. _Decision-maker_ yang sudah ahli, bagaimanapun, mengetahui bahwa mereka harus mengidentifikasi secara sadar apa uang harus diputuskan. Terlalu sering terdesak waktu dan membutuhkan jawaban yang segera, _decision-maker_ yang belum berpengalaman terjun ke dalam untuk mengumpulkan informasi atau membangun model kuantitatif tanpa berhenti untuk mengajukan pertanyaan-pertanyaan sebagai berikut ini:

- Apa yang diputuskan?
- Apa yang tidak diputuskan? 
- Apa yang akan didapat dari yang diberi?
- Apakah asumsi-asumsi sudah ditentukan secara jelas?

Terlepas dari seberapa sedikit waktu yang tersedia, seseorag tidak boleh melewatkan menanyakan pertanyaan-pertanyaan _framing-type_. Jika tidak bertanya dengan baik, maka memungkinkan akan lebih banyak waktu yang terbuang daripada "menghemat" karena mengambil risiko memecahkan masalah yang salah. 

##### _2. Creative Alternatives_ {#dq2}

Kurangnya tingkat kreativitas dan fleksibilitas alternatif adalah salah satu alasan utama perusahaan-perusahaan memiliki kesulitan dalam mencapai keputusan yang berkualitas tinggi. Bagian ini dapat diilustrasikan dengan menanyakan pertanyaan-pertanyaan sebagai berikut ini:

- Apa saja pilihan-pilihan kita?
- Apakah alternatif-alternatif tersebut dapat dilakukan?
- Apakah alternatif tersebut memecahkan masalah?
- Apakah berbagai alternatif lain sudah dipertimbangkan?

Bagian ini membutuhkan suatu tim untuk menggali ide-ide dan menjadi kreatif. Setiap alternatif yang telah diindetifikasi harus konsisten secara logika dan bisa dilakukan. Kualitas setiap keputusan hanya bisa sebaik alternatifnya yang telah diidentifikasi, jika tidak ada alternatif maka tidak ada keputusan.

##### _3. Useful Information_ {#dq3}

Bagian ini menjelaskan kebutuhan untuk menggunakan informasi yang terpercaya dan relevan yang berkaitan dengan penentuan keputusan. Hal tersebut dapat diilustrasikan dengan menanyakan pertanyaan-pertanyaan di bawah ini:

- Apa yang kita ketahui?
- Apakah kita memiliki informasi yang penting?
- Apakah informasi tersebut tidak bias?
- Seberapa akurat kita di masa lalu dengan penilaian serupa?
- Informasi apa dikumpulkan dengan adanya lebih banyak waktu/uang/sumber daya? 

Perusahaan-perusahaan dan individu-individu seringkali baik dalam memasukkan apa yang mereka tahu dalam analisis. Namun, keenderungan yang sangat berbahaya diilustrasikan dengan tepat sebagai berikut: _"Bukan banyaknya hal yang tidak kita ketahui yang membuat kita dalam masalah. Namun, hal-hal yang kita ketahui tidak seperti itu seharusnya"_. Kunci dari kualitas bagian ini adalah informasi mengenai apa yang belum diketahui (yaitu, keterbatasan pengetahuan). Terlalu banyak keputusan yang dibuat berdasarkan kesalahan atau kekurangan informasi. Penentuan kebutuhan informasi dan mengumpulan informasi yang bermanfaat secara sadar sebelum eksekusi merupakan hal yang sangat penting dilakukan untuk membuat keputusan yang baik.

##### _4. Clear Values_ {#dq4}

Seperti yang telah dibahas sebelumnya, komponen yang sangat penting untuk memebuat keputusan yang baik adalah mendefinisikan dan mengartikulasikan dengan jelas kriteria untuk mengukur _value_ dari alternatif-alternatif dan bagaimana perusahaan membuat _tradeoffs_ pada setiap alternatif. Untuk kebanyakan perusahaan-perusahaan E&P, kriteria kuncinya adalah beberapa dari kombinasi NPV, _cash flow_, produksi, dan penggantian _reserves_. Pertanyaan-pertanyaan yang dapat ditanyakan adalah sebagai berikut:

- Konsekuensi-konsekuensi apa saja yang perlu diperhatikan? 
- _Tradeoff_ apa saja yang dihasilkan?
- Apakah kita bisa mengukur _value_ secara akurat di masa lalu?

_Tradeoff_ seringkali dibutuhkan, dan kejelasan mengenai bagaimana kriteria dirankingkan juga sangat penting. _Value metric_ yang biasa digunakan pada E&P adalah pengurangan _uncertainty_ atau peningkatan kepercayaan. Seperti yang telah dibahas sebelumnya, _metric-metric_ ini tidak memiliki nilai ekonomi. Bahaya lain adalah mengabaikan _metric_ keputusan yang _intangible_, seperti reputasi atau keamanan perusahaan.

##### _5. Sound Reasoning_ {#dq5}

_Reasoning_ adalah bagaimana kita mengkombinasikan alternatif, informasi, dan _value_ agar menjadi keputusan. Itu adalah jawaban kita atas pertanyaan: "Kami memilih alternif ini karena .....". Bagian ini membutuhkan penggabungan input dari bagian-bagian sebelumnya untuk menentukan alternatif manakah yang menghasilkan _value_ terbanyak. Pada kebanyakan kasus, situasi keputusan cukup kompleks untuk memercayakan pada intuisi dan membutuhkan model. Bagian ini dapt diilustrasikan dengan menanyakan pertanyaan: "Apakah saya berpikir jernih tentang ini?".

Pada industri E&P tidak terbiasa untuk mengembangkan model yang terlalu rumit untuk menyampaikan kejelasan dan transparansi yang dibutuhkan. Prosedur biasa dalam pengembangan "*base case*" terkadang menghasilkan determinisktik model yang terlalu detail dan kompleks yang mengabaikan tidak hanya _uncertainties_ tetapi juga variabel-variabel kunci. 

Tujuan dari evaluasi adalah untuk mengembangkan rekomendasi yang jelas, transparan, dan mudah dimengerti. Rekomendasi yang mampu memaksimalkan _value_ dari _decision-maker_.

##### _6. Commitment to Follow Through_ {#dq6}

Bagian ini menggerakkan keputusan ke tahap implementasi, yang mana tidak trivial. Keputusan terbaik tidak berguna jika organisasi tidak mengimplementasikannya. Jika komitmen yang dimilki hanya setengah hati, maka pelaksanaanya biasanya kurang intens dan mungkin tidak mencapai hasil yang terbaik. Bagian ini dapat diilustrasikan dengan menanyakan beberapa pertanyaan:

- Apakah rekomendasi sesuai dan bisa dilakukan?
- Bagaimana kita akan mengkomunikasikan keputusan?
- Apakah organisasi bisa mendukung keputusan tersebut?
- Apakah sudah terdapat rencana implementasi?

Pelaksanaan yang sukses membutuhkan sumber daya, seperti waktu, usaha, uang, atau bantuan dari pihak lain. Selain itu pula juga membutuhkan kesiapan untuk mengatasi permasalahan. Berikut ini adalah beberapa contoh pertanyaan yang ada dalam modul _Decision Quality_.


|   |Question                                                                                                                             |Kategori                     |
|:--|:------------------------------------------------------------------------------------------------------------------------------------|:----------------------------|
|1  |apakah sudah tersedia analisa HSSE dan amdal?                                                                                        |Commitment to Follow Through |
|2  |apakah sudah dilaksanakan evaluasi keekonomian? (IRR > 10%)                                                                          |Commitment to Follow Through |
|3  |apakah sudah memiliki pattern design?                                                                                                |Commitment to Follow Through |
|4  |apakah telah membuat program monitoring dan surveillance?                                                                            |Commitment to Follow Through |
|5  |bagaimana kondisi operasional saat ini (kondisi sumur, fasilitas produksi, dan sumber media EOR?                                     |Commitment to Follow Through |
|6  |apakah project telah mendapat persetujuan dari pihak-pihak terkait? (Mulai dari pengadaan barang sampai monitoring dan surveillance) |Commitment to Follow Through |
|7  |apakah terdapat dana yang teralokasi khusus unutuk kegiatan EOR?                                                                     |Commitment to Follow Through |
|8  |apakah ada sumber daya manusia yang capable dibidang EOR?                                                                            |Commitment to Follow Through |
|9  |apakah sudah melalui uji laboratorium yang baik? (IRF > 10%)                                                                         |Commitment to Follow Through |
|10 |apakah baseline sudah dibuat dan disepekati semua pihak?                                                                             |Commitment to Follow Through |
|11 |apakah sudah memiliki program abandomant and site restoration?                                                                       |Commitment to Follow Through |
|12 |apakah sudah membuat project schedule?                                                                                               |Commitment to Follow Through |
|13 |apakah sudah memiliki model GGRPF?                                                                                                   |Commitment to Follow Through |
|14 |apakah sudah membuat forecast produksi?                                                                                              |Commitment to Follow Through |
|15 |Apakah jelas latar belakang, isi dan tujuan usulan?                                                                                  |Helpful Frame                |
|16 |Seberapa besar pengetahuan dari stakeholder terhadap usulan?                                                                         |Helpful Frame                |
|17 |Seberapa besar prioritas dari usulan?                                                                                                |Clear Value                  |
|18 |Seberapa besar pengaruh ke anggaran dari usulan?                                                                                     |Clear Value                  |
|19 |Apakah ada kemungkinan alternative lain dari usulan?                                                                                 |Creative Alternatives        |
|20 |Apakah dari usulan ada opsi yang bias dikurangi/efisien?                                                                             |Creative Alternatives        |
|21 |Apakah usulan Realistik dan bias dilaksanakan sesuai waktu?                                                                          |Creative Alternatives        |
|22 |Bila usulan diterima, apa yang bias didapat untuk menguntungkan PTM?                                                                 |Clear Value                  |
|23 |Seberapa lengkap dari usulan yang harus disampaikan?                                                                                 |Useful Information           |
|24 |Seberapa yakin dari sumber informasi/teknologi usulan?                                                                               |Useful Information           |
|25 |Seberapa jelas usulan dari kebutuhan dan fakta kegunaannya?                                                                          |Clear Value                  |
|26 |Seberapa jauh dapat diindentifikasi dan diklarifikasi kriteria usulan yang paling penting?                                           |Clear Value                  |
|27 |Seberapa baik kriteria usulan dalam prioritas yang mencerminkan Keuntungan internal PTM?                                             |Clear Value                  |
|28 |Seberapa komprehensif kriteria untuk mengukur kesuksesan dalam tujuan proyek dan keuntungan PTM?                                     |Clear Value                  |
|29 |Seberapa lengkap dan komprehensif dari riset, logic dan temuan dari usulan?                                                          |Sound Reasoning              |
|30 |Seberapa jelas dapat dijelaskan dari pilihan opsi dari opsi usulan yang diusulkan?                                                   |Sound Reasoning              |
|31 |Seberapa lengkap dari organisasi yang mengevaluasi usulan ini?                                                                       |Commitment to Follow Through |
|32 |Seberapa yakin hasil yang didapat dari usulan?                                                                                       |Commitment to Follow Through |
|33 |Apakah PTM siap dari sisi resource untuk melaksanakan usulan ini?                                                                    |Commitment to Follow Through |
|34 |Seberapa jauh PTM terlewatkan dari substantive analisis yang berpengaruh terhadap kualitas usulan?                                   |Clear Value                  |
|NA |NA                                                                                                                                   |NA                           |

Table: <span style="color: grey;"> Tabel 13.1: Pertanyaan-Pertanyaan dalam Modul Decision Quality </span>

## Pemetaan Ketidakpastian {#label18}
### Apa itu _Uncertainty_ {#label19}
### _Uncertainty & Probability_ {#label20}
<div class="figure" style="text-align: center">
<img src="images/decisionanalysis/dist.png" alt="_Decision Tree Analysis_" width="95%" />
<p class="caption">(\#fig:unnamed-chunk-13)_Decision Tree Analysis_</p>
</div>

## Menciptakan Nilai dari Sebuah Ketidakpastian {#label21}
### _Value of Information_ {#label22}
### _Value of Flexibility_ {#label23}

\@ref(label1)

## Tantangan Dalam Pengambilan Keputusan {#label24}
## Bias {#label25}
## _Encoding Probabilities_ {#label26}

[bookdown](https://bookdown.org/yihui/bookdown/cross-references.html)



