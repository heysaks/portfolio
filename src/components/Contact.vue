<template>
    <div class="contact-block">

        <BlockHeader description="For any questions" name="Contact me"/>

        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <p>sakshamthakurwork@gmail.com</p>
                    <p>+91 821-921-2412</p>
                    <a href="https://github.com/heysaks" rel="nofollow"
                       target="_blank"><i class="fa fa-github-square"></i></a>
                    <a href="https://www.linkedin.com/in/saksham-thakur-488abb19b/" rel="nofollow"
                       target="_blank"><i class="fa fa-linkedin-square"></i></a>
                    <a href="https://facebook.com/" rel="nofollow"
                       target="_blank"><i class="fa fa-facebook-square"></i></a>
                    <a href="https://www.instagram.com/_saksham_thakur_7/" rel="nofollow"
                       target="_blank"><i class="fa fa-instagram"></i></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
  import BlockHeader from '@/components/BlockHeader';

  export default {
    name: 'Contact',
    components: {BlockHeader}
  }
</script>

<style scoped>
    @import '../assets/css/icons.css';

    .contact-block {
        min-height: 100vh;
    }

    .contact-block .row {
        padding: 138px 0 0 0;
    }

    .contact-block p {
        color: #aaa;
        font-family: 'PT Sans Caption', sans-serif;
        font-size: 48px;
    }

    .contact-block p a {
        text-decoration: none;
        color: #aaa;
    }

    .contact-block i {
        color: #aaa;
        margin: 20px 20px 0 0;
        font-size: 48px;
        transition: all .35s ease-in-out;
    }

    .contact-block i:hover {
        color: #fff;
        transition: all .35s ease-in-out;
    }

    @media screen and (max-width: 768px) {
        .contact-block .row {
            padding: 50px 0;
            text-align: center;
        }

        .contact-block p {
            font-size: 24px;
        }

        .contact-block a:last-child i {
            margin-right: 0;
        }
    }
</style>