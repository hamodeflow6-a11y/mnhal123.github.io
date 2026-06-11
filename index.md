---
layout: default
---

<style>
  /* إعدادات الوضع الداكن */
  body {
    background-color: #121212;
    color: #e0e0e0;
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
  }
  
  .hero-section {
    text-align: center;
    padding: 60px 20px;
    background: #1e1e1e;
    border-radius: 20px;
    border: 1px solid #333;
    margin-bottom: 40px;
  }
  
  .btn-nav {
    padding: 12px 20px;
    background-color: #bb86fc;
    color: #000;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    margin: 5px;
    display: inline-block;
    transition: 0.3s;
  }
  .btn-nav:hover { background-color: #9965f4; color: #fff; }

  .section-card {
    background: #1e1e1e;
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 30px;
    border-left: 5px solid #bb86fc;
  }
  
  h2 { color: #bb86fc; margin-top: 0; }

  /* تنسيق زر التواصل */
  .social-btn {
    display: inline-block;
    padding: 12px 25px;
    background-color: #3b5998; /* لون فيسبوك المميز */
    color: white;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    transition: 0.3s;
  }
  .social-btn:hover { background-color: #2d4373; transform: translateY(-2px); }
</style>

<div class="hero-section">
  <h1>منهل صلاح الدين بشير آدم</h1>
  <p>طالب تقانة معلومات | مطور برمجيات</p>
  
  <div style="margin-top: 30px;">
    <a href="#cv" class="btn-nav">السيرة الذاتية</a>
    <a href="#skills" class="btn-nav">المهارات</a>
    <a href="#hobbies" class="btn-nav">الهوايات</a>
    <style>
  /* تصميم بطاقات المشاريع */
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  .project-card {
    background: #252525;
    padding: 20px;
    border-radius: 12px;
    border: 1px solid #444;
    transition: 0.3s;
  }
  .project-card:hover {
    border-color: #bb86fc;
    transform: translateY(-10px);
  }
  .project-card h3 { color: #bb86fc; margin-top: 0; }
  .project-link {
    display: inline-block;
    margin-top: 10px;
    color: #bb86fc;
    text-decoration: none;
    font-size: 0.9em;
  }
</style>

<div id="projects" class="section-card">
  <h2>🚀 معرض المشاريع</h2>
  <div class="projects-grid">
    
    <div class="project-card">
      <h3>نظام إدارة قواعد البيانات</h3>
      <p>بحث تقني مفصل للمقارنة بين Oracle و SQL Server.</p>
      <a href="#" class="project-link">عرض التفاصيل ←</a>
    </div>

    <div class="project-card">
      <h3>مشروع C++ قيد التطوير</h3>
      <p>خوارزميات معالجة البيانات وبناء هياكل بيانات مخصصة.</p>
      <a href="#" class="project-link">قريباً ←</a>
    </div>

  </div>
</div>

    <a href="#contact" class="btn-nav">تواصل معي</a>
  </div>
</div>

<div id="cv" class="section-card">
  <h2>📝 السيرة الذاتية</h2>
  <p>أنا منهل، متخصص في تقانة المعلومات، أسعى دائماً لتحويل التحديات البرمجية إلى حلول إبداعية.</p>
</div>

<div id="skills" class="section-card">
  <h2>💻 المهارات واللغات</h2>
  <ul>
    <li><strong>HTML / CSS:</strong> تطوير واجهات المواقع.</li>
    <li><strong>C++:</strong> بناء الخوارزميات والبرمجة المنطقية.</li>
  </ul>
</div>

<div id="hobbies" class="section-card">
  <h2>🎨 الهوايات</h2>
  <p>الرسم الرقمي هو نافذتي للإبداع بعيداً عن شاشات الكود.</p>
</div>

<div id="contact" class="section-card">
  <h2>📞 تواصل معي</h2>
  <p>يسعدني تواصلكم عبر حسابي الشخصي:</p>
  <a href="https://www.facebook.com/profile.php?id=61575944877447" target="_blank" class="social-btn">
    تابعني على فيسبوك
  </a>
</div>

