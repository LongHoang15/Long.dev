<template>
  <div class="cv-body">
    <section id="about" class="py-5 bg-white border-bottom">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-7 text-center text-lg-start">
            <h6 class="text-success fw-bold text-uppercase">About me</h6>
            <h1 class="display-3 fw-bold mb-4">XIN CHÀO, MÌNH LÀ <span class="text-success text-decoration-underline">Đoàn Hoàng Long</span></h1>
            <p class="lead text-muted mb-5 fs-4">Một lập trình viên đam mê sáng tạo các sản phẩm chất lượng cao, tối ưu hóa trải nghiệm người dùng.</p>
            
            <div class="d-flex gap-3 justify-content-center justify-content-lg-start mb-4">
              <button class="btn btn-success btn-lg px-5 rounded-pill shadow">Tải CV</button>
              <button class="btn btn-dark btn-lg px-5 rounded-pill">Liên hệ</button>
            </div>

            <div class="d-flex gap-4 justify-content-center justify-content-lg-start align-items-center mt-4">
              <a href="https://facebook.com/your-profile" target="_blank" class="text-decoration-none contact-icon fb" title="Facebook">
                <i class="bi bi-facebook fs-2"></i>
              </a>
              <a href="https://zalo.me/0xxxxxxxxx" target="_blank" class="text-decoration-none contact-icon zalo" title="Zalo">
                <span class="fs-4 fw-bold border border-2 rounded-circle px-2">Z</span>
              </a>
              <a href="mailto:long@example.com" class="text-decoration-none contact-icon mail" title="Gửi Email">
                <i class="bi bi-envelope-fill fs-2"></i>
              </a>
            </div>
          </div>

          <div class="col-lg-5 text-center mt-5 mt-lg-0">
            <img src="./img/avatar.jpg" class="img-fluid rounded-circle border border-5 border-white shadow-lg" style="width: 350px; height: 350px; object-fit: cover;">
          </div>
        </div>
      </div>
    </section>

    <section id="skills" class="py-5 bg-light">
      <div class="container">
        <h2 class="text-center fw-bold mb-5 display-5">Kỹ năng chuyên môn</h2>
        <div class="row g-4">
          <div class="col-md-6">
            <div class="card border-0 shadow-sm p-4 rounded-4 h-100">
              <h4 class="fw-bold text-success mb-4">Frontend</h4>
              <p class="fs-5 text-secondary">HTML, CSS, JavaScript, Vue.js, Bootstrap 5</p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card border-0 shadow-sm p-4 rounded-4 h-100">
              <h4 class="fw-bold text-primary mb-4">Backend & Database</h4>
              <p class="fs-5 text-secondary">Node.js, Express, MySQL, RESTful APIs</p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card border-0 shadow-sm p-4 rounded-4 h-100">
              <h4 class="fw-bold text-primary mb-4">Backend & Database</h4>
              <p class="fs-5 text-secondary">Node.js, Express, MySQL, RESTful APIs</p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card border-0 shadow-sm p-4 rounded-4 h-100">
              <h4 class="fw-bold text-primary mb-4">Backend & Database</h4>
              <p class="fs-5 text-secondary">Node.js, Express, MySQL, RESTful APIs</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="experience" class="py-5 bg-white">
      <div class="container">
        <h2 class="fw-bold mb-5 display-5 text-center">Kinh nghiệm làm việc</h2>
        <div class="card border-0 border-start border-success border-5 shadow-sm p-5 rounded-4">
          <h3 class="fw-bold">Web Developer</h3>
          <p class="text-muted fw-bold">Freelance | 2023 - Hiện tại</p>
          <p class="fs-5 mb-0">Thiết kế và phát triển giao diện người dùng, đảm bảo hiệu năng và tính tương thích trên mọi trình duyệt.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
section { padding: 80px 0; }
.card { transition: all 0.3s ease; }
.card:hover { transform: translateY(-10px); }

/* Style cho các icon liên hệ */
.contact-icon {
  transition: all 0.3s ease;
  color: #6c757d; /* Màu xám mặc định */
}

.contact-icon:hover {
  transform: scale(1.2);
}

.fb:hover { color: #1877F2; }    /* Màu đặc trưng Facebook */
.zalo:hover { color: #0068FF; }  /* Màu đặc trưng Zalo */
.mail:hover { color: #EA4335; }  /* Màu đặc trưng Google Mail */
</style>