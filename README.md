<h1> My Home Assistant config </h1>

<h2> My Home Assistant Configuration 🏡 </h2>
<p><a href="https://www.home-assistant.io">HASS</a> is installed on a <a href="https://www.raspberrypi.org/products/raspberry-pi-4-model-b">Raspberry Pi 4B+</a> with 2GB of RAM and 32GB Micro-SD card. Actually running version 0.111.4.</p>

<h2> Things running on HASS ⭐ </h2>

<ol>
  <li> <a href="https://hacs.xyz" target="_blank">HACS</a>                                           </li>
  <li> <a href="https://github.com/hassio-addons/addon-home-panel" target="_blank">Home Panel</a>    </li>
  <li> <a href="https://www.influxdata.com/products/influxdb-overview" target="_blank">InfluxDB</a>  </li>
  <li> <a href="https://github.com/hassio-addons/addon-log-viewer" target="_blank">Log Viewer</a>    </li>
  <li> <a href="https://tautulli.com" target="_blank">Tautulli</a>                                   </li>
  <li> <a href="https://github.com/hassio-addons/addon-ssh" target="_blank">SSH & Web Terminal</a>   </li>
</ol>

<h2> Components 🌟 </h2>
<div align="center" id="menu">
  
  | <a href="https://github.com/Fertry/my-homeassistant-config#devices">Devices</a> | <a href="https://github.com/Fertry/my-homeassistant-config#sensors">Sensors</a> | <a href="https://github.com/Fertry/my-homeassistant-config#media">Media</a> | <a href="https://github.com/Fertry/my-homeassistant-config#apps">Apps</a> | <a href="https://github.com/Fertry/my-homeassistant-config#others">Others</a> | <a href="https://github.com/Fertry/my-homeassistant-config#todo">TO-DO</a> | <a href="https://fertry.tech" target="_blank">Blog</a> |

</div>

<div align="center" id="devices">

<a name="devices">
  <h3> Devices </h3>
</a>

<table>
  <tr>
    <th>Raspberry Pi 4B+</th>
    <th>MicroSD-Card 32GB</th>
    <th>Power Adaptor 5V-3A</th>
    <th>2x Raspberry Pi Zero W</th>
  </tr>
  <tr>
    <th><a href="https://www.raspberrypi.org/products/raspberry-pi-4-model-b" target="_blank"><img src="https://www.notebookcheck.com/fileadmin/Notebooks/News/_nc3/raspberryPi4_2.jpg" width=100 height=100/></a></th>
    <th><a href="https://www.sdcard.org/developers/overview/speed_class/" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.explicit.bing.net%2Fth%3Fid%3DOIP.-R7NGTLsjybcEIUS5Q7sUgHaGE%26pid%3DApi&f=1" width=100 height=100/></a></th>
    <th><a href="https://www.raspberrypi.org/documentation/hardware/raspberrypi/power/README.md" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fecx.images-amazon.com%2Fimages%2FI%2F51UqUKxy2aL.jpg&f=1&nofb=1" width=100 height=100/></a></th>
    <th><a href="https://www.raspberrypi.org/products/raspberry-pi-zero-w/" target="_blank"><img src="https://www.raspberrypi.org/homepage-9df4b/static/9c6a7cd9c5f442d4279bd6862bef1657/a0db7/72a529ca180136e5ab43dcf1547253238e273b8b_pi-zero-w-tilt-1-1620x1080.jpg" width=100 height=100/></a></th>
  </tr>

</table>

</div>

<p>
  Along with the Raspberry Pi 4B+, that Home Assistant runs on, I use two Raspberrys Pi Zero W to run Pi-Hole and Grafana separately. In all cases, Application Class 2 microSD cards and power supplies with sufficient amperage are used.
</p>

<div align="center" id="sensors">

<a name="sensors">
  <h3> Sensors </h3>
</a>

