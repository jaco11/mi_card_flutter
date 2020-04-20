# Flutter application

## Widget settings 

### Margins
Margin is for the outside of the widget

```
margin: EdgeInsets.all(20.0),
```
```
margin: EdgeInsets.symmetric(vertical: 50.0, horizontal: 10.0),
```
```
margin: EdgeInsets.fromLTRB(left, top, right, bottom)
```
```
margin: EdgeInsets.only(left: 30.0),
```
```
margin: EdgeInsets.fromLTRB(30.0, 10.0, 50.0, 20.0),
```

### Margins
Padding is for the inside of the widget
```
padding: EdgeInsets.all(20.0),
```
```
padding: EdgeInsets.symmetric(vertical: 50.0, horizontal: 10.0),
```
```
padding: EdgeInsets.fromLTRB(left, top, right, bottom)
```
```
padding: EdgeInsets.only(left: 30.0),
```
```
padding: EdgeInsets.fromLTRB(30.0, 10.0, 50.0, 20.0),
```

### Container 
```
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.teal,
        body: SafeArea(
          child: Container(
            height: 100.0,
            width: 100.0,
            margin: EdgeInsets.fromLTRB(30.0, 10.0, 50.0, 20.0),
            padding: EdgeInsets.all(20.0),
            color: Colors.white,
            child: Text('Hello'),
          ),
        ),
      ),
    );
  }
}
```

