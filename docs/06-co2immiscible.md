# CO~2~ Immiscible Predictive Model



## Pendahuluan

Pendesakan secara _immiscible_ terjadi ketika fasa antara dua fluida terpisah dengan _interphase_ yang jelas. Pendesakan dengan teknik ini sangat potensial untuk kondisi:

- _Viscous oil_
- _Shallow reservoir_
- _Depleted reservoir_ dan
- _Thin formation_

Metode _miscible displacement_ lebih popular hingga kini karena menghasilkan efisiensi pendesakan optimum akibat penurunan _Interfacial Tension_ (IFT) antara minyak-gas. Namun jika tekanan reservoir telah terdeplesi hingga di bawah tekanan minimum _miscible_ (*minimum miscible pressure*) atau minyak didominasi oleh fraksi berat (C~7+~) maka kondisi _miscible_ tidak dapat tercapai sehingga metode _miscible displacement_ tidak lagi bermanfaat.

Mekanisme pendesakan dengan _immiscible displacement_ dilakukan dengan menurunkan viskositas minyak berat dengan men-_swelling_ fraksi berat minyak. Untuk API minyak di bawah 25$^\circ$API, secara umum, kondisi _miscible_ tidak dapat tercapai. Teknik _immiscible displacement_ merupakan alternatif yang baik untuk kondisi ini karena penurunan viskositas akan signifikan pada reservoir dan _pipeline_/transportasi. Selain itu, walaupun metode EOR lainnya seperti _steamflooding_ sangat banyak dilakukan, metode ini semakin lama cenderung dinilai lebih mahal dan banyak memberikan dampak polusi lingkungan.

Mekanisme transfer massa yang biasanya terjadi pada *immiscible* CO~2~ *flooding* yaitu kelarutan, difusi, dan dispersi. Kelarutan (*solubility*) merupakan fungsi dari tekanan, temperatur, dan salinitas air. Semakin tinggi tekanan dan semakin rendah temperatur, maka kelarutan CO~2~ akan semakin meningkat. Untuk kondisi tekanan rendah (1000 psi), efek kelarutan CO~2~ pada minyak akan dominan terjadi. CO~2~ bersifat lebih larut pada hidrokarbon dibandingkan dengan fasa _liquid_ lainnya. Hadirnya CO~2~ juga akan menurunkan viskositas minyak dan menaikkan viskositas air.

Difusi merupakan mekanisme transfer massa secara makroskopik akibat gerakan acak molekul dan tidak bergantung pada proses konveksi. Mekanisme difusi akan membantu CO~2~ menembus _heavy oil_ yang akan menurunkan efek gravitasi dan _viscous instability_.

Ketika CO~2~ mendesak dan melarut dalam fasa minyak, terdapat beberapa efek yang akan terjadi dalam perubahan sifat-sifat minyak,

- Penurunan viskositas minyak
- _Swelling_
- Penurunan _interfacial tension_
- _Blowdown_, dan
- Pengendapan _asphalt_

### Mekanisme Pendesakan Secara _Immiscible_

Aliran CO~2~ dapat dilakukan baik secara _immiscible_ maupun _miscible_. Secara umum tipe _miscible_ lebih dipilih karena dengan teknik ini akan diperoleh _recovery_ minyak yang lebih besar. Namun hal ini tidak selalu terjadi di lapangan karena tekanan injeksi akan dibatasi oleh tekanan rekah reservoir. Mekanisme _recovery_ minyak untuk pendesakan _immiscible_ dipengaruhi oleh temperatur reservoir, tekanan injeksi, komposisi minyak, dan kemurnian dari CO~2~.

Terdapat empat kontributor dalam _immiscible displacement_ untuk meningkatkan _recovery_ minyak: _swelling_ (ekspansi volume) minyak, penurunan viskositas, penurunan _interfacial tension_, dan _blowdown recovery_. CO~2~ bersifat sangat larut dalam minyak dan seiring dengan melarutnya CO~2~, volume minyak akan meningkat mulai dari 10% hingga 40%. Penurunan viskositas dapat terjadi dalam rentang 1/10 hingga 1/100 dari viskositas awal. Penurunan viskositas ini akan meningkatkan mobilitas dari minyak sehingga _recovery_ menjadi lebih besar. Selain itu, setelah fasa injeksi, tekanan reservoir dapat turun sehingga CO~2~ yang sebelumnya larut akan keluar dan mendesak minyak menuju sumur produksi. Mekanisme _blowdown recovery_ ini mirip dengan mekanisme _primary recovery_ untuk _solution gas drive reservoir_.

