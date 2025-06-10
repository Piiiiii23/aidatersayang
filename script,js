document.addEventListener('DOMContentLoaded', function() {
  const envelope = document.querySelector('.envelope');
  const letter = document.querySelector('.letter');
  const message = document.getElementById('message');
  const foto1 = document.getElementById('foto1');
  const foto2 = document.getElementById('foto2');
  const audio = document.getElementById('audio');

  const fullMessage = `Selamat ulang tahun yang ke-22, cintaku, Nur Aida S 💖
Hari ini adalah hari di mana seseorang yang paling aku sayangi terlahir ke dunia. Aku bersyukur karena Sang Penulis Skenario Terbaik telah mempertemukan aku denganmu—seseorang yang begitu lembut hatinya, sabar, penuh kasih, dan selalu mampu memberi warna dalam setiap babak hidupku.

Kini usiamu genap 22 tahun, dan setiap perjalanan yang telah kamu lalui membentukmu menjadi sosok yang semakin kuat dan menawan. Aku bangga melihat caramu bertumbuh, belajar dari setiap ujian, dan tetap menjaga senyum yang tak pernah gagal membuatku tenang.

Di usia barumu ini, aku memohon agar setiap mimpimu perlahan menemukan jalannya menuju kenyataan. Semoga setiap langkahmu selalu dipermudah, diberi kesehatan, dilimpahi keberkahan, dan dipenuhi kebahagiaan yang tulus. Dan semoga kamu tak pernah lupa, bahwa dalam setiap doaku, selalu terselip namamu.

Terima kasih telah hadir dalam hidupku. Terima kasih telah menjadi bagian dari hari-hariku. Dan terima kasih karena kamu masih memilih aku, meskipun dunia terus berubah. Semoga bahagiamu menjadi bahagiaku juga, dan setiap tahun baru dalam hidupmu, aku tetap di sisimu—menggenggam tanganmu, mencintaimu, dan merayakan hidup ini bersama.

Aku mencintaimu, untuk hari ini, esok, dan seterusnya.`;

  let index = 0;
  let typingInterval;

  function typeWriter() {
    if (index < fullMessage.length) {
      message.innerHTML += fullMessage.charAt(index);
      index++;
      setTimeout(typeWriter, 20); // Kecepatan mengetik
    } else {
      // Setelah selesai mengetik
      foto1.classList.add('show');
      foto2.classList.add('show');
      audio.play();
    }
  }

  envelope.addEventListener('click', function() {
    envelope.classList.add('open');
    letter.classList.add('show');
    typeWriter();
  });
});
