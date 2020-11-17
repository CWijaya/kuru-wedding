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
                <li><a href="#love" v-smooth-scroll>Love</a></li>
                <li><a href="#when" v-smooth-scroll>When</a></li>
                <li><a href="#pray" v-smooth-scroll>Pray</a></li>
            </ul>
        </div>

        <div id="love" class="section-linked">
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

        <div id="when" class="section-linked">
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

        <div id="pray" class="section-linked">
            <img
                :src="require('@/assets/images/gold-leaves.png')"
                alt="Flower"
                class="flower-1"
                v-if="windowWidth > 767"
            />
            <img
                :src="require('@/assets/images/gold-leaves.png')"
                alt="Flower"
                class="flower-2"
                v-if="windowWidth > 767"
            />
            <div class="content-container">
                <div class="text-center-desktop-up">
                    <div class="header">Doa & Harapan</div>
                </div>
                <div class="card">
                    <div
                        class="media"
                        v-for="(pray, index) in prays"
                        :key="'índex-' + index"
                    >
                        <div class="media-left">
                            <div class="initial">
                                <span>{{ pray.name | returnInitial }}</span>
                            </div>
                        </div>
                        <div class="media-body">
                            <div class="row">
                                <div class="col-xs-4 col-sm-3">
                                    <p class="name">{{ pray.name }}</p>
                                </div>
                                <div class="col-xs-8 col-sm-9 no-padding-left">
                                    <p>
                                        {{ pray.comment }}
                                    </p>
                                </div>
                            </div>
                            <p class="time">
                                {{ pray.created.toDate() | returnHours }}
                            </p>
                        </div>
                    </div>
                    <div class="pray-form">
                        <div class="row">
                            <div class="col-xs-12 col-sm-3">
                                <input
                                    type="text"
                                    placeholder="Name"
                                    v-model="name"
                                />
                            </div>
                            <div class="col-xs-12 col-sm-9">
                                <div class="comment-form">
                                    <!-- <input type="text" placeholder="Pray" /> -->
                                    <textarea
                                        placeholder="Pray"
                                        rows="1"
                                        v-model="comment"
                                    ></textarea>
                                    <button @click="addNewPray">
                                        <img
                                            src="./assets/images/arrow-gold.png"
                                            alt="Arrow"
                                            class="arrow"
                                        />
                                    </button>
                                </div>
                            </div>
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
import firebase from "firebase/app";
import "firebase/firestore";

// for sticky navbar
let mainNavLinks = document.querySelectorAll("ul.link-tab li a");
let mainSections = document.querySelectorAll(".section-linked");
let lastId;
let cur = [];

// Get a Firestore instance
export const db = firebase
    .initializeApp({ projectId: "kuru-wedding" })
    .firestore();

export default {
    name: "App",
    data: function () {
        return {
            windowWidth: window.innerWidth,
            prays: [],
            name: "",
            comment: "",
        };
    },
    filters: {
        returnInitial: function (name) {
            return name.charAt(0);
        },
        returnHours: function (time) {
            const hours = time.getHours();
            const minutes = time.getMinutes();

            return hours + ":" + minutes;
        },
    },
    methods: {
        listenToPrayChanges: function () {
            var self = this;
            db.collection("prays")
                .orderBy("created", "asc")
                .onSnapshot(function (querySnapshot) {
                    const prays = querySnapshot.docs.map((doc) => doc.data());
                    console.log(prays);
                    self.prays = prays;
                });
        },
        addNewPray: function () {
            var self = this;
            db.collection("prays").add({
                name: self.name,
                comment: self.comment,
                created: new Date(),
            });

            // reset form
            this.name = "";
            this.comment = "";
        },

        addStickyNavbar: function (event) {
            // var header = document.querySelector("ul.link-tab");
            var header = document.querySelector("ul.link-tab");
            var sticky = header.offsetTop;

            console.log(sticky);
            console.log(window.pageYOffset);

            if (window.pageYOffset > sticky) {
                header.classList.add("sticky");
            } else {
                header.classList.remove("sticky");
            }

            // let fromTop = window.scrollY;

            // mainNavLinks.forEach((link) => {
            //     let section = document.querySelector(link.hash);

            //     if (
            //         section.offsetTop <= fromTop &&
            //         section.offsetTop + section.offsetHeight > fromTop
            //     ) {
            //         link.classList.add("current");
            //     } else {
            //         link.classList.remove("current");
            //     }
            // });
        },
    },
    mounted() {
        // console.log(db);
        this.listenToPrayChanges();
    },
    created() {
        // add scroll listener
        // window.addEventListener("scroll", this.addStickyNavbar);
    },
    destroyed() {
        // window.removeEventListener("scroll", this.addStickyNavbar);
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

    @include media-query-tablet-portrait-up {
        width: 100%;
        max-width: 730px;
        height: 580px;
        margin-left: auto;
        margin-right: auto;
        border-radius: 12px;
        margin-top: 100px;
    }

    iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 5px;

        @include media-query-tablet-portrait-up {
            border-radius: 12px;
        }
    }
}

