<h2 align="center">minimalFOX</h2>

<h4 align="center">A compact & minimal Firefox theme build for macOS.</h4>
<p align="center"><img src="https://i.imgur.com/oFOo3lO.png"></img></p1>

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

<h4>about:config tweaks</h4>
<ul>
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
