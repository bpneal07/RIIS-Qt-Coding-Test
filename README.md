Documentation for RIIS Coding Test
1. Look up documentation on how to install QGC.
2. Install Qt version 6.10.1
3. Install dependencies.
4. Clone Git repo for QGC.
5. Open CMake list inside of QGC.
6. Grep-R to search for QML files.
7. Locate main pages within QGC.
8. Placed logo in Resource folder within project.
9. Look through QGC toolbar button.qml to see how the original image was set up.
10. Once I noticed that button.icon.source contained the image source, I did a search all for icon.source.
11. I noticed the icon.source was used in several places. 
12. I found the QGC resources.qml was the location where file aliases were set up.
13. So I created an alias for the RIIS company logo.
14. I started replacing the original logo in FlyViewToolbar.qml, MainWindow.qml, and PlainViewToolbar.qml.
15. Resized the canvas for the RIIS black company logo, so it's centered.
