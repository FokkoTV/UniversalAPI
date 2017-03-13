# UniversalAPI [on Spigot](https://www.spigotmc.org/resources/universal-api-1-8-x-1-11-x.37723/)

> [] - optional

## ActionBar 1.8 - 1.11
API.sendActionBar(player,message,[duration]);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
  <tr>
    <td>PLAYER</td><td>Player</td><td>Define the player where the BossBar will be set or removed</td><td>org.bukkit.entity.Player</td>
  </tr>
  <tr>
    <td>STRING</td><td>message</td><td>Message wich shoulde be show in the ActionBar you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i></td><td></td>
  </tr>
  <tr>
    <td>INTEGER</td><td>duration</td><td>Set a douration number. How long de Action bar should be send</td><td></td>
  </tr>
</table>

## BossBar 1.9 - 1.11
API.createBossBar(player, text, progress, barstyle, barcolor, barflag, visible);<br>
API.setBarTitle(text);<br>
API.setBarProgress(progress);<br>
API.setBarColor(color);<br>
API.setBarStyle(style);<br>
API.addBarFlag(flag);<br>
API.setBarVisibility(visible);<br>
API.removeBarFlag(flag);<br>
API.removeBossBar(player);<br>
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
  <tr>
    <td>PLAYER</td><td>Player</td><td>Define the player where the BossBar will be set or removed</td><td>org.bukkit.entity.Player</td>
  </tr>
  <tr>
    <td>STRING</td><td>Text</td><td>Message wich shoulde be show on the BossBar you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i></td><td></td>
  </tr>
  <tr>
    <td>DOUBLE</td><td>Progress</td><td>Set the Progress from the BossBar (0.0 - 1.0)</td><td></td>
  </tr>
  <tr>
    <td>BARSTYLE</td><td>Barsytle</td><td>Set the BossBar Style</td><td>org.bukkit.boss.BarStyle</td>
  </tr>
  <tr>
    <td>BARCOLOR</td><td>Barcolor</td><td>Set the BossBar Color</td><td>org.bukkit.boss.BarColor</td>
  </tr>
  <tr>
    <td>BARFLAG</td><td>Barflag</td><td>Set the BossBar Flag</td><td>org.bukkit.boss.BarFlag</td>
  </tr>
  <tr>
    <td>BOOLEAN</td><td>Visible</td><td>Set the visibility for the BossBar</td><td></td>
  </tr>
</table>

## EntityGlow 1.8 - 1.11
API.addEntityGlow(entity);<br>
API.removeEntityGlow(entity);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
  <tr>
    <td>ENTITY</td><td>entity</td><td>Set the Entity Wich should get the Entity Glow Effect </td><td>org.bukkit.entity.Entity</td>
  </tr>
</table>

## HeadSpawner 1.8 - 1.11
API.spawnHead(location,owner);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
  <tr>
    <td>LOCATION</td><td>Location</td><td>Define the location where the Head should be spawned</td><td>org.bukkit.Location</td>
  </tr>
  <tr>
    <td>STRING</td><td>owner</td><td>Define the Head owner with the Player Name</td><td></td>
  </tr>
</table>

## Hologramm 1.8 - 1.11
API.createHolo(location,lines);<br>
API.setHoloPlayers(players);<br>
API.removeHoloPlayers(players);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
   <tr>
    <td>PLAYER</td><td>Player</td><td>Define the player wich can see the Hologramm oder wich can't</td><td>org.bukkit.entity.Player</td>
  </tr>
  <tr>
    <td>LOCATION</td><td>Location</td><td>Define the location where the Hologram should be spawned</td><td>org.bukkit.Location</td>
  </tr>
  <tr>
    <td>LIST(STRING)</td><td>lines</td><td>Message wich shoulde be show in the ActionBar you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i></td><td>java.util.List</td>
  </tr>
</table>

## ItemGlowEffect 1.8 - 1.11
API.createItemGlow(itemmeta);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
   <tr>
    <td>ITEMMETA</td><td>itemmeta</td><td>Define a ItemMeta wich should get the Glow Effect</td><td>org.bukkit.inventory.meta.ItemMeta</td>
  </tr>
</table>

## Ping 1.8 - 1.11
API.getPing(player);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
   <tr>
    <td>PLAYER</td><td>Player</td><td>Define the Player where you want to get the Ping from</td><td>org.bukkit.entity.Player</td>
  </tr>
</table>

## Tablist 1.8 - 1.11
API.sendTablist(player,header,footer);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
   <tr>
    <td>PLAYER</td><td>Player</td><td>Define the player wich should revice the Tablist</td><td>org.bukkit.entity.Player</td>
  </tr>
  <tr>
    <td>STRING</td><td>Header</td><td>Define the message from the TabList Header you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i> or make a new line with <i>\n</i></td><td></td>
  </tr>
  <tr>
     <td>STRING</td><td>Footer</td><td>Define the message from the TabList Footer you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i> or make a new line with <i>\n</i></td><td></td>
  </tr>
</table>

## Title 1.8 - 1.11
API.sendTitle(player,title,fadein,stay,fadeout,subtitle,fadein,stay,fadeout);
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td><td><h3>Import</h3></td>
  </tr>
   <tr>
    <td>PLAYER</td><td>Player</td><td>Define the player wich should revice the Title</td><td>org.bukkit.entity.Player</td>
  </tr>
  <tr>
    <td>STRING</td><td>Title</td><td>Define the message wich should be show in the title you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i></td><td></td>
  </tr>
  <tr>
    <td>STRING</td><td>SubTitle</td><td>Define the message wich should be show in the subtitle you can user colors with <i>§</i> or <i>ChatColor.translateAlternateColorCodes()</i></td><td></td>
  </tr>
  <tr>
     <td>INTEGER</td><td>fadein</td><td>Time the title fades in</td><td></td>
  </tr>
  <tr>
     <td>INTEGER</td><td>stay</td><td>Time the title Stays on the Screen</td><td></td>
  </tr>
  <tr>
     <td>INTEGER</td><td>fadeout</td><td>Time the title fades ou</td><td></td>
  </tr>
</table>

## Ping 1.8 - 1.11
API.getTPS(ticks)
<table>
  <tr>
    <td><h3>Type</h3></td><td><h3>Name</h3></td><td><h3>Description</h3></td>
  </tr>
   <tr>
    <td>INTEGER</td><td>Ticks</td><td>Shows the Ticks per Second</td>
  </tr>
</table>
