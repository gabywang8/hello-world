<table class="table table-bordered table-striped table-condensed">
   <tr>
      <td colspan="14">Test Report for ESP BLE Smartphone Compatibility</td>
   </tr>
   <tr>
      <td>ESP32 Module:</td>
      <td colspan="13">ESP-WROOM-32</td>
   </tr>
   <tr>
      <td>Commit ID:</td>
      <td colspan="13">7c29a39d6f9f2dfbefc49d34d34e9267afc7200d</td>
   </tr>
   <tr>
      <td>Test Demo:</td>
      <td colspan="13">https://github.com/espressif/esp-idf/tree/master/examples/bluetooth/ble_compatibility_test</td>
   </tr>
   <tr>
      <td rowspan="2">Phone Brand</td>
      <td rowspan="2">Model</td>
      <td rowspan="2">OS Version</td>
      <td rowspan="2">Test APP & Version</td>
      <td colspan="9">Test Item</td>
      <td rowspan="2">Note</td>
   </tr>
   <tr>
      <td>ADV  </td>
      <td>Pairing</td>
      <td>Service Discovery</td>
      <td>Read & Encrypt</td>
      <td>Short Read & Write</td>
      <td>Long Read & Write</td>
      <td>Short Notify</td>
      <td>Connection Success Rate (10 times)</td>
      <td>Long Connection Stability</td>
   </tr>
   <tr>
      <td rowspan="8">Samsung （三星）</td>
      <td>Galaxy S9</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>"LightBlue" here is the abbreviation of "LightBlue® Explorer"</td>
   </tr>
   <tr>
      <td>Galaxy Note 4 </td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Galaxy S8+</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>S3 GT-I9300</td>
      <td>Android 4.3</td>
      <td>nRF Connect V4.10*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>Intallation of LightBlue failed, so nRF Connect was used alternatively.</td>
   </tr>
   <tr>
      <td>S4 GT-I9502</td>
      <td>Android 8.0.0</td>
      <td>nRF Connect V4.10*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>Intallation of LightBlue failed, so nRF Connect was used alternatively.</td>
   </tr>
   <tr>
      <td>S5 SM-G9008V</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>90%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>S4 GT-I9500</td>
      <td>Android 4.3</td>
      <td>nRF Connect V4.10*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>Intallation of LightBlue failed, so nRF Connect was used alternatively.</td>
   </tr>
   <tr>
      <td>S6 SM-G9209</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>90%*</td>
      <td>Pass</td>
      <td>The app was always in connection.</td>
   </tr>
   <tr>
      <td rowspan="7">Apple（苹果）</td>
      <td>iPhone 5S/A1518</td>
      <td>iOS 12.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPhone X</td>
      <td>iOS 12.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPhone SE</td>
      <td>iOS 10.2.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPhone 6s Plus</td>
      <td>iOS 12.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPhone 7</td>
      <td>iOS 12.0.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPhone 6</td>
      <td>iOS 10.3.1</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>iPod Touch</td>
      <td>iOS 12.0</td>
      <td>LightBlue V2.7</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="10">HUAWEI（华为）</td>
      <td>Huawei nova 3e</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Huawei Honor Enjoy 7X</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Huawei Mate 10</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Huawei P10</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>40%*</td>
      <td>Pass</td>
      <td>The result was 100% when nRF Connect was used, so it should be the problem of LightBlue.</td>
   </tr>
   <tr>
      <td>Huawei Mate 8</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>*</td>
      <td>?</td>
      <td>1. The connection sometimes cannot be broken, you need to restart bluetooth; 2. The onnection can't be established again after encryption, and we recommend starting the encryption from the phone end. </td>
   </tr>
   <tr>
      <td>Huawei P9</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>40%*</td>
      <td>Pass</td>
      <td>1. The app failed to break the connection and the device didn't output log about breaking connection; 2. The app tried to connect the device, but showed:"failed to establish connection to device, please select another device or try again."</td>
   </tr>
   <tr>
      <td>Huawei G9/P9 Lite</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Huawei Honor 8</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>10%*</td>
      <td>Pass</td>
      <td>Two problems in this phone: 1. The connection can't be broken. You need to manually turn off the bluetooth or reset the device to disconnect the bluetooth; 2. If the phone once established encrypted connection with the ESP device that is able to resolve random address, and when the encrypted connection is established again, the connection will break automatically in 30s. But there is no such trouble if the device uses a public address.</td>
   </tr>
   <tr>
      <td>Huawei nova</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Huawei Honor 4X</td>
      <td>Android 5.0.2</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>Sometimes the app cannot break bluetooth connection, so you need to manually switch on and off the bluetooth.</td>
   </tr>
   <tr>
      <td rowspan="2">OPPO（欧珀）</td>
      <td>OPPO A83</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>OPPO R9s</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="8">Xiaomi（小米）</td>
      <td>MIX 2S</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>80%*</td>
      <td>Pass</td>
      <td>1. The pairing page sometimes disappeared; 2. The app was always in connection, but the device didn't output any log indicating the connection was successful.</td>
   </tr>
   <tr>
      <td>Xiaomi Mi Max 2</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Xiaomi 5X</td>
      <td>Android 7.1.2</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Xiaomi Mi Note 2</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>?</td>
      <td></td>
   </tr>
   <tr>
      <td>Xiaomi Redmi Note 4</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Xiaomi Mi 5</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Xiaomi Mi 2A</td>
      <td>Android 4.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>Failed to boot up.</td>
   </tr>
   <tr>
      <td>Xiaomi Mi 3</td>
      <td>Android 4.4.4</td>
      <td>*</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>Failed to install test app.</td>
   </tr>
   <tr>
      <td rowspan="2">vivo（步步高）</td>
      <td>vivo Y85</td>
      <td>Android 8.1.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>vivo X7</td>
      <td>Android 5.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>?</td>
      <td></td>
   </tr>
   <tr>
      <td>LG（乐金）</td>
      <td>LG G5</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>70%*</td>
      <td>Pass</td>
      <td>1. The app failed to break the connection and the device didn't output log about breaking connection; 2. The app tried to connect the device, but showed:"failed to establish connection to device, please select another device or try again."</td>
   </tr>
   <tr>
      <td rowspan="2">Lenovo & Motoria （联想）</td>
      <td>Lenovo S5</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Lenovo K5</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="2">ZTE & Nubia（中兴）</td>
      <td>Nubia Z17 Mini</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>ZTE BA910</td>
      <td>Android 5.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>80%*</td>
      <td>Pass</td>
      <td>Lighblue has poor compatibility and the connection may fail. nRF Connect is highly recommded for testing.</td>
   </tr>
   <tr>
      <td rowspan="3">Gionee（金立）</td>
      <td>Gionee S11</td>
      <td>Android 7.11</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Gionee M7</td>
      <td>The phone was damaged.</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>The test went well when the device used a public address. But if a resovable random address was used, the connection will fail on the second attempt after encryption and the phone sent no "connection request". So we recommend using a public address at the device end when the phone is establishing encrypted connection with the device.</td>
   </tr>
   <tr>
      <td>Gionee GN9004</td>
      <td>Android 4.3</td>
      <td>nRF Connect V4.10*</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>Intallation of LightBlue failed, so nRF Connect was used alternatively.</td>
   </tr>
   <tr>
      <td>Google（谷歌）</td>
      <td>LG Nexus 4*</td>
      <td>Android 5.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td>BLE scan performance of this phone is poor.</td>
   </tr>
   <tr>
      <td>Sony（索尼）</td>
      <td>Sony Xperia XZ</td>
      <td>Android 8.0.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>HTC（宏达电）</td>
      <td>HTC U11</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Essential</td>
      <td>Essential Phone</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="3">Meizu（魅族）</td>
      <td>Meilan Note 3</td>
      <td>Android 5.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Meilan 5s</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>90%*</td>
      <td>Pass</td>
      <td>The app was always in connection, but the device didn't output any log indicating the connection was successful.</td>
   </tr>
   <tr>
      <td>Meilan E</td>
      <td>Android 5.2.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Asus（华硕） </td>
      <td>Asus Z017DA</td>
      <td>Android 7.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>*</td>
      <td>?</td>
      <td>No connection was established on the second attempt.</td>
   </tr>
   <tr>
      <td>Smartisan（锤子）</td>
      <td>Smartisan Nut Pro 2</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Sharp（夏普）</td>
      <td>Sharp AQUOS S3 mini </td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Hisense（海信）</td>
      <td>HiSense Small Dolphin 2（海信小海豚 2）</td>
      <td>Android 7.1.2</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="2">360（奇虎）</td>
      <td>360 N6 Lite</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>360 N5</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="2">Xiaolajiao（小辣椒）</td>
      <td>Red Chilli 4A（红辣椒 4A）</td>
      <td>Android 3.2.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Red Chilli Enjoy 6A（红辣椒畅玩 6A）</td>
      <td>Android 5.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td rowspan="2">Letv（乐视）</td>
      <td>LeTV LeEcoo Le S3</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>LeTV LeEoo Le1 (X600)</td>
      <td>Android 5.0.2</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>?</td>
      <td></td>
   </tr>
   <tr>
      <td>Coolpad（酷派）</td>
      <td>Coolpad Cool 1 dual</td>
      <td>Android 6.0.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Doov（朵唯）</td>
      <td>Doov A15S</td>
      <td>Android 5.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>AGM（艾捷莫）</td>
      <td>AGM X1</td>
      <td>Android 5.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>CMCC（中国移动）</td>
      <td>CMCC N3</td>
      <td>Android 7.1.2</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>Meitu（美图）</td>
      <td>Meitu M8s</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>K-Touch（天语）</td>
      <td>K-Touch X11</td>
      <td>Android 6.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>YEPEN（誉品）</td>
      <td>YEPEN I7S</td>
      <td>Android 6.0</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
      <td>MOTO</td>
      <td>Z2 Paly</td>
      <td>Android 7.1.1</td>
      <td>LightBlue V1.1.3</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>Pass</td>
      <td>100%</td>
      <td>Pass</td>
      <td></td>
   </tr>
   <tr>
</table>      
About the Symbols:
      "*" means there is a note for this item;
      "--" means this item is not tested because of the previous error;
      "?" means this item will be updated in future.
