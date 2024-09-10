<div align="center">
  <img src="https://raw.githubusercontent.com/opslag/toon/master/.github/logo.png" title="Logo" style="max-width:100%;" width="256" />
</div>
<div align="center">
  
  [![Build](https://github.com/opslag/toon/actions/workflows/build.yml/badge.svg)](https://github.com/opslag/toon)
  [![Version](https://img.shields.io/github/v/tag/opslag/toon?label=version&sort=semver&color=066da5)](https://github.com/opslag/toon)

</div>
<hr />

This Toon integration supports long-lived access tokens in the `client_secret` field, in order to fix issue [115290](https://github.com/home-assistant/core/issues/115290).

To generate such a token, use the following link filled in with your `client_id` in a webbrowser:

`https://api.toon.eu/toonapi-accesstoken?tenant_id=eneco&client_id=<consumer_key>`

and put the retrieved value in your `configuration.yaml` as the `client_secret`.

# Installation  🚀

## Manual

1. Clone the repository to your machine and copy the contents of custom_components/ to your config directory
2. Restart Home Assistant
3. Setup integration via the integration page.

## HACS

1. Add the integration through this link:
   [![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=opslag&repository=toon&category=integration)
2. Restart Home Assistant
3. Setup integration via the integration page.

 # Acknowledgements 🙏
 
Special thanks to [@FrankHoogmans](https://github.com/FrankHoogmans) for this patch.

# Stars 🌟
[![Stars](https://starchart.cc/opslag/toon.svg?variant=adaptive)](https://starchart.cc/opslag/toon)