<table>
  <tr>
    <th>3x Xiaomi Mijia Thermometer (2020)</th>
    <th>1x Xiaomi Mijia Thermometer (2019)</th>
    <th>1x ESP32</th>
  </tr>
  <tr>
    <th><a href="https://es.aliexpress.com/item/4000406818501.html?spm=a2g0o.productlist.0.0.57d81792LvTVdV&algo_pvid=f39a1014-be43-4992-8844-bf59594a70a2&algo_expid=f39a1014-be43-4992-8844-bf59594a70a2-5&btsid=0b0a182b15926682168313025ebae2&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://monkeyecho.com/wp-content/uploads/xiaomi-mijia-bluetooth-thermometer-hygrometer-2-smart-digital-lcd-screen.jpg" width=100 height=100/></a></th>
    <th><a href="https://es.aliexpress.com/item/32846083629.html?spm=a2g0o.productlist.0.0.57d81792LvTVdV&algo_pvid=f39a1014-be43-4992-8844-bf59594a70a2&algo_expid=f39a1014-be43-4992-8844-bf59594a70a2-10&btsid=0b0a182b15926682168313025ebae2&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.ebayimg.com%2Fimages%2Fg%2FNzEAAOSwFmxaUigH%2Fs-l300.jpg&f=1&nofb=1" width=100 height=100/></a></th>
    <th><a href="https://es.aliexpress.com/item/32864722159.html?spm=a2g0o.productlist.0.0.2efa683dScUYG9&algo_pvid=8557b67b-e94f-4b3c-8052-05c4895d565a&algo_expid=8557b67b-e94f-4b3c-8052-05c4895d565a-0&btsid=0b0a0ac215926682425545283e647e&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://cdn-reichelt.de/bilder/web/xxl_ws/A300/SBC-NODEMCU-ESP32-01.png" width=100 height=100/></a></th>
  </tr>

</table>

</div>

<p>
  I use Xiaomi thermometers that record temperature and humidity with good precision, connected via Zigbee/Bluetooth via a gateway.
</p>

<div align="center" id="media">

<a name="media">
  <h3> Media </h3>
</a>

<table>
  <tr>
    <th>Google Chromecast</th>
    <th>2x Google Home Mini</th>
    <th>Plex Media Server</th>
    <th>Synology DSM</th>
  </tr>
  <tr>
    <th><a href="https://store.google.com/product/chromecast" target="_blank"><img src="https://i5.walmartimages.com/asr/ce02c3e2-ddb0-48ce-9519-1870901b3b15_3.dfbbf2da6fa65c08bf68a650edc5ee03.jpeg" width=100 height=100/></a></th>
    <th><a href="https://support.google.com/googlenest/answer/7072284?hl=en" target="_blank"><img src="https://i5.walmartimages.ca/images/Large/664/833/6000197664833.jpg?odnBound=460" width=100 height=100/></a></th>
    <th><a href="https://www.plex.tv/es/?langr=1" target="_blank"><img src="https://ih0.redbubble.net/image.197089200.4025/sticker,375x360-bg,ffffff.png" width=100 height=100/></a></th>
    <th><a href="https://www.synology.com/en-en/products/series/home" target="_blank"><img src="https://www.synology.com/img/products/detail/DS720plus/heading@2x.png" width=100 height=100/></a></th>
  </tr>

</table>

</div>

<p>
  I use a Chromecast to stream video and two Home Mini (paired with each other) to play music. All this from a Plex server that saves the records to Tautulli.
</p>

<div align="center" id="apps">

<a name="apps">
  <h3> Apps </h3>
</a>

<table>
  <tr>
    <th>HACS</th>
    <th>Home Panel</th>
    <th>InfluxDB</th>
    <th>Log Viewer</th>
    <th>Tautulli</th>
    <th>SSH & Web Terminal</th>
    <th>Grafana</th>
    <th>Pi-Hole</th>
  </tr>
  <tr>
    <th><a href="https://hacs.xyz/" target="_blank"><img src="https://d33wubrfki0l68.cloudfront.net/0e05ce1e6d0ca7b8ec22febe0ed8b775f13a0c0d/a5474/img/hacs-logo.svg" width=100 height=100/></a></th>
    <th><a href="https://github.com/hassio-addons/addon-home-panel" target="_blank"><img src="https://raw.githubusercontent.com/timmo001/home-panel/master/documentation/resources/banner.png" width=100 height=100/></a></th>
    <th><a href="https://www.influxdata.com/products/influxdb-overview/" target="_blank"><img src="https://discoursecommunity.s3.dualstack.us-west-1.amazonaws.com/uploads/influxdata/original/2X/0/0c2a909efb7d83eba6621bdcf4cc69c290325135.png" width=100 height=100/></a></th>
    <th><a href="https://github.com/hassio-addons/addon-log-viewer" target="_blank"><img src="https://image.freepik.com/free-icon/log-file-format-symbol_318-45393.jpg" width=100 height=100/></a></th>
    <th><a href="https://tautulli.com/" target="_blank"><img src="https://avatars3.githubusercontent.com/u/34385001?s=400&v=4" width=100 height=100/></a></th>
    <th><a href="https://github.com/hassio-addons/addon-ssh" target="_blank"><img src="https://silicondales.com/wp-content/uploads/2018/09/ssh-icon-300x300.jpg" width=100 height=100/></a></th>
    <th><a href="https://grafana.com/" target="_blank"><img src="http://www.d0wn.com/wp-content/uploads/grafana-logo-1.jpg" width=100 height=100/></a></th>
    <th><a href="https://pi-hole.net/" target="_blank"><img src="https://i2.wp.com/pi-hole.net/wp-content/uploads/2016/12/Vortex-R.png?zoom=1.75&w=3840&ssl=1" width=100 height=100/></a></th>
  </tr>

