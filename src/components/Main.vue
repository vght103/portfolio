<template>
  <section>
    <div class="introduce text-center mb-5">
      <h2 class="pt-5 fs-1">About Me</h2>
      <p class="my-info fs-5 mb-5">
        오 충 현(Male) <br />
        1990. 06. 27 <br />
        (Mobile) 010-2978-5118 <br />
        vght103@naver.com
      </p>
      <p>안녕하세요, 저는 프론트엔드 개발자가 되고싶은 오충현입니다.</p>
      <p>
        처음 시작은 Yutube 를 통해 HTML 과 CSS의 개념과 간단한 스킬들을
        연습하였고, 웹페이지를 만들어보며 스킬을 익혔습니다.
      </p>
      <p>
        코드를 작성하는대로 웹브라우저가 직관적으로 변경되는 것에 큰 재미와
        흥미를 느꼈고,<br />
        보다 많은 공부를 하기 위해 직업훈련과정을 수강하며,<br />
        유튜브와 온라인 강의, 그리고 지인과의 스터디를 통해 Javascript 공부를
        진행하고 있습니다.
      </p>
      <p>
        최근에는 vue.js와 React.js 를 공부하고 있으며 간단한 프로젝트를 통해
        저에게 더 맞는 라이브러리를 찾고 있습니다.
      </p>
    </div>

    <div class="skill text-center mb-5 pt-5">
      <h2 class="mb-5 fs-1">Skills</h2>
      <div class="skill-imgs row justify-content-center ">
        <div class="skill skill-html col-lg-3">
          <img src="../assets/html.png" alt="" />
          <div class="skill-txt">
            마크업, 페이지 구조화, Form 요소 이용, Table 이용
          </div>
        </div>

        <div class="skill skill-css col-lg-3">
          <img src="../assets/css.jpg" alt="" />
          <div class="skill-txt">
            배경/텍스트 스타일링, Float/Flex 레이아웃 적용, 반응형
          </div>
        </div>
        <div class="skill skill-js col-lg-3">
          <img src="../assets/javascript.png" alt="" />
          <div class="skill-txt">DOM, 태그 생성 및 스타일 효과 적용</div>
        </div>
        <div class="skill skill-jquery col-lg-3">
          <img src="../assets/jquery.jpg" alt="" />
          <div class="skill-txt">
            이미지 슬라이드, 메뉴 노출과 같은 동적효과 적용
          </div>
        </div>
        <div class="skill skill-bootstrap col-lg-3">
          <img src="../assets/bootstrap.png" alt="" />
          <div class="skill-txt">레이아웃, Form 효과 및 디자인 적용</div>
        </div>
        <div class="skill skill-bootstrap col-lg-3">
          <img src="../assets/github.png" alt="" />
          <div class="skill-txt">레퍼지토리 생성 및 코드관리</div>
        </div>
      </div>
    </div>

    <div class="portfolio text-center row justify-content-center mb-5">
      <h2 class="mb-5 fs-1">What I Created</h2>

      <div class="card ms-5" style="width: 18rem;">
        <img src="../assets/blackyark.jpg" class="card-img-top" alt="" />
        <div class="card-body">
          <h5 class="card-title">BAC-블랙야크 리뉴얼</h5>
          <p class="card-text">
            HTML / CSS / Jquery 를 이용하여 BAC 블랙야크 페이지를 새롭게 리뉴얼
            하였습니다.
          </p>
          <a
            href="https://vght103.github.io/bac_blackyak/"
            target="blank"
            class="btn btn-primary stretched-link ms-2"
            >사이트</a
          >
          <a
            href="https://github.com/vght103/bac_blackyak"
            target="blank"
            class="btn btn-primary stretched-link ms-2"
            >Code</a
          >
        </div>
      </div>

      <div class="card ms-5" style="width: 18rem;">
        <img src="../assets/seoul.jpg" class="card-img-top" alt="" />
        <div class="card-body">
          <h5 class="card-title">서울시청 - 모바일 클론</h5>
          <p class="card-text">
            HTML / CSS / Jquery 를 이용하여 클론코딩을 진행했습니다.
            <br />레이아웃은 Flex 효과를 적용했으며 반응형으로 제작하였습니다.
          </p>
          <a
            href="https://vght103.github.io/m_seoul/"
            target="blank"
            class="btn btn-primary stretched-link"
            >사이트</a
          >
          <a
            href="https://github.com/vght103/m_seoul.git"
            target="blank"
            class="btn btn-primary stretched-link ms-2"
            >Code</a
          >
        </div>
      </div>

      <div class="card ms-5" style="width: 18rem;">
        <img src="../assets/todo.jpg" class="card-img-top" alt="" />
        <div class="card-body">
          <h5 class="card-title">JS - Todo List</h5>
          <p class="card-text">
            DOM을 잡고 이벤트를 적용하는 등 전반적인 자바스크립트 기초스킬을
            익히기 위한 Todo List 입니다.
          </p>
          <a
            href="https://vght103.github.io/JS_todo-list/"
            target="blank"
            class="btn btn-primary stretched-link"
            >사이트</a
          >
          <a
            href="https://github.com/vght103/JS_todo-list"
            target="blank"
            class="btn btn-primary stretched-link ms-2"
            >Code</a
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.my-info {
  display: inline-block;
  border-bottom: 1px solid #ddd;
  padding: 30px 0;
}

.skill-imgs > .skill {
  margin: 0 10px 50px 10px;
}

.skill-txt {
  margin-top: 20px;
  font-size: 16px;
  font-weight: bold;
}

.portfolio {
  font-size: 14px;
}
</style>