#pray {
    position: relative;

    img.flower-1,
    img.flower-2 {
        position: absolute;
        width: 20%;
        display: block;
        left: -4%;
        top: 6%;
        transform: scaleY(-1);
    }

    img.flower-2 {
        transform: scaleX(-1) scaleY(-1);
        left: initial;
        right: -4%;
    }

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

        @include media-query-tablet-portrait-up {
            font-size: 24px;
            margin-left: auto;
            border-radius: 10px 10px 0 0;
            padding: 18px 32px;
        }
    }

    .card {
        background-color: $secondary-color;
        padding: 25px 15px;
        margin: 0 15px;
        border-radius: 4px;

        @include media-query-tablet-portrait-up {
            padding: 40px 35px;
            border-radius: 12px;
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

            @include media-query-tablet-portrait-up {
                width: 56px;
                height: 56px;
                margin-right: 20px;
            }

            span {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translateX(-50%) translateY(-41%);
                font-size: 20px;
                color: #e5d29d;

                @include media-query-tablet-portrait-up {
                    font-size: 37px;
                }
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

                @include media-query-tablet-portrait-up {
                    top: 14px;
                    border-top: 13px solid transparent;
                    border-right: 20px solid #fff;
                    border-bottom: 13px solid transparent;
                }
            }
        }

        .media-body {
            position: relative;
            padding: 15px 10px 24px;
            background-color: #fff;
            border-radius: 6px;

            @include media-query-tablet-portrait-up {
                padding: 22px 24px 24px;
                border-radius: 12px;
            }

            p {
                margin-bottom: 0;

                @include media-query-tablet-portrait-up {
                    font-size: 23px;
                    line-height: 1.4;
                }

                &.name {
                    font-family: "Ageo Bold";
                }

                &.time {
                    position: absolute;
                    bottom: 6px;
                    right: 6px;
                    font-size: 11px;

                    @include media-query-tablet-portrait-up {
                        bottom: 10px;
                        right: 11px;
                        font-size: 13px;
                    }
                }
            }
        }

        .pray-form {
            input,
            textarea {
                display: block;
                background-color: #fff;
                border: none;
                box-shadow: none;
                outline: none;
                border-radius: 8px;
                width: 100%;
                padding: 15px;
                font-size: 15px;
                color: $primary-color;
                font-family: "Ageo Regular";

                @include media-query-tablet-portrait-up {
                    font-size: 19px;
                }

                @include media-query-desktop-up {
                    font-size: 23px;
                }

                @include media-query-medium-desktop-up {
                    font-size: 26px;
                }
            }

            .comment-form {
                position: relative;
                margin-top: 15px;

                @include media-query-tablet-portrait-up {
                    margin-top: 0;
                }

                input,
                textarea {
                    padding-right: 70px;
                }

                button {
                    position: absolute;
                    top: 50%;
                    right: 0;
                    transform: translateY(-50%);
                    background-color: #fff;
                    border: none;
                    box-shadow: none;
                    outline: none;
                    cursor: pointer;

                    img {
                        width: 60px;
                        display: block;
                    }
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
            padding-left: 20px;
            padding-right: 20px;
            text-align: left;
        }

        @include media-query-desktop-up {
            padding-left: 4%;
            padding-right: 4%;
        }

        @include media-query-medium-desktop-up {
            padding-left: 11%;
            padding-right: 11%;
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
                left: 0;
                padding-left: 15px;
                padding-right: 15px;
            }

            @include media-query-desktop-up {
                left: 3%;
            }

            @include media-query-medium-desktop-up {
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

        @include media-query-tablet-portrait-up {
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        li {
            padding-left: 0;
            flex: 1;
            text-transform: uppercase;
            color: $primary-color;
            margin: 0 10px;
            padding: 20px 15px;
            background-color: transparent;
            transition: all 0.3s ease-in-out;

            &.active {
                background-color: $primary-color;
                color: #fff;

                a {
                    color: #fff;
                }
            }

            @include media-query-tablet-portrait-up {
                margin: 0 30px;
            }

            a {
                color: $primary-color;
                text-decoration: none;
                font-size: 16px;
                font-family: "Ageo Regular";
                transition: all 0.3s ease-in-out;

                @include media-query-tablet-portrait-up {
                    font-size: 20px;
                }

                @include media-query-desktop-up {
                    font-size: 24px;
                }

                @include media-query-medium-desktop-up {
                    font-size: 26px;
                }
            }
        }

        &.sticky {
            position: fixed;
            top: 0;
            width: 100%;
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
