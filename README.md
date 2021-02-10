![](https://raw.githubusercontent.com/LinhNC/XPS9570-OpenCore/main/Capture.png)
<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="XPS9570OpenCore_0"></a>XPS9570 OpenCore</h1>
<p class="has-line-data" data-line-start="1" data-line-end="3">XPS 9570 Hackintosh with OpenCore 0.6.5<br>
macOS Catalina (10.15.7) to BigSur (11.1) on a Dell XPS 9570 with Touch 4k Screen</p>
<blockquote>
<p class="has-line-data" data-line-start="4" data-line-end="6">macOS Catalina: 10.15.4 - 10.15.7<br>
macOS BigSur: 11.1</p>
</blockquote>

<h4 class="code-line" data-line-start=7 data-line-end=8 ><a id="Hardware_configuration_7"></a>My hardware configuration:</h4>
<p class="has-line-data" data-line-start="8" data-line-end="18">Dell XPS 9570<br>
CPU: Intel i5-8300<br>
Memory: ADATA 2400 8G X2<br>
Display: 1080P<br>
SSD: HP S700<br>
Trackpad: Synaptics SYNA2393<br>
Touchscreen: Wacom WCOM488F<br>
Sound: Realtek ALC3266 (similar to ALC298)<br>
Wifi Card: replaced with intel ax200 (https://github.com/OpenIntelWireless/itlwm)<br>
Battery: Dell 6GTPY battery (11.4V, 8083mAh, 97Wh stated capacity, reports as 7488mAh)</p>
<h4 class="code-line" data-line-start=18 data-line-end=19 ><a id="Software_environment_18"></a>Software environment:</h4>
<p class="has-line-data" data-line-start="19" data-line-end="21">macOS dual-booting with Windows 10<br>
DELL BIOS: 1.17.1</p>
Specical Thanks To @xxxzc
<br>
<blockquote>
For 1080p Screen need to modify your config.plist:<br>
- Find uiscale and change its value to AQ== <br>
- Find dpcd-max-link-rate and change its value to CgAAAA==<br>
</blockquote>



