<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

TODO: Put a short description of the package here that helps potential users
know whether this package might be useful for them.



## Getting started

Make your apps responsive by using this package.

## Usage
MediaQuery is great for making our apps responsive but still it was really hectic to use MediaQuery and write it again and again. So I came up with an idea to make a separate class for mediaquery and extract its powers.

```dart

import 'package:flutter/material.dart';
import 'package:responsive_mediaquery.dart';
void main() {
  runApp(  const MyApp());
}

class MyApp extends StatelessWidget {
  const  MyApp({Key? key}) : super(key: key);
  @override
  Widget build(BuildContext context) {
 Responsive().init(context);
    return  MaterialApp(
home:Scaffold(
body:Container(
width:Responsive.horizontalLength*100,
height:Responsive.verticalLength*100,
color:Colors.red,
)));
}
}
```

## Additional information

TODO: Tell users more about the package: where to find more information, how to 
contribute to the package, how to file issues, what response they can expect 
from the package authors, and more.
i