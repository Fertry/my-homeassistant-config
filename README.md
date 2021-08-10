<h1> My Home Assistant config </h1>

<h2> My Home Assistant Configuration 🏡 </h2>
<p><a href="https://www.home-assistant.io">HASS</a> is installed on a <a href="https://amzn.to/3CqJG2F" target="_blank">Intel NUC Barebone</a> with 8GB (2x4) of <a href="https://amzn.to/3AB3i2D" target="_blank">2666MHz DDR4 RAM</a> and <a href="https://amzn.to/3CotMWN" target="_blank">120GB 2,5" SATA SSD</a>. Actually running version core-2021.8.3 (August 2021).</p>

<h2> Things running on HASS ⭐ </h2>

<ol>
  <li> <a href="https://hacs.xyz" target="_blank">HACS</a>                                                            </li>
  <li> <a href="https://www.influxdata.com/products/influxdb-overview" target="_blank">InfluxDB </a> along with <a href="https://grafana.com/"target="_blank">Grafana</a> for recording metrics                                        </li> 
  <li> <a href="https://www.duckdns.org/" target="_blank">DuckDNS</a> along with <a href="https://en.wikipedia.org/wiki/Dnsmasq" target="_blank">Dnsmasq</a> for remote access                                                              </li>
  <li> <a href="https://tautulli.com" target="_blank">Tautulli</a> for Plex management                                </li>
  <li> <a href="https://en.wikipedia.org/wiki/Zigbee" target="_blank">Zigbee</a> & <a href="https://en.wikipedia.org/wiki/MQTT" target="_blank">MQTT</a> system for Home Automation                                                           </li>
  <li> A bunch of custom components for backups, displays, etc.
</ol>

<h2> Components 🌟 </h2>

<div align="center" id="menu">
  
  | <a href="https://github.com/Fertry/my-homeassistant-config#devices">Devices</a> | <a href="https://github.com/Fertry/my-homeassistant-config#sensors">Sensors</a> | <a href="https://github.com/Fertry/my-homeassistant-config#media">Media</a> | <a href="https://github.com/Fertry/my-homeassistant-config#others">Others</a> | <a href="https://github.com/Fertry/my-homeassistant-config#todo">TO-DO</a> | <a href="https://fertry.tech" target="_blank">Blog</a> |

</div>

<div align="center" id="devices">

  <a name="devices">
    <h3> Devices </h3>
  </a>

  <table>
    <tr>
      <th>Intel NUC Barebone</th>
      <th>2x 4GB 2666MHz DDR4 RAM</th>
      <th>120GB 2,5" SATA SSD</th>
    </tr>
    <tr>
      <th><a href="https://amzn.to/3fKqTWx" target="_blank"><img src="https://m.media-amazon.com/images/I/41Ij8HhMqVL._AC_SL1023_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3s2t5h5" target="_blank"><img src="https://m.media-amazon.com/images/I/71Oys7qdffL._AC_SL1280_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3AoFWwM" target="_blank"><img src="https://m.media-amazon.com/images/I/91RL+MhTWbL._AC_SL1500_.jpg" width=120 height=120/></a></th>
    </tr>
  </table>

</div>

<div align="center" id="sensors">

  <a name="sensors">
    <h3> Sensors </h3>
  </a>

  <table>
    <tr>
      <th>3x Xiaomi Mijia Thermometer (2020)</th>
      <th>1x Xiaomi Mijia Thermometer (2019)</th>
      <th>1x ESP32</th>
      <th>2x Xiaomi Mijia Movement Sensor</th>
    </tr>
    <tr>
      <th><a href="https://amzn.to/3i6JM4T" target="_blank"><img src="https://m.media-amazon.com/images/I/41-zlO24wWL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/2QXlf6D" target="_blank"><img src="https://m.media-amazon.com/images/I/51xPG6gd+uL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3bvnt6J" target="_blank"><img src="https://m.media-amazon.com/images/I/71Q4jCOGohL._SL1500_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3347jx3" target="_blank"><img src="https://m.media-amazon.com/images/I/41uxYzhqiLL._AC_SL1000_.jpg" width=120 height=120/></a></th>
    </tr>
    <tr>
      <th>2x Sonoff SNZB-04 Door Sensor</th>
      <th>1x eMylo Water Leak Sensor</th>
      <th>1x Sonoff SNZB-01 Switch</th>
      <th>1x Aqara DJT11LM Vibration Sensor</th>
    </tr>
    <tr>
      <th><a href="https://amzn.to/3fL0V55" target="_blank"><img src="https://m.media-amazon.com/images/I/41gl5-hqNJL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3fL22BI" target="_blank"><img src="https://m.media-amazon.com/images/I/31DvcMVPhwL._AC_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3s20wjI" target="_blank"><img src="https://m.media-amazon.com/images/I/41Vv9-NKkIL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/2Vs3Qcd" target="_blank"><img src="https://m.media-amazon.com/images/I/61W2db81USL._AC_SL1500_.jpg" width=120 height=120/></a></th>
    </tr>
  </table>

