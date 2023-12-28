+++
template = "download.html"
title = "Download"
+++

<div class="container">
  <div>
    <picture class="logo">
      <img src="/static/assets/img/beep.png" alt="beep banner">
    </picture>
  </div>
  <meta http-equiv="refresh" content="7; URL={{ config.extra.github_game_url }}/releases/download/{{ config.extra.latest_release }}/SS3D_{{ config.extra.latest_release }}.zip" />

  <h1>Downloading latest version of SS3D<br>(<strong><i>{{ config.extra.latest_release }}</i></strong>)...</h1>
  <h3>if file does NOT automatically start downloading after 10 seconds, <a href="{{ config.extra.github_game_url }}/releases/download/{{ config.extra.latest_release }}/SS3D_{{ config.extra.latest_release }}.zip">click here</a>.</h3>
</div>