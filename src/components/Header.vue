<template>
  <div>
    <div id="nav-main-container" class="hidden-xs">
      <nav class="navbar navbar-inverse navbar-static-top">
        <div class="container-fluid">
          <p class="navbar-text slogan">La vie, du côté top</p>
          <ul class="nav navbar-nav navbar-right socialicons">
            <li class="btn-youtube"><a href="#"><i class="fa fa-lg fa-youtube"></i> </a></li>
            <li class="btn-facebook"><a href="#"><i class="fa fa-lg fa-facebook"></i> </a></li>
            <li class="btn-twitter"><a href="#"><i class="fa fa-lg fa-twitter"></i> </a></li>
            <li class="btn-instagram"><a href="#"><i class="fa fa-lg fa-instagram"></i> </a></li>
            <li class="btn-snapchat"><a href="#"><i class="fa fa-lg fa-snapchat-ghost"></i> </a></li>
            <li class="btn-rss"><a href="#"><i class="fa fa-lg fa-rss"></i></a></li>
            <li class="btn-envelope"><a href="#"><i class="fa fa-lg fa-envelope"></i></a></li>
            <li role="separator" class="divider"></li>
            <li class="btn-ios"><a href="#"><i class="fa fa-lg fa-apple"></i></a></li>
            <li class="btn-android"><a href="#"><i class="fa fa-lg fa-android"></i></a></li>
          </ul>
          <p class="navbar-text navbar-right">On est partout : </p>
        </div>
      </nav>
      <nav class="navbar navbar-primary navbar-static-top">
        <div class="container-fluid">
          <div class="navbar-header">
            <a class="navbar-brand" href="#">
              <img src="http://localhost/topito-html/wp-content/themes/topito/assets/images/logo_responsive_2.png" class="img-responsive">
            </a>
          </div>
          <!--<ul class="nav navbar-nav navbar-right">
              <li class="small"><a href="#"><i class="fa fa-plus"></i> Publier un top</a></li>
          </ul>-->
          <ul class="nav navbar-nav truncatable">
            <li class="">
              <!--a class="" href="quiz.php">
                Quiz                </a>-->
              <router-link to="/quiz">Quiz</router-link>
            </li>
            <!--<li class="">
                <a class="" href='https://www.topito.com/video' >
                    Vidéo                </a>
            </li>
            <li class="">
                <a class="" href='https://www.topito.com/battle' >
                    Battle                </a>
            </li>
            <li class="">
                <a class="" href='https://www.topito.com/shopping' >
                    Shopping                </a>
            </li>
            <li class="img">
                <a class="comedynight" href="https://www.topito.com/topito-comedy-night-stand-up-ouh-la-la-cest-dingue-ce-truc" >
                    <img data-src="http://localhost/topito-html/wp-content/themes/topito/assets/images/header/header-topito-comedy-night.svg" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="Topito Comedy Night" width="93">
                </a>
            </li>
            <li class="">
                <a class="" href='https://shop.topito.com/'  target="_blank" >
                    Boutique                </a>
            </li>-->
          </ul>
          <!--<ul class="nav navbar-nav">
              <li class="separator"><a href="/best-of">Best-of</a></li>
              <li class="separator"><a href="/?topopif=1" rel="nofollow"><i class="fa fa-random"></i></a></li>
              <li class="separator"><a href="#" class="btn btn-link btn-search"><i class="fa fa-lg fa-search"></i></a></li>
          </ul>-->
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
name: "Header"
}
</script>

<style scoped>

</style>