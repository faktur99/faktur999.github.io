<main class="container">
  <div class="row mt-3">
    <div class="col-md-8 mx-auto">
      <div class="card border-0 shadow-sm p-4">
        <h2 class="mb-3">Kontak</h2>
        <p class="text-muted">Hubungi saya lewat formulir di bawah atau melalui email/WhatsApp.</p>

        <div id="contactAlert" class="alert d-none" role="alert"></div>

        <form id="contactForm" method="post" action="<?= base_url('send_message.php') ?>" class="needs-validation" novalidate>
          <div class="mb-3">
            <label for="name" class="form-label">Nama</label>
            <input type="text" class="form-control" id="name" name="name" required>
            <div class="invalid-feedback">Nama wajib diisi.</div>
          </div>

          <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" name="email" required>
            <div class="invalid-feedback">Masukkan email yang valid.</div>
          </div>

          <div class="mb-3">
            <label for="message" class="form-label">Pesan</label>
            <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
            <div class="invalid-feedback">Tulis pesan Anda.</div>
          </div>

          <div class="d-flex gap-2">
            <button type="submit" class="btn btn-primary">Kirim Pesan</button>
            <a href="mailto:<?= CONTACT_EMAIL ?>" class="btn btn-outline-secondary">Email Langsung</a>
          </div>
        </form>
      </div>
    </div>
  </div>
</main>

<script>
// AJAX submit the contact form and show JSON response
(function(){
  const form = document.getElementById('contactForm');
  const alertBox = document.getElementById('contactAlert');
  if (!form) return;

  form.addEventListener('submit', async function(e){
    e.preventDefault();
    alertBox.className = 'alert alert-info';
    alertBox.textContent = '';
    alertBox.classList.remove('d-none');

    // client validation
    if (!form.checkValidity()) {
      form.classList.add('was-validated');
      alertBox.className = 'alert alert-danger';
      alertBox.textContent = 'Periksa kembali input Anda.';
      return;
    }

    const submitBtn = form.querySelector('button[type="submit"]');
    submitBtn.disabled = true;
    submitBtn.textContent = 'Mengirim...';

    const fd = new FormData(form);

    try {
      const res = await fetch(form.action, { method: 'POST', body: fd, headers: { 'Accept': 'application/json' } });
      const json = await res.json();
      if (res.ok && json.success) {
        alertBox.className = 'alert alert-success';
        alertBox.textContent = json.message || 'Pesan terkirim.';
        form.reset();
        form.classList.remove('was-validated');
      } else {
        alertBox.className = 'alert alert-danger';
        alertBox.textContent = json && json.message ? json.message : 'Gagal mengirim pesan.';
      }
    } catch (err) {
      alertBox.className = 'alert alert-danger';
      alertBox.textContent = 'Gagal mengirim pesan — koneksi bermasalah.';
    } finally {
      submitBtn.disabled = false;
      submitBtn.textContent = 'Kirim Pesan';
    }
  });
})();
</script>
