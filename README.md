# tailwind_colors

Dart package exposing Tailwind Colors to be used in flutter in a way similar to the Material colors.

Installation
----
1. Add to your `pubspec.yaml` file:

```yaml
dependencies:
    tailwind_colors: any
```

2. Get the package via your IDE or via the command line by typing:
```bash
$ pub get
```

3. Import the `tailwind_colors` package
```dart
import 'package:tailwind_colors/tailwind_colors.dart;
```

How to Use
----
Tailwind Colors can be created and used in the same way as the usual Material color palette.


```dart
    // TWColors has shades starting from 100 up to 900 in increment of 100
    Color myColor = TWColors.gray.shade100;
    Color mySecondColor = TWColors.blue.shade900;
```
TWColors features:
-  gray
-  red
-  orange
-  yellow 
-  green
-  teal
-  blue
-  indigo
-  purple
-  pink

This package also features the TailwindUI color palette which can be accessed similarly:
```dart
    Color myTailwindUIColor = TWUIColors.cool_gray.shade50;
```

TWUIColors features all the TailwindUI counterparts to the normal Tailwind colors with the addition of:
-  The cool_gray color
- An additional <b>shade50</b> shade  


TODO
---

- [ ] Create a parser for tailwind configuration files. Placeholder code can be found [here](https://gist.github.com/MBeliou/be358b9c68035f6061681010c49b448c)
- [ ] Show colors in the IDE tooltip