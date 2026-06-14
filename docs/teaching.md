<style type="text/css">

/* 全局正文：字体、基准字号、行高 */
body {
    font-family: "Muli", Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.6;
}

h1 {
    font-family: "Josefin Sans", Montserrat, "Muli", Arial, sans-serif;
    font-weight: 700;
    text-transform: uppercase;
    font-size: 34px;
    margin: 20px 0 10px 0;
}

h2 {
    font-family: "Muli", Arial, sans-serif;
    font-weight: 700;
    font-size: 24px;
    margin: 18px 0 8px 0;
    color: #003366;
}

h3 {
    font-family: "Muli", Arial, sans-serif;
    font-weight: 700;
    font-size: 20px;
    margin: 15px 0 6px 0;
    color: #003366;
}

.red-title {
    color: red;
    font-weight: 800;
    font-size: 1.3em;
}

/* ========== Teaching 课程卡片 ========== */
.course-grid {
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
    margin: 1rem 0 1.5rem 0;
}

.course-card {
    display: flex;
    align-items: stretch;
    background: #fff;
    border: 1px solid #e8ecf0;
    border-radius: 6px;
    border-left: 3px solid #e8ecf0;
}

.course-card:nth-child(odd)  { border-left-color: #3498DB; border-left-width: 3px; }
.course-card:nth-child(even) { border-left-color: #E67E22; border-left-width: 3px; }

.course-code {
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 142px;
    padding: 0.55rem 1rem;
    font-family: "Josefin Sans", Montserrat, sans-serif;
    font-weight: 700;
    font-size: 14px;
    color: #2C3E50;
    letter-spacing: 0.5px;
    text-align: center;
    line-height: 1.3;
}

.course-card:nth-child(odd)  .course-code { color: #3498DB; font-weight: 700; }
.course-card:nth-child(even) .course-code { color: #E67E22; font-weight: 700; }

.course-body {
    flex: 1;
    padding: 0.5rem 0.85rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.course-title {
    font-weight: 600;
    font-size: 14px;
    color: #2C3E50;
    margin-bottom: 0.2rem;
    line-height: 1.35;
}

.course-terms {
    display: flex;
    flex-wrap: wrap;
    gap: 0.35rem;
}

.course-term {
    display: inline-block;
    font-size: 0.65rem;
    font-weight: 600;
    color: #7f8c8d;
    background: #f2f4f6;
    padding: 2px 7px;
    border-radius: 3px;
    letter-spacing: 0.2px;
}

</style>


## Teaching

<div class="course-grid">

<div class="course-card">
  <div class="course-code">CMAA5041</div>
  <div class="course-body">
    <div class="course-title">Experiment Design for Protocol Optimization</div>
    <div class="course-terms">
      <span class="course-term">2025–26 Spring</span>
    </div>
  </div>
</div>

<div class="course-card">
  <div class="course-code">CMAA6018A</div>
  <div class="course-body">
    <div class="course-title">Independent Study</div>
    <div class="course-terms">
      <span class="course-term">2024–25 Spring</span>
      <span class="course-term">2025–26 Fall</span>
      <span class="course-term">2025–26 Spring</span>
    </div>
  </div>
</div>

<div class="course-card">
  <div class="course-code">CMAA6019A</div>
  <div class="course-body">
    <div class="course-title">Research Design and Optimization</div>
    <div class="course-terms">
      <span class="course-term">2024–25 Spring</span>
    </div>
  </div>
</div>

<div class="course-card">
  <div class="course-code">INFH5000</div>
  <div class="course-body">
    <div class="course-title">Information Science and Technology: Essentials and Trends</div>
    <div class="course-terms">
      <span class="course-term">2025–26 Fall (CMA)</span>
      <span class="course-term">2025–26 Spring (CMA)</span>
    </div>
  </div>
</div>

<div class="course-card">
  <div class="course-code">CMAA6101</div>
  <div class="course-body">
    <div class="course-title">CMA Seminar</div>
    <div class="course-terms">
      <span class="course-term">2025–26 Fall</span>
    </div>
  </div>
</div>

</div>
