<template>
    <div id="app">
        <top-bar></top-bar>
        <section-pages>
            <div id="introduction">
                <top-text>
                    
                    
                </top-text>
                <div id="use-cases">
                    <div id="case-internet" class="card">
                        
                        <header class="card-header">
                            <p class="card-header-title">
                                Component
                            </p>
                            <a href="#" class="card-header-icon" aria-label="more options">
                                <span class="icon">
                                    <i class="fas fa-angle-down" aria-hidden="true"></i>
                                </span>
                            </a>
                        </header>
                        <div class="card-content">
                            <div class="content">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                                <a href="#">@bulmaio</a>. <a href="#">#css</a> <a href="#">#responsive</a>
                                <br>
                                <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
                            </div>
                        </div>
                        <footer class="card-footer">
                            <a href="#" class="card-footer-item">Save</a>
                            <a href="#" class="card-footer-item">Edit</a>
                            <a href="#" class="card-footer-item">Delete</a>
                        </footer>
                        
                    </div>
                    <div id="case-energy"></div>
                    <div id="case-news"></div>
                    <div id="case-housing"></div>
                    <div id="case-rideshare"></div>
                    <div id="case-builder">                        
                    </div>                    
v                </div>
                <div id="video"></div>
            </div>
            <div id="roles">
                
                <heading>Everyone has a role to play in the Polils economy.</heading>
                <div id="reporter">
                    
                </div>
                <div id="">
                    
                </div>            
            </div>
            <div id="designs">
                <heading></heading>
                <div id="meta-designs">
                    <div id="currency"></div>
                    <div id="offer"></div>
                    <div id="proposal"></div>
                    <div id="organization"></div>
                    <div id="government"></div>
                </div>
                <div id="object-designs">
                    <heading></heading>                
                    <div id="internet"></div>
                    <div id="energy"></div>
                    <div id="news"></div>
                    <div id="real estate"></div>
                    <div id="insurance"></div>
                </div>            
        </section-pages>

            </div>
</template>

<script>
 import 'bulma/css/bulma.css'
 export default {
     name: 'app',
     data () {
         return {
             msg: 'Welcome to Your Vue.js App'
         }
     }
 }
</script>

<style>
 #app {
     font-family: 'Avenir', Helvetica, Arial, sans-serif;
     -webkit-font-smoothing: antialiased;
     -moz-osx-font-smoothing: grayscale;
     text-align: center;
     color: #2c3e50;
     margin-top: 60px;
 }

 h1, h2 {
     font-weight: normal;
 }

 ul {
     list-style-type: none;
     padding: 0;
 }

 li {
     display: inline-block;
     margin: 0 10px;
 }

 a {
     color: #42b983;
 }
</style>