Beberapa metode operasional yang termasuk ke dalam EOR _immiscible_ CO~2~ antara lain,

- _Continuous CO~2~ injection_ </br>
CO~2~ secara kontinu diinjeksikan pada reservoir dan mendesak minyak menuju sumur-sumur produksi. Teknik ini akan memperoleh hasil maksimal jika dilakukan pada minyak ringan dibandingkan dengan minyak berat.
- _CO~2~ slug driven by water_</br>
Dengan teknik ini, air diinjeksikan untuk mendesak slug CO~2~ pada reservoir. Teknik ini menghasilkan _recovery_ yang lebih baik dibandingkan dengan injeksi kontinu.
- _Water alternating gas (WAG)_</br>
Volume CO~2~ yang diperlukan untuk keseluruhan injeksi dibagi ke dalam 4-5 _slug_ yang sama banyak. _Recovery_ minyak bergantung pada volume total CO~2~ terinjeksi dan tidak bergantung pada jumlah dan ukuran _slug_. Tiap _slug_ diinjeksikan secara bergantian dengan air berdasarkan WAG _ratio_ yang direncanakan. _Channeling_ CO~2~ dapat dikurangi dengan adanya air karena mobilitas dari CO~2~ akan berkurang dan mekanisme ini akan meningkatkan efisiensi volumetrik pendesakan. Dengan teknik ini, _recovery_ minyak akan lebih besar dibandingkan dengan dua metode sebelumnya.
- _Cyclic CO~2~ stimulation/Huff ‘n’ Puff CO~2~_</br>
Metode ini mula-mula dilakukan dengan menginjeksikan CO~2~ dengan _rate_ injeksi tinggi. Sumur lalu ditutup untuk periode _soak_ tertentu setelah diproduksikan. Ketika laju produksi telah turun hingga di bawah batas tertentu, _slug_ berikutnya diinjeksikan dan diulangi seterusnya.
- _Simultaneous CO~2~ and water injection_</br>
Dengan dicampurnya CO~2~ dan air di permukaan, maka akan dihasilkan asam karbonat. Campuran fluida ini lalu diinjeksikan ke dalam reservoir. Metode ini akan menghasilkan _recovery_ yang lebih baik di antara semua metode di atas. Salah satu kekurangan dari metode ini adalah akan timbul permasalahan korosi pada sumur produksi maupun peralatan permukaan (terutama *pipeline*).

## _Immiscible_ CO~2~ _Predictive Model_

### Sifat-Sifat Fisik Fluida

#### Kelarutan CO~2~ pada Air dan Minyak

Distribusi CO~2~ pada air dan heaxadecane (*heavy oil*) dinyatakan dengan K-*value*,
$$K = \left[ \frac{\omega_{CO_2}^w}{\omega_{CO_2}^o} \right]_{p,T}...(1)$$
Korelasi Mehrotra and Svrcek (1982) digunakan untuk menentukan kelarutan CO~2~ dalam minyak, yaitu
$$Sol \left( \frac{m^3}{m^3} \right) = C_1 + C_2P_s + C_3\left( \frac{P_s}{T+273.16} \right) + C_4\left( \frac{P_s}{T+273.16} \right)^2...(2)$$
dimana,
$$C_1 = 0.0277041$$
$$C_2 = 4.0928$$
$$C_3 = 3.206 \times 10^{-6}$$
$$C_4 = 1.6428$$
$$C_5 = 0.098057$$
$$C_6 = 5.388$$
$$C_7 = 0.2499$$

#### Densitas Minyak dengan Adanya CO~2~ Terlarut

