## <font color='red'>If you are using v0.9.6 or later, Please check <a href='http://code.google.com/p/monomeemu/wiki/OperatingInstructions'>operating instructions</a>.</font> ##

<br>
<br>
<br>
<br>

<h1>Supporting osc protocols</h1>
<hr />
<table><thead><th>/press</th></thead><tbody>
<tr><td>/led  </td></tr>
<tr><td>/led_row</td></tr>
<tr><td>/led_col</td></tr>
<tr><td>/frame</td></tr>
<tr><td>/clear</td></tr>
<tr><td>/sys/prefix</td></tr></tbody></table>

<br>
<br>

<h1>In order to use 7up you'll need to do the following</h1>
<hr />
1. load monomeEmu device, and you select launchpad and user2 mode.<br>
2. set Prefix'7up' on monomeEmu.<br>
3. load sevenUpCore device, and you click 'start/stop connections' button only once.<br>
<br>

<del>In monome vertual grid size setting, Please select 'monome64'.</del><br>
<del>monomeemu dose not use the multicolor protocol.</del><br>
<del>(but I'm planing...)</del><br>
v0.9.2 or later, support mutliColorDevice option of 7up.<br>
"monome64" and "multiColorDevice" can be used either.<br>
<br>
7up will working with monomeEmu correctly.<br>
when you can not change nav menu, please check max window on M4L.<br>
if java exceptions or Errors string is occured, please reboot your live.<br>

udp(osc) server initializing process on 7up is slow.<br>
when you click 'start/stop connections' button repeatedly, Java Exception will throw.<br>
old osc process would continue to send packet.<br>

<br>
<br>