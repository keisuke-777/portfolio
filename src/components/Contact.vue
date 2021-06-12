<template>
  <div>
    <h1 class="content-title">
      <font-awesome-icon icon="phone" class="icon" /> Contact
    </h1>
    <div class="sam">
      <h2>
        <font-awesome-icon icon="address-card" class="icon" /> Contact me any
        way you like
      </h2>
      <div class="link">
        <a href="https://twitter.com/tsukuba_japan" class="link-icon"
          ><font-awesome-icon
            :icon="['fab', 'twitter']"
            class="web-icon twitter"
        /></a>
        <a href="hogehoge@gmail.com" class="link-icon"
          ><font-awesome-icon icon="envelope" class="web-icon mail"
        /></a>
        <a href="https://github.com/keisuke-777" class="link-icon"
          ><font-awesome-icon :icon="['fab', 'github']" class="web-icon github"
        /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style>
.sam {
  text-align: center;
}
.link {
  display: inline-flex;
  width: 30%;
  justify-content: center;
}
.link-icon {
  margin: 0 10px;
  margin-bottom: 20px;
}
.web-icon {
  font-size: 2em;
  background-color: white;
  padding: 0.3em;
  border-radius: 50%;
}
.web-icon:hover {
  color: white;
}
.twitter {
  color: #1da1f2;
}
.twitter:hover {
  background-color: #1da1f2;
}
.mail {
  color: #dd5144;
}
.mail:hover {
  background-color: #dd5144;
}
.github {
  color: #171515;
}
.github:hover {
  background-color: #171515;
}
.hateblo {
  color: #193278;
}
.hateblo:hover {
  background-color: #193278;
}
@media screen and (max-width: 768px) {
  .web-icon {
    color: white;
  }
  .twitter {
    background-color: #1da1f2;
  }
  .mail {
    background-color: #dd5144;
  }
  .github {
    background-color: #171515;
  }
  .hateblo {
    background-color: #193278;
  }
}
</style>