
<!DOCTYPE html>
<html lang="en-US" dir="ltr">

  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Flyight | Profile</title>

    <meta name="description" content="Welcome on your personnal profile, here you can manage your personnal data">

    <meta name="author" content="Sami Messalti">
<meta name="keywords" content="social, network, performance, flyight, sneakers, meta, dualverse, interaction, metaverse, data, profile, video, media, share, like, token, security, technology, sport, coach, virtual, room">

<link rel="icon" type="image/png" sizes="32x32" href="/material/img/global/32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/material/img/global/16x16.png">
<meta name="theme-color" content="#ffffff">
    <script>
        if (window.location.host == 'dev.flyight.com') {
                let meta = document.createElement('meta')
                meta.setAttribute('name', 'robots')
                meta.setAttribute('content', 'noindex')
                document.head.appendChild(meta)
        }
</script>
<link rel="apple-touch-icon" sizes="180x180" href="">
<link rel="icon" type="image/png" sizes="32x32" href="">
<link rel="icon" type="image/png" sizes="16x16" href="">
<link rel="shortcut icon" type="image/x-icon" href="">
<link rel="manifest" href="/material/manifest.json">
<meta name="msapplication-TileImage" content="">
<meta name="theme-color" content="#ffffff">

<link href="/vendors/swiper/swiper-bundle.min.css" rel="stylesheet">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,500,600,700%7cPoppins:300,400,500,600,700,800,900&amp;display=swap" rel="stylesheet">
<link href="/material/icons/font/bootstrap-icons.css" rel="stylesheet">
<link href="/vendors/glightbox/glightbox.min.css" rel="stylesheet">
<link href="/material/css/prium.css" rel="stylesheet" id="style-default">
<link href="/material/css/Chart.min.css" rel="stylesheet" />
<link href="/material/css/teal.css" rel="stylesheet" />
<link href="/material/css/argon.css" rel="stylesheet" />

<link href="/vendors/overlayscrollbars/OverlayScrollbars.min.css" rel="stylesheet" />

<script src='https://api.mapbox.com/mapbox-gl-js/v2.10.0/mapbox-gl.js'></script>
<link href='https://api.mapbox.com/mapbox-gl-js/v2.10.0/mapbox-gl.css' rel='stylesheet' />

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-2932788305129377" crossorigin="anonymous"></script>


<script> 
        var CONFIG = {  isNavbarVerticalCollapsed: false,   theme: 'dark',   isRTL: false,   isFluid: false,   navbarStyle: 'transparent',   navbarPosition: 'vertical'   };
        Object.keys(CONFIG).forEach(function (key) {    if (localStorage.getItem(key) === null) {        localStorage.setItem(key, CONFIG[key]);     }  });
        if (JSON.parse(localStorage.getItem('isNavbarVerticalCollapsed'))) { document.documentElement.classList.add('navbar-vertical-collapsed'); }
        if (localStorage.getItem('theme') === 'dark') {  document.documentElement.classList.add('dark'); }
</script>
  </head>

  <body>
    <main class="main" id="top">
      <div class="container" data-layout="container">
        <div class="content">
          <script src="https://kit.fontawesome.com/870b9241ea.js" crossorigin="anonymous"></script>

<nav class="navbar navbar-light navbar-glass navbar-top navbar-expand">
  <!-- toggle button -->
  <button class="btn navbar-toggler-humburger-icon navbar-toggler me-1 me-sm-3" type="button" data-bs-toggle="collapse" data-bs-target="#navbarVerticalCollapse" aria-controls="navbarVerticalCollapse" aria-expanded="false" aria-label="Toggle Navigation">
      <span class="navbar-toggle-icon">
        <span class="toggle-line"></span>
      </span>
  </button>

  <!-- searchbox-->
  <ul class="navbar-nav align-items-center d-md-block">
    <li class="nav-item">
      <div class="search-box"  style="width: 180px;">
        <form class="position-relative" data-bs-toggle="search" data-bs-display="static">
          <input id="search" class="form-control search-input fuzzy-search"  type="search" placeholder="Search..." aria-label="Search" />
          <span class="bi bi-search search-box-icon"></span>
        </form>
        <div class="btn-close-falcon-container position-absolute end-0 top-50 translate-middle shadow-none" data-bs-dismiss="search">
          <div class="btn-close-falcon" aria-label="Close"></div>
        </div>
        <!-- menu contextuel de recherche-->
        <div class="dropdown-menu border font-base start-0 mt-2 py-0 overflow-hidden" style="width: 260px;">
          <div class="scrollbar list py-3" style="max-height: 24rem;">
              <!-- search for people-->
              <h6 class="dropdown-header fw-medium text-uppercase px-card fs--2 pt-0 pb-2">Results</h6>
              <!-- display profile from search result -->
              <div id="members"></div>                      
          </div>
          <div class="text-center mt-n3">
            <p class="fallback fw-bold fs-1 d-none" id="noResult">No Result Found.</p>
          </div>
        </div>
      </div>
    </li>
  </ul>

  <!-- area icons -->
  <ul class="navbar-nav navbar-nav-icons ms-auto flex-row align-items-center">
    <!-- bluetooth icon only for gamespace-->
    <li class="nav-item connect" style="margin-right: 10px; display: none;">
      <a class="nav-link pe-0 ps-2" role="button" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          <i class="bi bi-bluetooth text-danger" id="bt_icon" style="font-size: 2em;"></i>
      </a>
    </li>
    <!-- message -->
    <li class="nav-item dropdown " style="margin-right: 10px;">
      <!-- icon notification change status color and update seen for notification on click -->
      <a class="nav-link px-0" id="navbarDropdownMessenger" role="button" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false" data-hide-on-body-scroll="data-hide-on-body-scroll">
        <span class="bi bi-chat-fill" style="font-size: 1.8em;"></span>
      </a>
      <!-- container de message -->
      <div class="dropdown-menu dropdown-caret dropdown-caret dropdown-menu-end dropdown-menu-card dropdown-menu-notification dropdown-caret-bg" aria-labelledby="navbarDropdownMessenger">
        <div class="card card-notification shadow-none">
          <!-- messenger header -->
          <div class="card-header">
            <div class="row justify-content-between align-items-center">
              <div class="">
                <h6 class="card-header-title mb-0 row justify-content-around">
                  <div class="col"> Messenger </div>
                </h6>
              </div>
            </div>
          </div>
          <div class="scrollbar-overlay" style="max-height:19rem">
            <div class="list-group list-group-flush fw-normal fs--1">
              <!-- about online-->
              <div id="available_user">
                <div class="list-group-title border-bottom">Online</div>
                <div id="display_available_user">

                </div>
              </div>
            </div>
          </div>
          <!-- messenger footer-->
          <div class="row">
              <!-- sharing space-->
              <div class="card-footer text-center border-top">
                <a class="card-link d-block" id="viewAllUser">Messenger</a>
              </div>
          </div>
        </div>
      </div>
    </li>
    <!-- notification -->
    <li class="nav-item dropdown">
      <!-- icon notification change status color and update seen for notification on click -->
      <a class="nav-link px-0" id="navbarDropdownNotification" role="button" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false" data-hide-on-body-scroll="data-hide-on-body-scroll">
          <i class="bi bi-bell" style="font-size: 1.8em;"></i>
      </a>
      <div class="dropdown-menu dropdown-caret dropdown-caret dropdown-menu-end dropdown-menu-card dropdown-menu-notification dropdown-caret-bg" aria-labelledby="navbarDropdownNotification">
        <div class="card card-notification shadow-none">
          <!-- title -->
          <div class="card-header">
            <div class="row justify-content-between align-items-center">
              <div class="">
                <h6 class="card-header-title mb-0 row justify-content-around">
                  <div class="col">
                    Notifications 
                  </div> 
                  <div class="col">
                  <div class="d-flex justify-content-end">
                    <button class="btn btn-sm btn-dark">
                      <i class="bi bi-person-plus-fill"></i>
                    </button>
                  </div>
                  </div>
                </h6>
              </div>
              <!--<div class="col-auto ps-0 ps-sm-3"><a class="card-link fw-normal" href="#">Mark all as read</a></div>-->
            </div>
          </div>
          <div class="scrollbar-overlay" style="max-height:19rem">
            <div class="list-group list-group-flush fw-normal fs--1">
              <!-- about follow-->
              <div id="follow_notification">
                <div class="list-group-title border-bottom">New relation</div>
                <div id="display_follow_notification">

                </div>
              </div>
              <!-- about interaction-->
              <div id="interaction_notification">
                <div class="list-group-title border-bottom">New interaction</div>
                <div id="display_interaction_notification">

                </div>
              </div>
            </div>
          </div>
          <!-- notification footer-->
          <div class="row">
            <div class="col">
              <div class="card-footer text-center border-top">
                <a class="card-link d-block" id="viewAllNotification">View all</a>
              </div>
            </div>
            <div class="col">
              <div class="card-footer text-center border-top">
                <a class="card-link text-secondary d-block" id="clearAllNotification">Clear all</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </li>
    <!-- avatar-->
    <li class="nav-item dropdown">
      <a class="nav-link pe-0 ps-2" id="navbarDropdownUser" role="button" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <div class="avatar avatar-xl">
          <img class="rounded-circle" id="picture_avatar" src="/material/img/global/default.png" alt="" />
        </div>
      </a>
      <div class="dropdown-menu dropdown-caret dropdown-caret dropdown-menu-end py-0" aria-labelledby="navbarDropdownUser" id="userMenu">
        <div class="bg-white dark__bg-1000 rounded-2 py-2">
          <!-- workout space -->
          <a class="dropdown-item fw-bold text-warning" href="/"><i class="bi bi-play-circle"></i><span> Playground</span></a>
          <!-- profile page -->
          <a class="dropdown-item fw-bold text-primary" href="/profile"><span class="bi bi-person me-1"></span><span>Profile</span></a>

          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#!">Set status</a>
          <a class="dropdown-item" href="#!">Feedback</a>
          <!-- switch light / dark -->
          <a class="dropdown-item" href="#!" id="colorMode">
            <div class="form-check form-switch" >
              <input class="form-check-input " id="switchDarkModeExample" type="checkbox" data-theme-control="theme" />
              <label for="switchDarkModeExample">Dark Mode</label>
            </div>
          </a>
          <div class="dropdown-divider" style="margin: 0;"></div>
          <!-- profile edition-->
          <a class="dropdown-item" href="/profile/settings">Settings</a>
          <a class="dropdown-item" href="/account/logout">Logout</a>
        </div>
      </div>
    </li>
  </ul>
