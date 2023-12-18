# Window Buttons Applet

This is a Plasma 5 applet that shows window buttons in your panels. This plasmoid is coming from [Latte land](https://phabricator.kde.org/source/latte-dock/repository/master/) but it can also support Plasma panels.

<p align="center">
<img src="https://i.imgur.com/4FItfte.gif" width="580"><br/>
<i>slide in/out animation</i>
</p>

<p align="center">
<img src="https://i.imgur.com/70qeMME.png" width="580"><br/>
<i>Breeze decoration</i>
</p>

<p align="center">
<img src="https://i.imgur.com/uEen6P0.png" width="580"><br/>
<i>BreezeEnhanced decoration</i>
</p>

<p align="center">
<img src="https://i.imgur.com/Zz20RXC.png" width="580"><br/>
<i>Settings window</i>
</p>

# Requires

- Qt >= 5.9
- KF5 >= 5.38
- Plasma >= 5.23.2
- KDecoration2 >= 5.23

**Qt elements**: Gui Qml Quick

**KF5 elements**: CoreAddons Declarative Plasma PlasmaQuick extra-cmake-modules


# Install
<h4>opensuse</h4>
```
1: open unstable branch
2: install kf6-extra-cmake-modules
3: install libQt6Quick3DAssetImport6 libQt6Quick3DAssetUtils6 libQt6Quick3DGlslParser6 libQt6Quick3DIblBaker6 libQt6Quick3DParticles6 libQt6QuickTimeline6 qt6-quick3d
4: install qt6-opengl-devel qt6-qmlmodels-devel qt6-quick-devel
5: install kf6-ksvg-devel
6: install kf6-kconfig-devel kf6-kcoreaddons-devel kf6-kdeclarative-devel qt6-xml-devel
7: install kf6-kpackage-devel
8: install kf6-kwindowsystem-devel plasma6-framework-devel
9: install kf6-kcmutils-devel kf6-kcodecs-devel kf6-kcolorscheme-devel kf6-kconfigwidgets-devel kf6-kguiaddons-devel kf6-ki18n-devel kf6-kwidgetsaddons-devel
10: install kf6-kservice-devel
```
You can execute `sh install.sh` in the root directory as long as you have installed the previous mentioned development packages. For more details please read [INSTALLATION.md](/INSTALLATION.md)
