<template>
    <div class="map-background">
        <img src="../assets/map.svg"/>
        <div class="tomsk"></div>
        <div class="burgas"></div>
        <div class="varna"></div>
        <div class="belgorod"></div>
        <div class="keninsberg"></div>
        <div class="kaunas"></div>
        <div class="vitebsk"></div>
        <div class="riga"></div>
        <div class="orsha"></div>
        <div class="smolensk"></div>
        <div class="elnya"></div>
        <div class="asino"></div>
        <div class="novosibirsk"></div>
        <div class="yurga"></div>
        <div class="vologda"></div>
        <div class="moskva"></div>
        <div class="vyazma"></div>
        <div class="white"></div>
        <div class="duhovshina"></div>
        <div class="kastornoe"></div>
        <div class="stalingrad"></div>
        <div class="zaporoje"></div>
        <div class="odessa"></div>
        <div class="odessa-korovel"></div>
        <div class="korovel"></div>
        <div class="lubvin"></div>
        <div class="lodz"></div>
        <div class="berlin"></div>
        <div class="st-russa"></div>
        <div class="kr-rog"></div>
        <div class="poznan"></div>
        <div class="magdeburg"></div>
        <div class="sinyavino"></div>
        <div class="tihvin"></div>
        <div class="myasnoy-bor"></div>
        <div class="vel-luki"></div>
        <div class="riga-left"></div>
        <svg width="1800px" height="1200px" class="svg">
            ////////////// ROSE PATH
            <a href="#" class="rose-a">
                <line
                        class="rose"
                        :x1="tomsk1.x + 9.5"
                        :y1="tomsk1.y + 9.5"
                        :x2="novosibirsk1.x + 9.5"
                        :y2="novosibirsk1.y + 9.5"
                        stroke="#ff3399"
                        stroke-width="5"
                />
                <path
                        :d="'M'+ novosibirsk1.x + ',' + novosibirsk1.y + ' ' + 'C' + (novosibirsk1.x - 136) + ',' + (novosibirsk1.y - 30) + ' '
                 + (novosibirsk1.x + 24) + ',' + (novosibirsk1.y) + ' ' + (novosibirsk1.x - 356) + ',' + (novosibirsk1.y + 72)"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ (novosibirsk1.x - 353) + ',' + (novosibirsk1.y + 71.5) + ' ' + 'C' + (novosibirsk1.x - 536) + ',' + (novosibirsk1.y + 120) + ' '
                 + (kastornoe1.x - 50) + ',' + (kastornoe1.y + 54) + ' ' + kastornoe1.x + ',' + kastornoe1.y"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ kastornoe1.x + ',' + kastornoe1.y + ' ' + 'C' + (kastornoe1.x - 110) + ',' + (kastornoe1.y + 104) + ' '
                 + (stalingrad1.x - 20) + ',' + (stalingrad1.y - 40) + ' ' + stalingrad1.x + ',' + stalingrad1.y"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ stalingrad1.x + ',' + stalingrad1.y + ' ' + 'C' + (stalingrad1.x - 100) + ',' + (stalingrad1.y + 36) + ' '
                 + (zaporoje1.x + 191) + ',' + (zaporoje1.y - 159) + ' ' + zaporoje1.x + ',' + zaporoje1.y"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ zaporoje1.x + ',' + zaporoje1.y + ' ' + 'C' + (zaporoje1.x - 20) + ',' + (zaporoje1.y + 10) + ' '
                 + (odessa1.x) + ',' + (odessa1.y - 100) + ' ' + odessa1.x + ',' + odessa1.y"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <line
                        class="rose"
                        :x1="odessa1.x"
                        :y1="odessa1.y"
                        :x2="odessaKorovel1.x"
                        :y2="odessaKorovel1.y"
                        stroke="#ff3399"
                        stroke-width="5"
                />
                <line
                        class="rose"
                        :x1="odessaKorovel1.x"
                        :y1="odessaKorovel1.y"
                        :x2="korovel1.x + 4"
                        :y2="korovel1.y + 6"
                        stroke="#ff3399"
                        stroke-width="5"
                />
                <path
                        :d="'M'+ korovel1.x + ',' + (korovel1.y + 4) + ' ' + 'C' + (korovel1.x) + ',' + (korovel1.y + 6) + ' '
                 + (lubvin1.x) + ',' + (lubvin1.y + 24) + ' ' + lubvin1.x + ',' + (lubvin1.y + 6)"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ (lubvin1.x - 1) + ',' + (lubvin1.y + 3) + ' ' + 'C' + (lubvin1.x) + ',' + (lubvin1.y + 9) + ' '
                 + (lodz1.x) + ',' + (lodz1.y + 34) + ' ' + lodz1.x + ',' + (lodz1.y + 3)"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
                <path
                        :d="'M'+ (lodz1.x) + ',' + (lodz1.y) + ' ' + 'C' + (lodz1.x) + ',' + (lodz1.y + 4) + ' '
                 + (berlin1.x) + ',' + (berlin1.y + 27) + ' ' + berlin1.x + ',' + (berlin1.y + 3)"
                        stroke="#ff3399"
                        fill="none"
                        stroke-width="5"
                        class="rose"
                />
            </a>
            //////////// BLUE PATH
            <a href="#" class="blue-a">
                <line
                        class="blue"
                        :x1="asino1.x - 1.5"
                        :y1="asino1.y - 1.5"
                        :x2="tomsk1.x - 1.5"
                        :y2="tomsk1.y - 1.5"
                        stroke="blue"
                        stroke-width="5"
                />
                <line
                        class="blue"
                        :x1="novosibirsk1.x - 7"
                        :y1="novosibirsk1.y - 7"
                        :x2="tomsk1.x - 7"
                        :y2="tomsk1.y - 7"
                        stroke="blue"
                        stroke-width="5"
                />
                <path
                        class="blue"
                        :d="'M'+ novosibirsk1.x + ',' + novosibirsk1.y + ' ' + 'C' + (novosibirsk1.x - 150) + ',' + (novosibirsk1.y - 150) + ' '
                 + (stRussa1.x + 120) + ',' + (stRussa1.y - 90) + ' ' + stRussa1.x + ',' + stRussa1.y"
                        stroke="blue"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="blue"
                        :x1="stRussa1.x"
                        :y1="stRussa1.y"
                        :x2="vyazma1.x"
                        :y2="vyazma1.y"
                        stroke="blue"
                        stroke-width="5"
                />
                <path
                        class="blue"
                        :d="'M'+ vyazma1.x + ',' + vyazma1.y + ' ' + 'C' + (vyazma1.x + 0) + ',' + (vyazma1.y + 50) + ' '
                 + (korovel1.x + 120) + ',' + (korovel1.y + 30) + ' ' + korovel1.x + ',' + korovel1.y"
                        stroke="blue"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="blue"
                        :x1="korovel1.x"
                        :y1="korovel1.y"
                        :x2="lubvin1.x"
                        :y2="lubvin1.y"
                        stroke="blue"
                        stroke-width="5"
                />
                <path
                        class="blue"
                        :d="'M'+ poznan1.x + ',' + poznan1.y + ' ' + 'C' + (poznan1.x + 0) + ',' + (poznan1.y + 50) + ' '
                 + (lubvin1.x - 20) + ',' + (lubvin1.y - 15) + ' ' + lubvin1.x + ',' + lubvin1.y"
                        stroke="blue"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="blue"
                        :x1="poznan1.x"
                        :y1="poznan1.y"
                        :x2="berlin1.x"
                        :y2="berlin1.y"
                        stroke="blue"
                        stroke-width="5"
                />
                <line
                        class="blue"
                        :x1="berlin1.x"
                        :y1="berlin1.y"
                        :x2="magdeburg1.x"
                        :y2="magdeburg1.y"
                        stroke="blue"
                        stroke-width="5"
                />
            </a>
            <a href="#" class="red-a">
                ////////////// RED PATH
                <path
                        class="red"
                        :d="'M'+ novosibirsk1.x + ',' + novosibirsk1.y + ' ' + 'C' + (novosibirsk1.x - 200) + ',' + (novosibirsk1.y - 100) + ' '
                 + (moskva1.x + 120) + ',' + (moskva1.y - 40) + ' ' + moskva1.x + ',' + moskva1.y"
                        stroke="red"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="tomsk1.x"
                        :y1="tomsk1.y"
                        :x2="novosibirsk1.x"
                        :y2="novosibirsk1.y"
                        stroke="red"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="tomsk1.x"
                        :y1="tomsk1.y"
                        :x2="yurga1.x"
                        :y2="yurga1.y"
                        stroke="red"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="moskva1.x"
                        :y1="moskva1.y"
                        :x2="vyazma1.x"
                        :y2="vyazma1.y"
                        stroke="red"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="white1.x"
                        :y1="white1.y"
                        :x2="vyazma1.x"
                        :y2="vyazma1.y"
                        stroke="red"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="white1.x"
                        :y1="white1.y"
                        :x2="duhovshina1.x"
                        :y2="duhovshina1.y"
                        stroke="red"
                        stroke-width="5"
                />
                <line
                        class="red"
                        :x1="vyazma1.x"
                        :y1="vyazma1.y"
                        :x2="duhovshina1.x"
                        :y2="duhovshina1.y"
                        stroke="red"
                        stroke-width="5"
                />
            </a>
            /////// LIGHT BLUE PATH
            <a href="#" class="light-blue-a">
                <line
                        class="light-blue"
                        :x1="asino1.x + 1.5"
                        :y1="asino1.y + 1.5"
                        :x2="tomsk1.x + 1.5"
                        :y2="tomsk1.y + 1.5"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
                <line
                        class="light-blue"
                        :x1="novosibirsk1.x + 3"
                        :y1="novosibirsk1.y + 3"
                        :x2="tomsk1.x + 3"
                        :y2="tomsk1.y + 3"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
                <line
                        class="light-blue"
                        :x1="novosibirsk1.x"
                        :y1="novosibirsk1.y"
                        :x2="stalingrad1.x"
                        :y2="stalingrad1.y"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
                <line
                        class="light-blue"
                        :x1="belgorod1.x"
                        :y1="belgorod1.y"
                        :x2="stalingrad1.x"
                        :y2="stalingrad1.y"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
                <line
                        class="light-blue"
                        :x1="belgorod1.x"
                        :y1="belgorod1.y"
                        :x2="kr_rog1.x"
                        :y2="kr_rog1.y"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
                <path
                        class="light-blue"
                        :d="'M'+ varna1.x + ',' + varna1.y + ' ' + 'C' + (varna1.x + 104) + ',' + (varna1.y - 239) + ' ' + (kr_rog1.x - -30) + ',' + (kr_rog1.y + 21) + ' ' + (kr_rog1.x - 2) + ',' + (kr_rog1.y - 6)"
                        stroke="deepskyblue"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="light-blue"
                        :x1="varna1.x"
                        :y1="varna1.y"
                        :x2="burgas1.x"
                        :y2="burgas1.y"
                        stroke="deepskyblue"
                        stroke-width="5"
                />
            </a>
            /////// VIOLET PATH
            <a href="#" class="violet-a">
                <line
                        class="violet"
                        :x1="tomsk1.x - 3.5"
                        :y1="tomsk1.y - 3.5"
                        :x2="novosibirsk1.x - 3.5"
                        :y2="novosibirsk1.y - 3.5"
                        stroke="indigo"
                        stroke-width="5"
                />
                <path
                        class="violet"
                        :d="'M'+ vologda1.x + ',' + vologda1.y + ' ' + 'C' + (vologda1.x + 35) + ',' + (vologda1.y - 10) + ' '
                 + (novosibirsk1.x - 110) + ',' + (novosibirsk1.y - 110) + ' ' + novosibirsk1.x + ',' + novosibirsk1.y"
                        stroke="indigo"
                        fill="none"
                        stroke-width="5"
                />
                <path
                        class="violet"
                        :d="'M'+ tihvin1.x + ',' + tihvin1.y + ' ' + 'C' + (tihvin1.x + 15) + ',' + (tihvin1.y - 10) + ' '
                 + (vologda1.x - 60) + ',' + (vologda1.y - 30) + ' ' + vologda1.x + ',' + vologda1.y"
                        stroke="indigo"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="myasnoyBor1.x"
                        :y1="myasnoyBor1.y"
                        :x2="tihvin1.x"
                        :y2="tihvin1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="sinyavino1.x"
                        :y1="sinyavino1.y"
                        :x2="myasnoyBor1.x"
                        :y2="myasnoyBor1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="sinyavino1.x"
                        :y1="sinyavino1.y"
                        :x2="vel_luki1.x"
                        :y2="vel_luki1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
                <path
                        class="violet"
                        :d="'M'+ duhovshina1.x + ',' + duhovshina1.y + ' ' + 'C' + (duhovshina1.x + 0) + ',' + (duhovshina1.y - 0) + ' '
                 + (vel_luki1.x - 0) + ',' + (vel_luki1.y + 60) + ' ' + vel_luki1.x + ',' + vel_luki1.y"
                        stroke="indigo"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="vitebsk1.x"
                        :y1="vitebsk1.y"
                        :x2="duhovshina1.x"
                        :y2="duhovshina1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="vitebsk1.x"
                        :y1="vitebsk1.y"
                        :x2="kaunas1.x"
                        :y2="kaunas1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
                <line
                        class="violet"
                        :x1="keninsberg1.x"
                        :y1="keninsberg1.y"
                        :x2="kaunas1.x"
                        :y2="kaunas1.y"
                        stroke="indigo"
                        stroke-width="5"
                />
            </a>
            //////// GREEN PATH
            <a href="#" class="green-a">
                <line
                        class="green"
                        :x1="tomsk1.x + 6.5"
                        :y1="tomsk1.y + 6.5"
                        :x2="novosibirsk1.x + 6.5"
                        :y2="novosibirsk1.y + 6.5"
                        stroke="limegreen"
                        stroke-width="5"
                />
                <path
                        class="green"
                        :d="'M'+ moskva1.x + ',' + moskva1.y + ' ' + 'C' + (moskva1.x + 110) + ',' + (moskva1.y - 30) + ' '
                 + (novosibirsk1.x - 120) + ',' + (novosibirsk1.y - 50) + ' ' + novosibirsk1.x + ',' + novosibirsk1.y"
                        stroke="limegreen"
                        fill="none"
                        stroke-width="5"
                />
                <path
                        class="green"
                        :d="'M'+ vel_luki1.x + ',' + vel_luki1.y + ' ' + 'C' + (vel_luki1.x - 0) + ',' + (vel_luki1.y + 25) + ' '
                 + (moskva1.x - 30) + ',' + (moskva1.y + 30) + ' ' + moskva1.x + ',' + moskva1.y"
                        stroke="limegreen"
                        fill="none"
                        stroke-width="5"
                />
                <line
                        class="green"
                        :x1="vel_luki1.x"
                        :y1="vel_luki1.y"
                        :x2="elnya1.x"
                        :y2="elnya1.y"
                        stroke="limegreen"
                        stroke-width="5"
                />
                <line
                        class="green"
                        :x1="smolensk1.x"
                        :y1="smolensk1.y"
                        :x2="elnya1.x"
                        :y2="elnya1.y"
                        stroke="limegreen"
                        stroke-width="5"
                />
                <line
                        class="green"
                        :x1="smolensk1.x"
                        :y1="smolensk1.y"
                        :x2="orsha1.x"
                        :y2="orsha1.y"
                        stroke="limegreen"
                        stroke-width="5"
                />
                <line
                        class="green"
                        :x1="riga1.x"
                        :y1="riga1.y"
                        :x2="orsha1.x"
                        :y2="orsha1.y"
                        stroke="limegreen"
                        stroke-width="5"
                />
                <path
                        class="green"
                        :d="'M'+ rigaLeft1.x + ',' + rigaLeft1.y + ' ' + 'C' + (rigaLeft1.x - 5) + ',' + (rigaLeft1.y + 25) + ' '
                 + (riga1.x - 10) + ',' + (riga1.y + 30) + ' ' + riga1.x + ',' + riga1.y"
                        stroke="limegreen"
                        fill="none"
                        stroke-width="5"
                />
            </a>
        </svg>
    </div>
