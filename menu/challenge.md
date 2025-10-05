# MIT Challenge - My Learning Curriculum

이 챌린지는 [Scott Young의 MIT Challenge](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)에서 영감을 받아, MIT 컴퓨터공학/수학/과학 커리큘럼을 1년간 독학하는 프로젝트입니다.

> **목표:** MIT 핵심 과목을 온라인 자료와 오픈 강의로 완주하며, 각 과목별로 학습 링크와 결과를 남깁니다.

---
## 커리큘럼

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
.course-content strong { color: #2d9da8; display: inline-block; min-width: 120px; }
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

### 📚 Phase 1: Mathematics & Physics Foundation (Months 1-3)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.01: Physics I – Classical Mechanics</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <p>I completed this class in July as part of a pilot experiment. The course is brilliant, Prof. Walter Lewin does an amazing job bringing physics to life.</p>
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">Access the course material for free</a></li>
      <li><strong>완료 기한:</strong> 2025년 12월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>학습 방법:</strong> Feynman Technique 사용</li>
      <li><strong>시험 결과:</strong> <a href="#">My exam results</a></li>
      <li><strong>MIT 솔루션:</strong> <a href="#">Actual MIT Solutions</a></li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 1월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>학습 시간:</strong> 120시간</li>
      <li><strong>주요 주제:</strong> Limits, Derivatives, Integrals, Series</li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/18-02-multivariable-calculus-fall-2007/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 2월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
      <li><strong>학습 시간:</strong> 100시간</li>
      <li><strong>주요 주제:</strong> Vectors, Partial Derivatives, Multiple Integrals</li>
    </ul>
  </div>
</div>

### 📚 Phase 2: Core Sciences (Months 4-6)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.02: Physics II – Electromagnetism</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 3월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>담당 교수:</strong> Prof. Walter Lewin</li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>5.111: Principles of Chemical Science</span>
    <span class="course-status">COMPLETED*</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 4월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
      <li><strong>비고:</strong> Basic chemistry principles</li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 5월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

### 📚 Phase 3: Computer Science Core (Months 7-9)

<div class="course-item">
  <div class="course-header in-progress">
    <span class="course-toggle">▶</span>
    <span>6.01: Introduction to EE and CS I</span>
    <span class="course-status">IN PROGRESS</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 6월</li>
      <li><strong>진행률:</strong> 45%</li>
      <li><strong>주요 주제:</strong> Programming, Circuits, Signals</li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 7월</li>
      <li><strong>시작 예정:</strong> 2026년 6월</li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 8월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>주요 주제:</strong> Sorting, Searching, Graph Algorithms, Dynamic Programming</li>
    </ul>
  </div>
</div>

### 📚 Phase 4: Advanced Topics (Months 10-12)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>18.03: Differential Equations</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 9월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 9월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>주요 주제:</strong> Proofs, Graph Theory, Probability</li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header not-started">
    <span class="course-toggle">▶</span>
    <span>최종 프로젝트: [프로젝트 제목]</span>
    <span class="course-status">PLANNED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>주제:</strong> 실제 문제를 해결하는 종합 프로젝트</li>
      <li><strong>완료 기한:</strong> 2026년 10월</li>
      <li><strong>목표:</strong> 학습한 모든 내용을 통합하여 실용적인 애플리케이션 개발</li>
      <li><strong>공개:</strong> GitHub 저장소 및 블로그 포스트</li>
    </ul>
  </div>
</div>

---
## 학습 자료

### 🎓 무료 온라인 강의
- [MIT OpenCourseWare](https://ocw.mit.edu/)
- [Stanford Online](https://online.stanford.edu/)
- [Coursera](https://www.coursera.org/)
- [edX](https://www.edx.org/)

### 📖 추천 도서
1. [도서명 1] - 저자명
2. [도서명 2] - 저자명
3. [도서명 3] - 저자명

### 💻 실습 플랫폼
- [GitHub](https://github.com) - 프로젝트 저장소
- [LeetCode](https://leetcode.com) - 코딩 연습
- [Kaggle](https://www.kaggle.com) - 데이터 과학 프로젝트

---
## 진행 상황

### 📊 전체 진행률
<div style="width: 100%; background-color: #e0e0e0; border-radius: 10px; height: 30px; margin: 20px 0;">
  <div style="width: 0%; background-color: #4CAF50; height: 30px; border-radius: 10px; text-align: center; line-height: 30px; color: white; font-weight: bold;">
    0%
  </div>
</div>

### 📅 주간 학습 현황

| 주차 | 날짜 | 학습 내용 | 시간 | 상태 |
|------|------|-----------|------|------|
| 1 | 2025-10-05 ~ 2025-10-11 | - | 0h | 🔜 |
| 2 | 2025-10-12 ~ 2025-10-18 | - | 0h | 🔜 |
| 3 | 2025-10-19 ~ 2025-10-25 | - | 0h | 🔜 |

---
## 완료된 과제 및 프로젝트

### 🎯 완료 목록
현재 완료된 항목이 없습니다.

---
## 학습 일지

### 📝 최근 업데이트
- **2025-10-05**: 챌린지 시작! 목표 설정 및 커리큘럼 계획

---
## TEDx 스타일 발표 준비

챌린지 완료 후, 학습 경험을 공유하는 발표를 준비할 예정입니다.

### 발표 주제 (예정)
- 제목: "[주제명]"
- 핵심 메시지: 집중적인 자기주도 학습의 힘
- 예상 일자: 2026년 10월

---
## 참고 자료

###
# My Learning Challenge

## 개요

이 챌린지는 [Scott Young의 MIT Challenge](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)에서 영감을 받아 시작한 개인 학습 프로젝트입니다. 

**목표**: 12개월 동안 집중적으로 학습하여 특정 분야의 전문성을 갖추기

---

## 챌린지 규칙

### 📋 기본 원칙
1. **기간**: 12개월 (시작일: 2025년 10월 5일)
2. **범위**: 선택한 커리큘럼의 모든 과정 완료
3. **증명**: 각 과정의 과제 및 프로젝트 완성
4. **공개**: 학습 과정 및 결과물 블로그에 공개

### ✅ 성공 기준
- [ ] 모든 강의 내용 학습 완료
- [ ] 각 과목의 과제 완료
- [ ] 최종 프로젝트 완성
- [ ] 학습 일지 작성 (주 1회 이상)

---

## 커리큘럼

<style>
.course-item {
  margin-bottom: 10px;
  border-radius: 8px;
  overflow: hidden;
}

.course-header {
  background: linear-gradient(135deg, #2d9da8 0%, #2d8a9a 100%);
  color: white;
  padding: 15px 20px;
  cursor: pointer;
  font-weight: 600;
  font-size: 16px;
  display: flex;
  align-items: center;
  transition: all 0.3s ease;
  user-select: none;
}

.course-header:hover {
  background: linear-gradient(135deg, #3ab0bd 0%, #359faf 100%);
  transform: translateX(5px);
}

.course-header.completed {
  background: linear-gradient(135deg, #2d9da8 0%, #2d8a9a 100%);
}

.course-header.in-progress {
  background: linear-gradient(135deg, #ffa726 0%, #fb8c00 100%);
}

.course-header.not-started {
  background: linear-gradient(135deg, #78909c 0%, #546e7a 100%);
}

.course-toggle {
  margin-right: 10px;
  font-size: 20px;
  transition: transform 0.3s ease;
  display: inline-block;
  width: 20px;
}

.course-toggle.open {
  transform: rotate(90deg);
}

.course-status {
  margin-left: auto;
  font-size: 14px;
  background: rgba(255,255,255,0.2);
  padding: 4px 12px;
  border-radius: 12px;
}

.course-content {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease;
  background: #f8f9fa;
  border: 1px solid #e0e0e0;
  border-top: none;
}

.course-content.open {
  max-height: 1000px;
  padding: 20px;
}

.course-content ul {
  list-style: none;
  padding-left: 0;
}

.course-content li {
  padding: 8px 0;
  border-bottom: 1px solid #e0e0e0;
}

.course-content li:last-child {
  border-bottom: none;
}

.course-content strong {
  color: #2d9da8;
  display: inline-block;
  min-width: 120px;
}

.rating-badge {
  background: #2d9da8;
  color: white;
  padding: 2px 8px;
  border-radius: 4px;
  font-size: 12px;
  margin-left: 10px;
}
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

### 📚 Phase 1: Mathematics & Physics Foundation (Months 1-3)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.01: Physics I – Classical Mechanics</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <p>I completed this class in July as part of a pilot experiment. The course is brilliant, Prof. Walter Lewin does an amazing job bringing physics to life.</p>
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">Access the course material for free</a></li>
      <li><strong>완료 기한:</strong> 2025년 12월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>학습 방법:</strong> Feynman Technique 사용</li>
      <li><strong>시험 결과:</strong> <a href="#">My exam results</a></li>
      <li><strong>MIT 솔루션:</strong> <a href="#">Actual MIT Solutions</a></li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 1월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>학습 시간:</strong> 120시간</li>
      <li><strong>주요 주제:</strong> Limits, Derivatives, Integrals, Series</li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/18-02-multivariable-calculus-fall-2007/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 2월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
      <li><strong>학습 시간:</strong> 100시간</li>
      <li><strong>주요 주제:</strong> Vectors, Partial Derivatives, Multiple Integrals</li>
    </ul>
  </div>
</div>

### 📚 Phase 2: Core Sciences (Months 4-6)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>8.02: Physics II – Electromagnetism</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 3월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>담당 교수:</strong> Prof. Walter Lewin</li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>5.111: Principles of Chemical Science</span>
    <span class="course-status">COMPLETED*</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 4월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
      <li><strong>비고:</strong> Basic chemistry principles</li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 5월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
    </ul>
  </div>
</div>

### 📚 Phase 3: Computer Science Core (Months 7-9)

<div class="course-item">
  <div class="course-header in-progress">
    <span class="course-toggle">▶</span>
    <span>6.01: Introduction to EE and CS I</span>
    <span class="course-status">IN PROGRESS</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 6월</li>
      <li><strong>진행률:</strong> 45%</li>
      <li><strong>주요 주제:</strong> Programming, Circuits, Signals</li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 7월</li>
      <li><strong>시작 예정:</strong> 2026년 6월</li>
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
      <li><strong>학습 자료:</strong> <a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/">MIT OCW</a></li>
      <li><strong>완료 기한:</strong> 2026년 8월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>주요 주제:</strong> Sorting, Searching, Graph Algorithms, Dynamic Programming</li>
    </ul>
  </div>
</div>

### 📚 Phase 4: Advanced Topics (Months 10-12)

<div class="course-item">
  <div class="course-header completed">
    <span class="course-toggle">▶</span>
    <span>18.03: Differential Equations</span>
    <span class="course-status">COMPLETED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 9월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">4/5</span></li>
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
      <li><strong>학습 자료:</strong> <a href="#">MIT OCW Link</a></li>
      <li><strong>완료 기한:</strong> 2026년 9월</li>
      <li><strong>내 평가:</strong> <span class="rating-badge">5/5</span></li>
      <li><strong>주요 주제:</strong> Proofs, Graph Theory, Probability</li>
    </ul>
  </div>
</div>

<div class="course-item">
  <div class="course-header not-started">
    <span class="course-toggle">▶</span>
    <span>최종 프로젝트: [프로젝트 제목]</span>
    <span class="course-status">PLANNED</span>
  </div>
  <div class="course-content">
    <ul>
      <li><strong>주제:</strong> 실제 문제를 해결하는 종합 프로젝트</li>
      <li><strong>완료 기한:</strong> 2026년 10월</li>
      <li><strong>목표:</strong> 학습한 모든 내용을 통합하여 실용적인 애플리케이션 개발</li>
      <li><strong>공개:</strong> GitHub 저장소 및 블로그 포스트</li>
    </ul>
  </div>
</div>

---

## 학습 자료

### 🎓 무료 온라인 강의
- [MIT OpenCourseWare](https://ocw.mit.edu/)
- [Stanford Online](https://online.stanford.edu/)
- [Coursera](https://www.coursera.org/)
- [edX](https://www.edx.org/)

### 📖 추천 도서
1. [도서명 1] - 저자명
2. [도서명 2] - 저자명
3. [도서명 3] - 저자명

### 💻 실습 플랫폼
- [GitHub](https://github.com) - 프로젝트 저장소
- [LeetCode](https://leetcode.com) - 코딩 연습
- [Kaggle](https://www.kaggle.com) - 데이터 과학 프로젝트

---

## 진행 상황

### 📊 전체 진행률
<div style="width: 100%; background-color: #e0e0e0; border-radius: 10px; height: 30px; margin: 20px 0;">
  <div style="width: 0%; background-color: #4CAF50; height: 30px; border-radius: 10px; text-align: center; line-height: 30px; color: white; font-weight: bold;">
    0%
  </div>
</div>

### 📅 주간 학습 현황

| 주차 | 날짜 | 학습 내용 | 시간 | 상태 |
|------|------|-----------|------|------|
| 1 | 2025-10-05 ~ 2025-10-11 | - | 0h | 🔜 |
| 2 | 2025-10-12 ~ 2025-10-18 | - | 0h | 🔜 |
| 3 | 2025-10-19 ~ 2025-10-25 | - | 0h | 🔜 |

---

## 완료된 과제 및 프로젝트

### 🎯 완료 목록
현재 완료된 항목이 없습니다.

---

## 학습 일지

### 📝 최근 업데이트
- **2025-10-05**: 챌린지 시작! 목표 설정 및 커리큘럼 계획

---

## TEDx 스타일 발표 준비

챌린지 완료 후, 학습 경험을 공유하는 발표를 준비할 예정입니다.

### 발표 주제 (예정)
- 제목: "[주제명]"
- 핵심 메시지: 집중적인 자기주도 학습의 힘
- 예상 일자: 2026년 10월

---

## 참고 자료

### 💡 영감을 준 사례들
- [Scott Young - MIT Challenge](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)
- [Scott Young - TEDx Talk](https://www.youtube.com/watch?v=piSLobJfZ3c)

### 📚 학습 방법론
- **Feynman Technique**: 배운 내용을 간단하게 설명하기
- **Active Recall**: 능동적 회상 학습
- **Spaced Repetition**: 간격 반복 학습
- **Pomodoro Technique**: 25분 집중 + 5분 휴식

---

## 연락 및 피드백

이 챌린지에 대한 질문이나 피드백이 있으시면 [Contact](/menu/contact.md) 페이지를 통해 연락 주세요!

---

<div style="text-align: center; margin-top: 40px; padding: 20px; background-color: #f0f0f0; border-radius: 10px;">
  <h3>🚀 "The only way to do great work is to love what you do." - Steve Jobs</h3>
  <p>함께 배우고 성장해요!</p>
</div>
