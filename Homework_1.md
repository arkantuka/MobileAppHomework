```Dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Homework 1',
      home: Scaffold(
        appBar: AppBar(title: Center( child: Text('Tanawat Silsa-ard'),)),   
        body: Center(
          child: Text('ชื่อ : ธนวัต ศิลป์สะอาด\nรหัสนักศึกษา : 630710654',
            style: TextStyle(
            fontSize: 24.0,
            fontWeight: FontWeight.bold,
            color: Color.fromARGB(189, 5, 87, 180),
            ),
          ),
        ),
      ),
    );
  }
}
```