Sedangkan densitas minyak dihitung dengan menggunakan korelasi,
$$\rho_o = \rho_i - 0.1027y^{0.608}+0.1407y^{0.6133}...(3)$$
dimana,
$$y = \frac{\gamma \rho_i (p-p_b)^{1.25}}{T}...(4)$$
$\rho_o$ = Densitas minyak dengan CO~2~ terlarut (kg/m^3^) </br>
$\rho_i$ = Densitas minyak awal tanpa CO~2~ (kg/m^3^) </br>
$\gamma$ = _Specific gravity_ minyak </br>
$p_b$ = Tekanan _bubble_ minyak (kPa) 

#### _Swelling Factor_ Minyak

_Swelling factor_ dihitung dengan korelasi yang diberikan oleh Emera and Sarma sebagai berikut,

Untuk minyak berat dengan berat molekul MW > 300 lb/lb-mol
$$SF = 1+0.3302Y - 0.8417Y^2 + 1.5804Y^3 - 1.074Y^4 - 0.0318Y^5 + 0.21755Y^6...(5)$$
dimana,
$$Y = 1000 \left[ \left( \left( \frac{Y}{MW} \right)Sol (Mol Fraction) \right)^2 \right] \frac{EXP \left( \frac{Y}{MW} \right)}{MW}...(6)$$
Untuk minyak ringan dengan MW < 300 lb/lb-mol
$$SF = 1 + 0.0484Y − 0.9928Y^2 + 1.6019Y^3 − 1.2773Y^4 − 0.482667Y^5 + 0.06671Y^6...(7)$$

#### Viskosias Miyak dengan Adanya CO~2~ Terlarut

Korelasi Beggs and Robinson (1975) digunakan dalam menentukan viskositas minyak dengan CO~2~ terlarut di dalamnya yaitu,
$$\mu = A (10^x - 1)^B ...(8)$$
dimana,
$$x = 10^{(3.0324-0.02023\gamma_o)}(T)^{-1.163}...(9)$$
$$A=10.7 \left( \frac{Sol\left( \frac{m^3}{m^3} \right)}{5.615}+100 \right)^{-0.515}...(10)$$
$$B=5.44\left( \frac{Sol\left( \frac{m^3}{m^3} \right)}{5.615}+150 \right)^{-0.388}...(11)$$
Viskositas aktual dari minyak dengan hadirnya CO~2~ terlarut akan berkurang dan dapat ditentukan dengan menggunakan korelasi Nissan and Grundberg berikut,
$$\log \mu = \omega_o^{CO_2}\log \mu_o^{CO_2}+\omega_o^{o}\log \mu_o^{o}+G\omega_o^{CO_2}\omega_o^{o}...(12)$$
Di mana G didefinisikan sebagai _interaction parameter_/Nissan and Grundberg Constant dan nilai G = 0 untuk kondisi ideal.

### _Fractional Flow Model_

Mobilitas dari fluida sangat dipengaruhi oleh permeabilitas relatif dan viskositas masing-masing komponen _liquid_. Dan seperti yang telah dibahas, viskositas sangat dipengaruhi oleh konsentrasi CO~2~ dalam _liquid_ dan beberapa parameter lainnya. Mobilitas dari fluida didefinisikan sebagai,
$$\lambda_o = \frac{kk_{ro}}{\mu_o}...(13)$$
$$\lambda_w = \frac{kk_{rw}}{\mu_w}...(14)$$
Sedangkan _fractional flow_ aliran merupakan perbandingan mobilitas air terhadap mobilitas total fluida,
$$f_w = \frac{\lambda_w}{\lambda_o + \lambda_w}...(15)$$
Jika diuraikan, maka persamaan di atas menjadi
$$f_w = \frac{S_{wD}^{W_{Exp}}}{S_{wD}^{W_{Exp}}+A \times (1-S_{wD})^{Oil_{Exp}}}...(16)$$
$$\frac{\partial f_w}{\partial S_w} = A \times B \times \frac{W_{Exp}\times S_{wD}^{(W_{Exp^{-1}})} \times (1-S_{wD})^{Oil_{Exp}}+Oil_{Exp} \times S_{wD}^{W_{Exp}}\times(1-S_{wD})^{(Oil_{Exp^{-1}})}}{(S_{wD}^{W_{Exp}}+A \times (1-S_{wD})^{Oil_{Exp}})^2}...(17)$$
dimana,
$$A = \frac{k_{ro@S_{wc}}\mu_w}{k_{rw@S_{or}}\mu_o}...(18)$$
$$B = \frac{1}{1-S_{wc}-S_{or}}...(19)$$
$$S_{wD} = \frac{S_{w}-S_{wc}}{1-S_{wc}-S_{or}}...(20)$$
$\mu_w$ = viskositas air </br>
$\mu_o$ = viskositas minyak </br>
$k_{ro@S_{wc}}$ = Permeabilitas relatif minyak pada _connate water saturation_. </br>
$k_{rw@S_{or}}$ = Permeabilitas relatif air pada _residual oil saturation_.

