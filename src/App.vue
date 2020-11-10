<template>
    <div id="app">
        <header>
            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/header.jpg')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/header.jpg')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/desktop/header.jpg')"
                    class="background"
                    alt="Kuru X Madha"
                />
            </picture>
            <img
                class="logo hidden-tablet-up"
                alt="Kuru X Madha Logo"
                src="./assets/images/logo.png"
            />
        </header>

        <div id="the-wedding">
            <picture>
                <source
                    :srcset="
                        require('@/assets/images/desktop/the-wedding-of.png')
                    "
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/the-wedding-of.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/desktop/the-wedding-of.png')"
                    alt="The Wedding of"
                    class="text"
                />
            </picture>

            <!-- leaves-1 -->
            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/gold-leaves.png')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/gold-leaves.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/gold-leaves.png')"
                    alt="Flower"
                    class="flower-1"
                />
            </picture>

            <!-- leaves-2 -->
            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/gold-leaves.png')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/gold-leaves.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/gold-leaves.png')"
                    alt="Flower"
                    class="flower-2"
                />
            </picture>

            <!-- leaves-3 -->
            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/gold-leaves.png')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/gold-leaves.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/gold-leaves.png')"
                    alt="Flower"
                    class="flower-3"
                />
            </picture>

            <!-- leaves-4 -->
            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/gold-leaves.png')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/gold-leaves.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/gold-leaves.png')"
                    alt="Flower"
                    class="flower-4"
                />
            </picture>

            <h5 class="name">
                RIZZA AMANDHA PUTRI <br />
                &<br />
                FAROUQ ZULKARNAIN SURANATA
            </h5>

            <h2>TETAP<br />PAKAI</h2>

            <picture>
                <source
                    :srcset="require('@/assets/images/desktop/mask.png')"
                    media="(min-width: 768px)"
                />

                <source
                    :srcset="require('@/assets/images/mask.png')"
                    media="(max-width: 768px)"
                />

                <img
                    :src="require('@/assets/images/desktop/mask.png')"
                    alt="Mask"
                    class="mask"
                />
            </picture>

            <h2>TETAP</h2>
            <h1>Sehat</h1>

            <ul class="link-tab">
                <li>Love</li>
                <li>When</li>
                <li>Pray</li>
            </ul>
        </div>

        <div id="love">
            <div class="content-container">
                <img
                    v-if="windowWidth > 767"
                    :src="require('@/assets/images/desktop/logo-big.png')"
                    class="big-logo-background"
                />
                <div class="part-1">
                    <div class="row">
                        <div class="col-xs-5 col-sm-6 no-padding-right-mobile">
                            <picture>
                                <source
                                    :srcset="
                                        require('@/assets/images/desktop/photoshoot-1.jpg')
                                    "
                                    media="(min-width: 768px)"
                                />

                                <source
                                    :srcset="
                                        require('@/assets/images/photoshoot-1.jpg')
                                    "
                                    media="(max-width: 768px)"
                                />

                                <img
                                    :src="
                                        require('@/assets/images/desktop/photoshoot-1.jpg')
                                    "
                                    alt=" Farouk X Mandha"
                                    class="photoshoot"
                                />
                            </picture>
                        </div>
                        <div class="col-xs-7 col-sm-6">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit, sed do eiusmod tempor
                                incididunt ut labore et dolore magna aliqua.
                                Quis ipsum suspendisse ultrices gravida. Risus
                                commodo viverra maecenas accumsan lacus vel
                                facilisis.
                            </p>
                        </div>
                    </div>
                </div>

                <div class="part-2">
                    <div class="row">
                        <div class="col-xs-5 col-sm-6">
                            <p class="right">
                                Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit, sed do eiusmod tempor
                                incididunt ut labore et dolore magna aliqua.
                                Quis ipsum suspendisse ultrices gravida. Risus
                                commodo viverra maecenas accumsan lacus vel
                                facilisis.
                            </p>
                        </div>
                        <div class="col-xs-7 col-sm-6 no-padding-left-mobile">
                            <picture>
                                <source
                                    :srcset="
                                        require('@/assets/images/desktop/photoshoot-2.jpg')
                                    "
                                    media="(min-width: 768px)"
                                />

                                <source
                                    :srcset="
                                        require('@/assets/images/photoshoot-2.jpg')
                                    "
                                    media="(max-width: 768px)"
                                />

                                <img
                                    :src="
                                        require('@/assets/images/desktop/photoshoot-2.jpg')
                                    "
                                    alt=" Farouk X Mandha"
                                    class="photoshoot"
                                />
                            </picture>
                        </div>
                    </div>
                </div>

                <div class="part-3">
                    <picture>
                        <source
                            :srcset="
                                require('@/assets/images/desktop/photoshoot-3.jpg')
                            "
                            media="(min-width: 768px)"
                        />

                        <source
                            :srcset="
                                require('@/assets/images/photoshoot-3.jpg')
                            "
                            media="(max-width: 768px)"
                        />

                        <img
                            :src="
                                require('@/assets/images/desktop/photoshoot-3.jpg')
                            "
                            alt=" Farouk X Mandha"
                            class="photoshoot-big"
                        />
                    </picture>
                </div>
            </div>
        </div>

        <div id="when">
            <div class="content-container">
                <img
                    class="logo-gold"
                    alt="Kuru X Madha Logo"
                    src="./assets/images/logo-gold.png"
                />

                <img class="doa" alt="Doa" src="./assets/images/doa.png" />

                <p class="hidden-mobile">
                    Dengan memohon rahmat dan ridho Allah SWT, <br />kami
                    bermaksud menyelenggarakan pernikahan putra-putri kami
                </p>

                <p class="hidden-tablet-up">
                    Dengan memohon rahmat dan ridho Allah SWT, kami bermaksud
                    menyelenggarakan pernikahan putra-putri kami
                </p>

                <h5 class="name">
                    RIZZA AMANDHA PUTRI <br />
                    &<br />
                    FAROUQ ZULKARNAIN SURANATA
                </h5>

                <p class="italic">
                    “Dan di antara tanda-tanda kekuasaan-Nya ialah Dia
                    menciptakan untukmu isteri-isteri dari jenismu sendiri,
                    supaya kamu cenderung dan merasa tenteram kepadanya, dan
                    dijadikan-Nya diantaramu rasa kasih dan sayang. Sesungguhnya
                    pada yang demikian itu benar-benar terdapat tanda-tanda bagi
                    kaum yang berfikir.”
                </p>

                <p class="italic">QS. Ar-Ruum : 21</p>
            </div>
            <div class="akad-container">
                <div class="row">
                    <div class="col-xs-12 col-sm-4">
                        <p class="akad">
                            Akad Nikah :<br />
                            Ahad 20 Desember 2020<br />
                            Pukul : 09.00 WIB
                        </p>
                    </div>
                    <div class="col-xs-12 col-sm-4">
                        <p class="akad">
                            Resepsi <br />
                            Ahad 20 Desember 2020<br />
                            Pukul : 11.00 - 01.00 WIB
                        </p>
                    </div>
                    <div class="col-xs-12 col-sm-4">
                        <p class="akad">
                            Bertempat :<br />
                            Aula Ahmad Yani Makodam Jaya<br />
                            No.8- 13630, Jl. Mayjen Sutoyo <br />
                            Jl. Bersama No.15, RT.7/RW.7, <br />
                            Cawang, Kec. Kramat jati, Kota Jakarta Timur,<br />
                            13640
                        </p>
                    </div>
                </div>
            </div>

            <hr />
        </div>

        <div id="pray">
            <div class="content-container">
                <div class="header">Doa & Harapan</div>
                <div class="card">
                    <div class="media">
                        <div class="media-left">
                            <div class="initial">
                                <span>T</span>
                            </div>
                        </div>
                        <div class="media-body">
                            <div class="row">
                                <div class="col-xs-4">
                                    <p class="name">Tara Basro</p>
                                </div>
                                <div class="col-xs-8 no-padding-left">
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit, sed do eiusmod tempor
                                        incididunt ut labore et dolore magna.
                                    </p>
                                </div>
                            </div>
                            <p class="time">06:05</p>
                        </div>
                    </div>

                    <div class="media">
                        <div class="media-left">
                            <div class="initial">
                                <span>A</span>
                            </div>
                        </div>
                        <div class="media-body">
                            <div class="row">
                                <div class="col-xs-4">
                                    <p class="name">Apit Mane</p>
                                </div>
                                <div class="col-xs-8 no-padding-left">
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit.
                                    </p>
                                </div>
                            </div>
                            <p class="time">06:05</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div id="map">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3963.3928699821636!2d106.7952779152981!3d-6.597999266334978!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69c5c62d7196cd%3A0xb9728ad803356b26!2sBogor%20Palace%2C%20Paledang%2C%20Central%20Bogor%2C%20Bogor%20City%2C%20West%20Java!5e0!3m2!1sen!2sid!4v1604819788924!5m2!1sen!2sid"
                frameborder="0"
                style="border: 0"
                allowfullscreen=""
                aria-hidden="false"
                tabindex="0"
            ></iframe>
        </div>

        <footer>
            <div class="row">
                <div class="col-xs-6">
                    <p>
                        \designed by <br />
                        kuru
                    </p>
                </div>
                <div class="col-xs-6">
                    <p class="text-right">
                        \web development <br />
                        by CWijaya
                    </p>
                </div>
            </div>
            <img
                src="./assets/images/arrow-bottom.png"
                alt="Arrow"
                class="arrow"
            />
        </footer>
    </div>