</template>

<script>
    export default {
        name: "Map.vue",
        data() {
            return {
                tomsk1: {},
                asino1: {},
                moskva1: {},
                novosibirsk1: {},
                yurga1: {},
                vyazma1: {},
                white1: {},
                duhovshina1: {},
                stalingrad1: {},
                belgorod1: {},
                kr_rog1: {},
                varna1: {},
                burgas1: {},
                vologda1: {},
                tihvin1: {},
                sinyavino1: {},
                vel_luki1: {},
                vitebsk1: {},
                kaunas1: {},
                keninsberg1: {},
                riga1: {},
                orsha1: {},
                elnya1: {},
                korovel1: {},
                kastornoe1: {},
                odessa1: {},
                odessaKorovel1: {},
                rigaLeft1: {},
                zaporoje1: {},
                lubvin1: {},
                lodz1: {},
                berlin1: {},
                stRussa1: {},
                poznan1: {},
                magdeburg1: {},
                myasnoyBor1: {},
                smolensk1: {}
            };
        },
        mounted() {
            for (let i = 0; i < document.all.length; i++) {
                if (
                    document.all[i].className != "map-background" &&
                    document.all[i].className != ""
                ) {
                    if (document.all[i].className == "tomsk") {
                        this.tomsk1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "asino") {
                        this.asino1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "moskva") {
                        this.moskva1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "novosibirsk") {
                        this.novosibirsk1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "yurga") {
                        this.yurga1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "vyazma") {
                        this.vyazma1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "white") {
                        this.white1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "duhovshina") {
                        this.duhovshina1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "stalingrad") {
                        this.stalingrad1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "belgorod") {
                        this.belgorod1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "kr-rog") {
                        this.kr_rog1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "varna") {
                        this.varna1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "burgas") {
                        this.burgas1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "vologda") {
                        this.vologda1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "tihvin") {
                        this.tihvin1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "sinyavino") {
                        this.sinyavino1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "vel-luki") {
                        this.vel_luki1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "vitebsk") {
                        this.vitebsk1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "kaunas") {
                        this.kaunas1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "keninsberg") {
                        this.keninsberg1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "riga") {
                        this.riga1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "orsha") {
                        this.orsha1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "smolensk") {
                        this.smolensk1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "elnya") {
                        this.elnya1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "kastornoe") {
                        this.kastornoe1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "zaporoje") {
                        this.zaporoje1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "odessa") {
                        this.odessa1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "odessa-korovel") {
                        this.odessaKorovel1 = {
                            x: document.all[i].offsetLeft + 5,
                            y: document.all[i].offsetTop + 5
                        };
                    } else if (document.all[i].className == "korovel") {
                        this.korovel1.x = document.all[i].offsetLeft + 5;
                        this.korovel1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "lubvin") {
                        this.lubvin1.x = document.all[i].offsetLeft + 5;
                        this.lubvin1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "lodz") {
                        this.lodz1.x = document.all[i].offsetLeft + 5;
                        this.lodz1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "berlin") {
                        this.berlin1.x = document.all[i].offsetLeft + 5;
                        this.berlin1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "st-russa") {
                        this.stRussa1.x = document.all[i].offsetLeft + 5;
                        this.stRussa1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "kr-rog") {
                        this.krRog1.x = document.all[i].offsetLeft + 5;
                        this.krRog1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "poznan") {
                        this.poznan1.x = document.all[i].offsetLeft + 5;
                        this.poznan1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "magdeburg") {
                        this.magdeburg1.x = document.all[i].offsetLeft + 5;
                        this.magdeburg1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "sinyavino") {
                        this.sinyavino1.x = document.all[i].offsetLeft + 5;
                        this.sinyavino1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "myasnoy-bor") {
                        this.myasnoyBor1.x = document.all[i].offsetLeft + 5;
                        this.myasnoyBor1.y = document.all[i].offsetTop + 5;
                    } else if (document.all[i].className == "riga-left") {
                        this.rigaLeft1.x = document.all[i].offsetLeft + 5;
                        this.rigaLeft1.y = document.all[i].offsetTop + 5;
                    }
                }
            }
        }
    };
