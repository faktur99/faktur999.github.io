<?php
$group = isset($_GET['group']) ? $_GET['group'] : 'dicoding';
$valid = ['dicoding','sololearn','course'];
if (!in_array($group, $valid)) $group = 'dicoding';
?>

<main class="container mt-5 pt-5">
  <h2>Certificates - <?php echo ucfirst($group); ?></h2>
  <p class="text-muted">Menampilkan 6 sertifikat untuk grup <strong><?php echo ucfirst($group); ?></strong>. Klik gambar untuk memperbesar.</p>
  <div id="certGallery" class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-3 mb-4"></div>
  <a href="<?= base_url('index.php') ?>" class="btn btn-outline-secondary mt-3">Kembali</a>
</main>
<?php
$page_footer = "<script>const BASE_URL='" . rtrim(base_url(''), '/') . "/';</script>\n";
 $page_footer .= <<<'FOOTER'
<script>
(function(){
  const certData = {
    dicoding: [
      { title: 'Belajar Dasar Pemrograman', subtitle: 'diCoding — 2026', img: BASE_URL + 'assets/images/certificates/dicoding/belajar Dasar Data Science.png' },
      { title: 'Front-end Fundamental', subtitle: 'diCoding — 2026', img: BASE_URL + 'assets/images/certificates/dicoding/Belajar Dasar Structured Query Language (SQL).png' },
      { title: 'Responsive Web Design', subtitle: 'diCoding — 2026', img: BASE_URL + 'assets/images/certificates/dicoding/Introduction to Financial Literacy.png' },
      { title: 'JavaScript Dasar', subtitle: 'diCoding — 2026', img: BASE_URL + 'assets/images/certificates/dicoding/Memulai Pemrograman dengan python.png' },
      { title: 'UX untuk Developer', subtitle: 'diCoding — 2026', img: BASE_URL + 'assets/images/certificates/dicoding/Spec-Driven Development dengan kiro.png' },
    ],
    sololearn: [
      { title: 'Introduction to CSS', subtitle: 'SoloLearn — 2025', img: BASE_URL + 'assets/images/certificates/sololearn/Sertifikat Introduction CSS.jpeg' },
      { title: 'Introduction to HTML', subtitle: 'SoloLearn — 2025', img: BASE_URL + 'assets/images/certificates/sololearn/Sertifikat Introduction to Html.jpeg' },
      { title: 'Introduction to SQL', subtitle: 'SoloLearn — 2025', img: BASE_URL + 'assets/images/certificates/sololearn/Sertifikat Introduction to SQL.jpeg' },
      { title: 'SQL Intermediate', subtitle: 'SoloLearn — 2025', img: BASE_URL + 'assets/images/certificates/sololearn/Sertikat SQL Intermediate.jpeg' },
    ],
    course: [
      { title: 'Networking Introduction', subtitle: 'Intern — 2020', img: BASE_URL + 'assets/images/certificates/course/magang.jpeg' },
      { title: 'Fiber Optic Basics', subtitle: 'Intern — 2022', img: BASE_URL + 'assets/images/certificates/course/fiber.jpeg' },
      { title: 'Router Configuration', subtitle: 'Intern — 2023', img: BASE_URL + 'assets/images/certificates/course/Blk.jpeg' },
    ],
  };

  function renderCertificateGallery(group) {
    const gallery = document.getElementById('certGallery');
    if (!gallery) return;
    const items = certData[group] || [];

    gallery.innerHTML = items.map(it => `
      <div class="col">
        <div class="card h-100 border-0 shadow-sm cert-card">
          <a href="${it.img}" class="glightbox d-block position-relative" data-gallery="cert-${group}">
            <div class="cert-img bg-light d-flex align-items-center justify-content-center overflow-hidden" style="height:200px;">
              <img src="${it.img}" alt="${it.title}" class="img-fluid" style="max-height:200px; width:auto;">
            </div>
            <span class="position-absolute top-0 end-0 m-2 badge bg-primary">View</span>
          </a>
          <div class="card-body py-2">
            <h6 class="card-title mb-1">${it.title}</h6>
            <p class="card-text small text-muted mb-0">${it.subtitle}</p>
          </div>
        </div>
      </div>
    `).join('');

    // Init GLightbox if available
    if (typeof GLightbox === 'function') {
      GLightbox({ selector: '.glightbox' });
    }
  }

  // Small hover effect
  const style = document.createElement('style');
  style.innerHTML = `
    .cert-img img{ transition: transform .35s ease; }
    .cert-card:hover .cert-img img{ transform: scale(1.06); }
    .cert-card .badge{ font-size: .65rem; }
  `;
  document.head.appendChild(style);

  window.renderCertificateGallery = renderCertificateGallery;

})();
</script>
FOOTER;

$page_footer .= "<script>window.addEventListener('load', function(){ var g=\"" . $group . "\"; if (window.renderCertificateGallery) window.renderCertificateGallery(g); });</script>\n";
?>