### _Material Balance Equation_

#### Untuk Perubahan Saturasi Kontinu

Untuk perubahan saturasi yang kontinu persamaan _material balance_ yang mengandung komposisi dari masing-masing fasa (Minyak, CO~2~, dan Air) diberikan sesuai persamaan berikut,
$$\frac{\partial}{\partial t}[S_wm_{wj}+(1-S_w)m_{oj}]=- \frac{\partial}{\partial x}\left[\frac{q}{A \phi}(f_wm_{wj}+(1-f_w)m_{oj})\right]...(21)$$
Untuk _region_ di mana tidak terjadi perubahan konsentrasi CO~2~ maka persamaan (21) dapat diubah menjadi
$$\left( \frac{\partial S_w}{\partial t} \right)_x = - \frac{q}{A \phi} \left( \frac{\partial f_w}{\partial x} \right)_t ...(22)$$
Di mana persamaan di atas merupakan solusi untuk Buckley-Leverett. Untuk region di mana terjadi perubahan konsentrasi massa dari komponen CO~2~, solusi yang dihasilkan dapat diuraikan ke dalam bentuk matrix pada komponen 1,2, dan 3 yaitu:

$$
\left[
  \begin{array}{c}
    u[f_wa_j^`+m_{oj}^`] & (m_{oj}^`+S_wa_j^`) & [(f_wa_j + m_{oj})]\\
    u[f_wa_j^`+m_{oj}^`] & (m_{oj}^`+S_wa_j^`) & [(f_wa_j + m_{oj})]\\
    u[f_wa_j^`+m_{oj}^`] & (m_{oj}^`+S_wa_j^`) & [(f_wa_j + m_{oj})]
  \end{array}
\right]
\left[
  \begin{array}{c}
    \frac{\partial C}{\partial x} \\
    \frac{\partial C}{\partial t} \\
    \frac{\partial u}{\partial x} 
  \end{array}
\right]
=
\left[
  \begin{array}{c}
    -\left[ \frac{\partial S_w}{\partial t} \right] + u \frac{\partial f}{\partial x}a_j \\
    -\left[ \frac{\partial S_w}{\partial t} \right] + u \frac{\partial f}{\partial x}a_j \\
    -\left[ \frac{\partial S_w}{\partial t} \right] + u \frac{\partial f}{\partial x}a_j
  \end{array}
\right]...(23)
$$
Untuk perubahan konsentrasi yang kontinu dapat diberikan persamaan kecepatan aliran menjadi
$$\left( \frac{\partial X}{\partial t} \right)^+ = -u^+\left( \frac{f_w^++\epsilon}{S_w^++\epsilon} \right)...(24)$$
Dengan $\epsilon$ adalah perbandingan antara dua determinan matrix
$$
\epsilon = \frac
{Det 
\left[
  \begin{array}{c}
    a_1^+ & (m_{o1}^{`+}) & [f_w^+a_1^++m_{o1}^+] \\ 
    a_2^+ & (m_{o2}^{`+}) & [f_w^+a_1^++m_{o2}^+] \\ 
    a_3^+ & (m_{o3}^{`+}) & [f_w^+a_1^++m_{o3}^+] \\ 
  \end{array}
\right]}
{Det
\left[
  \begin{array}{c}
    a_1^+ & (a_{1}^{`+}) & [f_w^+a_1^++m_{o1}^+] \\ 
    a_2^+ & (a_{2}^{`+}) & [f_w^+a_1^++m_{o2}^+] \\ 
    a_3^+ & (a_{3}^{`+}) & [f_w^+a_1^++m_{o3}^+] \\ 
  \end{array}
\right]}...(25)
$$
Maka untuk _region_ saturasi kontinu yang terletak pada bagian _upstream_, maka sesuai dengan notasi
$$\left( \frac{\partial X}{\partial t} \right)^- = -u^-\left( \frac{f_w^++\epsilon}{S_w^++\epsilon} \right)...(26)$$
Untuk menyelesaikan persamaan di atas secara keseluruhan dibutuhkan perhitungan mengenai konsentrasi komponen terhadap komponen lain dan juga _derivative_-nya. Untuk itu maka diberikan hubungan antara fraksi mol terhadap konsentrasi massa per volume _liquid_ sebagai berikut

