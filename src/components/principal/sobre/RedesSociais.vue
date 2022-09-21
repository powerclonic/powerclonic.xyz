<template>
    <article class="bg-cinza-25 rounded p-3 h-100">
        <h2 class="text-center text-white">Minhas redes</h2>
        <section class="container">
            <div class="row">
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="TwitterIcon" url="https://twitter.com/powerclonic" titulo="@powerclonic" />
                </div>
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="InstagramIcon" url="https://instagram.com/powermatheuss"
                        titulo="@powermatheuss" />
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="DiscordIcon" titulo="@power#7881" />
                </div>
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="YoutubeIcon" url="https://www.youtube.com/channel/UCAmEnE7yeKgJkyqurS2nRUw" titulo="Power" />
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="SpotifyIcon" url="https://open.spotify.com/user/aptz43iibr8uadjomzrps3zgh?si=bc615edc89884c31" titulo="Power" />
                </div>
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="SteamIcon" url="https://steamcommunity.com/id/powerclonic/" titulo="Power" />
                </div>
            </div>
        </section>
    </article>
</template>

<script setup>

import TwitterIcon from '@/assets/icons/sociais/twitter.svg';
import InstagramIcon from '@/assets/icons/sociais/instagram.svg';
import DiscordIcon from '@/assets/icons/sociais/discord.svg';
import YoutubeIcon from '@/assets/icons/sociais/youtube.svg';
import SteamIcon from '@/assets/icons/sociais/steam.svg';
import SpotifyIcon from '@/assets/icons/sociais/spotify.svg';
import BotaoSocial from '../../shared/BotaoSocial.vue';

</script>

<style>

</style>
