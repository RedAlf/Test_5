<template>
    <!-- include Includes/Header.pug -->
    
    <div class="mainBox">
    <div class="leftBox">
        <div class="menuHoverButton">
        <div class="menuButtonLine"></div>
        <div class="menuButtonLine"></div>
        <div class="menuButtonLine"></div>
        <div class="sideMenu">
            <ol>Зарегестрированные пользователи</ol>
        </div>
        </div>
    </div>
    <div class="content"> 
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit, eos eum minima odit pariatur consequatur! Aliquam temporibus harum sit ipsam voluptatum, libero enim ducimus culpa quod accusamus ab, cum nesciunt.Velit excepteur fugiat sit ex sit reprehenderit magna.Ea velit consectetur sit nostrud commodo non sint.Esse laborum irure laboris laborum dolor minim ullamco veniam.Laborum cillum ad enim proident aute.Voluptate id voluptate exercitation occaecat labore cupidatat.</p>
        <div class="image1 image"></div>
        <p>Fugiat et ad ut culpa veniam. Aliquip incididunt exercitation sit dolore quis nulla ipsum. Dolore incididunt deserunt cillum occaecat esse quis irure ipsum tempor dolore occaecat consequat officia.</p>
        <div class="image2 image"></div>
        <p>Nostrud Lorem commodo amet ad quis reprehenderit labore occaecat labore elit. Dolor qui deserunt ea adipisicing fugiat ut. Sit elit amet quis tempor ad dolor. Irure minim do sit mollit proident. Sint occaecat magna nulla reprehenderit qui fugiat. Culpa velit eu excepteur qui voluptate. Ut ex nostrud do et voluptate nisi do in nostrud. Id nulla anim incididunt nulla do ad magna. Cillum est nulla deserunt id eiusmod. Deserunt deserunt cillum aliqua adipisicing nulla tempor.</p>
    </div>
    </div>
    <!-- include Includes/Footer.pug -->
</template>

<script>
export default {
  name: 'Main'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import 'Includes/Common.scss';
@import 'Includes/Footer.scss';
@import 'Includes/Header.scss';


.mainBox {
    width: auto;
    height: auto;
    min-height: 600px;
    display: flex;
    padding: 15px;
    display: flex;

    .leftBox {
        min-width: 70px;
        width: 25%;

        .menuHoverButton:hover {
            .sideMenu {
                transition: opacity 3s 3s;
                display: inherit;
                opacity: 1;
            }
        }

        .menuHoverButton {
            width: 40px;
            height: 33px;
            background: darkgrey;
            border: 3px outset #ccc;
            padding: 12px 0 0 5px;
            cursor: pointer;

            .menuButtonLine {
                background: white;
                width: 30px;
                height: 2px;
                margin-bottom: 4px;
                border: 1px inset #ccc;
            }

            .sideMenu {
                width: 300px;
                height: 500px;
                background: white;
                position: relative;
                top: -39px;
                left: -8px;
                border: 2px outset #ccc;
                display: none;
                opacity: 0.5;
            }
        }
    }

    .content {
        border: 2px outset #ccc;
        min-width: 350px;
        max-width: 50%;
        background: darken($color: grey, $amount: 30);
        color: white;
        padding: 10px;

        p {
            margin-bottom: 15px;
        }

        .image {
            width: 100%;
            height: 383px;
            margin-bottom: 10px;
        }

        .image1 {
            background: url(./img/1_QXBIWcsS8IPYQUTIN6lvcA.png) no-repeat;
        }

        .image2 {
            background: url(./img/deepminds-new-ai-teaches-itself-chess-beats-grandmaster-312959.jpg) no-repeat;
        }
    }
}
</style>
