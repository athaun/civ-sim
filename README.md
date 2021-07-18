<p>
    <br />
    <img src="https://img.shields.io/badge/Made%20using-Java-red">
    <img src="https://img.shields.io/badge/Made%20Using-Open%20GL%20-yellow">
    <img src="https://img.shields.io/badge/Version-0.4-blue">
    <img src="https://img.shields.io/badge/Platforms-Windows, Linux-lightgrey">
</p>

<img src="./civSim.png">
<br>

## Prerequisites
* OpenGL capable graphics card (minimum `core 330`)
* OpenGL capable graphics driver
  * Linux nouveau drivers for nvidia cards do not currently work, you will have to install proprietary drivers.
  * FOSS AMD Drivers for linux do work.

Clone:
`git clone https://github.com/athaun/civ-sim.git`
* Terminal:
  cd into `civ-sim`
  1) Build: `./gradlew fatJar`
  2) Run: `java -jar ./build/libs/CivSim-1.0-SNAPSHOT-all.jar `
* Eclipse:
  idk lol
* Intellj:
  Select `File > new project > project from existing sources`
  Import as a gradle project and wait for it to download dependancies
  Find `main/java/Gprocessing/civ/CivScene.java`, right click it and run

### License
Copyright (c) 2020 Asher Haun and Ethan Grandin MIT License
See [LICENSE](https://github.com/athaun/civ-sim/blob/main/LICENSE) for more information.

### Contact
Discord: `Asher#6411`

### Credits
* Games With Gabe on Youtube for his [amazing tutorial series](https://www.youtube.com/channel/UCQP4qSCj1eHMHisDDR4iPzw/videos) on building a java game engine.
* Java ImGui bindings from [SpaiR/imgui-java](https://github.com/SpaiR/imgui-java)
