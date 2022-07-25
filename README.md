# Guci
Conky themes
------------
Display information:
- Date & time
- Weather
- Up times
- Replace MPD with general media player (Spotify, Rhythmbox, Youtube, etc)

Installation
------------
- Install conky</br><pre class="wp-block-preformatted">sudo apt install conky-all playerctl jq curl</pre><p>Next, open your file manager. Press <code>ctrl</code> + <code>h</code> to toggle hidden files on, go to the <code>.config</code> directory and inside of it create a new folder called ‘conky’ (lowercase).</p>
- Install Guci theme</br><p>Download the <a href="https://www.pling.com/p/1864538/" target="_blank" rel="noreferrer noopener">Guci Conky config from Pling</a>. Once the download is complete unpack the archive and move the top level folder (‘Guci’) to the  <code>.config/conky</code> folder. </p><p>You should now be able to open a Terminal and run <code>cd .config/conky/Guci</code>, and launch the Conky theme inside by running <code>./start.sh</code>. </p><p>You need to edit the <code>./config/conky/Guci/scripts/weather.sh</code> script to replace the <code>city_id</code> value with the relevant weather code for your location from <a href="https://openweathermap.org/find" target="_blank" rel="noreferrer noopener">openweathermap.org</a>. <em>If possible</em> do generate your own API key to use with the script (they’re free for personal use). If a lot of people use this script as-is, with the default API key it’ll probably stop working. Remember to save your changes!</p>

Even so:
---
Enjoy this nice Conky.
