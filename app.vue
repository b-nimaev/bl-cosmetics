<template>
  <div>
    <NavbarComponent></NavbarComponent>
    <HeaderComponent></HeaderComponent>
    <main>
      <section id="about">
        <div class="container">
          <div class="row">
            <div class="col-md-5 d-flex">
              <div class="m-auto">
                <h2>О компании</h2>

                <p>Мы обеспечиваем рынок косметологии и эстетической медицины современными и востребованными продуктами
                  для
                  решения эстетических проблем клиентов, одновременно предоставляя полноценное обучение и консультации
                  клиентам компании для правильного и безопасного применения препаратов и достижения желаемого эффекта от
                  процедур.</p>
              </div>
            </div>
            <div class="col d-flex">
              <iframe width="70%" height="250" class="m-auto" src="https://www.youtube.com/embed/ZvKC-oH0L8Q"
                title="Интервью с владельцем компании Beauty Lux" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen></iframe>
            </div>
          </div>
        </div>
      </section>

      <section id="why">
        <div class="container">
          <h2 class="text-center">Почему выбирают нас?</h2>
          <p class="text-center">Мы формируем высокие стандарты в сфере эстетической медицины,<br> продвигая ценность
            здоровой и естественной красоты</p>
          <div class="row mt-5">
            <div class="col-8 m-auto">
              <article>
                <div class="icon">
                  <img src="@/assets/images/icon1.png" alt="">
                </div>
                <div class="content">
                  <h4>Высокий уровень сервиса</h4>
                  <p>Наши менеджеры всегда готовы предоставить исчерпывающую информацию о продукте и организовать его
                    своевременную доставку. Пациент пришел на процедуру? Препарат уже на столике!</p>
                </div>
              </article>
              <article>
                <div class="icon">
                  <img src="@/assets/images/icon2.png" alt="">
                </div>
                <div class="content">
                  <h4>Высокое качество продукции</h4>
                  <p>Мы работаем с брендами, которые прочно зарекомендовали себя в мире эстетической и интегративной
                    медицины и соответствуют высоким стандартам международного качества</p>
                </div>
              </article>
              <article>
                <div class="icon">
                  <img src="@/assets/images/icon4.png" alt="">
                </div>
                <div class="content">
                  <h4>Надежность и безопасность</h4>
                  <p>Доверие клиентов - то, чем мы дорожим! А доверие прежде всего строится на таких показателях, как
                    надежность и безопасность.</p>
                </div>
              </article>
              <article>
                <div class="icon">
                  <img src="@/assets/images/icon4.png" alt="">
                </div>
                <div class="content">
                  <h4>Профессионалы выбирают профессионалов!</h4>
                  <p>Ежедневно мы работаем над тем, чтобы каждый аспект нашего дела выходил на качественно новый уровень:
                    сервис, ассортимент продукции, квалификация и компетентность команды, сотрудничество с лучшими
                    брендами!</p>
                </div>
              </article>
            </div>
          </div>
        </div>
      </section>

      <section id="store">
        <div class="container">
          <img src="@/assets/images/store.png" alt="">
        </div>
      </section>

      <section id="products">
        <div class="container">
          <h2 class="mb-5 text-center">Наша продукция</h2>
          <div class="row">
            <div class="m-auto">
              <div class="grid m-auto">

                <div class="grid-item grit-item--double-d-width">
                  <NuxtImg format="jpg" width="800"
                    src="/assets/images/products/Pani Walewska/Miraculum_PW_banner FB_classic.jpg">
                  </NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="jpg" width="400" src="/assets/images/products/Pani Walewska/PW_Classic_logo_Sweet.png">
                  </NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="jpg" width="400"
                    src="/assets/images/products/Pani Walewska/Miraculum_PW_banner FB_classic.jpg"></NuxtImg>
                </div>


                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="jpg" width="400" src="/assets/images/products/Pani Walewska/Miraculum_PW_FB_krem.jpg">
                  </NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="jpg" width="400"
                    src="/assets/images/products/Pani Walewska/Miraculum_PW_FB_perfumy.jpg">
                  </NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="jpg" width="400"
                    src="/assets/images/products/Pani Walewska/Miuraculum_BN2019_FB_Ruby.jpg">
                  </NuxtImg>
                </div>

                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="png" width="400" src="/assets/images/products/Pani Walewska/pw-post.jpg"></NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="png" width="400"
                    src="/assets/images/products/Pani Walewska/PW_PRZECIWZMARSZCZKOWY.png">
                  </NuxtImg>
                </div>
                <div class="grid-item grit-item--double-width">
                  <NuxtImg format="png" width="400" src="/assets/images/products/Pani Walewska/PW_NAPRAWCZY.png">
                  </NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="jpg" width="200" src="/assets/images/products/Miraculum/_MG_3571.JPG"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="jpg" width="200" src="/assets/images/products/Miraculum/_MG_3565.JPG"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="jpg" width="200" src="/assets/images/products/Miraculum/_MG_3580.JPG"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="jpg" width="200" src="/assets/images/products/Miraculum/_MG_3593.JPG"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="png" width="200" src="/assets/images/products/Miraculum/astaplanctom1.png"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="png" width="200" src="/assets/images/products/rs cosmetic/png/_DSF1596-removebg-preview.png"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="png" width="200" src="/assets/images/products/rs cosmetic/png/_DSF1601-removebg-preview.png"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="png" width="200" src="/assets/images/products/rs cosmetic/png/_DSF1603-removebg-preview.png"></NuxtImg>
                </div>
                <div class="grid-item">
                  <NuxtImg format="png" width="200" src="/assets/images/products/rs cosmetic/png/_DSF1607-removebg-preview.png"></NuxtImg>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

    </main>
    <footer id="contacts">
      <div class="container">
        <div class="row">
          <div class="col">
            <img src="@/assets/images/logo.png" width="200px" alt="">
          </div>
          <div class="col m-auto">
            <div class="d-flex" style="width: 100%">
              <div class="socials" style="margin: auto 0 auto auto">
                <ul>
                  <li><a href="javscript:void(0)"><svg width="36" height="36" viewBox="0 0 36 36" fill="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M11.7 3H24.3C29.1 3 33 6.9 33 11.7V24.3C33 26.6074 32.0834 28.8203 30.4518 30.4518C28.8203 32.0834 26.6074 33 24.3 33H11.7C6.9 33 3 29.1 3 24.3V11.7C3 9.39262 3.9166 7.17974 5.54817 5.54817C7.17974 3.9166 9.39262 3 11.7 3ZM11.4 6C9.96783 6 8.59432 6.56893 7.58162 7.58162C6.56893 8.59432 6 9.96783 6 11.4V24.6C6 27.585 8.415 30 11.4 30H24.6C26.0322 30 27.4057 29.4311 28.4184 28.4184C29.4311 27.4057 30 26.0322 30 24.6V11.4C30 8.415 27.585 6 24.6 6H11.4ZM25.875 8.25C26.3723 8.25 26.8492 8.44755 27.2008 8.79918C27.5525 9.15081 27.75 9.62772 27.75 10.125C27.75 10.6223 27.5525 11.0992 27.2008 11.4508C26.8492 11.8025 26.3723 12 25.875 12C25.3777 12 24.9008 11.8025 24.5492 11.4508C24.1975 11.0992 24 10.6223 24 10.125C24 9.62772 24.1975 9.15081 24.5492 8.79918C24.9008 8.44755 25.3777 8.25 25.875 8.25ZM18 10.5C19.9891 10.5 21.8968 11.2902 23.3033 12.6967C24.7098 14.1032 25.5 16.0109 25.5 18C25.5 19.9891 24.7098 21.8968 23.3033 23.3033C21.8968 24.7098 19.9891 25.5 18 25.5C16.0109 25.5 14.1032 24.7098 12.6967 23.3033C11.2902 21.8968 10.5 19.9891 10.5 18C10.5 16.0109 11.2902 14.1032 12.6967 12.6967C14.1032 11.2902 16.0109 10.5 18 10.5ZM18 13.5C16.8065 13.5 15.6619 13.9741 14.818 14.818C13.9741 15.6619 13.5 16.8065 13.5 18C13.5 19.1935 13.9741 20.3381 14.818 21.182C15.6619 22.0259 16.8065 22.5 18 22.5C19.1935 22.5 20.3381 22.0259 21.182 21.182C22.0259 20.3381 22.5 19.1935 22.5 18C22.5 16.8065 22.0259 15.6619 21.182 14.818C20.3381 13.9741 19.1935 13.5 18 13.5Z"
                          fill="white" />
                      </svg>
                    </a></li>
                  <li><a href="javscript:void(0)"><svg width="36" height="36" viewBox="0 0 36 36" fill="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M33.6901 9C32.5351 9.525 31.2901 9.87 30.0001 10.035C31.3201 9.24 32.3401 7.98 32.8201 6.465C31.5751 7.215 30.1951 7.74 28.7401 8.04C27.5551 6.75 25.8901 6 24.0001 6C20.4751 6 17.5951 8.88 17.5951 12.435C17.5951 12.945 17.6551 13.44 17.7601 13.905C12.4201 13.635 7.66506 11.07 4.50006 7.185C3.94506 8.13 3.63006 9.24 3.63006 10.41C3.63006 12.645 4.75506 14.625 6.49506 15.75C5.43006 15.75 4.44006 15.45 3.57006 15V15.045C3.57006 18.165 5.79006 20.775 8.73006 21.36C7.78615 21.6183 6.7952 21.6543 5.83506 21.465C6.24247 22.7437 7.04036 23.8626 8.11658 24.6644C9.1928 25.4662 10.4932 25.9105 11.8351 25.935C9.5605 27.7357 6.74105 28.709 3.84006 28.695C3.33006 28.695 2.82006 28.665 2.31006 28.605C5.16006 30.435 8.55006 31.5 12.1801 31.5C24.0001 31.5 30.4951 21.69 30.4951 13.185C30.4951 12.9 30.4951 12.63 30.4801 12.345C31.7401 11.445 32.8201 10.305 33.6901 9Z"
                          fill="white" />
                      </svg>
                    </a></li>
                  <li><a href="javscript:void(0)"><svg width="36" height="36" viewBox="0 0 36 36" fill="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M15 22.5L22.785 18L15 13.5V22.5ZM32.34 10.755C32.535 11.46 32.67 12.405 32.76 13.605C32.865 14.805 32.91 15.84 32.91 16.74L33 18C33 21.285 32.76 23.7 32.34 25.245C31.965 26.595 31.095 27.465 29.745 27.84C29.04 28.035 27.75 28.17 25.77 28.26C23.82 28.365 22.035 28.41 20.385 28.41L18 28.5C11.715 28.5 7.8 28.26 6.255 27.84C4.905 27.465 4.035 26.595 3.66 25.245C3.465 24.54 3.33 23.595 3.24 22.395C3.135 21.195 3.09 20.16 3.09 19.26L3 18C3 14.715 3.24 12.3 3.66 10.755C4.035 9.405 4.905 8.535 6.255 8.16C6.96 7.965 8.25 7.83 10.23 7.74C12.18 7.635 13.965 7.59 15.615 7.59L18 7.5C24.285 7.5 28.2 7.74 29.745 8.16C31.095 8.535 31.965 9.405 32.34 10.755Z"
                          fill="white" />
                      </svg>
                    </a></li>
                  <li><a href="javscript:void(0)"><svg width="36" height="36" viewBox="0 0 36 36" fill="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                          d="M18 3C16.0302 3 14.0796 3.38799 12.2597 4.14181C10.4399 4.89563 8.78628 6.00052 7.3934 7.3934C4.58035 10.2064 3 14.0218 3 18C3 24.63 7.305 30.255 13.26 32.25C14.01 32.37 14.25 31.905 14.25 31.5V28.965C10.095 29.865 9.21 26.955 9.21 26.955C8.52 25.215 7.545 24.75 7.545 24.75C6.18 23.82 7.65 23.85 7.65 23.85C9.15 23.955 9.945 25.395 9.945 25.395C11.25 27.675 13.455 27 14.31 26.64C14.445 25.665 14.835 25.005 15.255 24.63C11.925 24.255 8.43 22.965 8.43 17.25C8.43 15.585 9 14.25 9.975 13.185C9.825 12.81 9.3 11.25 10.125 9.225C10.125 9.225 11.385 8.82 14.25 10.755C15.435 10.425 16.725 10.26 18 10.26C19.275 10.26 20.565 10.425 21.75 10.755C24.615 8.82 25.875 9.225 25.875 9.225C26.7 11.25 26.175 12.81 26.025 13.185C27 14.25 27.57 15.585 27.57 17.25C27.57 22.98 24.06 24.24 20.715 24.615C21.255 25.08 21.75 25.995 21.75 27.39V31.5C21.75 31.905 21.99 32.385 22.755 32.25C28.71 30.24 33 24.63 33 18C33 16.0302 32.612 14.0796 31.8582 12.2597C31.1044 10.4399 29.9995 8.78628 28.6066 7.3934C27.2137 6.00052 25.5601 4.89563 23.7403 4.14181C21.9204 3.38799 19.9698 3 18 3Z"
                          fill="white" />
                      </svg>
                    </a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col">
            <h5>2023 BL Cosmetics - Fake Ltd. Şti. ™</h5>
            <p>None rights reserved.</p>
          </div>
          <div class="col text-right" style="text-align: right;">
            <p>+90543 219 87 65</p>
            <p><a href="javascript:void(0)">contact@kurdancioglu.com</a></p>
            <p class="muted">24 Pifidik Ave, Şibidik mah. <br>Kocasinan, Batman, Turkey</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
