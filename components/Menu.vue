<template>
    <b-container class="elevated">
        <b-navbar class="mt-2 ml-5 mr-5">
            <b-navbar-brand href="https://medium.com">
                <img src="~/assets/medium-logo.png" class="d-inline-block align-top" alt="logo">
            </b-navbar-brand>

            <b-navbar-nav>
                <hr class="divider">
                <b-nav-item href="https://medium.com/topic/software-engineering" style="font-size:18px">
                    Software Engineering
                </b-nav-item>
            </b-navbar-nav>

            <b-navbar-nav class="ml-auto">
                <b-nav-item href="https://medium.com/membership" class="right-menu">Become a member</b-nav-item>
                <b-nav-item href="https://medium.com/m/signin" class="right-menu">Sign in</b-nav-item>
                <b-button class="my-2 my-sm-0" variant="outline-success" style="font-size:14px">
                    Get Started
                </b-button>
            </b-navbar-nav>

        </b-navbar>
    </b-container>
</template>

<style scoped>
    img{
        height: 22px;
        width: 122px;
    }

    .right-menu{
        font-size: 14px;
    }

    .divider{
        width: 25px;
        border-top: 1px solid #8c8b8b;
        transform: rotate(90deg);
    }

    /* .elevated { 
            box-shadow: 1px 2px  gainsboro;
    } */


    @media only screen and (max-width: 1024px) {
        .right-menu, hr{
            display: none;
        }

        img{
            content:url("/assets/medium-logo-sm.png");
        }

    }
</style>