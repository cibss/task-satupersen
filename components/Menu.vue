<template>
    <b-container>
        <b-navbar class="mt-2">
            <b-navbar-brand href="https://medium.com">
                <img src="~/assets/medium-logo.png" class="d-inline-block align-top" alt="logo">
            </b-navbar-brand>

            <b-navbar-nav>
                <!-- <b-nav-item style="font-size:20px">|</b-nav-item> -->
                <b-nav-item href="https://medium.com/topic/software-engineering" style="font-size:18px">
                    Software Engineering
                </b-nav-item>
            </b-navbar-nav>

            <!-- Right aligned nav items -->
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

    @media only screen and (max-width: 1024px) {
        .right-menu{
            visibility: hidden;
        }
    }
</style>