</div>

<p>
  I use a bunch of Zigbee sensors thanks to a CC2531 Zigbee coordinator and those that need Bluetooht are connected through a ESP32 beacon running custom firmware by <a href="https://esphome.io/" target="_blank">ESPHome</a>. Also the new Mijia Thermometers (2020) are connected running custom firmware made by <a href="https://github.com/atc1441/ATC_MiThermometer/" target="_blank">atc1441</a>.
</p>

<div align="center" id="media">

  <a name="media">
    <h3> Media </h3>
  </a>

  <table>
    <tr>
      <th>2x Google Chromecast</th>
      <th>2x Google Home Mini</th>
      <th>Plex Media Server</th>
      <th>Synology DSM</th>
      <th>Raddar, Sonarr & Liddar</th>
    </tr>
    <tr>
      <th><a href="https://store.google.com/product/chromecast" target="_blank"><img src="https://i5.walmartimages.com/asr/ce02c3e2-ddb0-48ce-9519-1870901b3b15_3.dfbbf2da6fa65c08bf68a650edc5ee03.jpeg" width=120 height=120/></a></th>
      <th><a href="https://support.google.com/googlenest/answer/7072284?hl=en" target="_blank"><img src="https://i5.walmartimages.ca/images/Large/664/833/6000197664833.jpg?odnBound=460" width=120 height=120/></a></th>
      <th><a href="https://www.plex.tv/es/?langr=1" target="_blank"><img src="https://ih0.redbubble.net/image.197089200.4025/sticker,375x360-bg,ffffff.png" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3i5DEKo" target="_blank"><img src="https://www.synology.com/img/products/detail/DS720plus/heading@2x.png" width=120 height=120/></a></th>
      <th><a href="https://sonarr.tv/" target="_blank"><img src="https://avatars3.githubusercontent.com/u/1082903?v=3&s=400" width=120 height=120/></a></th>
    </tr>
  </table>

</div>

<div align="center" id="others">

  <a name="others">
    <h3> Others </h3>
  </a>

  <table>
    <tr>
      <th>Zigbee CC2531 USB</th>
      <th>Z-Wave USB</th>
      <th>TP-Link C100 Camera</th>
      <th>ESP32 Camera Module</th>
      <th>Magic Home Controller</th>
    </tr>
    <tr>
      <th><a href="https://amzn.to/3h17cHP" target="_blank"><img src="https://m.media-amazon.com/images/I/517Cxxcn-LL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3lN2kvN" target="_blank"><img src="https://m.media-amazon.com/images/I/61+d+A4ygIL._AC_SL1500_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3AsGhPj" target="_blank"><img src="https://m.media-amazon.com/images/I/61Nkt+sPmoL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3lPFR1b" target="_blank"><img src="https://m.media-amazon.com/images/I/81tp6MKahqL._AC_SL1500_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/2VzUBGV" target="_blank"><img src="https://m.media-amazon.com/images/I/51nyrR3+c8L._AC_SL1001_.jpg" width=120 height=120/></a></th>
    </tr>
  </table>

</div>

<div align="center" id="switch">

  <a name="switch">
    <h3> Switch </h3>
  </a>

  <table>
    <tr>
      <th>Bagotte Switch</th>
      <th>Sonoff Switch</th>
      <th>Sonoff Basic</th>
      <th>TP-Link HS110</th>
    </tr>
    <tr>
      <th><a href="https://amzn.to/2DzVF4p" target="_blank"><img src="https://images-na.ssl-images-amazon.com/images/I/51iBqwo6UBL._AC_SL1083_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/2R0ij9b" target="_blank"><img src="https://images-na.ssl-images-amazon.com/images/I/41euo4NNauL._AC_SL1000_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3ivwvWj" target="_blank"><img src="https://m.media-amazon.com/images/I/610g5Gke7aL._AC_SL1500_.jpg" width=120 height=120/></a></th>
      <th><a href="https://amzn.to/3Ay3vnc" target="_blank"><img src="https://m.media-amazon.com/images/I/51u0GrwKW3L._AC_SL1333_.jpg" width=120 height=120/></a></th>
    </tr>
  </table>

</div>

<p> A bunch of different appliances from differents brands all running custom firmware by <a href="https://esphome.io/" target="_blank">ESPHome</a>. 

<div align="left" id="todo">

  <a name="todo">
    <h3> TO-DO 📘 </h3>
  </a>

  <p>Pending things... you can check the Github project page here:</p>

  <a href="https://github.com/users/Fertry/projects/10" target="_blank">
    <img src="https://fertry.tech/wp-content/uploads/2021/03/Github-proyectos.png" width="380" height="200"></img>
  </a>

</div>
