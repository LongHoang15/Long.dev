<script setup>

</script>
<template>
  <div class="cv-body">
    <section id="about" class="py-5 bg-white border-bottom">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-7 text-center text-lg-start">
            <h6 class="text-success fw-bold text-uppercase">About me</h6>
            <h1 class="display-3 fw-bold mb-4">
              XIN CHÀO, MÌNH LÀ <span class="text-success text-decoration-underline">Đoàn Hoàng Long</span>
            </h1>
            <p class="lead text-muted mb-5 fs-4">
              Một lập trình viên đam mê sáng tạo các sản phẩm chất lượng cao, tối ưu hóa trải nghiệm người dùng.
            </p>
            
            <div class="d-flex gap-3 justify-content-center justify-content-lg-start mb-4">
              <button class="btn btn-success btn-lg px-5 rounded-pill shadow">Tải CV</button>
              <button class="btn btn-dark btn-lg px-5 rounded-pill">Liên hệ</button>
            </div>

            <div class="d-flex gap-4 justify-content-center justify-content-lg-start align-items-center mt-4">
              <a href="https://www.facebook.com/hoang.long.281381/" target="_blank" class="text-decoration-none contact-icon fb" title="Facebook">
                <i class="bi bi-facebook fs-2"></i>
              </a>
              <a href="https://zalo.me/0384039806" target="_blank" class="text-decoration-none contact-icon zalo" title="Zalo">
                <span class="fs-4 fw-bold border border-2 rounded-circle px-2">Z</span>
              </a>
              <a href="mailto:hoanglong15072004@gmail.com" class="text-decoration-none contact-icon mail" title="Gửi Email">
                <i class="bi bi-envelope-fill fs-2"></i>
              </a>
            </div>
          </div>

          <div class="col-lg-5 text-center mt-5 mt-lg-0">
            <img src="./img/avatar.jpg" class="img-fluid rounded-circle border border-5 border-white shadow-lg avatar-img">
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
              <h4 class="fw-bold text-center mb-4">Backend Development</h4>
              <div class="d-flex flex-column gap-3">
                <div class="d-flex align-items-center">
                  <img src="./img/java.webp" alt="Java" width="40" class="me-3">
                  <div><div class="fw-bold">Java</div><small class="text-secondary">Advanced</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/springboot.png" alt="Spring Boot" width="40" class="me-3">
                  <div><div class="fw-bold">Spring Boot</div><small class="text-secondary">Intermediate</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/sql.webp" alt="SQL Server" width="40" class="me-3">
                  <div><div class="fw-bold">SQL Server</div><small class="text-secondary">Advanced</small></div>
                </div>
              </div>
            </div>
          </div>

          <div class="col-md-6">
            <div class="card border-0 shadow-sm p-4 rounded-4 h-100">
              <h4 class="fw-bold text-center mb-4">Frontend Development</h4>
              <div class="d-flex flex-column gap-3">
                <div class="d-flex align-items-center">
                  <img src="./img/html.png" alt="HTML" width="40" class="me-3">
                  <div><div class="fw-bold">HTML</div><small class="text-secondary">Advanced</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/css.png" alt="CSS" width="40" class="me-3">
                  <div><div class="fw-bold">CSS</div><small class="text-secondary">Advanced</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/javascript.jpg" alt="JavaScript" width="40" class="me-3">
                  <div><div class="fw-bold">JavaScript</div><small class="text-secondary">Intermediate</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/bootstrap.jpg" alt="Bootstrap" width="40" class="me-3">
                  <div><div class="fw-bold">Bootstrap</div><small class="text-secondary">Intermediate</small></div>
                </div>
                <div class="d-flex align-items-center">
                  <img src="./img/vuejs.png" alt="Vue.js" width="40" class="me-3">
                  <div><div class="fw-bold">Vue.js</div><small class="text-secondary">Intermediate</small></div>
                </div>
              </div>
            </div>
          </div>

          <div class="col-12 mt-4">
            <div class="card border-0 shadow-sm p-4 rounded-4 text-center">
              <h4 class="fw-bold text-dark mb-4">KỸ NĂNG MỀM</h4>
              <div class="row g-2">
                <div class="col-md-3 col-6"><span class="badge bg-white text-dark border p-2 w-100 shadow-sm">Làm việc nhóm</span></div>
                <div class="col-md-3 col-6"><span class="badge bg-white text-dark border p-2 w-100 shadow-sm">Thuyết trình</span></div>
                <div class="col-md-3 col-6"><span class="badge bg-white text-dark border p-2 w-100 shadow-sm">Làm việc độc lập</span></div>
                <div class="col-md-3 col-6"><span class="badge bg-white text-dark border p-2 w-100 shadow-sm">Quản lý công việc</span></div>
              </div>
            </div>
          </div>
        </div> 
      </div> 
    </section>

    <section id="experience" class="py-5 bg-white">
      <div class="container">
        <h2 class="fw-bold mb-5 display-5 text-center">Dự án</h2>

        <div class="card border-0 border-start border-success border-5 shadow-sm p-4 mb-4 rounded-4 project-card">
          <div class="d-flex justify-content-between align-items-center flex-wrap mb-3">
            <h3 class="fw-bold mb-0 text-success">Bán áo phông WearZone</h3>
            <span class="text-muted fw-bold">06/2025 - 08/2025</span>
          </div>
          <ul class="list-unstyled fs-5">
            <li class="mb-2"><strong>Vị trí:</strong> Back-End Developer – <strong>Vai trò:</strong> Viết code, fix bug</li>
            <li class="mb-2"><strong>Chức năng:</strong> Quản lý sản phẩm, phân quyền, hóa đơn, thống kê, quản lý nhân viên.</li>
            <li class="mb-2"><strong>Ngôn ngữ:</strong> Java, SQL</li>
            <li><strong>Công cụ:</strong> NetBeans, SQL Server</li>
          </ul>
        </div>

        <div class="card border-0 border-start border-primary border-5 shadow-sm p-4 rounded-4 project-card">
          <div class="d-flex justify-content-between align-items-center flex-wrap mb-3">
            <h3 class="fw-bold mb-0 text-primary">Bán Sách BookStore</h3>
            <span class="text-muted fw-bold">11/2025 - 12/2025</span>
          </div>
          <ul class="list-unstyled fs-5">
            <li class="mb-2"><strong>Vị trí:</strong> Fullstack – <strong>Vai trò (Độc lập):</strong> Viết code, vẽ giao diện, fix bug</li>
            <li class="mb-2"><strong>Chức năng:</strong> Quản lý sách, khách hàng, bán sách online/office, quản lý phiếu giảm giá.</li>
            <li class="mb-2"><strong>Ngôn ngữ:</strong> Java, SQL, HTML, CSS, JavaScript</li>
            <li class="mb-2"><strong>Công cụ:</strong> IntelliJ, GitHub</li>
            <li><strong>Thư viện:</strong> Bootstrap 5</li>
          </ul>
        </div>
      </div>
    </section>
    
    <section id="project-gallery" class="py-5 bg-light">
      <div class="container text-center">
        <h2 class="fw-bold mb-5 display-5">Các hoạt động đã tham gia</h2>
        <div id="projectCarousel" class="carousel slide carousel-fade shadow-lg rounded-4 overflow-hidden" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#projectCarousel" data-bs-slide-to="0" class="active"></button>
            <button type="button" data-bs-target="#projectCarousel" data-bs-slide-to="1"></button>
            <button type="button" data-bs-target="#projectCarousel" data-bs-slide-to="2"></button>
            <button type="button" data-bs-target="#projectCarousel" data-bs-slide-to="3"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./img/top_150.JPG" class="d-block w-100 project-img" alt="WearZone">
              <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                <h5>Lễ Tôn vinh sinh viên tiêu biểu học kỳ Spring 2025</h5>
                <p>Lọt top 150 sinh viên tiêu biểu học kỳ Spring 2025.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="./img/top_1.JPG" class="d-block w-100 project-img" alt="BookStore">
              <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                <h5>INSPING TEACHER</h5>
                <p>Top 1 cuộc thi báo tường chuyền cảm hứng.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="./img/khuyen_khich.jpg" class="d-block w-100 project-img" alt="Coding">
              <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                <h5>OVERVIEW POLYDECODEFEST</h5>
                <p>Vào vòng chung kết cuộc thi giả mã.</p>
              </div>
            </div>
            <div class="carousel-item">
              <img src="./img/run.JPG" class="d-block w-100 project-img" alt="Coding">
              <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded">
                <h5>Giải chạy cuộc thi mở rộng</h5>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#projectCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#projectCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
          </button>
        </div>
      </div>
    </section>

    <footer class="py-5 bg-dark text-white text-center">
      <div class="container">
        <div class="mb-3">
          <img src="./img/FPT_Polytechnic.png" alt="FPT Logo" width="400" class="mb-3">
          <h4 class="fw-bold text-warning">HOẠT ĐỘNG TẠI CAO ĐẲNG FPT POLYTECHNIC</h4>
          <p class="text-secondary fs-5">Môi trường học tập năng động, thực tế và chuyên nghiệp.</p>
        </div>
        <hr class="border-secondary my-4">
        <p class="mb-0 text-secondary">&copy; 2026 Đoàn Hoàng Long. All Rights Reserved.</p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
section { padding: 100px 0; }
.cv-body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }

/* Avatar */
.avatar-img {
  width: 350px; 
  height: 350px; 
  object-fit: cover;
}

/* Hiệu ứng Card */
.card { 
  transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
}
.card:hover { 
  transform: translateY(-12px); 
  shadow: 0 1rem 3rem rgba(0,0,0,.175)!important;
}

/* Contact Icons */
.contact-icon {
  transition: all 0.3s ease;
  color: #6c757d;
}
.contact-icon:hover { transform: scale(1.2) rotate(5deg); }
.fb:hover { color: #1877F2; }
.zalo:hover { color: #0068FF; }
.mail:hover { color: #EA4335; }

/* Carousel/Gallery */
.project-img {
  height: 500px;
  object-fit: cover;
  filter: brightness(0.9);
}

@media (max-width: 768px) {
  .project-img { height: 300px; }
  .avatar-img { width: 250px; height: 250px; }
  section { padding: 60px 0; }
}
</style>