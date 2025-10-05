# MIT Challenge

Inspired by [Scott Young's MIT Challenge](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)

---

<style>
.course-item { margin-bottom: 10px; border-radius: 8px; overflow: hidden; }
.course-header { background: linear-gradient(135deg, #2d9da8 0%, #2d8a9a 100%); color: white; padding: 15px 20px; cursor: pointer; font-weight: 600; font-size: 16px; display: flex; align-items: center; transition: all 0.3s ease; user-select: none; }
.course-header:hover { background: linear-gradient(135deg, #3ab0bd 0%, #359faf 100%); transform: translateX(5px); }
.course-header.completed { background: linear-gradient(135deg, #2d9da8 0%, #2d8a9a 100%); }
.course-header.in-progress { background: linear-gradient(135deg, #ffa726 0%, #fb8c00 100%); }
.course-header.not-started { background: linear-gradient(135deg, #78909c 0%, #546e7a 100%); }
.course-toggle { margin-right: 10px; font-size: 20px; transition: transform 0.3s ease; display: inline-block; width: 20px; }
.course-toggle.open { transform: rotate(90deg); }
.course-status { margin-left: auto; font-size: 14px; background: rgba(255,255,255,0.2); padding: 4px 12px; border-radius: 12px; }
.course-content { max-height: 0; overflow: hidden; transition: max-height 0.3s ease; background: #f8f9fa; border: 1px solid #e0e0e0; border-top: none; }
.course-content.open { max-height: 1000px; padding: 20px; }
.course-content ul { list-style: none; padding-left: 0; }
.course-content li { padding: 8px 0; border-bottom: 1px solid #e0e0e0; }
.course-content li:last-child { border-bottom: none; }
.course-content strong { color: #2d9da8; display: inline-block; min-width: 100px; }
.rating-badge { background: #2d9da8; color: white; padding: 2px 8px; border-radius: 4px; font-size: 12px; margin-left: 10px; }
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const headers = document.querySelectorAll('.course-header');
  headers.forEach(header => {
    header.addEventListener('click', function() {
      const content = this.nextElementSibling;
      const toggle = this.querySelector('.course-toggle');
      content.classList.toggle('open');
      toggle.classList.toggle('open');
    });
  });
});
</script>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.01: Physics I – Classical Mechanics</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/8-01-physics-i-classical-mechanics-fall-1999/" target="_blank">MIT OCW</a></li>
      <li><strong>Video:</strong> <a href="https://www.youtube.com/playlist?list=PLUl4u3cNGP62QZp1G0Y2bKpL6R3F0bF1O" target="_blank">Walter Lewin Lectures</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">5/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>18.01: Single Variable Calculus</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">5/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>18.02: Multi-Variable Calculus</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/18-02-multivariable-calculus-fall-2007/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.02: Physics II – Electromagnetism</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/8-02-physics-ii-electricity-and-magnetism-spring-2007/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">5/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>5.111: Principles of Chemical Science</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/5-111-principles-of-chemical-science-fall-2008/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>7.012: Introduction to Biology</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/7-012-introduction-to-biology-fall-2004/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header in-progress">
    <span class="course-toggle">▶</span>
    <span>6.01: Introduction to EE and CS I</span>
    <span class="course-status">IN PROGRESS</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/6-01-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/" target="_blank">MIT OCW</a></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header not-started">
    <span class="course-toggle">▶</span>
    <span>6.02: Introduction to EE and CS II</span>
    <span class="course-status">PLANNED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/6-02-introduction-to-electrical-engineering-and-computer-science-ii-spring-2012/" target="_blank">MIT OCW</a></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>6.006: Introduction to Algorithms</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">5/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>18.03: Differential Equations</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/18-03-differential-equations-spring-2010/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>6.042J: Mathematics for Computer Science</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>Course:</strong> <a href="https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/" target="_blank">MIT OCW</a></li>
      <li><strong>Rating:</strong> <span class="rating-badge">5/5</span></li>
    </ul>
  </div>
</div>
