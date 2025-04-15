import 'package:flutter/material.dart';

void main() {
runApp(FlutterApp());
}

class FlutterApp extends StatelessWidget {
final ValueNotifier<bool> _dark = ValueNotifier<bool>(true);
final ValueNotifier<double> _widthFactor = ValueNotifier<double>(1.0);