</table>

</div>

<p>
  HACS allows you to install third-party integrations. In addition to those, I use the HASS integrations of Home Panel to display the data on a tablet, Log Viewer to view logs dynamically and SSH & Web Terminal to connect to the Raspberry remotely. I also use InfluxDB in the same instance of Home Assistant to generate records of the data which I then transfer to Grafana (separate) for display. I use Tautulli to keep logs from my Plex server and Pi-Hole (separate) as an ad blocking machine.
</p>

<div align="center" id="others">

<a name="others">
  <h3> Others </h3>
</a>

<table>
  <tr>
    <th>Xiaomi Gateway V2</th>
    <th>Xiaomi Gateway V3</th>
    <th>Zigbee CC2531 USB</th>
    <th>HP Envy 5010</th>
  </tr>
  <tr>
    <th><a href="https://es.aliexpress.com/item/32803186417.html?spm=a2g0o.productlist.0.0.54191b06FjQzLE&algo_pvid=6df9236d-1ece-4640-b9ee-8333fa72ac71&algo_expid=6df9236d-1ece-4640-b9ee-8333fa72ac71-2&btsid=0b0a182b15926707488172895ebaf2&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://xiaomi-mi.com/uploads/ck/xiaomi-mi-gateway-2-001.jpg" width=100 height=100/></a></th>
    <th><a href="https://es.aliexpress.com/item/32821192659.html?spm=a2g0o.productlist.0.0.54191b06FjQzLE&algo_pvid=6df9236d-1ece-4640-b9ee-8333fa72ac71&algo_expid=6df9236d-1ece-4640-b9ee-8333fa72ac71-0&btsid=0b0a182b15926707488172895ebaf2&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://www.nziomarket.com/958-large_default/xiaomi-mijia-mi-smart-home-multi-mode-gateway-v3-con-adaptador-eu.jpg" width=100 height=100/></a></th>
    <th><a href="https://es.aliexpress.com/item/4000816404730.html?spm=a2g0o.productlist.0.0.68f35d0fQtyj8m&algo_pvid=019e7b4e-0e9a-413a-b22e-5e56d2758058&algo_expid=019e7b4e-0e9a-413a-b22e-5e56d2758058-0&btsid=0b0a050b15926709440294024e68ed&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_" target="_blank"><img src="https://img.staticbg.com/thumb/large/oaupload/banggood/images/6B/97/438b0c1f-f9f5-478c-b481-877267eef0da.JPG" width=100 height=100/></a></th>
    <th><a href="https://support.hp.com/en-en/drivers/selfservice/model/14095645" target="_blank"><img src="https://ssl-product-images.www8-hp.com/digmedialib/prodimg/lowres/c06141390.png" width=100 height=100/></a></th>
  </tr>

</table>

</div>

<p>
  Xiaomi gateways allow me to connect Xiaomi devices and sensors with ease while the Zigbee adapter acts as a universal adapter. I also integrate my HP printer.
</p>

<div align="center" id="switch">

<a name="switch">
  <h3> Switch </h3>
</a>

<table>
  <tr>
    <th>Bagotte Switch</th>
    <th>Sonoff Switch</th>
  </tr>
  <tr>
    <th><a href="https://www.amazon.es/gp/product/B07DWTWM5Z/" target="_blank"><img src="https://images-na.ssl-images-amazon.com/images/I/51iBqwo6UBL._AC_SL1083_.jpg" width=100 height=100/></a></tr>
    <th><a href="https://www.amazon.es/gp/product/B07M63PLBG/" target="_blank"><img src="https://images-na.ssl-images-amazon.com/images/I/41euo4NNauL._AC_SL1000_.jpg" width=100 height=100/></a></tr>
  </tr>

</table>

</div>

<p>
  Different plugs that I have distributed around the house of different brands.
</p>

<div>

<div id="todo">

<a name="todo">
  <h3> TO-DO </h3>
</a>

<p>Pending...</p>

<ol>
  <li><strike>Update the Grafana connection to InfluxDB</strike></li>
  <li><strike>Upload the configuration.yaml</strike></li>
  <li><strike>Implement the Xiaomi Gateway V2</strike></li>
  <li>Implement the ESP32</li>
  <li>Implement the Zigbee CC2531 Adaptor</li>
  <li>Add the eWeLink switch to the configuration</li>
</ol>

</div>
