# LibGdx In-Game Console
This is a LibGdx library that allows a developer to add a console (similar to how it is featured in Source games) to their game. Check out the [Javadocs and changelog](http://strongjoshua.com/projects/games/in-game_console)! If you want to discuss the library without posting an issue, you can do so on the [forums](http://strongjoshua.com/forums/viewforum.php?f=6)!

###How it works
Essentially what the console allows you to do is specify commands that you will be able to access from within the game, using the console. The console also enables live logging from within the application.

###Purpose
This console speeds up development substantially by removing the need to recompile a program every time a minute change is made, specifically in regard to manipulating constants or other values when balancing a game, for example.

### Integration
#### Gradle
Add the following line to your build.gradle file under the dependencies section of the **core** project:  
`compile "com.strongjoshua:libgdx-inGameConsole:{version}"`  
Replace **{version}** with the newest version number!

Then simply right-click the project and choose `Gradle->Refresh All`.

#### Maven
Right-click on your project and choose `Maven->Add Dependency` and search for `strongjoshua`. Make sure to choose the most recent version if multiple appear!

#### Eclipse
First, clone this project to your computer and [add it to Eclipse](http://www.eclipse.org/forums/index.php/t/226301/). Then simply click on your project, and choose `Build Path->Configure Build Path`. Then go to `Projects->Add` and add the cloned project.

### Contributing
Contributions are always welcome, especially if they fix an **Issue**.  
If you are in the [contributors](https://github.com/StrongJoshua/libgdx-inGameConsole/graphs/contributors) tab and would like to be credited for your work please edit the [pom.xml](https://github.com/StrongJoshua/libgdx-inGameConsole/blob/master/pom.xml) file and add yourself to the contributors section using the [Apache guidelines](http://maven.apache.org/pom.html#Contributors).

Versions
========
Latest Stable: **0.5.0**  
Latest Snapshot:
###How the Numbers Work
####First Digit
This digit goes up whenever I feel that the project has reached a milestone and/or no longer resembles the first version in it's current digit (e.g.: 0.13.3 is completely different from 0.1.0).
####Second Digit
This digit goes up whenever a new feature is added, but if two or more features are added in one group of updates, this digit will still only rise by one. This number resets to 0 when the first digit goes up.
####Third Digit
This digit goes up whenever a bugfix is released. This number resets to 0 when the second digit goes up.

License
=======
Copyright 2015

Licensed under the Apache License, Version 2.0 (the "License");
you may not use these files except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
