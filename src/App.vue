<template>
  <div class="container-fluid bg-dark" style="height: 100vh; overflow-y: auto">
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top border-bottom border-light border-opacity-25"
      style="height: 100px"
    >
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Wteam</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">首页</a>
            </li>
            <li class="nav-item"><a class="nav-link" href="#">上位机</a></li>
            <li class="nav-item"><a class="nav-link" href="#">通讯</a></li>

            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdownMenuLink"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                前端
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                <li><a class="dropdown-item" href="#">HTML</a></li>
                <li><a class="dropdown-item" href="#">JavaScript</a></li>
                <li><a class="dropdown-item" href="#">CSS</a></li>
                <li><a class="dropdown-item" href="#">VUE</a></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="container my-4 bg-dark py-4">
      <div class="row w-100" style="padding-top: 100px">
        <div class="col-lg-6 d-flex justify-content-center align-items-center">
          <span class="color-lg u-fs" style="font-weight: bold">这是一个工控人的网站</span>
        </div>
        <div class="col-lg-6 d-flex justify-content-center align-items-center mt-lg-5">
          <div class="row w-100 justify-content-center align-items-center">
            <button class="btn btn-primary mt-3 col-6 col-lg-4 m-2">开始查看</button>
            <button class="btn btn-primary mt-3 col-6 col-lg-4 m-2">开始学习</button>
          </div>
        </div>
      </div>
    </section>
    <section class="container bg-dark pb-10">
      <div class="row justify-content-center mt-5">
        <div class="col">
          <h2 class="text-center mb-4 text-white fs-2">我们的优势</h2>
          <div class="row w-100">
            <div class="col-lg-4 mb-3">
              <div class="card h-100 text-light bg-dark border-light border-opacity-25">
                <div class="card-body">
                  <h5 class="card-title text-center fs-4">专业知识</h5>
                  <p class="card-text mt-3">
                    我们有丰富的专业知识，包括电路设计、嵌入式系统、控制系统、通信协议、工业控制、工业机器人、工业自动化、工业自动化系统、工业自动化控制、工业自动化控制理论、工业自动化控制实践、工业自动化控制应用、工业控制系统、工业控制系统理论、工业控制系统实践、工业控制系统应用、工业控制系统集成、工业控制系统集成理论、工业控制系统集成实践、工业控制系统集成应用、工业控制系统集成案例研究等。
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 mb-3">
              <div class="card h-100 text-light bg-dark border-light border-opacity-25">
                <div class="card-body">
                  <h5 class="card-title text-center fs-4">丰富的案例</h5>
                  <p class="card-text mt-3">
                    我们有丰富的案例研究，包括工业机器人、工业自动化、工业控制系统、工业控制系统集成、工业控制系统集成案例研究等。
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4 mb-3">
              <div class="card h-100 text-light bg-dark border-light border-opacity-25">
                <div class="card-body">
                  <h5 class="card-title text-center fs-4">专业团队</h5>
                  <p class="card-text mt-3">
                    &nbsp; &nbsp; &nbsp;
                    &nbsp;我们有一支专业的团队，包括电子工程师、电气工程师、控制工程师、通信工程师、自动化工程师、算法工程师、软件工程师、硬件工程师、工业工程师、工业自动化工程师、工业控制工程师、工业控制系统集成工程师、工业控制系统集成案例研究师等。
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="container bg-dark py-5"></section>

    <section
      class="bg-dark fixed-bottom border-top border-light border-opacity-25"
      style="height: 100px; width: 100%"
    >
      <div class="bg-dark text-white">
        <div class="w-100 row my-3 justify-content-center align-items-center">
          <div class="col">
            <h2 class="text-center mb-3">关于我们</h2>
            <p class="text-center d-block">
              我是一群热爱编程的工控人，我希望通过我们的努力，帮助更多的人受益。我们是一个团队，我们一起学习，一起进步。我们是一个有梦想的团队，我希望用我们的努力，帮助更多的人实现梦想。
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script setup></script>
<style>
/* 文字渐变效果： */
.color-lg {
  background: linear-gradient(to right, #dae7be, #999ecb);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.bg-gradient {
  background: linear-gradient(to bottom, #3aa1fc, #8bfe83);
  background-size: cover;
  height: 100vh;
  overflow: hidden;
}
.u-fs {
  font-size: calc(1.275rem + 3.3vw);
}

@media (max-width: 992px) {
  .mt-lg-5 {
    margin-top: 2rem !important;
  }
}
.h-g {
  height: calc(100vh - 100px) !important;
}
</style>