</template>

<script>
export default {
    name: "App",
    data: function () {
        return {
            windowWidth: window.innerWidth,
        };
    },
};
</script>

<style lang="scss">
@import "./src/assets/main.scss";
@import "./src/assets/vars/variables";

footer {
    position: relative;
    padding: 15px;
    margin-top: 40px;
    margin-bottom: 20px;

    img.arrow {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate3d(-50%, -50%, 0);
        width: 15px;
    }

    p {
        color: #000;
        font-size: 12px;
        font-weight: 600;
        margin-bottom: 0;
    }
}

#map {
    position: relative;
    // width: 100%;
    height: 300px;
    margin-left: 15px;
    margin-right: 15px;
    margin-top: 60px;

    iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 5px;
    }
}

#pray {
    .content-container {
        position: relative;
        width: 100%;

        @include media-query-tablet-portrait-up {
            position: relative;
            width: 100%;
            max-width: 860px;
            margin-left: auto;
            margin-right: auto;
        }
    }

    .header {
        background-color: $primary-color;
        color: #fff;
        padding: 15px 25px;
        text-transform: uppercase;
        border-radius: 5px 5px 0 0;
        margin-left: 30px;
        display: inline-block;
        font-family: "Ageo Bold";
        letter-spacing: 1px;
    }

    .card {
        background-color: $secondary-color;
        padding: 25px 15px;
        margin: 0 15px;
        border-radius: 4px;

        @include media-query-tablet-portrait-up {
            padding: 35px 30px;
        }

        .media {
            margin-bottom: 30px;
        }

        .initial {
            position: relative;
            width: 30px;
            height: 30px;
            background-color: $primary-color;
            border-radius: 50%;
            font-family: "Ageo Extra Bold";

            span {
                position: absolute;
                top: 7px;
                left: 9px;
                font-size: 20px;
                color: #e5d29d;
            }
        }

        .media-left {
            position: relative;
            padding-top: 5px;

            &:after {
                content: "";
                display: block;
                position: absolute;
                top: 10px;
                right: 0;
                border-top: 10px solid transparent;
                border-right: 10px solid #fff;
                border-bottom: 10px solid transparent;
            }
        }

        .media-body {
            position: relative;
            padding: 15px 10px 24px;
            background-color: #fff;
            border-radius: 6px;

            p {
                margin-bottom: 0;

                &.name {
                    font-family: "Ageo Bold";
                }

                &.time {
                    position: absolute;
                    bottom: 6px;
                    right: 6px;
                    font-size: 11px;
                }
            }
        }
    }
}

