# List of Awesome Flutter Packages
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/leisim/awesome-flutter-packages) [![Travis](https://travis-ci.com/leisim/awesome-flutter-packages.svg?branch=master)](https://travis-ci.com/leisim/awesome-flutter-packages)


A curated list of awesome Flutter packages. These are some of the most valuable gems of the Flutter community.

Is your favourite package missing? Let me know or create a pull request...

## Index
- [Widgets](#Widgets)
- [Animations](#Animations)
- [Images](#Images)
- [Swipe & Slide](#Swipe--Slide)
- [Dialogs & Pickers](#Dialogs--Pickers)
- [Input & Forms](#Input--Forms)
- [Device](#Device)
- [Networking](#Networking)
- [Bluetooth & Wifi](#Bluetooth--Wifi)
- [Utils](#Utils)
- [Frameworks & Design Patterns](#Frameworks--Design-Patterns)
- [Audio & Video](#Audio--Video)
- [Files](#Files)
- [Persistance](#Persistance)
- [Logging & Error Handling](#Logging--Error-Handling)

<br>

# Widgets

## WebView for Flutter (Flutter Team) [![](https://img.shields.io/pub/v/webview_flutter.svg)](https://pub.dartlang.org/packages/webview_flutter) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/webview_flutter) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/webview_flutter)

A Flutter plugin that provides a WebView widget on Android and iOS.

On iOS the WebView widget is backed by a `WKWebView`; On Android the WebView widget is backed by a `WebView`.

---

## Splash Screen [![](https://img.shields.io/pub/v/splashscreen.svg)](https://pub.dartlang.org/packages/splashscreen) [![](https://img.shields.io/github/last-commit/KarimMohamed2005/SplashScreenFlutterPackage.svg)](https://github.com/KarimMohamed2005/SplashScreenFlutterPackage) [![](https://img.shields.io/github/stars/KarimMohamed2005/SplashScreenFlutterPackage.svg?style=social)](https://github.com/KarimMohamed2005/SplashScreenFlutterPackage)

Easy to use splash screen package.

<img src="images/splashscreen1.png" height="250px">

---

## auto_size_text [![](https://img.shields.io/pub/v/auto_size_text.svg)](https://pub.dartlang.org/packages/auto_size_text) [![](https://img.shields.io/github/last-commit/leisim/auto_size_text.svg)](https://github.com/leisim/auto_size_text) [![](https://img.shields.io/github/stars/leisim/auto_size_text.svg?style=social)](https://github.com/leisim/auto_size_text)

Flutter widget that automatically resizes text to fit perfectly within its bounds.

<img src="images/auto_size_text1.gif" width="500px">

---

## Flutter Sticky Headers [![](https://img.shields.io/pub/v/sticky_headers.svg)](https://pub.dartlang.org/packages/sticky_headers) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter_sticky_headers.svg)](https://github.com/fluttercommunity/flutter_sticky_headers) [![](https://img.shields.io/github/stars/fluttercommunity/flutter_sticky_headers.svg?style=social)](https://github.com/fluttercommunity/flutter_sticky_headers)

Lets you place headers on scrollable content that will stick to the top of the container whilst the content is scrolled.

<img src="images/sticky_headers1.gif" width="300px">

---

## Flutter Speed Dial [![](https://img.shields.io/pub/v/flutter_speed_dial.svg)](https://pub.dartlang.org/packages/flutter_speed_dial) [![](https://img.shields.io/github/last-commit/darioielardi/flutter_speed_dial.svg)](https://github.com/darioielardi/flutter_speed_dial) [![](https://img.shields.io/github/stars/darioielardi/flutter_speed_dial.svg?style=social)](https://github.com/darioielardi/flutter_speed_dial)

Flutter plugin to implement a beautiful and dynamic Material Design Speed Dial, with labels, animated icons and hide on scrolling.

![](images/flutter_speed_dial1.gif)

---

## Flutter Platform Widgets [![](https://img.shields.io/pub/v/flutter_platform_widgets.svg)](https://pub.dartlang.org/packages/flutter_platform_widgets) [![](https://img.shields.io/github/last-commit/aqwert/flutter_platform_widgets.svg)](https://github.com/aqwert/flutter_platform_widgets) [![](https://img.shields.io/github/stars/aqwert/flutter_platform_widgets.svg?style=social)](https://github.com/aqwert/flutter_platform_widgets)

Simplifying the use of both Material and Cupertino widgets with a single widget.

```dart
PlatformWidget(
  ios: (_) => Icon(CupertinoIcons.flag),
  android: (_) => Icon(Icons.flag),
);
```

```dart
PlatformButton(
  onPressed: () => print('send'),
  child: PlatformText('Send'),
);
```

```dart
PlatformAlertDialog(
  title: Text('Alert'),
  content: Text('Some content'),
  actions: <Widget>[
    PlatformDialogAction(),
    PlatformDialogAction(),
  ],
);
```
etc.


---

## flutter_staggered_grid_view [![](https://img.shields.io/pub/v/flutter_staggered_grid_view.svg)](https://pub.dartlang.org/packages/flutter_staggered_grid_view) [![](https://img.shields.io/github/last-commit/letsar/flutter_staggered_grid_view.svg)](https://github.com/letsar/flutter_staggered_grid_view) [![](https://img.shields.io/github/stars/letsar/flutter_staggered_grid_view.svg?style=social)](https://github.com/letsar/flutter_staggered_grid_view)

A Flutter staggered grid view which supports multiple columns with rows of varying sizes.

![](images/flutter_staggered_grid_view1.png)

---

## FancyBottomNavigation [![](https://img.shields.io/pub/v/fancy_bottom_navigation.svg)](https://pub.dartlang.org/packages/fancy_bottom_navigation) [![](https://img.shields.io/github/last-commit/tunitowen/fancy_bottom_navigation.svg)](https://github.com/tunitowen/fancy_bottom_navigation) [![](https://img.shields.io/github/stars/tunitowen/fancy_bottom_navigation.svg?style=social)](https://github.com/tunitowen/fancy_bottom_navigation)

An animated Bottom Navigation Bar for Flutter apps, icon animates into place, colors are customisable.

![](images/fancy_bottom_navigation1.gif)

---

## Liquid Pull To Refresh [![](https://img.shields.io/pub/v/liquid_pull_to_refresh.svg)](https://pub.dartlang.org/packages/liquid_pull_to_refresh) [![](https://img.shields.io/github/last-commit/aagarwal1012/Liquid-Pull-To-Refresh.svg)](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh/) [![](https://img.shields.io/github/stars/aagarwal1012/Liquid-Pull-To-Refresh.svg?style=social)](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh/)

A beautiful and custom refresh indicator with some cool animations and transitions for flutter.

![](images/liquid_pull_to_refresh1.gif)

---

## folding_cell [![](https://img.shields.io/pub/v/folding_cell.svg)](https://pub.dartlang.org/packages/folding_cell) [![](https://img.shields.io/github/last-commit/faob-dev/folding_cell.svg)](https://github.com/faob-dev/folding_cell) [![](https://img.shields.io/github/stars/faob-dev/folding_cell.svg?style=social)](https://github.com/faob-dev/folding_cell)

Simple folding cell widget implemented in Flutter. Its a widget so add it to any container widget as a child.

![](images/folding_cell.gif)

---

## snaplist [![](https://img.shields.io/pub/v/snaplist.svg)](https://pub.dartlang.org/packages/snaplist) [![](https://img.shields.io/github/last-commit/ariedov/flutter_snaplist.svg)](https://github.com/ariedov/flutter_snaplist) [![](https://img.shields.io/github/stars/ariedov/flutter_snaplist.svg?style=social)](https://github.com/ariedov/flutter_snaplist)

Small cozy library that allows you to make snappable list views.

![](images/snaplist1.gif)

---

## Infinite ListView [![](https://img.shields.io/pub/v/infinite_listview.svg)](https://pub.dartlang.org/packages/infinite_listview) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter_infinite_listview.svg)](https://github.com/fluttercommunity/flutter_infinite_listview) [![](https://img.shields.io/github/stars/fluttercommunity/flutter_infinite_listview.svg?style=social)](https://github.com/fluttercommunity/flutter_infinite_listview)

ListView with items that can be scrolled infinitely in both directions.

![](images/infinite_listview1.gif)

---

## flutter_tags [![](https://img.shields.io/pub/v/flutter_tags.svg)](https://pub.dartlang.org/packages/flutter_tags) [![](https://img.shields.io/github/last-commit/Dn-a/flutter_tags.svg)](https://github.com/Dn-a/flutter_tags) [![](https://img.shields.io/github/stars/Dn-a/flutter_tags.svg?style=social)](https://github.com/Dn-a/flutter_tags)

Flutter tags let you create a list of tags or insert them dynamically with the input.

![](images/flutter_tags1.gif)

---

## Draggable Scrollbar [![](https://img.shields.io/pub/v/draggable_scrollbar.svg)](https://pub.dartlang.org/packages/draggable_scrollbar) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter-draggable-scrollbar.svg)](https://github.com/fluttercommunity/flutter-draggable-scrollbar) [![](https://img.shields.io/github/stars/fluttercommunity/flutter-draggable-scrollbar.svg?style=social)](https://github.com/fluttercommunity/flutter-draggable-scrollbar)

A scrollbar that can be dragged for quickly navigating through a vertical list. Additionally it can show a label next to the scrollthumb with information about the current item.

![](images/draggable_scrollbar1.gif)

---

## Fluid Slider [![](https://img.shields.io/pub/v/flutter_fluid_slider.svg)](https://pub.dartlang.org/packages/flutter_fluid_slider) [![](https://img.shields.io/github/last-commit/rvamsikrishna/flutter_fluid_slider.git.svg)](https://github.com/rvamsikrishna/flutter_fluid_slider.git) [![](https://img.shields.io/github/stars/rvamsikrishna/flutter_fluid_slider.git.svg?style=social)](https://github.com/rvamsikrishna/flutter_fluid_slider.git)

A fluid design slider that works just like the Slider material widget.

![](images/flutter_fluid_slider1.gif)

---

## BubbleBottomBar [![](https://img.shields.io/pub/v/bubble_bottom_bar.svg)](https://pub.dartlang.org/packages/bubble_bottom_bar) [![](https://img.shields.io/github/last-commit/westdabestdb/bubble_bottom_bar.svg)](https://github.com/westdabestdb/bubble_bottom_bar) [![](https://img.shields.io/github/stars/westdabestdb/bubble_bottom_bar.svg?style=social)](https://github.com/westdabestdb/bubble_bottom_bar)

BubbleBottomBar is a Flutter widget designed by cubertodesign and developed by westdabestdb.

![images/bubble_bottom_bar1.gif]

---

## Zefyr [![](https://img.shields.io/pub/v/zefyr.svg)](https://pub.dartlang.org/packages/zefyr) [![](https://img.shields.io/github/last-commit/memspace/zefyr.svg)](https://github.com/memspace/zefyr) [![](https://img.shields.io/github/stars/memspace/zefyr.svg?style=social)](https://github.com/memspace/zefyr)

Clean, minimalistic and collaboration-ready rich text editor for Flutter.

![](images/zefyr1.png)

---

## Passcode Lock Screen [![](https://img.shields.io/pub/v/passcode_screen.svg)](https://pub.dartlang.org/packages/passcode_screen) [![](https://img.shields.io/github/last-commit/xPutnikx/flutter-passcode.svg)](https://github.com/xPutnikx/flutter-passcode) [![](https://img.shields.io/github/stars/xPutnikx/flutter-passcode.svg?style=social)](https://github.com/xPutnikx/flutter-passcode)

A platform agnostic Flutter package for showing passcode input screen, similar to Native iOS. Screen customizable with a colors, sizes, fonts etc.

![](images/passcode_screen1.png)

---

## ProgressButton [![](https://img.shields.io/pub/v/progress_button.svg)](https://pub.dartlang.org/packages/progress_button) [![](https://img.shields.io/github/last-commit/halilozercan/progressbutton.svg)](https://github.com/halilozercan/progressbutton) [![](https://img.shields.io/github/stars/halilozercan/progressbutton.svg?style=social)](https://github.com/halilozercan/progressbutton)

A Material Flutter Button that supports progress and error visuals.

<img src="images/progress_button1.gif" width="320px">

---

## stepper_touch [![](https://img.shields.io/pub/v/stepper_touch.svg)](https://pub.dartlang.org/packages/stepper_touch) [![](https://img.shields.io/github/last-commit/Rahiche/stepper_touch.svg)](https://github.com/Rahiche/stepper_touch) [![](https://img.shields.io/github/stars/Rahiche/stepper_touch.svg?style=social)](https://github.com/Rahiche/stepper_touch)

A Flutter stepper widget with nice aniamtion.

![](images/stepper_touch1.gif)

<br>

# Animations

## ✨Flutter Spinkit [![](https://img.shields.io/pub/v/flutter_spinkit.svg)](https://pub.dartlang.org/packages/flutter_spinkit) [![](https://img.shields.io/github/last-commit/jogboms/flutter_spinkit.svg)](https://github.com/jogboms/flutter_spinkit) [![](https://img.shields.io/github/stars/jogboms/flutter_spinkit.svg?style=social)](https://github.com/jogboms/flutter_spinkit)

A collection of loading indicators animated with flutter.

![](images/flutter_spinkit1.gif)

---

## Shimmer [![](https://img.shields.io/pub/v/shimmer.svg)](https://pub.dartlang.org/packages/shimmer) [![](https://img.shields.io/github/last-commit/hnvn/flutter_shimmer.svg)](https://github.com/hnvn/flutter_shimmer) [![](https://img.shields.io/github/stars/hnvn/flutter_shimmer.svg?style=social)](https://github.com/hnvn/flutter_shimmer)

A package provides an easy way to add shimmer effect in Flutter project.

![](images/shimmer1.gif)

---

## Animated Text Kit [![](https://img.shields.io/pub/v/animated_text_kit.svg)](https://pub.dartlang.org/packages/animated_text_kit) [![](https://img.shields.io/github/last-commit/aagarwal1012/Animated-Text-Kit.svg)](https://github.com/aagarwal1012/Animated-Text-Kit/) [![](https://img.shields.io/github/stars/aagarwal1012/Animated-Text-Kit.svg?style=social)](https://github.com/aagarwal1012/Animated-Text-Kit/)

A flutter package project which contains a collection of cool and beautiful text animations.

<p>
	<img src="images/animated_text_kit1.gif" />
	<img src="images/animated_text_kit2.gif" />
    <img src="images/animated_text_kit3.gif" />
    <img src="images/animated_text_kit4.gif" />
</p>

---

## spritewidget [![](https://img.shields.io/pub/v/spritewidget.svg)](https://pub.dartlang.org/packages/spritewidget) [![](https://img.shields.io/github/last-commit/spritewidget/spritewidget.svg)](https://github.com/spritewidget/spritewidget) [![](https://img.shields.io/github/stars/spritewidget/spritewidget.svg?style=social)](https://github.com/spritewidget/spritewidget)

SpriteWidget is a toolkit for building complex, high performance animations and 2D games with Flutter. Your sprite render tree lives inside a widget that mixes seamlessly with other Flutter and Material widgets. You can use SpriteWidget to create anything from an animated icon to a full fledged game.

---

## flutter_sequence_animation [![](https://img.shields.io/pub/v/flutter_sequence_animation.svg)](https://pub.dartlang.org/packages/flutter_sequence_animation) [![](https://img.shields.io/github/last-commit/Norbert515/flutter_sequence_animation.svg)](https://github.com/Norbert515/flutter_sequence_animation) [![](https://img.shields.io/github/stars/Norbert515/flutter_sequence_animation.svg?style=social)](https://github.com/Norbert515/flutter_sequence_animation)

Composite together any animation with this robust and simple to use package.

<p>
	<img src="images/flutter_sequence_animation1.gif" />
	<img src="images/flutter_sequence_animation2.gif" />
</p>

---

## flutter_villains [![](https://img.shields.io/pub/v/flutter_villains.svg)](https://pub.dartlang.org/packages/flutter_villains) [![](https://img.shields.io/github/last-commit/Norbert515/flutter_villains.svg)](https://github.com/Norbert515/flutter_villains) [![](https://img.shields.io/github/stars/Norbert515/flutter_villains.svg?style=social)](https://github.com/Norbert515/flutter_villains)

Page transitions with just a few lines of code. What are heroes without villains?

<img src="images/flutter_villains1.gif" width="250px">

---

## Flutter Page Transition Package [![](https://img.shields.io/pub/v/page_transition.svg)](https://pub.dartlang.org/packages/page_transition) [![](https://img.shields.io/github/last-commit/kalismeras61/flutter_page_transition.svg)](https://github.com/kalismeras61/flutter_page_transition) [![](https://img.shields.io/github/stars/kalismeras61/flutter_page_transition.svg?style=social)](https://github.com/kalismeras61/flutter_page_transition)

This package gives you beautiful page transitions.

![](images/page_transition1.gif)

---

## Wave [![](https://img.shields.io/pub/v/wave.svg)](https://pub.dartlang.org/packages/wave) [![](https://img.shields.io/github/last-commit/TheProtoss/wave.svg)](https://github.com/TheProtoss/wave) [![](https://img.shields.io/github/stars/TheProtoss/wave.svg?style=social)](https://github.com/TheProtoss/wave)

Widget for displaying waves with custom color, duration, floating and blur effects.

![](images/wave1.gif)

---

## flip_card [![](https://img.shields.io/pub/v/flip_card.svg)](https://pub.dartlang.org/packages/flip_card) [![](https://img.shields.io/github/last-commit/fedeoo/flip_card.svg)](https://github.com/fedeoo/flip_card/) [![](https://img.shields.io/github/stars/fedeoo/flip_card.svg?style=social)](https://github.com/fedeoo/flip_card/)

A component that provides flip card animation. It could be used for hide and show details of a product.

<p>
	<img src="images/flip_card1.gif" />
	<img src="images/flip_card2.gif" />
</p>

---

## fluttie: Lottie for flutter [![](https://img.shields.io/pub/v/fluttie.svg)](https://pub.dartlang.org/packages/fluttie) [![](https://img.shields.io/github/last-commit/simolus3/fluttie.svg)](https://github.com/simolus3/fluttie) [![](https://img.shields.io/github/stars/simolus3/fluttie.svg?style=social)](https://github.com/simolus3/fluttie)

Fluttie allows you to easily display stunning Lottie animations in flutter.

![](images/fluttie1.gif)

---

## Hidden Drawer Menu [![](https://img.shields.io/pub/v/hidden_drawer_menu.svg)](https://pub.dartlang.org/packages/hidden_drawer_menu) [![](https://img.shields.io/github/last-commit/RafaelBarbosatec/hidden_drawer_menu.svg)](https://github.com/RafaelBarbosatec/hidden_drawer_menu) [![](https://img.shields.io/github/stars/RafaelBarbosatec/hidden_drawer_menu.svg?style=social)](https://github.com/RafaelBarbosatec/hidden_drawer_menu)

Hidden Drawer Menu is a library for adding a beautiful drawer mode menu feature with perspective animation.

![](images/hidden_drawer_menu1.gif)

---

## flip_panel [![](https://img.shields.io/pub/v/flip_panel.svg)](https://pub.dartlang.org/packages/flip_panel) [![](https://img.shields.io/github/last-commit/hnvn/flutter_flip_panel.svg)](https://github.com/hnvn/flutter_flip_panel) [![](https://img.shields.io/github/stars/hnvn/flutter_flip_panel.svg?style=social)](https://github.com/hnvn/flutter_flip_panel)

A package for flip panel with built-in animation.

<p>
	<img src="images/flip_panel1.gif" width="250" />
	<img src="images/flip_panel2.gif" width="250" />
</p>

---

## flame [![](https://img.shields.io/pub/v/flame.svg)](https://pub.dartlang.org/packages/flame) [![](https://img.shields.io/github/last-commit/luanpotter/flame.svg)](https://github.com/luanpotter/flame) [![](https://img.shields.io/github/stars/luanpotter/flame.svg?style=social)](https://github.com/luanpotter/flame)

A minimalist Flutter game engine, provides a nice set of somewhat independent modules you can choose from.

```dart
import 'package:flame/components/component.dart';

Sprite sprite = new Sprite('player.png');

const size = 128.0;
final player = new SpriteComponent.fromSprite(size, size, sprite); // width, height, sprite

player.x = ... // 0 by default
player.y = ... // 0 by default
player.angle = ... // 0 by default

// on your render method...
player.render(canvas);
```

---

## WaveProgress [![](https://img.shields.io/pub/v/wave_progress_widget.svg)](https://pub.dartlang.org/packages/wave_progress_widget) [![](https://img.shields.io/github/last-commit/studioidan/wave_progress.svg)](https://github.com/studioidan/wave_progress) [![](https://img.shields.io/github/stars/studioidan/wave_progress.svg?style=social)](https://github.com/studioidan/wave_progress)

A custom wave progress widget.

![](images/wave_progress_widget1.gif)

---

## Text to Path Maker [![](https://img.shields.io/pub/v/text_to_path_maker.svg)](https://pub.dartlang.org/packages/text_to_path_maker) [![](https://img.shields.io/github/last-commit/hathibelagal-dev/text-to-path-maker-for-flutter.svg)](https://github.com/hathibelagal-dev/text-to-path-maker-for-flutter) [![](https://img.shields.io/github/stars/hathibelagal-dev/text-to-path-maker-for-flutter.svg?style=social)](https://github.com/hathibelagal-dev/text-to-path-maker-for-flutter)

Tis is a pure Flutter and Dart package that allows you to convert text (both characters and icons) into paths and animate them.

![](images/text_to_path_maker1.gif)

---

## drawing_animation [![](https://img.shields.io/pub/v/drawing_animation.svg)](https://pub.dartlang.org/packages/drawing_animation) [![](https://img.shields.io/github/last-commit/biocarl/drawing_animation.svg)](https://github.com/biocarl/drawing_animation) [![](https://img.shields.io/github/stars/biocarl/drawing_animation.svg?style=social)](https://github.com/biocarl/drawing_animation)

An dart-only library for gradually painting SVG path objects on canvas (drawing line animation).

![](images/drawing_animation1.gif)

---

## Path Morph [![](https://img.shields.io/pub/v/path_morph.svg)](https://pub.dartlang.org/packages/path_morph) [![](https://img.shields.io/github/last-commit/hathibelagal-dev/path_morph_for_flutter.svg)](https://github.com/hathibelagal-dev/path_morph_for_flutter) [![](https://img.shields.io/github/stars/hathibelagal-dev/path_morph_for_flutter.svg?style=social)](https://github.com/hathibelagal-dev/path_morph_for_flutter)

This package lets you create path tween animations. In other words, it lets you morph one path into another.

![](images/path_morph1.gif)

<br>

# Images

## Image Picker (Flutter Team) [![](https://img.shields.io/pub/v/image_picker.svg)](https://pub.dartlang.org/packages/image_picker) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/image_picker) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/image_picker)

A Flutter plugin for iOS and Android for picking images from the image library, and taking new pictures with the camera.

---

## flutter_svg [![](https://img.shields.io/pub/v/flutter_svg.svg)](https://pub.dartlang.org/packages/flutter_svg) [![](https://img.shields.io/github/last-commit/dnfield/flutter_svg.svg)](https://github.com/dnfield/flutter_svg) [![](https://img.shields.io/github/stars/dnfield/flutter_svg.svg?style=social)](https://github.com/dnfield/flutter_svg)

An SVG rendering and widget library for Flutter, which allows painting and displaying Scalable Vector Graphics 1.1 files.

```dart
final String assetName = 'assets/image.svg';
final Widget svg = new SvgPicture.asset(
  assetName,
  semanticsLabel: 'Acme Logo'
);
```

---

## Flutter Photo View [![](https://img.shields.io/pub/v/photo_view.svg)](https://pub.dartlang.org/packages/photo_view) [![](https://img.shields.io/github/last-commit/renancaraujo/photo_view.svg)](https://github.com/renancaraujo/photo_view) [![](https://img.shields.io/github/stars/renancaraujo/photo_view.svg?style=social)](https://github.com/renancaraujo/photo_view)

A simple zoomable image widget for Flutter.

Resolves a image provider and shows the result with useful gestures support, such as pinch to zoom and pan.

<img src="images/photo_view1.gif" height="240px">

---

## Image Cropper [![](https://img.shields.io/pub/v/image_cropper.svg)](https://pub.dartlang.org/packages/image_cropper) [![](https://img.shields.io/github/last-commit/hnvn/flutter_image_cropper.svg)](https://github.com/hnvn/flutter_image_cropper) [![](https://img.shields.io/github/stars/hnvn/flutter_image_cropper.svg?style=social)](https://github.com/hnvn/flutter_image_cropper)

A Flutter plugin for Android and iOS supports cropping images.

<p>
	<img src="images/image_cropper1.gif" width="250" />
	<img src="images/image_cropper2.gif" width="250" />
</p>

---

## Flutter Advanced Network Image [![](https://img.shields.io/pub/v/flutter_advanced_networkimage.svg)](https://pub.dartlang.org/packages/flutter_advanced_networkimage) [![](https://img.shields.io/github/last-commit/mchome/flutter_advanced_networkimage.svg)](https://github.com/mchome/flutter_advanced_networkimage) [![](https://img.shields.io/github/stars/mchome/flutter_advanced_networkimage.svg?style=social)](https://github.com/mchome/flutter_advanced_networkimage)

An advanced image provider provides caching and retrying for flutter app. Now with zoomable widget and transition to image widget

```dart
Image(
  image: AdvancedNetworkImage(
    url,
    header: header,
    useDiskCache: true,
    cacheRule: CacheRule(maxAge: const Duration(days: 7)),
  ),
  fit: BoxFit.cover,
)
```

---

## CachedNetworkImage [![](https://img.shields.io/pub/v/cached_network_image.svg)](https://pub.dartlang.org/packages/cached_network_image) [![](https://img.shields.io/github/last-commit/renefloor/flutter_cached_network_image.svg)](https://github.com/renefloor/flutter_cached_network_image) [![](https://img.shields.io/github/stars/renefloor/flutter_cached_network_image.svg?style=social)](https://github.com/renefloor/flutter_cached_network_image)

A flutter library to show images from the internet and keep them in the cache directory.

```dart
CachedNetworkImage(
  imageUrl: "http://via.placeholder.com/350x150",
  placeholder: (context, url) => CircularProgressIndicator(),
  errorWidget: (context, url, error) => Icon(Icons.error),
)
```

---

## Flutter Multi Image Picker [![](https://img.shields.io/pub/v/multi_image_picker.svg)](https://pub.dartlang.org/packages/multi_image_picker) [![](https://img.shields.io/github/last-commit/Sh1d0w/multi_image_picker.svg)](https://github.com/Sh1d0w/multi_image_picker) [![](https://img.shields.io/github/stars/Sh1d0w/multi_image_picker.svg?style=social)](https://github.com/Sh1d0w/multi_image_picker)

Flutter plugin that allows you to display multi image picker on iOS and Android.

![](images/multi_image_picker1.png)

---

## flutter_image_compress [![](https://img.shields.io/pub/v/flutter_image_compress.svg)](https://pub.dartlang.org/packages/flutter_image_compress) [![](https://img.shields.io/github/last-commit/OpenFlutter/flutter_image_compress.svg)](https://github.com/OpenFlutter/flutter_image_compress) [![](https://img.shields.io/github/stars/OpenFlutter/flutter_image_compress.svg?style=social)](https://github.com/OpenFlutter/flutter_image_compress)

Compress images with native code (objc kotlin), it's faster. This package supports Android and iOS.

```dart
var result = await FlutterImageCompress.compressWithFile(
  file.absolute.path,
  minWidth: 2300,
  minHeight: 1500,
  quality: 94,
  rotate: 90,
);
```

---

## Material Design Icons [![](https://img.shields.io/pub/v/material_design_icons_flutter.svg)](https://pub.dartlang.org/packages/material_design_icons_flutter) [![](https://img.shields.io/github/last-commit/ziofat/material_design_icons_flutter.svg)](https://github.com/ziofat/material_design_icons_flutter) [![](https://img.shields.io/github/stars/ziofat/material_design_icons_flutter.svg?style=social)](https://github.com/ziofat/material_design_icons_flutter)

The Material Design Icons from the community for Flutter.

<img src="images/material_design_icons_flutter1.png" width="600px">

---

## Image Cropping plugin [![](https://img.shields.io/pub/v/image_crop.svg)](https://pub.dartlang.org/packages/image_crop) [![](https://img.shields.io/github/last-commit/VolodymyrLykhonis/image_crop.svg)](https://github.com/VolodymyrLykhonis/image_crop) [![](https://img.shields.io/github/stars/VolodymyrLykhonis/image_crop.svg?style=social)](https://github.com/VolodymyrLykhonis/image_crop)
A flutter plugin to crop image on iOS and Android. It processes image files off main thread natively. The plugin provides a Crop widget to display image cropping to a user.

<p>
	<img src="images/image_crop1.jpg" height="250px" />
	<img src="images/image_crop2.jpg" height="250px" />
</p>

---

## image [![](https://img.shields.io/pub/v/image.svg)](https://pub.dartlang.org/packages/image) [![](https://img.shields.io/github/last-commit/brendan-duncan/image.svg)](https://github.com/brendan-duncan/image) [![](https://img.shields.io/github/stars/brendan-duncan/image.svg?style=social)](https://github.com/brendan-duncan/image)

Provides server and web apps the ability to load, manipulate, and save images with various image file formats including PNG, JPEG, GIF, WebP, TIFF, TGA, PSD, PVR, and OpenEXR.

```dart
Image image = decodeImage(Io.File('test.webp').readAsBytesSync());

// Resize the image to a 120x? thumbnail (maintaining the aspect ratio).
Image thumbnail = copyResize(image, 120);

// Save the thumbnail as a PNG.
Io.File('thumbnail.png')
  ..writeAsBytesSync(encodePng(thumbnail));
```

<br>

# Swipe & Slide

## flutter_swiper [![](https://img.shields.io/pub/v/flutter_swiper.svg)](https://pub.dartlang.org/packages/flutter_swiper) [![](https://img.shields.io/github/last-commit/jzoom/flutter_swiper.svg)](https://github.com/jzoom/flutter_swiper) [![](https://img.shields.io/github/stars/jzoom/flutter_swiper.svg?style=social)](https://github.com/jzoom/flutter_swiper)

The best swiper for flutter, with multiple layouts, infinite loop. Compatible with Android & iOS.

<img src="images/flutter_swiper1.gif" height="180px">

---

## flutter_slidable [![](https://img.shields.io/pub/v/flutter_slidable.svg)](https://pub.dartlang.org/packages/flutter_slidable) [![](https://img.shields.io/github/last-commit/letsar/flutter_slidable.svg)](https://github.com/letsar/flutter_slidable) [![](https://img.shields.io/github/stars/letsar/flutter_slidable.svg?style=social)](https://github.com/letsar/flutter_slidable)

A Flutter implementation of slidable list item with directional slide actions that can be dismissed.

![](images/flutter_slidable1.gif)

---

## intro_views_flutter [![](https://img.shields.io/pub/v/intro_views_flutter.svg)](https://pub.dartlang.org/packages/intro_views_flutter) [![](https://img.shields.io/github/last-commit/aagarwal1012/IntroViews-Flutter.svg)](https://github.com/aagarwal1012/IntroViews-Flutter) [![](https://img.shields.io/github/stars/aagarwal1012/IntroViews-Flutter.svg?style=social)](https://github.com/aagarwal1012/IntroViews-Flutter)

A Flutter package for simple material design app intro screens with some cool animations.

![](images/intro_views_flutter1.gif)

---

## carousel_slider [![](https://img.shields.io/pub/v/carousel_slider.svg)](https://pub.dartlang.org/packages/carousel_slider) [![](https://img.shields.io/github/last-commit/serenader2014/flutter_carousel_slider.svg)](https://github.com/serenader2014/flutter_carousel_slider) [![](https://img.shields.io/github/stars/serenader2014/flutter_carousel_slider.svg?style=social)](https://github.com/serenader2014/flutter_carousel_slider)

A carousel slider widget, support infinite scroll and custom child widget, with auto play feature.

<img src="images/carousel_slider1.gif" height="300px">

---

## intro_slider [![](https://img.shields.io/pub/v/intro_slider.svg)](https://pub.dartlang.org/packages/intro_slider) [![](https://img.shields.io/github/last-commit/duytq94/flutter-intro-slider.svg)](https://github.com/duytq94/flutter-intro-slider) [![](https://img.shields.io/github/stars/duytq94/flutter-intro-slider.svg?style=social)](https://github.com/duytq94/flutter-intro-slider)

A plugin to help you make intro slider screen to show the major features of your app. You can change the image, button, text style, color, and more things.

<img src="images/intro_slider1.gif" height="300px">

---

## Flushbar [![](https://img.shields.io/pub/v/flushbar.svg)](https://pub.dartlang.org/packages/flushbar) [![](https://img.shields.io/github/last-commit/AndreHaueisen/flushbar.svg)](https://github.com/AndreHaueisen/flushbar) [![](https://img.shields.io/github/stars/AndreHaueisen/flushbar.svg?style=social)](https://github.com/AndreHaueisen/flushbar)

A flexible widget for user notification. Customize your text, button, duration, animations and much more. For Android devs, it is made to replace Snackbars and Toasts.

![](images/flushbar1.gif)

---

## smooth_star_rating [![](https://img.shields.io/pub/v/smooth_star_rating.svg)](https://pub.dartlang.org/packages/smooth_star_rating) [![](https://img.shields.io/github/last-commit/thangmam/smoothratingbar.git.svg)](https://github.com/thangmam/smoothratingbar.git) [![](https://img.shields.io/github/stars/thangmam/smoothratingbar.git.svg?style=social)](https://github.com/thangmam/smoothratingbar.git)

A Star rating with touch and swipe rate enabled
- Supports half rate and full rate (1.0 or 0.5)
- Swipe for incrementing/decrementing rate amount
- Change star body and boundary colors independently

![](images/smooth_star_rating1.gif)

---

## Rubber [![](https://img.shields.io/pub/v/rubber.svg)](https://pub.dartlang.org/packages/rubber) [![](https://img.shields.io/github/last-commit/mcrovero/rubber.svg)](https://github.com/mcrovero/rubber) [![](https://img.shields.io/github/stars/mcrovero/rubber.svg?style=social)](https://github.com/mcrovero/rubber)

Rubber is an elastic bottom sheet widget with the customizable material spring animation.

![](images/rubber1.gif)

<br>

# Dialogs & Pickers

## modal_progress_hud [![](https://img.shields.io/pub/v/modal_progress_hud.svg)](https://pub.dartlang.org/packages/modal_progress_hud) [![](https://img.shields.io/github/last-commit/mmcc007/modal_progress_hud.svg)](https://github.com/mmcc007/modal_progress_hud) [![](https://img.shields.io/github/stars/mmcc007/modal_progress_hud.svg?style=social)](https://github.com/mmcc007/modal_progress_hud)

A modal progress indicator widget (HUD = heads-up display). Wrap around another widget to block access to widget during an async call. Also accepts a custom spinner.

![](images/modal_progress_hud1.gif)

---

## file_picker [![](https://img.shields.io/pub/v/file_picker.svg)](https://pub.dartlang.org/packages/file_picker) [![](https://img.shields.io/github/last-commit/miguelpruivo/plugins_flutter_file_picker.svg)](https://github.com/miguelpruivo/plugins_flutter_file_picker) [![](https://img.shields.io/github/stars/miguelpruivo/plugins_flutter_file_picker.svg?style=social)](https://github.com/miguelpruivo/plugins_flutter_file_picker)

A plugin that allows you to pick absolute paths from different file types.

![](images/file_picker1.gif)

---

## NumberPicker [![](https://img.shields.io/pub/v/numberpicker.svg)](https://pub.dartlang.org/packages/numberpicker) [![](https://img.shields.io/github/last-commit/MarcinusX/NumberPicker.svg)](https://github.com/MarcinusX/NumberPicker) [![](https://img.shields.io/github/stars/MarcinusX/NumberPicker.svg?style=social)](https://github.com/MarcinusX/NumberPicker)

`NumberPicker` is a custom widget designed for choosing an integer or decimal number by scrolling spinners.

It is possible to use `NumberPicker` as a standalone widget as well as in `NumberPickerDialog`.

![](images/numberpicker1.gif)

---

## country_pickers [![](https://img.shields.io/pub/v/country_pickers.svg)](https://pub.dartlang.org/packages/country_pickers) [![](https://img.shields.io/github/last-commit/figengungor/country_pickers.svg)](https://github.com/figengungor/country_pickers) [![](https://img.shields.io/github/stars/figengungor/country_pickers.svg?style=social)](https://github.com/figengungor/country_pickers)

Countries, codes, flags and several ways of picking them at your service...

<p>
	<img src="images/country_pickers1.png" height="320px" />
	<img src="images/country_pickers2.png" height="320px" />
</p>

---

## Date Range Picker [![](https://img.shields.io/pub/v/date_range_picker.svg)](https://pub.dartlang.org/packages/date_range_picker) [![](https://img.shields.io/github/last-commit/anicdh/date_range_picker.svg)](https://github.com/anicdh/date_range_picker) [![](https://img.shields.io/github/stars/anicdh/date_range_picker.svg?style=social)](https://github.com/anicdh/date_range_picker)

Date Range Pickers use a dialog window to select a range of date on mobile.

![](images/date_range_picker1.gif)

---

## progress_dialog [![](https://img.shields.io/pub/v/progress_dialog.svg)](https://pub.dartlang.org/packages/progress_dialog) [![](https://img.shields.io/github/last-commit/fayaz07/progress_dialog.svg)](https://github.com/fayaz07/progress_dialog) [![](https://img.shields.io/github/stars/fayaz07/progress_dialog.svg?style=social)](https://github.com/fayaz07/progress_dialog)

A light weight library to easily manage a progress dialog with simple steps whenever you need to do it. You can easily show and hide it.

![](images/progress_dialog1.gif)

<br>

# Input & Forms

## Flutter TypeAhead [![](https://img.shields.io/pub/v/flutter_typeahead.svg)](https://pub.dartlang.org/packages/flutter_typeahead) [![](https://img.shields.io/github/last-commit/AbdulRahmanAlHamali/flutter_typeahead.svg)](https://github.com/AbdulRahmanAlHamali/flutter_typeahead) [![](https://img.shields.io/github/stars/AbdulRahmanAlHamali/flutter_typeahead.svg?style=social)](https://github.com/AbdulRahmanAlHamali/flutter_typeahead)

A highly customizable typeahead (autocomplete) text input field.

![](images/flutter_typeahead1.gif)


---

## Email validator [![](https://img.shields.io/pub/v/email_validator.svg)](https://pub.dartlang.org/packages/email_validator) [![](https://img.shields.io/github/last-commit/fredeil/email-validator.dart.svg)](https://github.com/fredeil/email-validator.dart) [![](https://img.shields.io/github/stars/fredeil/email-validator.dart.svg?style=social)](https://github.com/fredeil/email-validator.dart)

A simple (but correct) dart class for validating email addresses.

```dart
var email = "fredrik@gmail.com";

assert(EmailValidator.validate(email) == true);
```

---

## stripe_payment [![](https://img.shields.io/pub/v/stripe_payment.svg)](https://pub.dartlang.org/packages/stripe_payment) [![](https://img.shields.io/github/last-commit/jonasbark/flutter_stripe_payment.svg)](https://github.com/jonasbark/flutter_stripe_payment) [![](https://img.shields.io/github/stars/jonasbark/flutter_stripe_payment.svg?style=social)](https://github.com/jonasbark/flutter_stripe_payment)

A flutter plugin to integrate the stripe plugin for iOS and Android. Currently only adding a credit card as source is implemented.

<p>
	<img src="images/stripe_payment1.png" />
	<img src="images/stripe_payment2.png" />
</p>

---

## flutter_form_builder [![](https://img.shields.io/pub/v/flutter_form_builder.svg)](https://pub.dartlang.org/packages/flutter_form_builder) [![](https://img.shields.io/github/last-commit/danvick/flutter_form_builder.svg)](https://github.com/danvick/flutter_form_builder) [![](https://img.shields.io/github/stars/danvick/flutter_form_builder.svg?style=social)](https://github.com/danvick/flutter_form_builder)

Package to build Material Form with components such as TextField (With number, url, email validation), DropDown, TypeAhead, Radios, Checkboxes

```dart
FormBuilder(
  context,
  autovalidate: true,
  controls: [
    FormBuilderInput.textField(
      type: FormBuilderInput.TYPE_TEXT,
      attribute: "name",
      label: "Name",
      require: true,
      min: 3,
    ),
    FormBuilderInput.password(
      attribute: "password",
      label: "Password",
      //require: true,
    ),
  ],
  onChanged: () {
    print("Form Changed");
  },
  onSubmit: (formValue) {
    if (formValue != null) {
      print(formValue);
    } else {
      print("Form invalid");
    }
  },
),
```

<br>

# Device

## device_info (Flutter Team) [![](https://img.shields.io/pub/v/device_info.svg)](https://pub.dartlang.org/packages/device_info) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/device_info) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/device_info)

Flutter plugin providing detailed information about the device (make, model, etc.), and Android or iOS version the app is running on.

```dart
import 'package:device_info/device_info.dart';

DeviceInfoPlugin deviceInfo = DeviceInfoPlugin();
AndroidDeviceInfo androidInfo = await deviceInfo.androidInfo;
print('Running on ${androidInfo.model}');  // e.g. "Moto G (4)"

IosDeviceInfo iosInfo = await deviceInfo.iosInfo;
print('Running on ${iosInfo.utsname.machine}');  // e.g. "iPod7,1"
```

---

## share (Flutter Team) [![](https://img.shields.io/pub/v/share.svg)](https://pub.dartlang.org/packages/share) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/share) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/share)

Flutter plugin for sharing content via the platform share UI, using the ACTION_SEND intent on Android and UIActivityViewController on iOS.

```dart
import 'package:share/share.dart';
Share.share('check out my website https://example.com');
```

---

## package_info (Flutter Team) [![](https://img.shields.io/pub/v/package_info.svg)](https://pub.dartlang.org/packages/package_info) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/package_info) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/package_info)

Flutter plugin for querying information about the application package, such as CFBundleVersion on iOS or versionCode on Android.

```dart
import 'package:package_info/package_info.dart';

PackageInfo packageInfo = await PackageInfo.fromPlatform();

String appName = packageInfo.appName;
String packageName = packageInfo.packageName;
String version = packageInfo.version;
String buildNumber = packageInfo.buildNumber;
```

---

## Flutter Geolocator [![](https://img.shields.io/pub/v/geolocator.svg)](https://pub.dartlang.org/packages/geolocator) [![](https://img.shields.io/github/last-commit/baseflowit/flutter-geolocator.svg)](https://github.com/baseflowit/flutter-geolocator) [![](https://img.shields.io/github/stars/baseflowit/flutter-geolocator.svg?style=social)](https://github.com/baseflowit/flutter-geolocator)

Geolocation plugin for Flutter. This plugin provides a cross-platform (iOS, Android) API for generic location (GPS etc.) functions.

```dart
import 'package:geolocator/geolocator.dart';

Position position = await Geolocator().getCurrentPosition(desiredAccuracy: LocationAccuracy.high);
```

---

## contacts_service [![](https://img.shields.io/pub/v/contacts_service.svg)](https://pub.dartlang.org/packages/contacts_service) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter_contacts.svg)](https://github.com/fluttercommunity/flutter_contacts) [![](https://img.shields.io/github/stars/fluttercommunity/flutter_contacts.svg?style=social)](https://github.com/fluttercommunity/flutter_contacts)

A Flutter plugin to retrieve and manage contacts on Android and iOS devices.

```dart
import 'package:contacts_service/contacts_service.dart';

// Get all contacts
Iterable<Contact> contacts = await ContactsService.getContacts();

// Get contacts matching a string
Iterable<Contact> johns = await ContactsService.getContacts(query : "john");

await ContactsService.addContact(newContact);
await ContactsService.deleteContact(contact);
```

---

## Screen [![](https://img.shields.io/pub/v/screen.svg)](https://pub.dartlang.org/packages/screen) [![](https://img.shields.io/github/last-commit/clovisnicolas/flutter_screen.svg)](https://github.com/clovisnicolas/flutter_screen) [![](https://img.shields.io/github/stars/clovisnicolas/flutter_screen.svg?style=social)](https://github.com/clovisnicolas/flutter_screen)

A Flutter plugin to manage the device's screen on Android and iOS.

```dart
import 'package:screen/screen.dart';

// Get the current brightness:
double brightness = await Screen.brightness;

// Set the brightness:
Screen.setBrightness(0.5);

// Check if the screen is kept on:
bool isKeptOn = await Screen.isKeptOn;

// Prevent screen from going into sleep mode:
Screen.keepOn(true);
```

---

## battery [![](https://img.shields.io/pub/v/battery.svg)](https://pub.dartlang.org/packages/battery) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/battery) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/battery)

Flutter plugin for accessing information about the battery state (full, charging, discharging) on Android and iOS.

```dart
import 'package:battery/battery.dart';

var battery = Battery();
print(battery.batteryLevel); // Access current battery level

// Be informed when the state (full, charging, discharging) changes
_battery.onBatteryStateChanged.listen((BatteryState state) {
  // Do something with new state
});
```

<br>

# Networking

## url_launcher (Flutter Team) [![](https://img.shields.io/pub/v/url_launcher.svg)](https://pub.dartlang.org/packages/url_launcher) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/url_launcher) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/url_launcher)

Flutter plugin for launching a URL on Android and iOS. Supports web, phone, SMS, and email schemes.

```dart
import 'package:url_launcher/url_launcher.dart';

const url = 'https://flutter.io';
if (await canLaunch(url)) {
  await launch(url);
} else {
  throw 'Could not launch $url';
}
```

---

## dio [![](https://img.shields.io/pub/v/dio.svg)](https://pub.dartlang.org/packages/dio) [![](https://img.shields.io/github/last-commit/flutterchina/dio.svg)](https://github.com/flutterchina/dio) [![](https://img.shields.io/github/stars/flutterchina/dio.svg?style=social)](https://github.com/flutterchina/dio)

A powerful Http client for Dart, which supports Interceptors, FormData, Request Cancellation, File Downloading, Timeout etc.

```dart
import 'package:dio/dio.dart';
void getHttp() async {
  try {
    Response response = await Dio().get("http://www.google.com");
    return print(response);
  } catch (e) {
    return print(e);
  }
}
```

---

## http (Flutter Team) [![](https://img.shields.io/pub/v/http.svg)](https://pub.dartlang.org/packages/http) [![](https://img.shields.io/github/last-commit/dart-lang/http.svg)](https://github.com/dart-lang/http) [![](https://img.shields.io/github/stars/dart-lang/http.svg?style=social)](https://github.com/dart-lang/http)

A composable, cross-platform, Future-based API for making HTTP requests.

```dart
import 'package:http/http.dart' as http;

http.read("http://example.com/foobar.txt").then(print);
```

---

## Flutter Downloader [![](https://img.shields.io/pub/v/flutter_downloader.svg)](https://pub.dartlang.org/packages/flutter_downloader) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter_downloader.svg)](https://github.com/fluttercommunity/flutter_downloader) [![](https://img.shields.io/github/stars/fluttercommunity/flutter_downloader.svg?style=social)](https://github.com/fluttercommunity/flutter_downloader)

A plugin for creating and managing download tasks. Supports iOS and Android.

This plugin is based on `WorkManager` in Android and `NSURLSessionDownloadTask` in iOS to run download task in background mode.

```dart
final taskId = await FlutterDownloader.enqueue(
  url: 'your download link',
  savedDir: 'the path of directory where you want to save downloaded files',
  showNotification: true, // show download progress in status bar (for Android)
  openFileFromNotification: true, // click on notification to open downloaded file (for Android)
);

FlutterDownloader.registerCallback((id, status, progress) {
  // code to update your UI
});
```

<br>

# Bluetooth & Wifi

## connectivity (Flutter Team) [![](https://img.shields.io/pub/v/connectivity.svg)](https://pub.dartlang.org/packages/connectivity) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/connectivity) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/connectivity)

This plugin allows Flutter apps to discover network connectivity and configure themselves accordingly. It can distinguish between cellular vs WiFi connection. This plugin works for iOS and Android.

```dart
import 'package:connectivity/connectivity.dart';

var connectivityResult = await (Connectivity().checkConnectivity());
if (connectivityResult == ConnectivityResult.mobile) {
  // I am connected to a mobile network.
} else if (connectivityResult == ConnectivityResult.wifi) {
  // I am connected to a wifi network.
}
```

---

## flutter_offline [![](https://img.shields.io/pub/v/flutter_offline.svg)](https://pub.dartlang.org/packages/flutter_offline) [![](https://img.shields.io/github/last-commit/jogboms/flutter_offline.svg)](https://github.com/jogboms/flutter_offline) [![](https://img.shields.io/github/stars/jogboms/flutter_offline.svg?style=social)](https://github.com/jogboms/flutter_offline)

A tidy utility to handle offline/online connectivity like a Boss. It provides support for both iOS and Android platforms.

```dart
OfflineBuilder(
  connectivityBuilder: (
    BuildContext context,
    ConnectivityResult connectivity,
    Widget child,
  ) {
    final bool connected = connectivity != ConnectivityResult.none;
    return Text(connected ? "online" : "offline");
  },
);
```

---

## FlutterBlue [![](https://img.shields.io/pub/v/flutter_blue.svg)](https://pub.dartlang.org/packages/flutter_blue) [![](https://img.shields.io/github/last-commit/pauldemarco/flutter_blue.svg)](https://github.com/pauldemarco/flutter_blue) [![](https://img.shields.io/github/stars/pauldemarco/flutter_blue.svg?style=social)](https://github.com/pauldemarco/flutter_blue)

Popular Bluetooth plugin for Flutter

FlutterBlue aims to offer the most from both platforms (iOS and Android).

Using the `FlutterBlue` instance, you can scan for and connect to nearby devices. Once connected to a device, the `BluetoothDevice` object can discover services, characteristics, and descriptors. The `BluetoothDevice` object is then used to directly interact with characteristics and descriptors.

---

## Flutter NFC Reader [![](https://img.shields.io/pub/v/flutter_nfc_reader.svg)](https://pub.dartlang.org/packages/flutter_nfc_reader) [![](https://img.shields.io/github/last-commit/matteocrippa/flutter-nfc-reader.svg)](https://github.com/matteocrippa/flutter-nfc-reader) [![](https://img.shields.io/github/stars/matteocrippa/flutter-nfc-reader.svg?style=social)](https://github.com/matteocrippa/flutter-nfc-reader)

A new flutter plugin to help developers looking to use internal hardware inside iOS or Android devices for reading NFC tags.

The system activate a pooling reading session that stops automatically once a tag has been recognised. You can also trigger the stop event manually using a dedicated function.

```dart
Future<NfcData> startNFC() async {
   NfcData response;

  try {
    response = await FlutterNfcReader.read;
  } on PlatformException {
    //Something went wrong
  }
    
  return response;
}
```

<br>

# Utils

## RxDart [![](https://img.shields.io/pub/v/rxdart.svg)](https://pub.dartlang.org/packages/rxdart) [![](https://img.shields.io/github/last-commit/ReactiveX/rxdart.svg)](https://github.com/ReactiveX/rxdart) [![](https://img.shields.io/github/stars/ReactiveX/rxdart.svg?style=social)](https://github.com/ReactiveX/rxdart)
RxDart is a reactive functional programming library for Google Dart, based on ReactiveX.

### Reading the Konami Code

```dart
const konamiKeyCodes = const <int>[
  KeyCode.UP, KeyCode.UP,
  KeyCode.DOWN, KeyCode.DOWN,
  KeyCode.LEFT, KeyCode.RIGHT,
  KeyCode.LEFT, KeyCode.RIGHT,
  KeyCode.B, KeyCode.A
];

  final result = querySelector('#result');
  final keyUp = new Observable<KeyboardEvent>(document.onKeyUp);

  keyUp
    .map((event) => event.keyCode)
    .bufferCount(10, 1)
    .where((lastTenKeyCodes) => const IterableEquality<int>().equals(lastTenKeyCodes, konamiKeyCodes))
    .listen((_) => result.innerHtml = 'KONAMI!');
```

---

## fluro [![](https://img.shields.io/pub/v/fluro.svg)](https://pub.dartlang.org/packages/fluro) [![](https://img.shields.io/github/last-commit/theyakka/fluro.svg)](https://github.com/theyakka/fluro) [![](https://img.shields.io/github/stars/theyakka/fluro.svg?style=social)](https://github.com/theyakka/fluro)

Fluro is a Flutter routing library that adds flexible routing options like wildcards, named parameters and clear route definitions.

```dart
var usersHandler = Handler(handlerFunc: (BuildContext context, Map<String, dynamic> params) {
  return UsersScreen(params["id"][0]);
});

final router = Router();
router.define("/users/:id", handler: usersHandler);
```

---

## after_layout [![](https://img.shields.io/pub/v/after_layout.svg)](https://pub.dartlang.org/packages/after_layout) [![](https://img.shields.io/github/last-commit/fluttercommunity/flutter_after_layout.svg)](https://github.com/fluttercommunity/flutter_after_layout) [![](https://img.shields.io/github/stars/fluttercommunity/flutter_after_layout.svg?style=social)](https://github.com/fluttercommunity/flutter_after_layout)

Brings functionality to execute code after the first layout of a widget has been performed, i.e. after the first frame has been displayed.

```dart
class HomeScreen extends StatefulWidget {
  @override
  HomeScreenState createState() => new HomeScreenState();
}

class HomeScreenState extends State<HomeScreen> with AfterLayoutMixin<HomeScreen> {
  @override
  Widget build(BuildContext context) {
    return new Scaffold(body: new Container(color: Colors.red));
  }

  @override
  void afterFirstLayout(BuildContext context) {
    showDialog(
      context: context,
      builder: (context) => AlertDialog(
        content: Text('Hello World'),
      ),
    );
  }
}
```

---

## json_serialize (Flutter Team) [![](https://img.shields.io/pub/v/json_serializable.svg)](https://pub.dartlang.org/packages/json_serializable) [![](https://img.shields.io/github/last-commit/dart-lang/json_serializable.svg)](https://github.com/dart-lang/json_serializable) [![](https://img.shields.io/github/stars/dart-lang/json_serializable.svg?style=social)](https://github.com/dart-lang/json_serializable)

Generates utilities to aid in serializing to/from JSON.

```dart
import 'package:json_annotation/json_annotation.dart';

part 'example.g.dart';

@JsonSerializable(nullable: false)
class Person {
  final String firstName;
  final String lastName;
  final DateTime dateOfBirth;

  Person({this.firstName, this.lastName, this.dateOfBirth});

  factory Person.fromJson(Map<String, dynamic> json) => _$PersonFromJson(json);
  
  Map<String, dynamic> toJson() => _$PersonToJson(this);
}
```

---

## fluwx WeChatSDK [![](https://img.shields.io/pub/v/fluwx.svg)](https://pub.dartlang.org/packages/fluwx) [![](https://img.shields.io/github/last-commit/JarvanMo/fluwx.svg)](https://github.com/JarvanMo/fluwx) [![](https://img.shields.io/github/stars/JarvanMo/fluwx.svg?style=social)](https://github.com/JarvanMo/fluwx)

A implement of WeChatSDK on Flutter. Enjoy sharing or payments in Flutter.

```dart
import 'package:fluwx/fluwx.dart' as fluwx;

fluwx.register(appId:"wxd930ea5d5a258f4f");

fluwx.share(
  WeChatShareTextModel(
    text: "text from fluwx",
    transaction: "transaction",
    scene: WeChatScene.SESSION,
  ),
);
```

---

## tuple [![](https://img.shields.io/pub/v/tuple.svg)](https://pub.dartlang.org/packages/tuple) [![](https://img.shields.io/github/last-commit/dart-lang/tuple.svg)](https://github.com/dart-lang/tuple) [![](https://img.shields.io/github/stars/dart-lang/tuple.svg?style=social)](https://github.com/dart-lang/tuple)

Tuple data structure.

```dart
var t = const Tuple2<String, int>('a', 10);

print(t.item1); // prints 'a'
print(t.item2); // prints '10'
```

---

## superpower [![](https://img.shields.io/pub/v/superpower.svg)](https://pub.dartlang.org/packages/superpower) [![](https://img.shields.io/github/last-commit/leisim/superpower.svg)](https://github.com/leisim/superpower) [![](https://img.shields.io/github/stars/leisim/superpower.svg?style=social)](https://github.com/leisim/superpower)

Lists, Iterables and Maps on steroids! 🦄 Extends Lists with negative indices, sort, group, distinct, slice, flatten etc. Inspired by Kotlin.

Just wrap your existing List with $(myList) or create a new empty list with $() and you are good to go.

```dart
var superList = $([0, 10, 100, 1000]);
var sum = superList.sum(); // 1110
var last = superList[-1]; // 1000
var lastTwo = superList.slice(-2); // [100, 1000]
```

---

## rosetta [![](https://img.shields.io/pub/v/rosetta.svg)](https://pub.dartlang.org/packages/rosetta) [![](https://img.shields.io/github/last-commit/TeamWanari/rosetta.svg)](https://github.com/TeamWanari/rosetta) [![](https://img.shields.io/github/stars/TeamWanari/rosetta.svg?style=social)](https://github.com/TeamWanari/rosetta)

This is a localization library to simplify Flutter localization with the help of code generation.

`i18n/en.json`
```json
{
    "hello_there": "Hello there!",
    "see_you_soon": "See you soon!"
}
```

```dart
part 'translation.g.dart';

@Stone(path: 'i18n')
class Translation with _$TranslationHelper { 
  static LocalizationsDelegate<Translation> delegate = _$TranslationDelegate();

  static Translation of(BuildContext context) {
    return Localizations.of(context, Translation);
  }
}
```

<br>

# Frameworks & Design Patterns

## scoped_model [![](https://img.shields.io/pub/v/scoped_model.svg)](https://pub.dartlang.org/packages/scoped_model) [![](https://img.shields.io/github/last-commit/brianegan/scoped_model.svg)](https://github.com/brianegan/scoped_model) [![](https://img.shields.io/github/stars/brianegan/scoped_model.svg?style=social)](https://github.com/brianegan/scoped_model)

A Widget that passes a Reactive Model to all of it's children.

A set of utilities that allow you to easily pass a data Model from a parent Widget down to it's descendants. In addition, it also rebuilds all of the children that use the model when the model is updated. This library was originally extracted from the Fuchsia codebase.

```dart
class CounterModel extends Model {
  int _counter = 0;
  int get counter => _counter;

  void increment() {
    _counter++; // First, increment the counter
    notifyListeners(); // Then notify all the listeners.
  }
}

class CounterApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    // Create a `ScopedModel` widget. This will provide the `model` to the children that request it. 
    return ScopedModel<CounterModel>(
      model: CounterModel(),
      child: Column(children: [
        // Create a ScopedModelDescendant. This widget will get the CounterModel from the nearest
        // ScopedModel<CounterModel>. It will rebuild  any time the CounterModel changes
        ScopedModelDescendant<CounterModel>(
          builder: (context, child, model) => Text('${model.counter}'),
        ),
        Text("Another widget that doesn't depend on the CounterModel")
      ]),
    );
  }
}
```

---

## flutter_redux [![](https://img.shields.io/pub/v/flutter_redux.svg)](https://pub.dartlang.org/packages/flutter_redux) [![](https://img.shields.io/github/last-commit/brianegan/flutter_redux.svg)](https://github.com/brianegan/flutter_redux) [![](https://img.shields.io/github/stars/brianegan/flutter_redux.svg?style=social)](https://github.com/brianegan/flutter_redux)

A set of utilities that allow you to easily consume a Redux Store to build Flutter Widgets.

### Redux Widgets
- `StoreProvider` - The base Widget. It will pass the given Redux Store to all descendants that request it.
- `StoreBuilder` - A descendant Widget that gets the Store from a StoreProvider and passes it to a Widget builder function.
- `StoreConnector` - A descendant Widget that gets the Store from the nearest StoreProvider ancestor, converts the Store into a ViewModel with the given converter function, and passes the ViewModel to a builder function. Any time the Store emits a change event, the Widget will automatically be rebuilt. No need to manage subscriptions!

---

## flutter_bloc [![](https://img.shields.io/pub/v/flutter_bloc.svg)](https://pub.dartlang.org/packages/flutter_bloc) [![](https://img.shields.io/github/last-commit/felangel/bloc.svg)](https://github.com/felangel/bloc) [![](https://img.shields.io/github/stars/felangel/bloc.svg?style=social)](https://github.com/felangel/bloc)

Flutter Widgets that make it easy to implement the BLoC (Business Logic Component) design pattern. Built to be used with the bloc state management package.

---

## synchronized [![](https://img.shields.io/pub/v/synchronized.svg)](https://pub.dartlang.org/packages/synchronized) [![](https://img.shields.io/github/last-commit/tekartik/synchronized.dart.svg)](https://github.com/tekartik/synchronized.dart) [![](https://img.shields.io/github/stars/tekartik/synchronized.dart.svg?style=social)](https://github.com/tekartik/synchronized.dart)

Lock mechanism to prevent concurrent access to asynchronous code.

```dart
import 'package:synchronized/synchronized.dart';

main() async {
  // Use this object to prevent concurrent access to data
  var lock = new Lock();
  ...
  await lock.synchronized(() async {
    // Only this block can run (once) until done
    ...
  });
}
```

---

## Flutter Hooks [![](https://img.shields.io/pub/v/flutter_hooks.svg)](https://pub.dartlang.org/packages/flutter_hooks) [![](https://img.shields.io/github/last-commit/rrousselGit/flutter_hooks.svg)](https://github.com/rrousselGit/flutter_hooks) [![](https://img.shields.io/github/stars/rrousselGit/flutter_hooks.svg?style=social)](https://github.com/rrousselGit/flutter_hooks)

A flutter implementation of React hooks. It adds a new kind of widget with enhanced code reuse.

```dart
class Example extends HookWidget {
  final Duration duration;

  const Example({@required this.duration});

  @override
  Widget build(BuildContext context) {
    final controller = useAnimationController(duration: duration);
    return Container();
  }
}
```

---

## Flutter MobX [![](https://img.shields.io/pub/v/flutter_mobx.svg)](https://pub.dartlang.org/packages/flutter_mobx) [![](https://img.shields.io/github/last-commit/mobxjs/mobx.dart.svg)](https://github.com/mobxjs/mobx.dart) [![](https://img.shields.io/github/stars/mobxjs/mobx.dart.svg?style=social)](https://github.com/mobxjs/mobx.dart)

MobX is a library for reactively managing the state of your applications. Use the power of observables, actions, and reactions to supercharge your Dart and Flutter apps.

```dart
part 'counter.g.dart';

class Counter = _Counter with _$Counter;

abstract class _Counter implements Store {
  @observable
  int value = 0;

  @action
  void increment() {
    value++;
  }
}
```

```dart
class CounterExample extends StatefulWidget {
  @override
  _CounterExampleState createState() => _CounterExampleState();
}

class _CounterExampleState extends State<CounterExample> {
  final _counter = Counter();

  @override
  Widget build(BuildContext context) {
    return Column(
      mainAxisAlignment: MainAxisAlignment.center,
        children: <Widget>[
          Observer(
            builder: (_) => Text('${_counter.value}'),
          ),
          Button(
            onPressed: _counter.increment,
            child: const Icon(Icons.add),
          )
        ],
    );
  }
}
```

<br>

# Audio & Video

## Video Player (Flutter Team) [![](https://img.shields.io/pub/v/video_player.svg)](https://pub.dartlang.org/packages/video_player) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/video_player) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/video_player)

A Flutter plugin for iOS and Android for playing back video on a Widget surface.

![](images/video_player1.jpg)

---

## chewie [![](https://img.shields.io/pub/v/chewie.svg)](https://pub.dartlang.org/packages/chewie) [![](https://img.shields.io/github/last-commit/brianegan/chewie.svg)](https://github.com/brianegan/chewie) [![](https://img.shields.io/github/stars/brianegan/chewie.svg?style=social)](https://github.com/brianegan/chewie)

The video player for Flutter with a heart of gold.

The video_player plugin provides low-level access to video playback. Chewie uses the video_player under the hood and wraps it in a friendly Material or Cupertino UI!

![](images/chewie1.jpg)

---

## audioplayers [![](https://img.shields.io/pub/v/audioplayers.svg)](https://pub.dartlang.org/packages/audioplayers) [![](https://img.shields.io/github/last-commit/luanpotter/audioplayer.svg)](https://github.com/luanpotter/audioplayer) [![](https://img.shields.io/github/stars/luanpotter/audioplayer.svg?style=social)](https://github.com/luanpotter/audioplayer)

A Flutter plugin to play multiple audio files simultaneously (Android/iOS).

<p>
	<img src="images/audioplayers1.jpg" />
	<img src="images/audioplayers2.jpg" />
    <img src="images/audioplayers3.jpg" />
</p>

---

## Flutter Sound [![](https://img.shields.io/pub/v/flutter_sound.svg)](https://pub.dartlang.org/packages/flutter_sound) [![](https://img.shields.io/github/last-commit/dooboolab/flutter_sound.svg)](https://github.com/dooboolab/flutter_sound) [![](https://img.shields.io/github/stars/dooboolab/flutter_sound.svg?style=social)](https://github.com/dooboolab/flutter_sound)

This plugin provides simple recorder and player functionalities for both Android and iOS.

![](images/flutter_sound1.gif)

---

## audioplayer [![](https://img.shields.io/pub/v/audioplayer.svg)](https://pub.dartlang.org/packages/audioplayer) [![](https://img.shields.io/github/last-commit/rxlabz/audioplayer.svg)](https://github.com/rxlabz/audioplayer) [![](https://img.shields.io/github/stars/rxlabz/audioplayer.svg?style=social)](https://github.com/rxlabz/audioplayer)

A flutter plugin to play audio files

```dart
AudioPlayer audioPlugin = new AudioPlayer();

audioPlayer.play(kUrl);

audioPlayer.pause();

audioPlayer.stop();
```

<br>

# Files

## path_provider (Flutter Team) [![](https://img.shields.io/pub/v/path_provider.svg)](https://pub.dartlang.org/packages/path_provider) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/path_provider) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/path_provider)

A Flutter plugin for finding commonly used locations on the filesystem. Supports iOS and Android.

```dart
Directory tempDir = await getTemporaryDirectory();
String tempPath = tempDir.path;

Directory appDocDir = await getApplicationDocumentsDirectory();
String appDocPath = appDocDir.path;
```

---

## open_file [![](https://img.shields.io/pub/v/open_file.svg)](https://pub.dartlang.org/packages/open_file) [![](https://img.shields.io/github/last-commit/crazecoder/open_file.svg)](https://github.com/crazecoder/open_file) [![](https://img.shields.io/github/stars/crazecoder/open_file.svg?style=social)](https://github.com/crazecoder/open_file)

A plug-in that can call native apps to open files with string result in flutter. Supports iOS (UTI) and Android (Intent)

```dart
import 'package:open_file/open_file.dart';

OpenFile.open("/sdcard/example.txt");
```

<br>

# Persistance

## Shared preferences (Flutter Team) [![](https://img.shields.io/pub/v/shared_preferences.svg)](https://pub.dartlang.org/packages/shared_preferences) [![](https://img.shields.io/github/last-commit/flutter/plugins.svg)](https://github.com/flutter/plugins/tree/master/packages/shared_preferences) [![](https://img.shields.io/github/stars/flutter/plugins.svg?style=social)](https://github.com/flutter/plugins/tree/master/packages/shared_preferences)

Flutter plugin for reading and writing simple key-value pairs. Wraps NSUserDefaults on iOS and SharedPreferences on Android.

```dart
incrementCounter() async {
  SharedPreferences prefs = await SharedPreferences.getInstance();

  int counter = (prefs.getInt('counter') ?? 0) + 1;
  print('Pressed $counter times.');
  
  await prefs.setInt('counter', counter);
}
```

---

## sqflite [![](https://img.shields.io/pub/v/sqflite.svg)](https://pub.dartlang.org/packages/sqflite) [![](https://img.shields.io/github/last-commit/tekartik/sqflite.svg)](https://github.com/tekartik/sqflite) [![](https://img.shields.io/github/stars/tekartik/sqflite.svg?style=social)](https://github.com/tekartik/sqflite)
SQLite plugin for Flutter. Supports both iOS and Android.

- Support transactions and batches
- Automatic version management during open
- Helpers for insert/query/update/delete queries
- DB operation executed in a background thread on iOS and Android

---

## redux_persist [![](https://img.shields.io/pub/v/redux_persist.svg)](https://pub.dartlang.org/packages/redux_persist) [![](https://img.shields.io/github/last-commit/Cretezy/redux_persist.svg)](https://github.com/Cretezy/redux_persist/tree/master/packages/redux_persist) [![](https://img.shields.io/github/stars/Cretezy/redux_persist.svg?style=social)](https://github.com/Cretezy/redux_persist/tree/master/packages/redux_persist)
Persist Redux state across app restarts in Flutter, Web, or custom storage engines.

Features:
- Save and load from multiple engine (Flutter, Web, File, custom)
- Fully type safe
- Transform state and raw on load/save
- Custom serializers
- Easy to use, integrate into your codebase in a few minutes!

---

## CookieJar [![](https://img.shields.io/pub/v/cookie_jar.svg)](https://pub.dartlang.org/packages/cookie_jar) [![](https://img.shields.io/github/last-commit/flutterchina/cookie_jar.svg)](https://github.com/flutterchina/cookie_jar) [![](https://img.shields.io/github/stars/flutterchina/cookie_jar.svg?style=social)](https://github.com/flutterchina/cookie_jar)
A cookie manager for http requests in Dart, by which you can deal with the complex cookie policy and persist cookies easily.

```dart
import 'package:cookie_jar/cookie_jar.dart';
void main() async {
  List<Cookie> cookies = [new Cookie("name", "wendux"), new Cookie("location", "china")];
  var cj = new CookieJar();
  //Save cookies   
  cj.saveFromResponse(Uri.parse("https://www.baidu.com/"), cookies);
  //Get cookies  
  List<Cookie> results = cj.loadForRequest(Uri.parse("https://www.baidu.com/xx"));
  print(results);  
}  
```

---

## sembast [![](https://img.shields.io/pub/v/sembast.svg)](https://pub.dartlang.org/packages/sembast) [![](https://img.shields.io/github/last-commit/tekartik/sembast.dart.svg)](https://github.com/tekartik/sembast.dart) [![](https://img.shields.io/github/stars/tekartik/sembast.dart.svg?style=social)](https://github.com/tekartik/sembast.dart)

NoSQL persistent embedded file system document-based database for Dart VM and Flutter with encryption support.

```dart
await db.put('Simple application', 'title');
await db.put(10, 'version');
await db.put({'offline': true}, 'settings');

// read values
String title = await db.get('title') as String; 
int version = await db.get('version') as int;
Map settings = await db.get('settings') as Map;
  
// ...and delete
await db.delete('version');
```

---

## hydrated [![](https://img.shields.io/pub/v/hydrated.svg)](https://pub.dartlang.org/packages/hydrated) [![](https://img.shields.io/github/last-commit/lukepighetti/hydrated.svg)](https://github.com/lukepighetti/hydrated) [![](https://img.shields.io/github/stars/lukepighetti/hydrated.svg?style=social)](https://github.com/lukepighetti/hydrated)

Hydrated provides a BehaviorSubject that automatically persists to Flutter's local storage and hydrates on creation!

All values are persisted with shared_preferences and restored with automatic hydration.

```dart
final count$ = HydratedSubject<int>("count", seedValue: 0);

/// count$ will automatically be hydrated with 42 next time it is created
count$.add(42);
```

---

## objectdb_flutter [![](https://img.shields.io/pub/v/objectdb_flutter.svg)](https://pub.dartlang.org/packages/objectdb_flutter) [![](https://img.shields.io/github/last-commit/netz-chat/objectdb_flutter.svg)](https://github.com/netz-chat/objectdb_flutter) [![](https://img.shields.io/github/stars/netz-chat/objectdb_flutter.svg?style=social)](https://github.com/netz-chat/objectdb_flutter)
Reactive ObjectDB helper.

```dart
db = ObjectDB(File(dbFilePath));
db.open();
// insert sample data
db.insert({
  'name': {'first': 'Alex', 'last': 'Boyle'},
  'message': 'abc',
  'active': true,
  'count': 0,
});
```

---

## mkvv_flutter [![](https://img.shields.io/pub/v/mmkv_flutter.svg)](https://pub.dartlang.org/packages/mmkv_flutter) [![](https://img.shields.io/github/last-commit/yuyongmao/mmkv_flutter.svg)](https://github.com/yuyongmao/mmkv_flutter) [![](https://img.shields.io/github/stars/yuyongmao/mmkv_flutter.svg?style=social)](https://github.com/yuyongmao/mmkv_flutter)

Plugin that allow Flutter to read value from persistent storage or save value to persistent storage based on MMKV framework.

```dart
MmkvFlutter mmkv = await MmkvFlutter.getInstance();

mmkv.setBool('boolKey', true);
print('get bool value is ${ await mmkv.getBool('boolKey')}');

String stringtest = await mmkv.getString('stringKey') + '1';
print('GetSetStringTest value is $stringtest');
await mmkv.setString('stringKey', stringtest);
```

<br>

# Logging & Error Handling

## logging (Flutter Team) [![](https://img.shields.io/pub/v/logging.svg)](https://pub.dartlang.org/packages/logging) [![](https://img.shields.io/github/last-commit/dart-lang/logging.svg)](https://github.com/dart-lang/logging) [![](https://img.shields.io/github/stars/dart-lang/logging.svg?style=social)](https://github.com/dart-lang/logging)

Provides APIs for debugging and error logging. This library introduces abstractions similar to those used in other languages, such as the Closure JS Logger and java.util.logging.Logger.

```dart
Logger.root.level = Level.ALL;
Logger.root.onRecord.listen((LogRecord rec) {
  print('${rec.level.name}: ${rec.time}: ${rec.message}');
});
```

---

## catcher [![](https://img.shields.io/pub/v/catcher.svg)](https://pub.dartlang.org/packages/catcher) [![](https://img.shields.io/github/last-commit/jhomlala/catcher.svg)](https://github.com/jhomlala/catcher) [![](https://img.shields.io/github/stars/jhomlala/catcher.svg?style=social)](https://github.com/jhomlala/catcher)

Plugin for error catching. Allows handling errors when they're not catched by developer. Plugin provides multiple handlers for errors.

```dart
main() {
  var debugOptions = CatcherOptions(
    DialogReportMode(),
    [ConsoleHandler()],
  );
  var releaseOptions = CatcherOptions(
    DialogReportMode(),
    [EmailManualHandler(["recipient@email.com"])],
  );

  Catcher(MyApp(), debugConfig: debugOptions, releaseConfig: releaseOptions);
}
```