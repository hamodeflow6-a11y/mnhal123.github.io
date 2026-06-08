---
layout: default
---

<style>
  /* تصميم الواجهة */
  .hero-section {
    padding: 60px 20px;
    text-align: center;
    background: linear-gradient(135deg, #2c3e50 0%, #000000 100%);
    color: white;
    border-radius: 20px;
    margin-bottom: 40px;
  }
  .hero-section h1 { font-size: 2.5em; color: #fff; margin-bottom: 10px; }
  .btn-custom {
    padding: 12px 30px;
    background-color: #2ecc71;
    color: white;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    display: inline-block;
    transition: 0.3s;
  }
  .btn-custom:hover { background-color: #27ae60; transform: scale(1.05); }

  /* تصميم قسم السيرة الذاتية */
  .cv-card {
    background: #ffffff;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    margin-bottom: 40px;
    border-right: 5px solid #2ecc71;
  }

  /* تصميم أزرار التواصل */
  .social-btns { display: flex; gap: 15px; margin-top: 20px; justify-content: center; }
  .social-btn {
    padding: 10px 20px;
    background-color: #34495e;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    font-size: 0.9em;
  }
  .social-btn:hover { background-color: #2c3e50; }
</style>

<div class="hero-section">
  <h1>منهل صلاح الدين بشير</h1>
  <p>طالبة تقانة معلومات | شغوفة بالبرمجة والابتكار الرقمي</p>
  <br>
  <a href="#cv" class="btn-custom">عرض السيرة الذاتية ↓</a>
</div>

<div id="cv" class="cv-card">
  <h2>📝 السيرة الذاتية</h2>
  <p><strong>الاسم:</strong> منهل صلاح الدين بشير</p>
  <p><strong>التخصص:</strong> تقانة معلومات</p>
  <p><strong>الهوايات:</strong> الرسم الرقمي، التعلم المستمر، والحلول البرمجية</p>
  
  <hr>
  
  <h3>🔗 تواصل معي</h3>
  <div class="social-btns">
    <a href="ضع_رابط_GitHub_هنا" class="social-btn">GitHub</a>
    <a href="ضع_رابط_LinkedIn_هنا" class="social-btn">LinkedIn</a>
  </div>
</div>
