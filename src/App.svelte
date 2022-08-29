<script>
  import SvgIcon from "@jamescoyle/svelte-icon";
  import androidLogo from "./assets/android_jetpack.svg";
  import kotlinLogo from "./assets/kotlin.svg";
  import { mdiSend, mdiGithub, mdiLinkedin, mdiEmail } from "@mdi/js";
</script>

<main>
  <div>
    <img src={kotlinLogo} class="logo kotlin" alt="Kotlin Logo" />
    <img src={androidLogo} class="logo android" alt="Android Logo" />
  </div>

  <h1>Nazar Dunets</h1>
  <h3>Android Developer</h3>

  <div class="row email" style="padding-bottom: 1em; padding-top: 1em">
    <SvgIcon type="mdi" path={mdiEmail} />
    <div style="padding-left: 0.5em">jcq.nazardunets@gmail.com</div>
  </div>

  <div class="row">
    <a href="https://www.linkedin.com/in/nazar-dunets/" target="_blank" class="contact">
      <SvgIcon type="mdi" path={mdiLinkedin} />
    </a>
    <a href="https://t.me/jcqNazar" target="_blank" class="contact">
      <SvgIcon type="mdi" path={mdiSend} />
    </a>
    <a href="https://github.com/NazarDunets" target="_blank" class="contact">
      <SvgIcon type="mdi" path={mdiGithub} />
    </a>
  </div>
</main>
