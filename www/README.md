<p> The <em>www</em> folder is necessary to store images (or other media) that we want to show in HASS. It is also used by <a href="https://hacs.xyz/" target="_blank">HACS</a> (which creates the <b>community</b> folder automatically) for storing visual add-ons for the Lovelace interface.</p>

<p>This folder shall not be confused with the /media folder, since this one is located in /config and the organization is as follows:

- /media
- /config
-- /config/www

The /media folder is the default storage for media files like music files, videos, etc. and it's wise to use this one instead of www.

¿Why? Because as stated in the <a href="https://www.home-assistant.io/integrations/http/#hosting-files" target="_blank">documentation</a>, the www is <b>not password-protected</b> so any files stored inside can be accessed by devices on the same network. Anyways, if we store any media in there, we will we able to display it in the Lovelace interface as well.</p>

<img src="https://raw.githubusercontent.com/Fertry/my-homeassistant-config/master/www/cactus.png" width="100" height="100"></img>

<p>Please refer to the creators of each add-on for how-to instructions and don't forget to endorse their work.</p>