</nav>
<script>
  var navbarPosition = localStorage.getItem('navbarPosition');
  var navbarVertical = document.querySelector('.navbar-vertical');
  var navbarTopVertical = document.querySelector('.content .navbar-top');
  var navbarTop = document.querySelector('[data-layout] .navbar-top');
  var navbarTopCombo = document.querySelector('.content [data-navbar-top="combo"]');
  if (navbarPosition === 'top') {
    navbarTop.removeAttribute('style');
    navbarTopVertical.remove(navbarTopVertical);
    navbarVertical.remove(navbarVertical);
    navbarTopCombo.remove(navbarTopCombo);
  } else if (navbarPosition === 'combo') {
    navbarVertical.removeAttribute('style');
    navbarTopCombo.removeAttribute('style');
    navbarTop.remove(navbarTop);
    navbarTopVertical.remove(navbarTopVertical);
  } else {
    navbarVertical.removeAttribute('style');
    navbarTopVertical.removeAttribute('style');
    navbarTop.remove(navbarTop);
    navbarTopCombo.remove(navbarTopCombo);
  }
</script>

<script>
  //service de geolocalisation 
  position = {
        longitude : null,
        latitude : null,
        timestamp : null,
        speed : null,
        heading: null,
        city: null
  }

  document.addEventListener('DOMContentLoaded', function(){
    //affichage personnalisé pour gamespace (icon bluetooth)
    if (window.location.pathname.split('/')[1] == 'playground') {
      $(".connect").show()
    }
    //recherche utilisateur
    $('#search').on('keyup', function () {
        let data = $('#search').val()
        $('#members').text("")
        //document.getElementById('members').innerText = ""
        let formdata = new FormData()
        if(data.length){
            formdata.append('data', JSON.stringify(data))
            let uri = '/search/user'
            let option = {
                method: 'POST',
                mode: 'cors',
                body: formdata
            }
            let request = new Request(uri, option)
            fetch(request)
            .then(response => response.text())
            .then((response)=>{
                //console.log(response)
                //console.log(response.length)
                
                if (response == 'noResult') {
                  //no result found
                  //document.getElementById('members').innerText = ""
                // _list = []
                } else {
                  response = JSON.parse(response)
                  //console.log("from server " ,response)
                  for (let i = 0; i < response.length; i++) {
                    const element = response[i];
                    if (element.username != null) {
                      if (element.username != self.username) {
                          //display member found
                          let _status
                          if (element.status == "1") {
                            _status = 'online'
                          } else if (element.status == "unauthorized") {
                            _status = "unauthorized"
                          } else if(element.status == "0"){
                            _status = 'offline'
                          }
                          let _user = 
                          '<a class="dropdown-item px-card py-2" href="/world/profile/'+element.username+'">'+
                            '<div class="d-flex align-items-center">'+
                              '<div class="avatar avatar-l status-'+_status+' me-2">'+
                                // picture of user -->
                                '<img class="rounded-circle" src="/material/img/global/'+element.picture+'" alt="" />'+
                              '</div>'+
                              // information de l'utilisateur -->
                              '<div class="flex-1">'+
                                '<h6 class="mb-0 title"><span>'+element.firstname+'</span>&nbsp;<span>'+element.lastname+'</span></h6>'+
                                '<p class="fs--2 mb-0 d-flex">'+element.username+'</p>'+
                              '</div>'+
                            '</div>'+
                          '</a>'+
                          '<hr class="text-200 dark__text-900" />'
                          $('#members').append(_user)
                      }
                    } 
                  }
                }
            })
            .catch((err) => {
                console.log('error', err)
            })
        } else{
            $('#displayResult').css('display','none')
            $('#nameFound').text('')
            $('#hrefFound').removeAttr('href', '')
        }
    })
   
    //view or clear notification
    $('#viewAllNotification, #clearAllNotification').hover(function(){
      $(this).css("cursor","pointer")
    })
    .click(function(){
      let el = this.id
      if (el == 'viewAllNotification') {
        console.log('action for viewing')
      }else if (el == 'clearAllNotification'){
        console.log('action to clear notification')
        clearNotifications()
        .then((response)=>{
          if (response == 'done') {
            $('#display_follow_notification').html('<p class="text-center p-4">Aucune liaison</p>')
            $('#display_interaction_notification').html('<p class="text-center p-4">Aucune interaction</p>')
          }
        })
      }
    })
     
    //audio 
    audio_in_message = new Audio('/material/audio/social/in_message.mp3');

    //récupération des données générale de mon profile au chargement de la page
    let formdataid = new FormData()
    formdataid.append('id', self.id)
    let query = new Request('/profile/', {
      method: 'POST',
      mode : 'cors',
      body: formdataid
    })
    fetch(query)
    .then(response => response.text())
    //récupère les données du profile 
    .then(response => {
      response = JSON.parse(response)
      self.follower = response.follower
      self.following = response.following
      self.notification = response.notification
      self.race = response.race
    })
    //follower, following, mutual dispatch
    .then(()=>{
      self.follower ? $('#selfnumberfollower').text(self.follower.length) : $('#selfnumberfollower').text(0)
      self.following ? $('#selfnumberfollowing').text(self.following.length) : $('#selfnumberfollowing').text(0)
      $('#myworkout').text(self.race.length)

      self.followerid = []
      self.followingid = []
      self.mutual = []

      self.follower.forEach(follower =>{
        self.followerid.push(follower.id)
      })

      self.following.forEach(following =>{
        self.followingid.push(following.id)
      })

      let ref = self.followerid.length < self.followingid.length ? 'follower' : 'following'

      if (ref == 'follower') {
        for (let i = 0; i < self.followerid.length; i++) {
         for (let j = 0; j < self.followingid.length; j++) {
          if(self.followerid[i] == self.followingid[j]){
            self.mutual.push(self.followerid[i])
          }
         }
        }

        self.follower.forEach(follower =>{
          self.mutual.forEach(mutual =>{
            if (follower.id == mutual ) {
              let pos = self.mutual.indexOf(mutual)
              self.mutual.splice(pos, 1)
              self.mutual.push(follower)
            }
          })
        })

      } else if(ref == 'following') {
        for (let i = 0; i < self.following.length; i++) {
          for (let j = 0; j < self.follower.length; j++) {
            if (self.followingid[i] == self.followerid[j]) {
              self.mutual.push(self.followingid[i])
            }
          }
        }

        self.following.forEach(following =>{
          self.mutual.forEach(mutual =>{
            if (following.id == mutual ) {
              let pos = self.mutual.indexOf(mutual)
              self.mutual.splice(pos, 1)
              self.mutual.push(following)
            }
          })
        })
      }

      delete self.followerid
      delete self.followingid

    })
    //affectation des notifications
    .then(()=>{
      //si il y a des notifications
      if (self.notification) {
        //information about notification 
        let awaiting_notification = false
        let display_notification = false 
        let notificationBtn = $('#navbarDropdownNotification')
        
        //traitement de chaque notification
        self.notification.forEach(element => {
          //si element non cliqué
          if (element.clicked == 0) {
            display_notification = true
          }
          //indicate notifications pointer
          if(element.seen == 0) {
            awaiting_notification = true
            notificationBtn.addClass('notification-indicator notification-indicator-danger')
          }

          //notification about follow
          if (element.about == 'friendship') {
              //if notification type is just show
              if (element.type == "show") {
                if (element.clicked == false ) {
                    //if notification is younger than 7 days display on dropdown
                    if (Math.ceil(Date.now()/1000) - element.created_at < 604800) {
                      let read_notification
                      (element.seen == 0) ? read_notification = "notification-unread" : read_notification = ""
                      
                      let notif = '<div class="list-group-item" id="'+element.id+'" >'+
                                    '<a class="notification notification-flush '+read_notification+'" >'+
                                        '<div class="notification-avatar">'+
                                          '<div class="avatar avatar-l me-3">'+
                                            '<img class="rounded-circle" src="/material/img/global/default.png" alt="" />'+
                                          '</div>'+
                                        '</div>'+
                                        '<div class="notification-body d-flex align-items-center">'+
                                              '<strong>'+element.username+'</strong>'+
                                              '<span>&nbspvous suit&nbsp</span>'+
                                              '<span class="notification-time" style="margin-left:20px;">'+
                                                '<span class="me-2" role="img" aria-label="Emoji">&nbsp<i class="bi bi-clock"></i></span>'+
                                                '<span>'+getDateDelay(element.created_at)+'</span>'+
                                              '</span>'+
                                        '</div>'+
                                    '</a>'+
                                  '</div>'
                      //display the notification          
                      $('#display_follow_notification').append(notif)
                      //set clicked to notification if clicked 
                      $('#'+element.id).click(function(){
                          setNotificationClicked(element.id)
                          .then((response)=>{
                            if (response == 'done') {
                              //$('#'+element.id).remove()
                              window.location.href = '/world/profile/'+element.username
                            } else { console.log(response)}
                          })
                      })
                    } 
                    //if notification is younger than 6 month display on notification history
                    else if (Math.ceil(Date.now()/1000) - element.created_at < 15724800){
                    } 
                    //if notification is older than 6 month remove it
                    else {
                      removeNotification(element.id)
                      .then((_)=> {
                        $('#'+element.id).remove()
                      })
                    }
                } //if notification is clicked load it on notification history
                else if (element.clicked == true){
                  //if notification is younger than 6 month display on notification page 

                } 
              }

              //si la notification est de type request, she will not be remove til clicked
              if (element.type == "request") {
                if (element.clicked == false) {
                  //if notification is younger than 7 days display on dropdown
                  if (Math.ceil(Date.now()/1000) - element.created_at < 604800) {
                      let read_notification
                      (element.seen == 0) ? read_notification = "notification-unread" : read_notification = ""
                      
                      let notif = '<div class="list-group-item" id="'+element.id+'" >'+
                                    '<a class="notification notification-flush '+read_notification+'" >'+
                                        '<div class="notification-avatar">'+
                                          '<div class="avatar avatar-l me-3">'+
                                            '<img class="rounded-circle" src="/material/img/global/default.png" alt="" />'+
                                          '</div>'+
                                        '</div>'+
                                        '<div class="notification-body d-flex align-items-center">'+
                                              '<strong>'+element.username+'</strong>'+
                                              '<span class="notification-time" style="margin-left:20px;">'+
                                                '<span class="me-2" role="img" aria-label="Emoji">&nbsp<i class="bi bi-clock"></i></span>'+
                                                '<span>'+getDateDelay(element.created_at)+'</span>'+
                                              '</span>'+
                                              '<button style="margin-left:10px;" id="'+element.id+'-accept" class="btn btn-success btn-sm"><i class="bi bi-check"></i></button>'+
                                              '<button style="margin-left:10px;" id="'+element.id+'-reject" class="btn btn-danger btn-sm"><i class="bi bi-x"></i></button>'+
                                        '</div>'+
                                    '</a>'+
                                  '</div>'
                      //display the notification          
                      $('#display_follow_notification').append(notif)
                      //set clicked to notification if clicked 
                      $('#'+element.id+'-accept, #'+element.id+"-reject").click(function(){
                          setNotificationRequest(element.id,this.id, element.notifier)
                          .then((response)=>{
                            $('#'+element.id).remove()
                          })
                      })
                    } 
                  //if notification is younger than 6 month display on notification history
                  else if (Math.ceil(Date.now()/1000) - element.created_at < 15724800){
                  } 
                }
                else if (element.clicked == true) {
                  //display on notification history
                }
              }
              
              //si la notification est de type acceptation
              if (element.type == 'accepted') {
                if (element.clicked == false ) {
                    //if notification is younger than 7 days display on dropdown
                    if (Math.ceil(Date.now()/1000) - element.created_at < 604800) {
                      let read_notification
                      (element.seen == 0) ? read_notification = "notification-unread" : read_notification = ""
                      
                      let notif = '<div class="list-group-item" id="'+element.id+'" >'+
                                    '<a class="notification notification-flush '+read_notification+'" >'+
                                        '<div class="notification-avatar">'+
                                          '<div class="avatar avatar-l me-3">'+
                                            '<img class="rounded-circle" src="/material/img/global/default.png" alt="" />'+
                                          '</div>'+
                                        '</div>'+
                                        '<div class="notification-body d-flex align-items-center">'+
                                              '<strong>'+element.username+'</strong>'+
                                              '<span>&nbspaccepted&nbsp</span>'+
                                              '<span class="notification-time" style="margin-left:20px;">'+
                                                '<span class="me-2" role="img" aria-label="Emoji">&nbsp<i class="bi bi-clock"></i></span>'+
                                                '<span>'+getDateDelay(element.created_at)+'</span>'+
                                              '</span>'+
                                        '</div>'+
                                    '</a>'+
                                  '</div>'
                      //display the notification          
                      $('#display_follow_notification').append(notif)
                      //set clicked to notification if clicked 
                      $('#'+element.id).click(function(){
                          setNotificationClicked(element.id)
                          .then((response)=>{
                            if (response == 'done') {
                              //$('#'+element.id).remove()
                              window.location.href = '/world/profile/'+element.username
                            } else { console.log(response)}
                          })
                      })
                    } 
                    //if notification is younger than 6 month display on notification history
                    else if (Math.ceil(Date.now()/1000) - element.created_at < 15724800){
                    } 
                    //if notification is older than 6 month remove it
                    else {
                      removeNotification(element.id)
                      .then((_)=> {
                        $('#'+element.id).remove()
                      })
                    }
                } //if notification is clicked load it on notification history
                else if (element.clicked == true){
                  //if notification is younger than 6 month display on notification page 

                } 
              }
          }
        });
        
        //si des notifications n'ont pas été vu
        if (awaiting_notification) {
          notificationBtn.click(function(){
            //set notification seen to true where notified is me 
            setNotificationSeen()
            .then((response)=>{
              notificationBtn.removeClass('notification-indicator notification-indicator-danger') 
              awaiting_notification_nb = 0
            })
          })
        } 

        if (display_notification == false) {
          $('#display_follow_notification').html('<p class="text-center p-4">Aucune liaison</p>')
          $('#display_interaction_notification').html('<p class="text-center p-4">Aucune interaction</p>')
        }
      } 
      //si il n'y a aucune notifiation
      else if (!self.notification){
          $('#display_follow_notification').html('<p class="text-center p-4">Aucune liaison</p>')
          $('#display_interaction_notification').html('<p class="text-center p-4">Aucune interaction</p>')
      }
    })
    //messenger
    .then(()=>{
      //suivi des utilisateurs connectés
      connectedUser = []
      //suivi des fenetres de conversation crée
      offcanvasCreated = []
      //suivi des fenêtres de conversation ouverte
      offcanvasOpen = null
      //suivi des notifications de message 
      dropdownMessengerNotification = 0
      //?????
      messengerNotification = []
      //affichage des relation mutuel en ligne
      self.mutual.forEach(element => {
        //si la relation est connecté
        if (element.connected.status == 1) {
          //creation de la ligne utilisateur connecté
          let onlineUser = 
          '<div class="list-group-item" id="show-'+element.id+'">'+
            '<a class="notification notification-flush">'+
                '<div class="notification-avatar">'+
                  '<div class="avatar avatar-s me-3 status-online">'+
                    '<img class="rounded-circle" src="/material/img/global/default.png" alt="" />'+
                  '</div>'+
                '</div>'+
                '<div class="notification-body d-flex align-items-center" id="showContent-'+element.id+'"">'+
                      '<strong>'+element.username+'</strong>&nbsp'+
                      '<!--<span class="text-secondary">('+element.firstname+' </span>&nbsp-->'+
                      '<!--<span class="text-secondary">'+element.lastname+')</span>-->'+
                '</div>'+
            '</a>'+
          '</div>'

          //integration de la ligne utilisateur au dropdown
          $('#display_available_user').append(onlineUser)

          //ajout de l'utilisateur connecter à la liste des utilisateurs connecté
          connectedUser.push(element.id)
          
          //sur clique de la ligne utilisateur
          $('#show-'+element.id).click(function(){
            //----------------------------------- creation d'un environnement de communication------------------------------------------------------ sur un utilisateur deja présent
            if (offcanvasCreated.indexOf(element.id) == -1) {
                    var response;
                    $.ajax({ type: "GET",   
                        url: "/templates/partial/navbar/messageBodyOffcanvas.ejs",   
                        async: false,
                        success : function(text)
                        {   
                            //personnalisation du template
                            text = text.replace('messageCanvas', 'message-'+element.id)
                            text = text.replace('offcanvasClose', 'offcanvasClose-'+element.id)
                            text = text.replace('appendNewMessage', 'appendNewMessage-'+element.id)
                            text = text.replace('imageLink', '/material/img/global/'+element.picture)
                            text = text.replace('profileLink', '/world/profile/'+element.username)
                            text = text.replaceAll('firstname-lastname', element.firstname+' '+element.lastname)
                            text = text.replace('text-message', 'text-message-'+element.id)
                            text = text.replace('sendMessage', 'send-to-'+element.id)
                            text = text.replace('formMessage', 'form-to-'+element.id)
                            response= text;
                        }
                    });

                    //integration de la fenetre au document 
                    $('body').append(response);

                    //envoi du message avec la touche entrée
                    $("#text-message-"+element.id).keyup(function(event) {
                      event.preventDefault()
                        if (event.keyCode === 13) {
                            $('#send-to-'+element.id).click();
                        }
                    });

                    //envoi d'un message à un destinataire
                    $('#form-to-'+element.id).submit(function(e){
                      e.preventDefault()
                      console.log('message sent')
                      let messageContent = $('#text-message-'+element.id).text()
                      let user = element.id
                      let message = {
                        content : messageContent,
                        user : user,
                        socket : element.connected.id,
                        timestamp : Math.ceil(Date.now()/1000)
                      }

                      //emission du message vers le serveur pour le destinataire
                      socket.emit('message', message, (response)=>{
                        //retour du serveur sur le status de connexion de l'utilisateur 
                        $('#text-message-'+element.id).text('')
                        if (response.status == 0) {
                          //l'utilisateur est indisponible
                        } else if (response.status == 1){
                          //l'utilisateur est disponible -> forte probabilité de livraison du message -> on affiche 
                          let selfMessage = 
                          `
                          <div class="d-flex p-3">
                            <div class="flex-1 d-flex justify-content-end">
                              <div class="w-100 w-xxl-75">
                                <div class="hover-actions-trigger d-flex flex-end-center">
                                  <ul class="hover-actions position-relative list-inline mb-0 text-400 me-2">
                                    <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Forward"><span class="fas fa-share"></span></a></li>
                                    <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Archive"><span class="fas fa-archive"></span></a></li>
                                    <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Edit"><span class="fas fa-edit"></span></a></li>
                                    <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Remove"><span class="fas fa-trash-alt"></span></a></li>
                                  </ul>
                                  <div class="bg-primary text-white p-2 rounded-2 chat-message light">
                                    ${message.content}  
                                  </div>
                                </div>
                                <div class="text-400 fs--2 text-end">${moment.unix(message.timestamp).format('h:mm')}<!--<span class="fas fa-check ms-2 text-success"></span>--></div>
                              </div>
                            </div>
                          </div>
                          `
                          $('#appendNewMessage-'+response.user).append(selfMessage)
                          var messageBody = document.querySelector('#appendNewMessage-'+response.user);
                          messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;
                        }
                      })
                    })

                    //ajout de la fenetre crée
                    offcanvasCreated.push(element.id) 

                    //ouverture de la fenetre
                    $('#message-'+element.id).offcanvas('show')
                    offcanvasOpen = element.id

                    //fermeture de la fenetre de communication
                    $('#offcanvasClose-'+element.id).click(function(){
                      //aucune fenetre de communication ouverte
                      offcanvasOpen = null
                    })

                    console.log('creation discussion sur utilisateur deja present')
            } 
            
            //si une fenetre de communication existe pour l'utilisateur
            else if(offcanvasCreated.indexOf(element.id) != -1) {
              //ouverture de la fenetre
              $('#message-'+element.id).offcanvas('show')
              offcanvasOpen = element.id
              //listener sur fermeture de la fenetre
              $('#offcanvasClose-'+element.id).click(function(){
                offcanvasOpen = null
              })
              //si une notification de message existe
              if (messengerNotification.indexOf(element.id) != -1) {
                //suppression de la notification sur la ligne utilisateur active
                $('#showContent-'+element.id).removeClass('bg-primary')
                //récupérationd de la position de la notification dans le tableau de notification 
                let ind = messengerNotification.indexOf(element.id)
                //suppression de la notification dans le tableau de notification 
                messengerNotification.splice(ind,1)
                //suppression du contenu dans la notification 
                $('#showContent-'+element.id).children().last().remove()
                //suppression du backround color de la notification
                $('#show-'+element.id).removeClass('bg-primary')
              }
              //affichage du dernier message
              var messageBody = document.querySelector('#appendNewMessage-'+element.id);
              messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;

              console.log('ouverture discussion sur utilisateur deja present')
            }

            //si une notification de message existe pour l'utilisateur
            //if (messengerNotification.indexOf(element.id) != -1) {
              //suppression de la notification sur la ligne utilisateur active
             // $('#showContent-'+element.id).removeClass('bg-primary')
             // let ind = messengerNotification.indexOf(element.id)
             // messengerNotification.splice(ind,1)
             // $("#messageNotification-"+element.id).remove()
             // $('#show-'+element.id).removeClass('bg-primary')
           // }
          })
        }
      });

       //dropdown message
      $('#navbarDropdownMessenger').click(function(){
        if (dropdownMessengerNotification == 1) {
          $('#navbarDropdownMessenger').removeClass("notification-indicator notification-indicator-primary")
          dropdownMessengerNotification = 0
        }
      })
    }) 
    //run 
    .then(()=>{
      //about workout
      let dist = 0
      let spe = 0
      let tim = 0

      if (self.race.length) {
        //data race parsing
        for (let i = 0; i < self.race.length; i++) {
          const race = self.race[i];

          self.race[i].race = JSON.parse(race.race)

          self.race[i].start = JSON.parse(race.start)
          self.race[i].stop = JSON.parse(race.stop)

          self.race[i].distance = JSON.parse(race.distance)
          let distance = self.race[i].distance

          self.race[i].speed = JSON.parse(race.speed)
          let speed = self.race[i].speed

          self.race[i].time = JSON.parse(race.time)
          let time = self.race[i].time

          for (let j = 0; j < distance.length; j++) {
            dist += distance[j];
            spe += speed[j]
            tim += time[j]
          }

          dist = dist/distance.length
          spe = spe/speed.length
          tim = tim/time.length

          //format du temps de course total
          let duration = moment.duration(tim, 'seconds');
          let formatted = duration.format("hh:mm:ss");
          tim = formatted

          if (tim.length == 2) { tim = tim+'s'}else if(tim.length == 5){ tim = tim+' min' }else { tim = tim+'h'  }

          let status = distance.length > 1 ? "Updated" : "Created"

          //data layout
          let performance = ` 
          <a class="border-bottom-0 notification rounded-0 border-x-0 border border-300" href="#!">
            <div class="notification-avatar">
              <div class="avatar avatar-xl me-3">
                <div class="avatar-emoji rounded-circle ">
                  <span role="img" aria-label="Emoji"><i class="fa-solid fa-person-running"></i></span>
                </div>
              </div>
            </div>
            <div class="notification-body">
              <p class="mb-1"><i class="bi bi-geo-alt-fill"></i>&nbsp;<strong>${race.city}</strong></p>
              <p class="mb-1">
                ${dist.toFixed(1)} km at <strong>${spe.toFixed(1)} km/h </strong>in ${tim} 
              </p>
              <div class="row">
                <div class="col">
                  <div class="row justify-content-around">
                    <span class="notification-time">Repetition : ${distance.length}</span>
                    <span class="notification-time">${status+" : "+getDateDelay(self.race[i].timestamp)} ago</span>
                  </div>
                </div>
                <div class="col">
                  <button class="btn btn-primary" id="race_${i}"><i class="bi bi-pie-chart-fill"></i></button>
                </div>
              </div>
            </div>
          </a>`
          $('#myperformance').append(performance)

          $('#race_'+i).click(function(){
            window.location.href = '/run/race?id='+i
          })

          dist = 0
          spe = 0
          tim = 0
        }
      } else {
       $('#mytitleperformance').text('Aucune performance')
       let startperformance = ` 
       <a class="border-bottom-0 notification rounded-0 border-x-0 border border-300" href="/run">
         <div class="notification-avatar">
           <div class="avatar avatar-xl me-3">
             <div class="avatar-emoji rounded-circle ">
               <span role="img" aria-label="Emoji"><i class="fa-solid fa-road"></i></span>
             </div>
           </div>
         </div>
         <div class="notification-body">
           <p class="mb-1">
            <button class="btn btn-primary">Start run</button>
           </p>
         </div>
       </a>`
       let noperformance = ` 
       <a class="border-bottom-0 notification rounded-0 border-x-0 border border-300" href="#!">
         <div class="notification-avatar">
           <div class="avatar avatar-xl me-3">
             <div class="avatar-emoji rounded-circle ">
               <span role="img" aria-label="Emoji"><i class="fa-solid fa-road"></i></span>
             </div>
           </div>
         </div>
         <div class="notification-body">
           <p class="mb-1">
             <strong>You</strong> have <strong>0</strong> 
             performance
           </p>
           <span class="notification-time">${moment().format("MMM Do YY")}</span>
         </div>
       </a>`
       $('#myperformance').append(startperformance)
      }
    })
    
    //reception d'un message
    socket.on("message", (message) =>{
      console.log('message recu')

      //notification audio
      if (offcanvasOpen != message.from.userid) {
        audio_in_message.play()
      }
      
      //renvoi une confirmation de reception
      socket.emit('received', message )
      
      //récupération de la relation à l'origine du message 
      self.mutual.forEach(element => {
          //la relation correspond à l'emetteur
          if (element.id == message.from.userid) {
               //--------------------------------------------------------------------------------------------------------- creation d'un environnement de communication------------------a reception d'un message
              if (offcanvasCreated.indexOf(message.from.userid) == -1) {
                console.log('creation de la discussion depuis reception du message : ', message.from.userid)
                var response;
                $.ajax({ type: "GET",   
                    url: "/templates/partial/navbar/messageBodyOffcanvas.ejs",   
                    async: false,
                    success : function(text)
                    {   
                        //personnalisation du template
                        text = text.replace('messageCanvas', 'message-'+element.id)
                        text = text.replace('offcanvasClose', 'offcanvasClose-'+element.id)
                        text = text.replace('appendNewMessage', 'appendNewMessage-'+element.id)
                        text = text.replace('imageLink', '/material/img/global/'+element.picture)
                        text = text.replace('profileLink', '/world/profile/'+element.username)
                        text = text.replaceAll('firstname-lastname', element.firstname+' '+element.lastname)
                        text = text.replace('text-message', 'text-message-'+element.id)
                        text = text.replace('sendMessage', 'send-to-'+element.id)
                        text = text.replace('formMessage', 'form-to-'+element.id)
                        response = text;
                    }  
                })
                
                //integration de la fenetre au document 
                $('body').append(response);

                //integration du message tiers a la fentre
                let userMessage = `
                <!-- user message -->
                <div class="d-flex p-3">
                  <!-- avatar-->
                  <div class="avatar avatar-l me-2">
                    <img class="rounded-circle" src="/material/img/global/${element.picture}" alt="" />
                  </div>
                  <div class="flex-1">
                    <div class="w-xxl-75">
                      <div class="hover-actions-trigger d-flex align-items-center">
                        <!-- message -->
                        <div class="chat-message bg-200 p-2 rounded-2">
                            ${message.from.message}
                        </div>
                        <!-- option pour le message -->
                        <ul class="hover-actions position-relative list-inline mb-0 text-400 ms-2">
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Forward"><span class="fas fa-share"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Archive"><span class="fas fa-archive"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Edit"><span class="fas fa-edit"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Remove"><span class="fas fa-trash-alt"></span></a></li>
                        </ul>
                      </div>
                      <!-- l'heure du message -->
                      <div class="text-400 fs--2"><span>${moment.unix(message.from.timestamp).format('h:mm')}</span></div>
                    </div>
                  </div>
                </div>
                `
                $('#appendNewMessage-'+element.id).append(userMessage)

                //option touche entrée
                $("#text-message-"+element.id).keyup(function(event) {
                  event.preventDefault()
                    if (event.keyCode === 13) {
                        $('#send-to-'+element.id).click();
                    }
                });

                //envoi d'un message à un destinataire
                $('#form-to-'+element.id).submit(function(e){
                  e.preventDefault()
                  console.log('message sent')
                  let messageContent = $('#text-message-'+element.id).text()
                  let user = element.id
                  let message = {
                    content : messageContent,
                    user : user,
                    socket : element.connected.id,
                    timestamp : Math.ceil(Date.now()/1000)
                  }
                  //emission du message vers le serveur pour le destinataire
                  socket.emit('message', message, (response)=>{
                    //retour du serveur sur le status de connexion de l'utilisateur 
                    $('#text-message-'+element.id).text('')
                    if (response.status == 0) {
                      //l'utilisateur est indisponible
                    } else if (response.status == 1){
                      //l'utilisateur est disponible -> forte probabilité de livraison du message -> on affiche 
                      let selfMessage = 
                      `
                      <div class="d-flex p-3">
                          <div class="flex-1 d-flex justify-content-end">
                            <div class="w-100 w-xxl-75">
                              <div class="hover-actions-trigger d-flex flex-end-center">
                                <ul class="hover-actions position-relative list-inline mb-0 text-400 me-2">
                                  <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Forward"><span class="fas fa-share"></span></a></li>
                                  <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Archive"><span class="fas fa-archive"></span></a></li>
                                  <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Edit"><span class="fas fa-edit"></span></a></li>
                                  <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Remove"><span class="fas fa-trash-alt"></span></a></li>
                                </ul>
                                <div class="bg-primary text-white p-2 rounded-2 chat-message light">
                                  ${message.content}  
                                </div>
                              </div>
                              <div class="text-400 fs--2 text-end">${moment.unix(message.timestamp).format('h:mm')}<!--<span class="fas fa-check ms-2 text-success"></span>--></div>
                            </div>
                          </div>
                        </div>
                      `
                      $('#appendNewMessage-'+response.user).append(selfMessage)
                      var messageBody = document.querySelector('#appendNewMessage-'+response.user);
                      messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;
                    }
                  })
                })
              
                //affichage de la notification dans la ligne utilisateur 
                let firstChars = message.from.message.substr(0,7)
                if (firstChars.length > 7) {  firstChars+='...'}
                let userMessageNotification =  `<span class="text-secondary" id="messageNotification-${element.id}">${firstChars}</span>`
                $('#showContent-'+element.id).append(userMessageNotification)
                $('#show-'+element.id).addClass('bg-info')

                //affichage de la notification dans l'icone de messagerie
                $('#navbarDropdownMessenger').addClass("notification-indicator notification-indicator-danger")

                //suivi d'état des badge de notification 
                dropdownMessengerNotification = 1
                messengerNotification.push(element.id)

                //sur chaque click de la ligne user active
                $('#show-'+element.id).click(function(){
                  //si une notification de message existe pour l'utilisateur
                  if (messengerNotification.indexOf(element.id) != -1) {
                    //suppression de la notification sur la ligne utilisateur active
                    $('#showContent-'+element.id).removeClass('bg-info')
                    //retrait de la notification utilisateur
                    let ind = messengerNotification.indexOf(element.id)
                    messengerNotification.splice(ind,1)
                    //suppression des badges
                    $("#messageNotification-"+element.id).remove()
                    $('#show-'+element.id).removeClass('bg-info')
                  }
                })
                
                //ajout de la fenetre crée
                offcanvasCreated.push(message.from.userid)

                //ajout de la notification du message
                messengerNotification.push(element.id)

                 //fermeture de la fenetre de communication 
                 $('#offcanvasClose-'+element.id).click(function(){
                  //aucune fenetre ouverte
                  offcanvasOpen = null
                })
              }         
              
              //si la fenetre de communication offcanvas existe
              else if (offcanvasCreated.indexOf(message.from.userid) != -1) {
                
                //integration du mesage reçu
                let userMessage = `
                    <!-- user message -->
                    <div class="d-flex p-3">
                      <!-- avatar-->
                      <div class="avatar avatar-l me-2">
                        <img class="rounded-circle" src="/material/img/global/${element.picture}" alt="" />
                      </div>
                      <div class="flex-1">
                        <div class="w-xxl-75">
                          <div class="hover-actions-trigger d-flex align-items-center">
                            <!-- message -->
                            <div class="chat-message bg-200 p-2 rounded-2">
                                ${message.from.message}
                            </div>
                            <!-- option pour le message -->
                            <ul class="hover-actions position-relative list-inline mb-0 text-400 ms-2">
                              <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Forward"><span class="fas fa-share"></span></a></li>
                              <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Archive"><span class="fas fa-archive"></span></a></li>
                              <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Edit"><span class="fas fa-edit"></span></a></li>
                              <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Remove"><span class="fas fa-trash-alt"></span></a></li>
                            </ul>
                          </div>
                          <!-- l'heure du message -->
                          <div class="text-400 fs--2"><span>${moment.unix(message.from.timestamp).format('h:mm')}</span></div>
                        </div>
                      </div>
                    </div>
                    `
                $('#appendNewMessage-'+element.id).append(userMessage)     
                
                //si la fenetre est ouverte 
                if (offcanvasOpen == message.from.userid) {  
                  var messageBody = document.querySelector('#appendNewMessage-'+element.id);
                  messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;
                }
                
                //si la fenetre est fermé
                else {
                  //affichage de la notification dans la ligne utilisateur 
                  let firstChars = message.from.message.substr(0,7)
                  if (firstChars.length > 7) { firstChars+='...'  }
                  let userMessageNotification =  `<span class="text-secondary">${firstChars}</span>`
                  $('#showContent-'+element.id).append(userMessageNotification)
                  $('#show-'+element.id).addClass('bg-info')
                  //affichage de la notification dans l'icone de messagerie
                  $('#navbarDropdownMessenger').addClass("notification-indicator notification-indicator-danger")
                  //suivi d'état des badge de notification 
                  dropdownMessengerNotification = 1
                  messengerNotification.push(element.id)
                  //ajout de la notification du message
                  messengerNotification.push(element.id)
                }
              }
            }
        });
    })

    //connexion d'une relation  ->>>>>> ici aucune fenêtre ne doit être crée, la ligne utlisateur doit être proposé
    socket.on("online", (user)=>{
      console.log('connection : ', user)
      let element

      //on récupère son profile
      for (let i = 0; i < self.mutual.length; i++) {
        let u = self.mutual[i];
        if (u.id == user) {
          //affectation de l'utilisateur
          element = self.mutual[i];
          self.mutual[i].connected.status = 1
        }
      }

      //si l'utilisateur n'est pas présent dans la liste des utilisateurs connecté  //il ne doit pas l'être
      if (connectedUser.indexOf(user) == -1) {
        let onlineUser = 
        '<div class="list-group-item" id="show-'+element.id+'">'+
          '<a class="notification notification-flush">'+
              '<div class="notification-avatar">'+
                '<div class="avatar avatar-s me-3 status-online">'+
                  '<img class="rounded-circle" src="/material/img/global/default.png" alt="" />'+
                '</div>'+
              '</div>'+
              '<div class="notification-body d-flex align-items-center" id="showContent-'+element.id+'"">'+
                    '<strong>'+element.username+'</strong>&nbsp'+
                    '<!--<span class="text-secondary">('+element.firstname+' </span>&nbsp-->'+
                    '<!--<span class="text-secondary">'+element.lastname+')</span>-->'+
              '</div>'+
          '</a>'+
        '</div>'

        //integration de la ligne utilisateur au dropdown
        $('#display_available_user').append(onlineUser)

        //ajout de l'utilisateur connecté à la liste des utilisateurs connecté
        connectedUser.push(element.id)
      } 

      //si une fenetre de communication (offcanvas) existe déja
      if (offcanvasCreated.indexOf(user) != -1) {

        //notification de connexion sur la conversation 
        enterConversation = `<small>${element.username} a rejoint la conversation</small><br>`
        $('#appendNewMessage-'+element.id).append(enterConversation)

        //sur le clique de la ligne utilisateur active
        $('#show-'+element.id).click(function(){

          //affichage de la fenetre de communication 
          $('#message-'+element.id).offcanvas('show')
          offcanvasOpen = element.id

          //si une notification de message existe
          if (messengerNotification.indexOf(element.id) != -1) {
         //suppression de la notification sur la ligne utilisateur active
           $('#showContent-'+element.id).removeClass('bg-primary')
            let ind = messengerNotification.indexOf(element.id)
            messengerNotification.splice(ind,1)
            $('#showContent-'+element.id).children().last().remove()
          }

          //mise en bas de la conversation
          var messageBody = document.querySelector('#appendNewMessage-'+element.id);
          messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;
          
        })
      }

      //si aucune fenetre de communication (offcanvas) n'existe 
      else if (offcanvasCreated.indexOf(user) == -1){
        //sur clique de la ligne utilisateur
        $('#show-'+element.id).click(function(){
          console.log('creation fenetre discussion sur nouvelle connexion de follower : ', user)
          //--------------------------------------------------------------------------------------------------------- creation d'un environnement de communication-----------------------nouvelle connection
          var response;
          $.ajax({ type: "GET",   
              url: "/templates/partial/navbar/messageBodyOffcanvas.ejs",   
              async: false,
              success : function(text)
              {   
                  //personnalisation du template
                  text = text.replace('messageCanvas', 'message-'+element.id)
                  text = text.replace('offcanvasClose', 'offcanvasClose-'+element.id)
                  text = text.replace('appendNewMessage', 'appendNewMessage-'+element.id)
                  text = text.replace('imageLink', '/material/img/global/'+element.picture)
                  text = text.replace('profileLink', '/world/profile/'+element.username)
                  text = text.replaceAll('firstname-lastname', element.firstname+' '+element.lastname)
                  text = text.replace('text-message', 'text-message-'+element.id)
                  text = text.replace('sendMessage', 'send-to-'+element.id)
                  text = text.replace('formMessage', 'form-to-'+element.id)
                  response= text;
              }
          });

          //integration du canvas au document 
          $('body').append(response);

          //option touche entrée
          $("#text-message-"+element.id).keyup(function(event) {
            event.preventDefault()
              if (event.keyCode === 13) {
                  $('#send-to-'+element.id).click();
              }
          });

          //envoi d'un message à un destinataire
          $('#form-to-'+element.id).submit(function(e){
            e.preventDefault()
            console.log('message sent')
            let messageContent = $('#text-message-'+element.id).text()
            let user = element.id
            let message = {
              content : messageContent,
              user : user,
              socket : element.connected.id,
              timestamp : Math.ceil(Date.now()/1000)
            }

            //emission du message vers le serveur pour le destinataire
            socket.emit('message', message, (response)=>{
              //retour du serveur sur le status de connexion de l'utilisateur 
              $('#text-message-'+element.id).text('')
              if (response.status == 0) {
                //l'utilisateur est indisponible
              } else if (response.status == 1){
                //l'utilisateur est disponible -> forte probabilité de livraison du message -> on affiche 
                let selfMessage = 
                `
                <div class="d-flex p-3">
                  <div class="flex-1 d-flex justify-content-end">
                    <div class="w-100 w-xxl-75">
                      <div class="hover-actions-trigger d-flex flex-end-center">
                        <ul class="hover-actions position-relative list-inline mb-0 text-400 me-2">
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Forward"><span class="fas fa-share"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Archive"><span class="fas fa-archive"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Edit"><span class="fas fa-edit"></span></a></li>
                          <li class="list-inline-item"><a class="chat-option" href="#!" data-bs-toggle="tooltip" data-bs-placement="top" title="Remove"><span class="fas fa-trash-alt"></span></a></li>
                        </ul>
                        <div class="bg-primary text-white p-2 rounded-2 chat-message light">
                          ${message.content}  
                        </div>
                      </div>
                      <div class="text-400 fs--2 text-end">${moment.unix(message.timestamp).format('h:mm')}<!--<span class="fas fa-check ms-2 text-success"></span>--></div>
                    </div>
                  </div>
                </div>
                `
                $('#appendNewMessage-'+response.user).append(selfMessage)
                var messageBody = document.querySelector('#appendNewMessage-'+response.user);
                messageBody.scrollTop = messageBody.scrollHeight - messageBody.clientHeight;
              }
            })
          })

          //ajout d'une fenetre ouverte
          offcanvasCreated.push(element.id) 

          //si une notification de message existe pour l'utilisateur
          if (messengerNotification.indexOf(element.id) != -1) {
            //suppression de la notification sur la ligne utilisateur active
            $('#showContent-'+element.id).removeClass('bg-primary')
            let ind = messengerNotification.indexOf(element.id)
            messengerNotification.splice(ind,1)
            $("#messageNotification-"+element.id).remove()

            $('#show-'+element.id).removeClass('bg-primary')
          }

          //affichage de la fenetre de communication
          $('#message-'+element.id).offcanvas('show')
          offcanvasOpen = element.id

          //fermeture de la fenetre de communication
          $('#offcanvasClose-'+element.id).click(function(){
            offcanvasOpen = null
          })
        })
      }
    
    })
  
    //deconnexion d'un follower
    socket.on("offline", (user)=>{
      console.log('disconnection : ', user)
      //si l'utilisateur etait inscris dans la liste des user connecté (il doit l'être)
      if (connectedUser.indexOf(user) != -1){
        //on cache l'utilisateur de la liste des user connecté
        $('#show-'+user).remove()
        let ind = connectedUser.indexOf(user)
        connectedUser.splice(ind,1)

        //on met son status de connexion a 0
        for (let i = 0; i < self.mutual.length; i++) {
          const element = self.mutual[i];
          self.mutual[i].connected.status = 0
          //si une fenetre de communication (offcanvas) existe
          if (offcanvasCreated.indexOf(element.id) != -1) {
            //notification de deconnexion sur la conversation 
            leaveConversation = `<small>${element.username} a quitté la conversation</small><br>`
            $('#appendNewMessage-'+element.id).append(leaveConversation)

            //desactivation des champs de saisie

          }          
        }
      }
    })
  
    //confirmation de livraison d'un message
    socket.on("delivred", (message)=>{
      console.log('delivred', message)
      
      //affichage 
      //confirmation de livraison du message par green tick 
    })
    
    //on getting position
    function success(pos) {  
      console.log(pos)
      position.longitude = pos.coords.longitude; 
      position.latitude = pos.coords.latitude; 
      position.accuracy = pos.coords.accuracy;
      position.heading = pos.coords.heading;
      position.timestamp = Math.round(pos.timestamp/1000)
      console.log(`Latitude : ${position.latitude}, Longitude : ${position.longitude}, La précision est de ${position.accuracy} mètres.`);
      //envoi de la geolocalisation
      if (position.accuracy < 200) {
        //envoi en base de données
        let geoForm = new FormData()
        geoForm.append('geodata', JSON.stringify(position))
        fetch(new Request('/geolocation', {method:"POST", mode: "cors", body: geoForm}))
        .then(response => response.text())
        .then(response =>{
          position.city = response
        })
      }
    }

    //error on position
    function error(err) {
        console.warn(`ERREUR (${err.code}): ${err.message}`);
    }

    //start geolocation
    navigator.geolocation.getCurrentPosition(success, error, {
        enableHighAccuracy: true,
        timeout: 30000,
        maximumAge: 0
    })
  })


