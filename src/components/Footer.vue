<template>
  <footer class="bg-dark text-white">
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <p>Handmade with <i class="fa fa-heart-o" /> by me © {{ new Date().getFullYear() }}.</p>
          <div class="social-links">
            <a
              v-b-tooltip.hover
              title="Email"
              data-aos="flip-right"
              href="mailto:pktharindu@outlook.com"
            ><i class="fa fa-envelope" /></a>
            <a
              v-b-tooltip.hover
              title="Twitter"
              data-aos="flip-left"
              href="https://twitter.com/pktharindu1"
              target="_blank"
            ><i class="fa fa-twitter" /></a>
            <a
              v-b-tooltip.hover
              title="Instagram"
              data-aos="flip-right"
              href="https://www.instagram.com/pktharindu"
              target="_blank"
            ><i class="fa fa-instagram" /></a>
            <a
              v-b-tooltip.hover
              title="Linkedin"
              data-aos="flip-left"
              href="https://www.linkedin.com/in/pktharindu"
              target="_blank"
            ><i class="fa fa-linkedin" /></a>
            <a
              v-b-tooltip.hover
              title="Skype"
              data-aos="flip-right"
              href="skype:pktharindu?chat"
              target="_blank"
            ><i class="fa fa-skype" /></a>
            <a
              v-b-tooltip.hover
              title="Facebook"
              data-aos="flip-left"
              href="https://www.facebook.com/pktharindu"
              target="_blank"
            ><i class="fa fa-facebook" /></a>
            <a
              v-b-tooltip.hover
              title="Dribbble"
              data-aos="flip-right"
              href="https://dribbble.com/pktharindu"
              target="_blank"
            ><i class="fa fa-dribbble" /></a>
            <a
              v-b-tooltip.hover
              title="Github"
              data-aos="flip-left"
              href="https://github.com/pktharindu"
              target="_blank"
            ><i class="fa fa-github" /></a>
            <a
              v-b-tooltip.hover
              title="Stack Overflow"
              data-aos="flip-right"
              href="https://stackoverflow.com/users/4886202"
              target="_blank"
            ><i class="fa fa-stack-overflow" /></a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
