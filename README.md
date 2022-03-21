### Modulepath
JreSE-17

### Javafx Version
17

### Eclipse VM Arguments

--module-path "C:\Program Files\Eclipse Adoptium\openjfx-17.0.2_windows-x64_bin-sdk\javafx-sdk-17.0.2\lib" --add-modules=javafx.controls,javafx.graphics,javafx.fxml,javafx.web
--add-opens=javafx.graphics/javafx.scene=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.css=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.util=ALL-UNNAMED
--add-exports=javafx.base/com.sun.javafx.reflect=ALL-UNNAMED
--add-exports=javafx.base/com.sun.javafx.beans=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.scene=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.sg.prism=ALL-UNNAMED
--add-exports=javafx.base/com.sun.javafx.logging=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.prism=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.glass.ui=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.geom.transform=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.tk=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.glass.utils=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.font=ALL-UNNAMED
--add-exports=javafx.controls/com.sun.javafx.scene.control=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.scene.input=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.application=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.geom=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.iio=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.prism.paint=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.scenario.effect=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.scenario.effect.impl=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.scenario.effect.impl.prism=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.text=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.scene=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.scene.text=ALL-UNNAMED
--add-exports=javafx.graphics/javafx.scene.paint=ALL-UNNAMED
--add-exports=javafx.controls/com.sun.javafx.scene.control.behavior=ALL-UNNAMED
--add-exports=javafx.controls/com.sun.javafx.scene.control.inputmap=ALL-UNNAMED
--add-exports=javafx.graphics/com.sun.javafx.scene.traversal=ALL-UNNAMED

# DockFX [![Build Status](https://goombert.visualstudio.com/DockFX/_apis/build/status/RobertBColton.DockFX?branchName=master)](https://goombert.visualstudio.com/DockFX/_build/latest?definitionId=1&branchName=master)
<table>
<tr>
<th><img src="http://sites.psu.edu/robertbcolton/wp-content/uploads/sites/19608/2014/10/dockfxhover.png" ></th>
<th><img src="http://sites.psu.edu/robertbcolton/wp-content/uploads/sites/19608/2014/10/dockfxdocked.png" ></th>
</tr>
</table>

## About
This library was created to fill the void for docking frameworks available in the JavaFX RIA platform. Its intention is to provide you with a fully featured docking library. This project and its source code is licensed under the [Mozilla Public License version 2](https://www.mozilla.org/en-US/MPL/2.0/) and you should feel free to make adaptations of this work. Please see the included LICENSE file for further details.

DockFX has a number of features:
* Full documentation
* Gratis and open source
* CSS and styling support

Features to be added in a to be determined future version:
* FXML support
* Scene builder integration
* DockBar support for floating toolbars
* Tab pane stacking of dock nodes with draggable headers
* A light docking library using no detachable windows

## Using the Library
You can obtain a binary of the latest jar from the [releases](https://github.com/RobertBColton/DockFX/releases) page. The library itself includes a demo as the main class for testing purposes. This demo is always included for the time being as it is very small and not expected to get much bigger. An HTML readme file is included next to the jar but does not need to be distributed with the library. The library and the demo will also work regardless of whether the readme HTML file exists. You should be able to add the library to your class path and use it like any normal library.

## Compiling from Source
The project was originally written in the Eclipse IDE but is also configured for Apache Maven. The project will continue to facilitate development with both command line tools and the Eclipse IDE. Default icons are included from the [Calico icon set](https://github.com/enigma-dev/Calico-Icon) for the dock indicators and title bar.

## Contributing
Adaptations of the project are welcome but you are encouraged to send fixes upstream to the master repository. I use the [Google Java style conventions](https://github.com/google/styleguide) which you can download an Eclipse plugin for. After importing the Eclipse formatter you can use CTRL+SHIFT+F to run the formatter on your code. It is requested that commits sent to this repository follow these conventions. Please see the following [link](https://github.com/HPI-Information-Systems/Metanome/wiki/Installing-the-google-styleguide-settings-in-intellij-and-eclipse) for instructions on configuring the Google style conventions with the Eclipse or IntelliJ IDE.