</script>





          <!-- profile -->
          <div class="card mb-3">
            <!-- cover picture -->
            <div class="row m-2 bg-light rounded-3 rounded-bottom-0 mb-2" style="height: 150px;">
              <div class="col-5 p-0">
                <!-- avatar -->
                <div class="avatar avatar-4xl avatar-profile" style="top: -20px; margin-left: 30px;">
                  <img class="rounded-circle img-thumbnail shadow-sm" src="/material/img/global/default.png" width="200" alt="" id="picture_profile" />
                </div>
              </div>
            </div>
            
            <div class="card-body p-0">
              <!-- user badge-->
              <div class="row">
                <div class="col p-4 pt-0 pb-0">
                  <!-- firstname, lastname, verified --> 
                  <h4 class="mb-1">
                    <span id="firstname"></span>
                    <span id="lastname"></span>
                    
                    <span id="verified" data-bs-toggle="tooltip" data-bs-placement="right" title="Verified">
                        <small class="bi bi-check-circle text-primary ml-2" data-fa-transform="shrink-4 down-2"></small>
                    </span>
                  </h4>
                  <!-- username -->
                  <p class="mb-1">
                    <a href="">
                      <span>@</span><span id="username"></span>
                    </a>
                  </p>
                  <!-- ici charger le travail / cursus / status actuel -->
                  <h6 class="fs-0 fw-normal" id="heading"></h6>
                  <!-- ici charger la localité -->
                  <p class="text-500 mb-0" id="location"></p>
                  <!-- follower / message  -->
                  <div class="row m-4 mb-0 mt-0">
                    <div class="col-3 hstack gap-2 gap-xl-3 justify-content-center m-4">
                      <!-- WORKOUT -->
                      <div class="text-center" id="performance">
                        <h6 class="mb-0 text-center" id="myworkout"></h6>
                        <small>Workout</small>
                      </div>
                      <div class="vr"></div>
                      <!-- FOLLOWER -->
                      <div class="text-center"  id="follower">
                        <h6 class="mb-0 text-center" id="selfnumberfollower"></h6>
                        <small>Followers</small>
                      </div>
                      <div class="vr"></div>
                      <!-- FOLLOWING -->
                      <div class="text-center"  id="following">
                        <h6 class="mb-0 text-center" id="selfnumberfollowing"></h6>
                        <small>Following</small>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!-- categories-->
              <div class="row">
                <ul class="nav nav-tabs w-100 p-4 pt-0" id="myTab" role="tablist" style="border: none;">
                  <li class="nav-item" role="presentation">
                    <button style="padding: 0 10px;" class="nav-link active" id="bio-tab" data-bs-toggle="tab" data-bs-target="#bio-tab-pane" type="button" role="tab" aria-controls="bio-tab-pane" aria-selected="true">Bio</button>
                  </li>
                  <li class="nav-item" role="presentation">
                    <button style="padding: 0 10px;" class="nav-link" id="perf-tab" data-bs-toggle="tab" data-bs-target="#perf-tab-pane" type="button" role="tab" aria-controls="perf-tab-pane" aria-selected="false">Workout</button>
                  </li>
                  <li class="nav-item" role="presentation">
                    <button style="padding: 0 10px;" class="nav-link" id="media-tab" data-bs-toggle="tab" data-bs-target="#media-tab-pane" type="button" role="tab" aria-controls="media-tab-pane" aria-selected="false">Media</button>
                  </li>
                  <li class="nav-item" role="presentation">
                    <button style="padding: 0 10px;" class="nav-link" id="stats-tab" data-bs-toggle="tab" data-bs-target="#stats-tab-pane" type="button" role="tab" aria-controls="stats-tab-pane" aria-selected="false">Stats</button>
                  </li>
                  <!-- this hidden-->
                  <li class="nav-item" role="presentation">
                    <button  style="border: none;" class="nav-link" id="followers-tab" data-bs-toggle="tab" data-bs-target="#followers-tab-pane" type="button" role="tab" aria-controls="followers-tab-pane" aria-selected="false" hidden></button>
                  </li>
                  <li class="nav-item" role="presentation">
                    <button  style="border: none;" class="nav-link" id="following-tab" data-bs-toggle="tab" data-bs-target="#following-tab-pane" type="button" role="tab" aria-controls="following-tab-pane" aria-selected="false" hidden></button>
                  </li>
                </ul>
                <div class="tab-content" id="myTabContent" >
                  <!-- biographie-->
                  <div class="tab-pane fade show active" id="bio-tab-pane" role="tabpanel" aria-labelledby="bio-tab" tabindex="0">
                      <!-- intro -->
                    <div class="mb-3 mt-3" id="bio">
                      <div class="card-header bg-light">
                        <h5 class="mb-0">Biographie</h5>
                      </div>
                      <div class="card-body text-justify">
                        <!-- describe 4 moment fort de votre parcours-->
                        <!-- 150 chars max-->
                        <p class="mb-0 text-1000" id="show_part_one_intro">
                          
                        </p>
                        <!-- 300 chars max -->
                        <div class="collapse" id="profile-intro">
                          <!--
                          <p class="mt-3 text-1000" id="show_part_two_intro">I’ve acquired a wide depth of knowledge and expertise in using my technical skills in programming, computer science, software development, and mobile app development to developing solutions to help organizations increase productivity, and accelerate business performance. </p>
                          <p class="text-1000" id="show_part_three_intro">It’s great that we live in an age where we can share so much with technology but I’m but I’m ready for the next phase of my career, with a healthy balance between the virtual world and a workplace where I help others face-to-face.</p>
                          <p class="text-1000 mb-0"  id="show_part_four_intro">There’s always something new to learn, especially in IT-related fields. People like working with me because I can explain technology to everyone, from staff to executives who need me to tie together the details and the big picture. I can also implement the technologies that successful projects need.</p>
                          !-->
                        </div>
                      </div>
                      <!-- button show more less-->
                      <!--<div class="card-footer bg-light p-0 border-top">
                        <button class="btn btn-link d-block w-100 btn-intro-collapse" type="button" data-bs-toggle="collapse" data-bs-target="#profile-intro" aria-expanded="false" aria-controls="profile-intro">
                          Show 
                          <span class="less">
                            less
                            <span class="bi bi-chevron-up ms-2 fs--2"></span>
                          </span>
                          <span class="full">
                            full
                            <span class="bi bi-chevron-down ms-2 fs--2"></span>
                          </span>
                        </button>
                      </div> -->
                    </div>
                    <!-- experience-->
                    <div class="mb-3">
                      <div class="card-header bg-light">
                        <h5 class="mb-0">Experience</h5>
                      </div>
                      <div class="card-body fs--1 mt-3">
                        <div class="" id="exp">
                    
                        </div>
                      </div>
                    </div>
                    <!-- Education-->
                    <div class="mb-3">
                      <div class="card-header bg-light">
                        <h5 class="mb-0">Education</h5>
                      </div>
                      <div class="card-body fs--1">
                        <div class="" id="edu">
                    
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- workout -->
                  <div class="tab-pane fade" id="perf-tab-pane" role="tabpanel" aria-labelledby="perf-tab" tabindex="0">
                    <!-- last exercice activty-->
                    <div class="card mb-3">
                      <div class="card-header bg-light d-flex justify-content-between">
                        <h5 class="mb-0" id="mytitleperformance">Last Performance</h5>
                        <a class="font-sans-serif" href="/" id="allperf" style="display: none;">All perf</a>
                      </div>
                      <div class="card-body fs--1 p-0" id="myperformance">
                        <!-- list of performance -->
                      </div>
                    </div>
                  </div>
                  <!-- media -->
                  <div class="tab-pane fade" id="media-tab-pane" role="tabpanel" aria-labelledby="media-tab" tabindex="0">
                      <!-- some content imported from networks-->
                    <!--<div class="card mb-3 mb-lg-0">
                      <div class="card-body overflow-hidden p-0">
                        <div class="row g-0">
                          <div class="col-6 p-1">
                            <a class="glightbox" href="https://flyight.com/material/img/assets/generic/4.jpg" data-gallery="gallery1" data-glightbox="data-glightbox">
                              <img class="img-fluid rounded" src="https://flyight.com/material/img/assets/generic/4.jpg" alt="..." />
                            </a>
                          </div>
                          <div class="col-6 p-1">
                            <a class="glightbox" href="https://flyight.com/material/img/assets/generic/5.jpg" data-gallery="gallery1" data-glightbox="data-glightbox">
                              <img class="img-fluid rounded" src="https://flyight.com/material/img/assets/generic/5.jpg" alt="..." />
                            </a>
                          </div>
                          <div class="col-4 p-1">
                            <a class="glightbox" href="https://flyight.com/material/img/assets/gallery/4.jpg" data-gallery="gallery1" data-glightbox="data-glightbox">
                              <img class="img-fluid rounded" src="https://flyight.com/material/img/assets/gallery/4.jpg" alt="..." />
                            </a>
                          </div>
                          <div class="col-4 p-1">
                            <a class="glightbox" href="https://flyight.com/material/img/assets/gallery/5.jpg" data-gallery="gallery1" data-glightbox="data-glightbox">
                              <img class="img-fluid rounded" src="https://flyight.com/material/img/assets/gallery/5.jpg" alt="..." />
                            </a>
                          </div>
                          <div class="col-4 p-1">
                            <a class="glightbox" href="https://flyight.com/material/img/assets/gallery/3.jpg" data-gallery="gallery1" data-glightbox="data-glightbox">
                              <img class="img-fluid rounded" src="https://flyight.com/material/img/assets/gallery/3.jpg" alt="..." />
                            </a>
                          </div>
                        </div>
                      </div>
                    </div>-->
                  </div>
                  <!-- stats -->
                  <div class="tab-pane fade" id="stats-tab-pane" role="tabpanel" aria-labelledby="stats-tab" tabindex="0">
                    <div class="card mb-3">
                      <div class="card-header bg-light d-flex justify-content-between">
                        <h5 class="mb-0">Statistics</h5>
                      </div>
                      <div class="card-body fs--1">
                        <!-- list of performance -->
                        <div class="col-7">
                          <small class="m-0">Distance parcourue : <span></span></small>
                          <br>
                          <small class="m-0">Distance moyenne : <span></span></small>
                          <br>
                          <small class="m-0">Vitesse moyenne : <span></span></small>
                          <br>
                          <small class="m-0">Temps moyen 100m : <span></span></small>
                          <br>
                          <small class="m-0">Détente maximum : <span></span></small>
                          <br>
                          <small class="m-0">Détente moyenne : <span></span></small>
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- followers -->
                  <div class="tab-pane fade" id="followers-tab-pane" role="tabpanel" aria-labelledby="followers-tab" tabindex="0">
                      <!-- follower -> people user follow  display 12 + load more when window on bottom-->
                    <div class="card mt-3">
                      <div class="card-header bg-light">
                        <div class="row">
                          <div class="col">
                            <h5 class="mb-0" id="">Online (<span class="d-none d-sm-inline-block" id="followeronline">0</span>)</h5>
                          </div>
                        </div>
                      </div>

                      <div class="row p-2 justify-content-center" id="displayFollower">
                        <!-- container for all following -->
                       
                      </div>
                      <div class="col text-center m-4"><a class="font-sans-serif" href="#">View all following</a></div>


                    </div>
                  </div>
                  <!-- following-->
                  <div class="tab-pane fade" id="following-tab-pane" role="tabpanel" aria-labelledby="following-tab" tabindex="0">
                    <div class="card mt-3">
                      <div class="card-header bg-light">
                        <div class="row">
                          <div class="col">
                            <h5 class="mb-0" id="">Online (<span class="d-none d-sm-inline-block">0</span>)</h5>
                          </div>
                        </div>
                      </div>
                      <div class="row p-2 justify-content-center" id="displayFollowing">
                        <!-- container for all following -->
                      
                        
                      </div>
                      <div class="col text-center m-4"><a class="font-sans-serif" href="#">View all following</a></div>

                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- footer-->
          <footer class="footer">
    <div class="row g-0 justify-content-between fs--1 mt-4">
      <div class="col-12 col-sm-auto text-center">
        <p class="mb-0 text-600 opacity-85">
          &copy; Flyight.com
          <script>
            document.write(new Date(Date.now()).getFullYear())
          </script> 
        </p>
      </div>
    </div>
