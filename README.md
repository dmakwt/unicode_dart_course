# Dart #1


- main method
```dart
void main() {
  
}
```

- print function
```dart
void main() {
  print('أهلا وسهلا');
}
```

------------------------

- variables (start with lowercase, Camel case, can't start with @ ! etc, you can start with $)
```dart
void main() {
   String name = 'Dhari';
   String name2 = "Dhari";
   int age = 24;
   double height = 174.5;
   bool likesPizza = true;
    
   print(name);
   print(age);
}
```


- var keyword
```dart
void main() {
   var name = 'Dhari';
   var age = 23;
   var height = 174.5;
   var likesPizza = true;
    
   print(name);
   print(age);
}
```
- dynamic
```dart
void main() {
  dynamic name2 = 'Dhari';
  print(name2);

  name2 = 20;
  print(name2);
}
```

- var vs const

```dart
void main() {
  var age = 22;
  print(age);
  
  age = 25;
  print(age);

  const age1 = 22;
  print(age1);
  
  final age2 = 22;
  print(age2);
}
```

- null safety
```dart
void main() {
  String value1 = 'abc'; // String
  //  String value1 = null; -> error
  
  String? value2 = null; // null or String

  print(value1);
  print(value2);
}
```


------------------------

- طباعة المتغير داخل نص
```dart
void main() {
   var name = 'Dhari';
   var age = 23;
   print('Name: $firstName, age: $age');
}
```


- Convert String to double or int
```dart
void main() {
  String height3 = '170';
  double height4 = 4;
  
  // print(height3 + height4);  -> error
  
  print(double.parse(height3) + height4);
}
```

- Convert int or double to String
```dart
void main() {
  int age = 50;
  String myAge = age.toString();
  print(myAge);
  
  // or
  int age = 50;
  String myAge = '$age';
  print(myAge);
  
}

- Comments
```dart
void main() {
  // Hi
  
  /*
    test
    test
  */
}
```

------------------------

- String methods - toUpperCase(), toLowerCase()
```dart
void main() {
   String title = 'Flutter course';
   print(title.toUpperCase());
   
  title = title.toLowerCase();
  print(title);
}
```

- String methods - replaceAll()
```dart
void main() {
  String myFood = 'I love pasta';
  print(myFood);
  String myFood2 = myFood.replaceAll('pasta', 'pizza');
  print(myFood2);
}
```

------------------------

- Arithmatics ( + - * / )
```dart
void main() {
  int x = 10;
  int x2 = 20;
  print(x + x2);

  int x3 = x + 11;
  print(x3);
}
```

- Operators (== , != , >= , > , <= , <)
```dart
void main(){
  print(10 == 5);
  print(10 != 5);
  print(10 >= 5);
  print(10 > 5);
  print(10 <= 5);
  print(10 < 5);
}
```

- Operators (|| , &&)
```dart
void main(){
  print(10 < 5 || 5 < 7);
  print(10 < 5 && 5 < 7);
}
```

- Operators (!)
```dart
void main(){
  print(!(10 > 5));
}
```
------------------------

### Part2 - Conditions

- if condition
```dart
void main() {
  var grade = 80;

  if (grade >= 90) {
    print('A');
  } else if (grade >= 80) {
    print('B');
  } else if (grade >= 70) {
    print('C');
  } else if (grade >= 60) {
    print('D');
  } else {
    print('F');
  }
}
```





















