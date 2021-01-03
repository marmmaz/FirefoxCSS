<h2 align="center">minimalFOX</h2>

<h4 align="center">A compact & minimal Firefox theme built for macOS.</h4>
<p align="center"><img width='770px' src="https://i.imgur.com/oFOo3lO.png"></img></p1>

<h4 align="center">Hidden toolbar, reveal it by hovering over it with your cursor.</h4>
<p align="center"><img src="https://res.cloudinary.com/dhnodbdcr/image/upload/v1609679736/screencast_2021-01-03_14-13-48_i3lhn8.gif"></img></p>

<h4 align="center">Clean, color matching context menus, sidebars and tooltips.</h4>
<p align="center"><img width ='500px' src="https://i.imgur.com/gYnNDKm.png"></img></p1>

<h4>Steps for applying this configuration</h4>
<ol>
  <li>Type about:profiles into your urlbar, accept the displayed warning.</li>  
  <li>Open the root directory folder found on the page.</li>  
  <li>Inside this folder, create a folder named "chrome".</li>  
  <li>Add the userChrome.css file from this repo your new "chrome" folder.</li>  
  <li>Type about:config into your urlbar and go to the page</li>
  <li>Paste "toolkit.legacyUserProfileCustomizations.stylesheets" into the search bar and set its value to true</li>
  <li>Restart Firefox.</li>
  <li>Done!</li>
</ol>

<h4 align="center">Navbar Layout</h4>
<p align="center">Right click on the bar and select customize</h5>
<p align="center"><img src="https://i.imgur.com/IDxoP4o.png"></img></p>

<p align="center">At the bottom of the window, click on Density and select Compact.</p>
<p align="center"><img src="https://i.imgur.com/0ZBHZS4.png"></img></p>

<p align="center">Finally add/remove shortcuts/extensions/spaces via drag and drop.</p>
<p align="center"><img src="https://i.imgur.com/Mv8Jwrs.png"></img></p>

<h4>about:config tweaks</h4>
<ul>
  <li>full-screen-api.approval-required = false</li>
  <li>full-screen-api.warning.delay = 0</li>
  <li>full-screen-api.warning.timeout = 0</li>
  <li>full-screen-api.transition-duration.enter = 0 0</li>
  <li>full-screen-api.transition-duration.leave = 0 0</li>
  <li>browser.tabs.loadBookmarksInTabs = true</li>
  <li>browser.tabs.loadBookmarksInBackground = true</li>
  <li>browser.tabs.tabMinWidth = 50</li>
  <li>extensions.pocket.enabled = false</li>
  <li>extensions.screenshots.disabled = true</li>
  <li>ui.prefersReducedMotion = 1</li>
</ul>