</script>

<style scoped>
    img {
        width: 100%;
        height: 100%;
    }

    .green-a:hover .green {
        stroke-width: 9;
    }

    .red-a:hover .red {
        stroke-width: 9;
    }

    .light-blue-a:hover .light-blue {
        stroke-width: 9;
    }

    .violet-a:hover .violet {
        stroke-width: 9;
    }

    .blue-a:hover .blue {
        stroke-width: 9;
    }

    .rose-a:hover .rose {
        stroke-width: 9;
    }

    .map-background {
        width: 100%;
        height: 100%;
    }

    .tomsk {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 47.3%;
        left: 79.6%;
    }

    .burgas {
        width: 10px;
        height: 10px;
        position: relative;
        left: 24.6%;
        bottom: 6%;
    }

    .varna {
        width: 10px;
        height: 10px;
        position: relative;
        left: 25.8%;
        bottom: 12.2%;
    }

    .belgorod {
        width: 10px;
        height: 10px;
        position: relative;
        left: 41.7%;
        bottom: 38.7%;
    }

    .keninsberg {
        width: 10px;
        height: 10px;
        position: relative;
        left: 23.2%;
        bottom: 52.1%;
    }

    .kaunas {
        width: 10px;
        height: 10px;
        position: relative;
        left: 26.2%;
        bottom: 53.7%;
    }

    .vitebsk {
        width: 10px;
        height: 10px;
        position: relative;
        left: 33.5%;
        bottom: 54.6%;
    }

    .riga {
        width: 10px;
        height: 10px;
        position: relative;
        left: 29.9%;
        bottom: 61.9%;
    }

    .orsha {
        width: 10px;
        height: 10px;
        position: relative;
        left: 33.2%;
        bottom: 53.7%;
    }

    .smolensk {
        width: 10px;
        height: 10px;
        position: relative;
        left: 35.4%;
        bottom: 53.3%;
    }

    .elnya {
        width: 10px;
        height: 10px;
        position: relative;
        left: 37.9%;
        bottom: 53%;
    }

    .asino {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 65.5%;
        left: 82.6%;
    }

    .novosibirsk {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 53%;
        left: 75.8%;
    }

    .yurga {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 53.9%;
        left: 84%;
    }

    .vologda {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 75.4%;
        left: 50.9%;
    }

    .moskva {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 64.4%;
        left: 45.9%;
    }

    .vyazma {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 61.5%;
        left: 41.8%;
    }

    .white {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 65.8%;
        left: 37.1%;
    }

    .duhovshina {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 64.4%;
        left: 37.5%;
    }

    .kastornoe {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 58.7%;
        left: 47.7%;
    }

    .stalingrad {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 48.7%;
        left: 54.1%;
    }

    .zaporoje {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 41.8%;
        left: 40.6%;
    }

    .odessa {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 41.7%;
        left: 32.6%;
    }

    .odessa-korovel {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 42.9%;
        left: 28.2%;
    }

    .korovel {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 53.8%;
        left: 26.1%;
    }

    .lubvin {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 56.1%;
        left: 22.3%;
    }

    .lodz {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 61.5%;
        left: 20.2%;
    }

    .berlin {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 72%;
        left: 15.6%;
    }

    .st-russa {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 78%;
        left: 38.6%;
    }

    .kr-rog {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 51.1%;
        left: 37.9%;
    }

    .poznan {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 70%;
        left: 19.8%;
    }

    .magdeburg {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 78.5%;
        left: 13.8%;
    }

    .sinyavino {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 92.8%;
        left: 37.8%;
    }

    .tihvin {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 90.8%;
        left: 39.8%;
    }

    .myasnoy-bor {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 90.5%;
        left: 38.3%;
    }

    .vel-luki {
        width: 10px;
        height: 10px;
        position: relative;
        bottom: 85.6%;
        left: 35.4%;
    }

    .riga-left {
        width: 10px;
        height: 10px;
        position: relative;
        left: 28.4%;
        bottom: 89%;
    }

    .svg {
        position: absolute;
        top: 0;
    }
</style>