Untuk fasa air
$$m_{wj} = \frac{1}{\left(1+\frac{M_j}{M_w}\left(\frac{1-x_{wj}}{x_{wj}}\right)\right)}\rho_w ...(27)$$
dimana, </br>
$m_{wj}$ = Konsentrasi komponen-j dalam air (gr/cc) </br>
$x_{wj}$ = Fraksi mol komponen-j dalam air </br>
$M_j$ = Berat molekul komponen-j (gr/mol) </br>
$\rho_w$ = Densitas air (gr/cc)

Untuk fasa minyak
$$m_{oj} = \frac{1}{\left(1+\frac{M_j}{M_o}\left(\frac{1-x_{oj}}{x_{oj}}\right)\right)}\rho_o ...(28)$$
dimana, </br>
$m_{oj}$ = Konsentrasi komponen-j dalam minyak (gr/cc) </br>
$x_{oj}$ = Fraksi mol komponen-j dalam minyak </br>
$M_j$ = Berat molekul komponen-j (gr/mol) </br>
$\rho_o$ = Densitas minyak (gr/cc)

Sedangkan hubungan antara fraksi mol antarkomponen diberikan sebagai berikut,
$$x_{w1} + x_{w2} + x_{w3} = 1...(29)$$
dimana, </br>
$x_{w1}$ = Fraksi mol komponen minyak dalam fasa air (mol/mol) </br>
$x_{w2}$ = Fraksi mol komponen CO~2~ dalam fasa air (mol/mol) </br>
$x_{w3}$ = Fraksi mol komponen air dalam fasa air (mol/mol)

$$x_{o1} + x_{o2} + x_{o3} = 1...(30)$$
dimana, </br>
$x_{o1}$ = Fraksi mol komponen minyak dalam fasa minyak (mol/mol) </br>
$x_{o2}$ = Fraksi mol komponen CO~2~ dalam fasa minyak (mol/mol) </br>
$x_{o3}$ = Fraksi mol komponen air dalam fasa minyak (mol/mol) 

_Derivative_ dari konsentrasi untuk fasa air dan minyak berturut-turut diberikan,
$$m_{wj}^`= \frac{d}{dC}(m_{wj})...(31)$$
dimana, </br>
$m_{wj}^`$ = Derivatif konsentrasi komponen-j dalam air terhadap konsentrasi CO~2~ (gr/cc) 


$$m_{oj}^`= \frac{d}{dC}(m_{oj})...(32)$$
dimana, </br>
$m_{oj}^`$ = Derivatif konsentrasi komponen-j dalam minyak terhadap konsentrasi CO~2~ (gr/cc)

Selain itu untuk perubahan saturasi yang kontinu dalam area _region_ di luar _boundary interphase_, nilai saturasi dapat ditentukan dengan mengiterasi persamaan berikut,
$$\frac{K^n + K^{n+1} \left( \frac{2+\sigma^n \times \Delta X_{w2}}{2-\sigma^n \times \Delta X_{w2}} \right)}{2}=\frac{\left( \frac{2+\sigma^n \times \Delta X_{w2}}{2-\sigma^n \times \Delta X_{w2}} \right)F^{n+1}-F^n}{B^{n+1}-B^n}...(33)$$
dimana, </br>
$$K^n = \frac{f_w^n + \epsilon^n}{S_w^n + \epsilon^n} ...(34)$$
$$\sigma^n = \frac{S_w^n - f_w^n}{S_w^n + \epsilon^n} ...(35)$$
$$F^n = f_w^nm_{w1}^n+(1-f_w^n)m_{o1}^n ...(36)$$
$$B^n = S_w^nm_{w1}^n+(1-S_w^n)m_{o1}^n ...(37)$$

