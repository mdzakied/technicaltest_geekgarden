<template>
  <div class="main">
    <div class="container">
      <div class="row mt-5">
        <div class="col">
          <div>
            <b-tabs content-class="mt-3" fill>
              <!-- Tabs-->
              <b-tab title="Case 1" active>
                <div class="row">
                  <div class="col">
                    <b-tabs content-class="mt-3 text-center">
                      <!-- Tabs For Case-->
                      <b-tab title="Case" active>
                        <br />
                        <h5>
                          Buatlah fungsi untuk menampilkan jumlah digit angka
                          tergantung dimana posisi atau tempat dari angka dalam
                          sebuah string “9.86-A5.321”! Contoh:
                          printDigitValue(‘9.86-A5.321’); Hasil : 9865321
                          9000000 800000 60000 5000 300 20’ 1
                        </h5></b-tab
                      >
                      <!-- Tabs For Code-->
                      <b-tab title="Answer">
                        <b-link
                          href=" https://codepen.io/mdzakied/pen/xxPvRzx?editors=1010"
                        >
                          Go to Codepen Case 1</b-link
                        >
                      </b-tab>
                    </b-tabs>
                  </div>
                </div>
              </b-tab>
              <!-- Tabs-->
              <b-tab title="Case 2">
                <div class="row">
                  <div class="col">
                    <b-tabs content-class="mt-3 text-center">
                      <!-- Tabs For Case-->
                      <b-tab title="Case" active>
                        <br />
                        <h5>
                          Ketik kode untuk swap 2 integer variables tanpa
                          VARIABLE TAMBAHAN ataupun membuat function dan dalam 3
                          lines of code (hanya boleh 3 baris): Contoh : let a =
                          3, let b = 7 => hasilnya a = 7, b = 3
                        </h5></b-tab
                      >
                      <!-- Tabs For Code-->
                      <b-tab title="Answer">
                        <b-link
                          href="https://codepen.io/mdzakied/pen/KKyONYr?editors=1010"
                        >
                          Go to Codepen Case 2</b-link
                        >
                      </b-tab>
                    </b-tabs>
                  </div>
                </div>
              </b-tab>
              <!-- Tabs-->
              <b-tab title="Case 3">
                <div class="row">
                  <div class="col">
                    <b-tabs content-class="mt-3 text-center">
                      <!-- Tabs For Case-->
                      <b-tab title="Case" active>
                        <br />
                        <h5>
                          Buatlah function yang bisa mengerjakan hal berikut:
                          Tulis function yang bisa menyatukan 2 sorted array
                          menjadi 1 sorted array. Tes apakah jalan dengan input
                          array yang kosong? Atau ada hal lain yang penting
                          untuk dites? E.g. A[] = [1,2,5,7] , B[] = [3,4,8] =>
                          C[] = [1,2,3,4,5,7,8] <br />
                          <br />
                          <strong>
                            NB : Tidak boleh memakai function seperti sort(),
                            array_merge() atau pakai library apapun. Ingat,
                            inputnya sudah ke sort jadi pasti ada cara yang
                            lebih efisien karena sort() sangat mengambil memory
                            dan waktu! 9000000 800000 60000 5000 300 20’ 1
                          </strong>
                        </h5></b-tab
                      >
                      <!-- Tabs For Code-->
                      <b-tab title="Answer">
                        <b-link
                          href=" https://codepen.io/mdzakied/pen/wvPVoLj?editors=1010"
                        >
                          Go to Codepen Case 3</b-link
                        >
                      </b-tab>
                    </b-tabs>
                  </div>
                </div>
              </b-tab>
              <!-- Tabs-->
              <b-tab title="Case 4">
                <div class="row">
                  <div class="col">
                    <b-tabs content-class="mt-3 text-center">
                      <!-- Tabs For Case-->
                      <b-tab title="Case" active>
                        <br />
                        <h5>
                          Ada 25 kuda dengan berkecapatan berbeda, anda hanya
                          bisa melihat perbedaan kecepatan kuda dengan
                          mengadakan balapan kuda dan hanya bisa mengikut
                          sertakan 5 kuda dalam 1 balapan. Anda tidak punya
                          penghitung waktu, tapi anda bisa mengetahui dari mata
                          Anda dalam 1 balapan siapa yang juara 1 sampai 5.
                          Berapa banyak balapan yang anda harus gelarkan untuk
                          mencari 3 kuda tercepat? <br />
                          <br />
                          <strong>
                            NB : kalau anda mentok jawabannya adalah 3+4 hehehe,
                            tapi berikan penjelasannya
                          </strong>
                        </h5></b-tab
                      >
                      <!-- Tabs For Code-->
                      <b-tab title="Answer" class="text-left">
                        <h5>
                          Jawaban Murni / Mentok :
                          <br />
                          <br />
                          Balapan lebih dari 6
                          <br />
                          <br />
                          Alasan :
                          <br />
                          <br />
                          Adakan balapan sebanyak 5x untuk mengambil
                          masing-masing kuda tercepat dalam grup lalu 1x lagi
                          untuk mengambil kuda tercepat. Lalu saya menyadari
                          bahwa meskpun diadakan 1x lagi dan mendapatkan 3 kuda
                          pemenang belum tentu juga kuda yang kalah sebelumnya
                          akan kalah dengan kuda final karena kata kunci dalam
                          pertanyaan ini adalah tercepat tanpa melihat waktu dan
                          metode saya kurang tepat karena hanya sampai pemenang,
                          dimana menang belum tentu lebih cepat dari kuda lain
                          di pertandingan yang berbeda.
                          <br />
                          <br />
                          Jawaban Ekspor : 7 Balapan
                          <br />
                          <br />
                          Alasan :
                          <br />
                          <br />
                          Menggunakan metode penamaan regu A-D dengan nomor 1-5
                          dan eliminasi.
                          <br />
                          <br />
                          Balapan 5x untuk mengammbil masing-masing kuda
                          tercepat pada regu (Dapat A1 B1 C1 D1 E1)
                          <br />
                          <br />
                          Balapan 1x untuk mengambil kuda tercepat (Dapat A1 di
                          posisi 1)
                          <br />
                          <br />
                          Cari peringkat 2 dan 3 dengan balapan 1x lagi dengan
                          eliminasi kuda paling lambat (Regu nomor 4 5 gugur
                          karena balapan pertama dimenangkan nomor 1 2 3 pada
                          masing-masing regu), (E1-E3 D1-D3 gugur karena selalu
                          peringkat ke 4 dan 5 dalam 2 balapan), (C2-C3 gugur
                          karena C1 peringkat ke 3 dalam final sehingga mereka
                          lebih lambat), (B3 gugur karena B1-B2 peringkat 1 dan
                          2 sehingga mereka lebih lambat). Tersisa 6 kuda A1 A2
                          A3 B1 B2 C1, A1 otomatis peringkat 1 karena tercepat
                          lalu adakan balapan 1x lagi untuk mencari peringkat 2
                          dan 3.
                        </h5>
                      </b-tab>
                    </b-tabs>
                  </div>
                </div>
              </b-tab>
            </b-tabs>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>