</footer>
        </div>
      </div>
    </main>
    <script src="/vendors/jquery.min.js" type="text/javascript"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<script src="/vendors/anchorjs/anchor.min.js"></script>
<script src="/vendors/is/is.min.js"></script>
<script src="/vendors/dropzone/dropzone.min.js"></script>
<script src="/vendors/lottie/lottie.min.js"></script>
<script src="/vendors/validator/validator.min.js"></script>
<script src="/vendors/swiper/swiper-bundle.min.js"> </script>
<script src="/vendors/rater-js/index.js"> </script>
<script src="/vendors/typed.js/typed.js"> </script>
<script src="/vendors/lodash/lodash.min.js"></script>
<script src="/vendors/list.js/list.min.js"></script>
<script src="/vendors/countup/countUp.umd.js"></script>
<script src="/vendors/glightbox/glightbox.min.js"></script>
<script src="/vendors/prium.js"></script>
<script src="/vendors/Chart.min.js" type="text/javascript"></script>
<script src="/socket.io/socket.io.js"></script>
<script src="/vendors/moment.js"></script>
<script src="/vendors/moment-duration-format.min.js"></script>
<script src="/vendors/ble.js"></script>
<script src="/vendors/mapbox.js"></script>
<script src="/script/global/function.js" type="text/javascript"></script>
<script src="/script/global/gateway.js" type="text/javascript"></script>
<script src="/script/global/notification.js" type="text/javascript"></script>
<script src="https://api.payplug.com/js/1/form.latest.js" type="text/javascript"></script>   
<script src="/vendors/overlayscrollbars/OverlayScrollbars.min.js"></script>
<script src="https://js.stripe.com/v3/"></script>


<script>
	//socket.io
	const socket = io("",{
		reconnectionDelayMax: 10000,
	});

	//overlayScrollbars
	let scrol = OverlayScrollbars(document.querySelectorAll("body"), {
		className       : "os-theme-dark",
		resize          : "both",
		sizeAutoCapable : true,
		paddingAbsolute : true,
		scrollbars : {
			clickScrolling : true
		}
	});

	//screen wake
	let wakeLock = null;
	
	let wake = async () => {
          try {
               wakeLock = await navigator.wakeLock.request('screen');
               console.log('screen active')
          } catch (err) {
               console.log(err)
          }
    }
</script>
   <script src="/script/profile/self/self.js"></script>
  </body>
</html>