#### Untuk Perubahan Saturasi Diskontinu

Untuk perubahan saturasi yang tidak kontinu persamaan material balance yang mengandung komposisi dari masing-masing fasa akan memberikan
$$\frac{A\phi}{q^-}\left(\frac{dx}{dt}\right) = \frac{\frac{q^+}{q^-}[f_w^+m_{wj}^++(1-f_w^+)m_{oj}^+]-[f_w^-m_{wj}^-+(1-f_w^-)m_{oj}^-]}{[S_w^+m_{wj}^++(1-S_w^+)m_{oj}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{oj}^-]}...(38)$$

Solusi umum persamaan _material balance_ untuk persamaan di atas dapat dilakukan dengan membagi ke dalam komponen-komponen aliran: minyak, CO~2~, dan air. Sehingga dapat dituliskan,

Untuk fasa minyak,
$$\frac{A\phi}{q^-}\left(\frac{dx}{dt}\right)_{S_w} = \frac{\frac{q^+}{q^-}[f_w^+m_{wj}^++(1-f_w^+)m_{o1}^+]-[f_w^-m_{wj}^-+(1-f_w^-)m_{o1}^-]}{[S_w^+m_{wj}^++(1-S_w^+)m_{o1}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{o1}^-]}...(39)$$

Untuk fasa CO~2~,
$$\frac{A\phi}{q^-}\left(\frac{dx}{dt}\right)_{S_w} = \frac{\frac{q^+}{q^-}[f_w^+m_{wj}^++(1-f_w^+)m_{o2}^+]-[f_w^-m_{wj}^-+(1-f_w^-)m_{o2}^-]}{[S_w^+m_{wj}^++(1-S_w^+)m_{o2}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{o2}^-]}...(40)$$

Untuk fasa air,
$$\frac{A\phi}{q^-}\left(\frac{dx}{dt}\right)_{S_w} = \frac{\frac{q^+}{q^-}[f_w^+m_{wj}^++(1-f_w^+)m_{o3}^+]-[f_w^-m_{wj}^-+(1-f_w^-)m_{o3}^-]}{[S_w^+m_{wj}^++(1-S_w^+)m_{o3}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{o3}^-]}...(41)$$

Dengan menganggap suku yang tidak diketahui $\left(\frac{dx}{dt}\right)$, $u^-$, dan $u^+$ lalu diselesaikan dengan menggunakan aturan aljabar linear oleh _Cramer_, dan diperoleh
$$\left(\frac{dx}{dt}\right) = \frac{(0)}{Det
\left[
  \begin{array}{c}
    \left[ [S_w^+m_{wj}^++(1-S_w^+)m_{oj}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{oj}^-] \right] & [f_w^-m_{wj}^-+(1-f_w^-)m_{oj}^-]-[f_w^+m_{wj}^++(1-f_w^+)m_{oj}^+] \\
    \left[ [S_w^+m_{wj}^++(1-S_w^+)m_{oj}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{oj}^-] \right] & [f_w^-m_{wj}^-+(1-f_w^-)m_{oj}^-]-[f_w^+m_{wj}^++(1-f_w^+)m_{oj}^+] \\
    \left[ [S_w^+m_{wj}^++(1-S_w^+)m_{oj}^+]-[S_w^-m_{wj}^-+(1-S_w^-)m_{oj}^-] \right] & [f_w^-m_{wj}^-+(1-f_w^-)m_{oj}^-]-[f_w^+m_{wj}^++(1-f_w^+)m_{oj}^+] \\
  \end{array}
\right]}...(42)$$

