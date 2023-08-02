<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.2/font/bootstrap-icons.css">

    <!-- Your Chat plugin code -->
    <div id="fb-customer-chat" class="fb-customerchat">
</div>
<script>
      var chatbox = document.getElementById('fb-customer-chat');
      chatbox.setAttribute("page_id", "103385375856407");
      chatbox.setAttribute("attribution", "biz_inbox");
</script>
<!-- Your SDK code -->
<script>
      window.fbAsyncInit = function() {
        FB.init({
          xfbml            : true,
          version          : 'v16.0'
        });
      };
      (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/en_GB/sdk/xfbml.customerchat.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));
</script>

<img style="width: 250px; height: auto" src="/assets/img/zioniyes-rainbow-sm-trim.png" />

---

[<i class="bi bi-camera"></i>Photo gallery](https://zioniyes.github.io/gallery) | [Services](services) | [Contact](contact)

## About me

You may know me for several of the things I do on a regular basis:

### Photography

- Primarily in Bruges & Ghent
- Reggae & Dub

### Audio electronics

I am involved with a variety of genres of repair & design:

- Amplifier repair
- Amplifier maintenance
- Sound generator modification
- Customizations
- Assembly and/or design of new equipment
- Speaker design (coop w/ Ruben Boucké)

## Contact

You can contact me in various ways. The quickest way as of now, is to send me a twitter message: <https://twitter.com/BittieBot125>

---

This site on GitHub: <https://github.com/ZionIyes/zioniyes.github.io> 
