<template>
    <div>
        <Header id="main">
            <div class="container">
                <div class="row">
                    <div class="col">
                        <h1><span>Лучшая</span> косметология<br> BL cosmetics</h1>
                        <p>With various different versions of toothpicks in great quality for a wide angle of purposes</p>

                        <div class="buttons-row">
                            <a href="#products" class="btn btn-success">Посмотреть продукты</a>
                            <a href="#about" class="btn btn-light">Узнать больше</a>
                        </div>
                    </div>
                    <div class="col">
                        <img src="@/assets/images/crown-1-svgrepo-com 1.png" width="270">
                    </div>
                </div>
            </div>
        </Header>
    </div>
</template>

<style lang="scss" scoped>
header {
    padding: 150px;

    h1 {
        span {
            text-shadow: -20px -8px 2px #d6cdcd
        }
    }
}

.buttons-row {
    margin-top: 50px;

    a {
        &:first-child {
            margin-right: 15px;
        }
    }
}</style>