Karena $\left(\frac{dx}{dt}\right)$ ≠ 0 maka determinan dari penyebut pada ruas kanan haruslah bernilai 0. Maka nilai determinan berikut harus sama dengan 0.
$$
Det
\left[
  \begin{array}{c}
    \left[ [S_w^+m_{w1}^++(1-S_w^+)m_{o1}^+]-[S_w^-m_{w1}^-+(1-S_w^-)m_{o1}^-] \right] & [f_w^-m_{w1}^-+(1-f_w^-)m_{o1}^-]-[f_w^+m_{w1}^++(1-f_w^+)m_{o1}^+] \\
    \left[ [S_w^+m_{w2}^++(1-S_w^+)m_{o2}^+]-[S_w^-m_{w2}^-+(1-S_w^-)m_{o2}^-] \right] & [f_w^-m_{w2}^-+(1-f_w^-)m_{o2}^-]-[f_w^+m_{w2}^++(1-f_w^+)m_{o2}^+] \\
    \left[ [S_w^+m_{w3}^++(1-S_w^+)m_{o3}^+]-[S_w^-m_{w3}^-+(1-S_w^-)m_{o3}^-] \right] & [f_w^-m_{w3}^-+(1-f_w^-)m_{o3}^-]-[f_w^+m_{w3}^++(1-f_w^+)m_{o3}^+] \\
  \end{array}
\right] = 0 ... (43)
$$
Besarnya konsentrasi CO~2~ dalam liquid dapat ditentukan dengan menggunakan batas iterasi di atas, yaitu di mana determinan dari matrix tersebut bernilai 0.

### Parameter-Parameter Performa _Immiscible_ CO~2~

Asumsi-asumsi yang digunakan di dalam perhitungan _carbonate waterflood_ antara lain,
- Digunakan asumsi-asumsi persamaan Buckley-Leverett: variasi porositas dan permeabilitas diabaikan, formasi linear, fluida _incompressible_, terdapat hanya dua fasa fluida yang mengalir pada suatu waktu, saturasi air dan minyak awal konstan, dan digunakan persamaan _fractional flow_ $f_w = \frac{\lambda_w}{\lambda_o + \lambda_w}$ sehingga diabaikan efek gravitasi dan kapiler.

- Terlarutnya minyak dalam air maupun air dalam minyak dapat diabaikan.
- Tekanan di seluruh formasi cukup untuk membuat CO~2~ fasa gas tidak terlepas dari _liquid_.
- Fasa air dan minyak berada dalam kondisi kesetimbangan sehingga tekanan parsial CO~2~ pada air sama dengan tekanan parsial CO~2~ pada minyak.
- Perubahan viskositas CO~2~-Minyak akibat terdesaknya komponen methane dari minyak sama dapat diabaikan.
- Difusi _molecular_ dan efek dispersi (*convection*) dapat diabaikan.

Model _predictive_ untuk _immiscible_ CO~2~ yang dikembangkan dalam penelitian ini merupakan gabungan dari solusi yang diberikan oleh Welge (1960) untuk _Enriched Gas Injection_ dan DeNevers (1963) untuk _simulataneous CO~2~+Water Injection_ atau _Carbonate Waterflooding_ yang termasuk salah satu kategori _immiscible_ CO~2~. Dalam penelitian kali ini juga akan digunakan _predictive model_ untuk kondisi tekanan antara sumur injeksi dan produksi konstan sesuai algoritma yang diusulkan oleh Whillite (1986). Hal ini dilakukan mengingat pentingnya menjaga tekanan konstan di bawah tekanan rekah dari formasi.