.grid {
  .grid-item {
    width: 200px;
  }

  .grit-item--double-width {
    width: 400px;
  }

  .grit-item--double-d-width {
    width: 800px;
  }
}

#products {
  padding: 80px 0 100px;
}

#about,
#why {
  padding: 100px 0;
}

#why {
  article {
    display: flex;
    margin-bottom: 30px;

    &:last-child {
      margin-bottom: 0
    }

    .icon {
      display: flex;
      margin-right: 30px;

      img {
        width: 70px;
        display: block;
        margin: auto;
      }
    }

    .content {
      margin: auto 0;
    }
  }
}

#store {
  img {
    width: 100%;
    height: auto;
    max-height: min(400px, 35vh);
    object-fit: cover;
    object-position: center;
  }

  // height: 200px;
  margin-bottom: 50px;
  // background-image: url('@/assets/images/store.png');
  // background-position: center;
}

footer {
  padding: 50px 0;
  background-color: #fafafa;

  .socials {
    ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
      display: flex;

      li {
        margin: 0 7.5px;

        a {

          svg,
          path {
            fill: #333
          }
        }
      }
    }
  }
}
</style>

<script setup>
onMounted(() => {
  var elem = document.querySelector('.grid');
  var msnry = new Masonry(elem, {
    // options
    itemSelector: '.grid-item',
    originTop: true,
    columnWidth: 200,
    fitWidth: true
  });

  console.log(msnry)
})
</script>