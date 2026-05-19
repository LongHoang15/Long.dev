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
              <a href="https://github.com/LongHoang15" target="_blank" class="text-decoration-none contact-icon github" title="GitHub">
                <i class="bi bi-github fs-2"></i>
              </a>
              <a href="https://www.tiktok.com/@ahihi1507" target="_blank" class="text-decoration-none contact-icon tiktok" title="TikTok">
                <i class="bi bi-tiktok fs-2"></i>
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
          <div class="col-12">
            <div class="card border-0 shadow-sm p-4 rounded-4">
              <h4 class="fw-bold text-dark mb-4 text-center"><i class="bi bi-laptop me-2"></i>LẬP TRÌNH & CÔNG NGHỆ</h4>
              <div class="row g-4 fs-5">
                <div class="col-md-6">
                  <h5 class="fw-bold text-success border-bottom pb-2"><i class="bi bi-code-square me-2"></i>Ngôn ngữ lập trình</h5>
                  <p class="text-secondary mb-0">Java, JavaScript, SQL, HTML, CSS</p>
                </div>
                <div class="col-md-6">
                  <h5 class="fw-bold text-primary border-bottom pb-2"><i class="bi bi-database-fill me-2"></i>Cơ sở dữ liệu</h5>
                  <p class="text-secondary mb-0">SQL Server, MySQL</p>
                </div>
                <div class="col-md-6">
                  <h5 class="fw-bold text-danger border-bottom pb-2"><i class="bi bi-cpu-fill me-2"></i>Công nghệ</h5>
                  <p class="text-secondary mb-0">Spring Boot, Spring Data JPA/Hibernate, Vue.js, Vue Router, Bootstrap, JDBC, RESTful API, Spring Security, JWT Authentication, Docker, Maven, Axios</p>
                </div>
                <div class="col-md-6">
                  <h5 class="fw-bold text-info border-bottom pb-2"><i class="bi bi-tools me-2"></i>Công cụ</h5>
                  <p class="text-secondary mb-0">Intellij IDEA, Visual Studio Code, NetBeans, SQL Server Management Studio (SSMS), Postman, Git, GitHub, Docker Desktop, Docker Compose</p>
                </div>
              </div>
            </div>
          </div>

          <div class="col-12 mt-4">
            <div class="card border-0 shadow-sm p-4 rounded-4">
              <h4 class="fw-bold text-dark mb-4 text-center"><i class="bi bi-robot me-2"></i>KỸ NĂNG AI DATA LABELER & KỸ NĂNG MỀM</h4>
              <div class="row g-4 text-start">
                <div class="col-md-4">
                  <h5 class="fw-bold text-success border-bottom pb-2"><i class="bi bi-person-gear me-2"></i>Kỹ năng chuyên môn</h5>
                  <ul class="text-secondary mt-3 mb-0">
                    <li class="mb-2">Phân tích và gán nhãn dữ liệu video.</li>
                    <li class="mb-2">Rà soát lỗi, kiểm soát chất lượng dữ liệu (QC).</li>
                    <li>Phân loại hành động và đối tượng logic.</li>
                  </ul>
                </div>
                <div class="col-md-4">
                  <h5 class="fw-bold text-primary border-bottom pb-2"><i class="bi bi-pc-display me-2"></i>Công cụ</h5>
                  <ul class="text-secondary mt-3 mb-0">
                    <li class="mb-2">Thao tác máy tính tốc độ cao (thành thạo phím tắt).</li>
                    <li class="mb-2">Tiếp thu nhanh các phần mềm gán nhãn AI chuyên dụng.</li>
                    <li>Báo cáo công việc (Word, Excel, Google Docs).</li>
                  </ul>
                </div>
                <div class="col-md-4">
                  <h5 class="fw-bold text-warning border-bottom pb-2"><i class="bi bi-people-fill me-2"></i>Kỹ năng mềm</h5>
                  <ul class="text-secondary mt-3 mb-0">
                    <li class="mb-2">Tỉ mỉ, quan sát tốt và chú ý chi tiết nhỏ.</li>
                    <li class="mb-2">Kiên nhẫn với khối lượng dữ liệu lớn và tác vụ lặp lại.</li>
                    <li class="mb-2">Tuân thủ nghiêm ngặt bảo mật thông tin.</li>
                    <li>Làm việc nhóm, thuyết trình, làm việc độc lập, quản lý công việc.</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div> 
      </div> 
    </section>

    <section id="experience" class="py-5 bg-white">
      <div class="container">
        <h2 class="fw-bold mb-5 display-5 text-center">Dự án</h2>

        <div class="card border-0 border-start border-danger border-5 shadow-sm p-4 mb-4 rounded-4 project-card">
          <div class="d-flex justify-content-between align-items-center flex-wrap mb-3">
            <h3 class="fw-bold mb-0 text-danger">Website đặt bàn lẩu Thái FourSpiceHotpot</h3>
            <span class="text-muted fw-bold">02/2026 - 05/2026</span>
          </div>
          <ul class="list-unstyled fs-5">
            <li class="mb-2"><strong>Vị trí:</strong> Fullstack Developer (Java Spring boot + Vue.js)</li>
            <li class="mb-2"><strong>Mô tả dự án:</strong> Xây dựng hệ thống quản lý nhà hàng lẩu, xử lý luồng nghiệp vụ thực tế gồm đặt bàn, check-in, phục vụ và thanh toán, đảm bảo đồng bộ trạng thái giữa các thực thể trong hệ thống.</li>
            <li class="mb-2"><strong>Công việc thực hiện:</strong>
              <ul>
                <li><strong>Backend:</strong> Thiết kế hệ thống Layered Architecture, sử dụng DTO. Xây dựng RESTful API và thao tác database bằng Spring Data JPA / Hibernate.</li>
                <li><strong>Nghiệp vụ:</strong> Quản lý luồng xử lý liên hoàn (Đặt bàn &rarr; Check-in &rarr; Tạo hóa đơn &rarr; Phục vụ &rarr; Thanh toán). Xử lý quan hệ n-n giữa Hóa đơn và Bàn ăn, tránh conflict dữ liệu.</li>
                <li><strong>Frontend:</strong> Xây dựng SPA với Vue Router. Giao diện hiển thị sơ đồ bàn, check-in, cập nhật dữ liệu và gọi API thời gian thực.</li>
              </ul>
            </li>
            <li class="mb-2"><strong>Công nghệ:</strong> Java (Spring Boot), Spring Data JPA / Hibernate, SQL Server, Vue.js, Vue Router, REST API, JWT, Docker.</li>
            <li><strong>Công cụ:</strong> IntelliJ IDEA, Visual Studio Code, SSMS, Postman, Git, GitHub, Docker Desktop.</li>
          </ul>
        </div>

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
    
    <section id="awards" class="py-5 bg-light">
      <div class="container">
        <h2 class="fw-bold mb-5 display-5 text-center">Giải thưởng & Danh hiệu</h2>
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="card border-0 border-start border-warning border-5 shadow-sm p-4 rounded-4 project-card">
              <ul class="list-unstyled mb-0 fs-5">
                <li class="mb-3"><i class="bi bi-trophy-fill text-warning me-3"></i><strong>2026:</strong> Danh hiệu top 150 sinh viên Xuất Sắc Kỳ Fall 2025</li>
                <li class="mb-3"><i class="bi bi-award-fill text-success me-3"></i><strong>2025:</strong> Đạt học bổng Kỳ Spring 2026</li>
                <li class="mb-3"><i class="bi bi-star-fill text-primary me-3"></i><strong>2025:</strong> Danh hiệu sinh viên Giỏi Kỳ Summer 2025</li>
                <li class="mb-3"><i class="bi bi-trophy-fill text-warning me-3"></i><strong>2025:</strong> Danh hiệu top 150 sinh viên Xuất Sắc Kỳ Spring 2025</li>
                <li><i class="bi bi-star-fill text-primary me-3"></i><strong>2024:</strong> Danh hiệu sinh viên Giỏi Kỳ Fall 2024</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="certificates" class="py-5 bg-white">
      <div class="container">
        <h2 class="fw-bold mb-5 display-5 text-center">Chứng chỉ</h2>
        <div class="row justify-content-center">
          <div class="col-md-8 col-lg-6">
            <div class="card border-0 shadow-sm p-3 rounded-4 text-center">
              <img src="./img/chungChiGemini.jpg" alt="Chứng chỉ Gemini" class="img-fluid rounded-3 mb-3 border">
              <h4 class="fw-bold text-dark mb-1 mt-2">Gemini Certified Student</h4>
              <p class="text-muted mb-0">Cấp bởi Google for Education</p>
            </div>
          </div>
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
.github:hover { color: #24292e; }
.tiktok:hover { color: #000000; }

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