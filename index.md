---
layout: default
title:  "Alex' Projects"
date:   2017-05-10 20:31:00 +0200
---

# Alex' Projects

[**► GitHub Profile**](https://github.com/albar965)

**All my projects, releases, source code, issue lists and more.**

[**► GitBook Online Manuals**](https://www.gitbook.com/@albar965)

**Online manuals for all programs with version equal or above 1.2.**

[**► Support Forum at Avsim**](http://www.avsim.com/forum/780-little-navmap-little-navconnect-little-logbook-support-forum)

**Help for users, preview of new releases, development progress, screenshots and beta releases.**


## News
<p>
  {% for post in site.posts %}
    <p>
      <span class="bold">{{ post.date | date_to_long_string }} - <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></span>
    </p>
  {% endfor %}
</p>

## A small Promotion

**All my projects will remain free and open source.**

I am not asking for donations, but if you're into German Science Fiction have a look at my wife's novel [**Alkatar**](http://www.anja-fahrner.de/meine-buecher-und-geschichten/alkatar) or short story [**Die Erben der Verbannten**](http://www.anja-fahrner.de/die-erben-der-verbannten).

---

Ich möchte keine Spenden, würde mich aber darüber freuen, wenn ihr euch das Projekt meiner Frau anschaut. Sie schreibt gesellschaftskritische Science-Fiction.

Vielleicht ist etwas zum Verschenken oder für Euch selbst dabei.

![Alkatar und Die Erben der Verbannten](assets/images/alkatar_und_erben.jpg) Das Buch [**Alkatar**](http://www.anja-fahrner.de/meine-buecher-und-geschichten/alkatar) oder die Kurzgeschichte [**Die Erben der Verbannten**](http://www.anja-fahrner.de/die-erben-der-verbannten).

## Little Navmap

[![Little Navmap](assets/images/navroute.png)](littlenavmap.html) [**► Little Navmap**](littlenavmap.html) is a free open source flight planner, navigation tool, moving map, airport search and airport information system for Flight Simulator X and Prepar3D.

**Supported Flight Simulators:** All FSX versions from SP2 up, Flight Simulator - Steam Edition, Prepar3D v2 and Prepar3D v3.
**Supported platforms:** Windows 7/8/10, Linux (Ubuntu and derived) and macOS.

**Windows XP is not supported.**

## Little Navconnect

[![Little Navconnect](assets/images/navconnect.png)](littlenavconnect.html) [**► Little Navconnect**](littlenavconnect.html) is a
small free open source application that acts as an agent connecting Little Navmap with a flight simulator. This allows to use Little Navmap
on Linux or Mac and saves the the pain of setting up remote SimConnect links.

**Supported Flight Simulators:** All FSX versions from SP2 up, Flight Simulator - Steam Edition, Prepar3D v2 and Prepar3D v3.
**Supported platforms:** Windows 7/8/10. SimConnect installation needed.

**Windows XP is not supported.**

## Little Logbook

[![Little Logbook](assets/images/logbook.png)](littlelogbook.html) [**► Little Logbook**](littlelogbook.html) is a view and extraction program
for the FSX logbook. It allows fast and intuitive search and grouping of logbook entries based on several parameters, as well as export to HTML,
CSV and Google Earth KML documents. Additional information about airports can be shown together with the MakeRunways Utility by Peter Dowson.

**Supported platforms:** Windows XP/7/8/10.
