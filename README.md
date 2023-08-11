// ==UserScript==
// @name         Settings!
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       Draxh
// @match        https://cellcraft.io/
// @icon         https://www.google.com/s2/favicons?sz=64&domain=cellcraft.io
// @grant        none
// ==/UserScript==
//RainbowMenuPanel
function keybindInfo() {
var body = document.querySelector("body");
var container = document.createElement("div");
    container.style.zIndex="10"; container.style.marginTop="125px"; container.style.position="absolute"; container.style.border="2px solid white"; container.style.borderRadius="7px"; container.style.color="white"; container.style.padding="10px";
    container.innerHTML = '<p> Freeze, Virus and Anti Rec: 1</p><p> Anti Rec: 2</p><p>Freeze and Virus: 3</p><p>Mothercell: 4</p><p>Recombine: 5</p><p>Speed: 6 </p><p>Portal: 7</p><p>Growth: C</p><p>Anti-Freze: V</p><p>Toggle Bots: Q</p><p>Split Bots: A</p><p>Feed Bots: X</p><p style="color: gold">MultiDrop & Bots Settings</p>';
    body.appendChild(container);
}
keybindInfo()
