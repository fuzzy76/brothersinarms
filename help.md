---
layout: biapage
path: help
title: Help
---

<div class="accordion" id="accordionExample">
  <div class="card">
    <div class="card-header" id="headingOne">
      <h2 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Installing CoD:UO
        </button>
      </h2>
    </div>

    <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordionExample">
      <div class="card-body">
<ol>
<li>Install <a href="https://store.steampowered.com/sub/222/">Call of Duty and the expansion pack United Offensive</a>.</li>
<li>Start the game and enter multiplayer options. Choose a playername and enable downloads from server.</li>
<li>Enter the multiplayer serverlist. Select favorites for view.</li>
<li>Add the server with any name you'd like and the address "coduo.brothersinarms.no". Ensure filters shows non-pure servers and servers without Punkbuster. Refresh and verify that the server seems online.</li>
<li>Doubleclick the server and the fun begins! :)</li>
</ol>
<p>Or if you do a "manual" install:</p>
<ul>
<li><a href="http://thepiratebay.org/torrent/5943445">Direct download if you have a cd-key but no media</a></li>
<li><a href="http://callofduty.filefront.com/file/Call_of_Duty_United_Offensive_151_Patch;36116">Upgrade to 1.51</a></li>
<li><a href="http://www.gamefront.com/files/CoD_United_Offensive_Map_Pack/;3771736;;/fileinfo.html">Official CoD:UO map pack, if you don't want to load maps when needed</a></li>
</ul>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingTwo">
      <h2 class="mb-0">
        <button class="btn btn-link collapsed" type="button" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          CoD:UO in widescreen
        </button>
      </h2>
    </div>
    <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
      <div class="card-body">
<p>Find and edit the following config file with notepad: C:\Program Files\Call of Duty\uo\uoconfig_mp.cfg
 (For W7 and newer it is in C:\Users\yourusername\AppData\Local\VirtualStore\Program Files (x86)\Call of Duty\uo\uoconfig_mp.cfg</p>
<p>All of the following commands need to be changed in the file (they are already there but with different values - if cg_fov i missing, just add it). Obviously only one of 16:9 or 16:10 needs to be done, depending on your screen. Replace 1440 and 900 with your monitor resolution (1920 and 1200 for me).</p>
<p>For a 16:9 Aspect Ratio Resolution: (usually for widescreen TV)</p>
<code><pre>seta cg_fov 96.4183
seta r_mode -1
seta r_customheight 900
seta r_customwidth 1440</pre></code>
<p>For a 16:10 Aspect Ratio Resolution: (usually for widescreen pc monitor)</p>
<code><pre>seta cg_fov 90.3951
seta r_mode -1
seta r_customheight 900
seta r_customwidth 1440</pre></code>
<p>Once done, when you go in the game menu, it may not show the correct resolution in the options, but it will be in game. Do not change your resolution in the game. If you do, you will lose widescreen, and have to do this all over again.</p>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingThree">
      <h2 class="mb-0">
        <button class="btn btn-link collapsed" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Punkbuster problems
        </button>
      </h2>
    </div>
    <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
      <div class="card-body">
<ol>
<li>Download and run PunkBuster Service Installer from <a href="http://www.evenbalance.com/downloads.php">http://www.evenbalance.com/downloads.php</a></li>
<li>Download cod_pb.zip from <a href="http://www.callofdutyview.net/downloads/call-of-duty-punkbuster-downloads/">http://www.callofdutyview.net/downloads/call-of-duty-punkbuster-downloads/</a>, extract it and replace your original pb folder with the one from the zip file.</li>
</ol>
<dl>
<dt>Problem: PunkBuster is not running.</dt>
<dd>Solution: Try running the game as administrator, by right-clicking on the shortcut and select "Run as administrator"</dd>
<dt>Problem: PunkBuster complains about files with "d3d" in their name being corrupt.</dt>
<dd>Solution: Reinstall DirectX from <a href="http://www.microsoft.com/en-us/download/details.aspx?id=35">http://www.microsoft.com/en-us/download/details.aspx?id=35</a></dd>
<dt>Problem: PunkBuster says I'm banned! I swear I'm not a cheater!</dt>
<dd>Solution: Create a post in the general part of the forum, and we'll take it from there. But we only remove bans, we don't whitelist. If PunkBuster doesn't like your computer, neither do we.</dd>
</dl>
<p>Some other links:</p>
<ul>
<li><a href="https://answers.ea.com/t5/Battlefield-Hardline/Punkbuster-Guide/td-p/4390461">https://answers.ea.com/t5/Battlefield-Hardline/Punkbuster-Guide/td-p/4390461</a></li>
<li><a href="http://www.funteamgermany.de/?path=download&contentid=21&catid=4&themeid=0">http://www.funteamgermany.de/?path=download&contentid=21&catid=4&themeid=0</a></li>
</ul>
      </div>
    </div>
  </div>
</div>