Ketika injeksi dilakukan dengan kondisi tekanan konstan, maka laju alir akan bervariasi sesuai dengan waktu. Solusi pendesakan frontal untuk _pressure drop_ konstan dapat ditentukan dengan mereview kembali persamaan aliran semi-empirik Darcy,
$$\frac{dx}{dt} = \frac{q_t}{A\phi}\left( \frac{\partial f_w}{\partial S_w} \right)...(44)$$
ketika _pressure drop_ bernilai konstan, maka aliran fluida akan mengikuti persamaan Darcy sebagai berikut,
$$q_t = - \left(\frac{k_{ro}}{\mu_o}+\frac{k_{rw}}{\mu_w}\right)k_bA \frac{dP}{dx}...(45)$$
atau
$$q_t = - \lambda_rk_bA \frac{dP}{dx}...(46)$$
Dimana $\lambda_r$ merupakan total _relative mobility_, dan k~b~ adalah permeabilitas absolut batuan. Karena q~t~ konstan untuk posisi dan waktu tertentu. Dengan mengintegralkan persamaan di atas, maka akan diperoleh
$$q_t =frac{k_bA(p_i-p)}{\int_0^L \lambda_r^{-1}dx}...(47)$$
dimana
$$\lambda_r^{-1} = \frac{1}{\lambda_o+\lambda_w}...(48)$$
Dikenal dengan istilah _apparent viscosity_ dari minyak dan air pada saturasi tertentu. Untuk memudahkan menyelesikan persamaan di atas, maka dikenalkan konsep _average apparent viscosity_ yang didefinisikan sebagai,
$$\bar{\lambda^{-1}} = \frac{\int_0^L\lambda_r^{-1}dx}{\int_0^Ldx}...(49)$$
Jika integral di atas dapat dihitung, maka laju alir total fluida dapat ditentukan dengan menggunakan persamaan berikut
$$q_t = \frac{k_bA(p_i-p)}{\bar{\lambda^{-1}}L}...(50)$$
Atau dalam satuan lapangan,
$$q_t = 1.127 \times 10^{-3}\frac{k_bA(p_i-p)}{\bar{\lambda^{-1}}L}...(51)$$
Untuk kondisi sebelum _water breakthrough_, _average apparent viscosity_ diberikan oleh persamaan berikut,
$$\bar{\lambda_r^{-1}} = (\bar{\lambda_{swf}^{-1}}-\lambda_{ro}^{-1})Q_i\left( \frac{\partial f_w}{\partial S_w} \right) + \lambda_{ro}^{-1}...(52)$$
dimana
$$\lambda_{ro}^{-1} = \frac{\mu_o}{(k_{ro})_{siw}}...(53)$$

Diberkan selang waktu _t^n^_ dan _t^n+1^_, dan diasumsikan _q~t~_ dapat diestimasi dengan $\frac{1}{2}$(*q~t~^n+1^ + q~t~^n^*) besarnya _t^n+1^_ dapat diestimasi dengan persamaan berikut,
$$t^{n+1} = t^n + \frac{2(Q_i^{n+1}-Q_i^n)V_p}{(q_t^{n+1}-q_t^n)}...(54)$$
Untuk n = 0, _t^n^_ = 0, dan _Q~i~^n^_ = 0. Untuk kasus ini, besarnya _t^1^_ dapat ditentukan dengan menggunakan persamaan berikut, 
$$t^1 = \frac{2(Q_i^1)V_p}{(q_t^1+q_t^0)}...(55)$$
Karena fluida diasumsikan _incompressible_, maka _pressure drop_ akan terpropagasi ke seluruh reservoir dan menyebabkan laju alir awal dapat diestimasi dengan persamaan aliran pada kondisi saturasi awal,
$$q_t^0 = 1.127 \times 10^{-3}\frac{k_bA(p_i-p)}{\bar{\lambda^{-1}}L} ...(56)$$
_Water cut_ di permukaan dari total aliran dapat ditentukan dengan menggunakan persamaan berikut,
$$f_{ws} = \frac{f_w}{f_w + (1-f_w)B_o}...(57)$$
Sehingga laju alir minyak yang diperoleh di permukaan sebesar,
$$q_o^n = Q_r^n(1-f_{ws})...(58)$$

Dan laju alir di permukaan,
$$q_w^n = Q_r^n -q_{or}^n...(59)$$

Kumulatif produksi minyak dapat dihitung dengan menggunakan persamaan berikut,
$$N_p^{n-1} = N-p^n = \left(\frac{q_o^n + q_o^{n-1}}{2}\right) \times (t^{n-1}-t^n)...(60)$$
Sedangkan _recovery factor_ dapat dihitung dengan menggunakan persamaan berikut,
$$RF^n = \frac{N_{pF}^n}{IOIP} \times 100 ... (61)$$