#when {
    position: relative;
    text-align: center;
    padding: 45px 15px 70px;

    @include media-query-tablet-portrait-up {
        padding: 8% 15px;
    }

    .content-container {
        position: relative;
        width: 100%;

        @include media-query-tablet-portrait-up {
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
        }
    }

    .akad-container {
        position: relative;
        width: 100%;

        @include media-query-tablet-portrait-up {
            padding-top: 4%;
            padding-left: 11%;
            padding-right: 11%;
            text-align: left;
        }

        .row {
            .col-sm-4 {
                position: relative;

                @include media-query-tablet-portrait-up {
                    text-align: center;
                }

                &:after {
                    @include media-query-tablet-portrait-up {
                        content: "";
                        display: block;
                        position: absolute;
                        top: 0;
                        right: 0;
                        width: 3px;
                        background-color: $primary-color;
                        height: 130%;
                    }
                }

                &:last-child {
                    &:after {
                        @include media-query-tablet-portrait-up {
                            content: none;
                        }
                    }
                }
            }
        }
    }

    img.logo-gold {
        width: 17%;
        min-width: 75px;
        display: block;
        margin: 0 auto;
        margin-bottom: 9%;

        @include media-query-tablet-portrait-up {
            min-width: initial;
            width: 60px;
            margin-bottom: 30px;
        }
    }

    img.doa {
        position: relative;
        width: 85%;
        display: block;
        margin: 0 auto;
        margin-bottom: 12%;

        @include media-query-tablet-portrait-up {
            width: 100%;
            max-width: 250px;
            margin-bottom: 30px;
        }
    }

    h5.name {
        line-height: 2.4;
        margin-top: 13%;
        margin-bottom: 13%;

        @include media-query-tablet-portrait-up {
            font-size: 32px;
            margin-top: 35px;
            margin-bottom: 35px;
            line-height: 2;
        }
    }

    p {
        line-height: 1.5;

        &.akad {
            margin-top: 38px;

            @include media-query-tablet-portrait-up {
                margin-top: 0;
                display: inline-block;
                text-align: left;
                max-width: 80%;
            }
        }

        &.italic {
            @include media-query-tablet-portrait-up {
                font-size: 22px;
                line-height: 2;
            }
        }
    }

    hr {
        width: 24%;
        border-top: 1px solid $primary-color;
        margin: 0 auto;
        margin-top: 15%;

        @include media-query-tablet-portrait-up {
            margin-top: 7%;
        }
    }
}

#love {
    .content-container {
        position: relative;
        width: 100%;

        img.big-logo-background {
            position: absolute;
            top: 50%;
            left: 0;
            transform: translateY(-90%);
            width: 28%;
        }

        .part-1,
        .part-2,
        .part-3 {
            position: relative;

            @include media-query-tablet-portrait-up {
                max-width: 1100px;
                margin-left: auto;
                margin-right: auto;
            }
        }

        .part-1,
        .part-2 {
            @include media-query-tablet-portrait-up {
                left: 7%;
            }
        }
    }

    img.photoshoot {
        display: block;
        width: 100%;
        margin-bottom: 40px;

        @include media-query-tablet-portrait-up {
            margin-bottom: 55px;
        }
    }

    img.photoshoot-big {
        display: block;
        width: 100%;
        margin-top: 40px;
    }

    p {
        line-height: 1.5;

        @include media-query-tablet-portrait-up {
            line-height: 1.6;
        }
    }
}

#the-wedding {
    position: relative;
    padding: 45px 30px 60px;
    text-align: center;

    @include media-query-tablet-portrait-up {
        padding: 4% 30px;
    }

    img.text {
        display: block;
        position: relative;
        width: 60%;
        margin: 0 auto;
        margin-bottom: 15%;

        @include media-query-tablet-portrait-up {
            width: 42%;
            margin-bottom: 6.5%;
        }
    }

    h5.name {
        line-height: 1.4;
        margin-bottom: 15%;
    }

    img.mask {
        display: block;
        width: 136%;
        position: relative;
        left: 50%;
        transform: translateX(-50%);
        margin-top: 20px;
        margin-bottom: 36px;

        @include media-query-tablet-portrait-up {
            width: 60%;
        }
    }

    ul.link-tab {
        display: flex;
        padding-left: 0;
        list-style: none;
        width: 100%;
        padding-left: 20px;
        padding-right: 20px;
        margin-top: 120px;

        li {
            padding-left: 0;
            flex: 1;
            text-transform: uppercase;
            color: $primary-color;
            margin: 0 10px;
        }
    }

    img.flower-1,
    img.flower-2,
    img.flower-3,
    img.flower-4 {
        position: absolute;
        width: 20%;
        display: block;
        left: -4%;
        top: 6%;
    }

    img.flower-2 {
        transform: scaleX(-1);
        left: initial;
        right: -4%;
    }

    img.flower-3 {
        transform: scaleY(-1);
        top: initial;
        bottom: 6%;
    }

    img.flower-4 {
        transform: scaleX(-1) scaleY(-1);
        left: initial;
        right: -4%;
        top: initial;
        bottom: 6%;
    }
}

header {
    position: relative;
    width: 100%;

    img.background {
        display: block;
        position: relative;
        width: 100%;
    }

    img.logo {
        position: absolute;
        bottom: 23%;
        left: 0;
        right: 0;
        width: 17%;
        min-width: 75px;
        display: block;
        margin: 0 auto;
    }
}
</style>
