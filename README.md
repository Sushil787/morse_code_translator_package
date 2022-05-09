# Morse Code Translator


# Usage
Fist depend on the library by adding this to your package's `pubspec.yaml`:

```yaml
dependencies:
  morse_code_translator: ^0.0.1
```
Now inside your dart project you can import it.
```dart
import 'package:morse_code_translator/morse_code_translator.dart';
```
### Decoding Morse code
For this example we're going to use the following Morse code :
```dart
String  decodingValue = ".... .. / - .... . .-. . / .... --- .-- / .- .-. . / -.-- --- ..- ..--..";
```
Now, we have to decode the Morse code to corresponding string .First we initialize the object.
```dart
MorseCode  meroMorseCode = MorseCode();
var  de = meroMorseCode.deCode(decodingValue);
```

and the corresponding output can be seen
```dart
print("The morse code '$decodingValue' is decoded to corresponding String:");
print(de);
```
print statement is for test purpose we can use it with widgets by passing value to text widget or we can use it with TextField and pass value in onChanged property.
### Encoding 
```dart
String  encodingValue = "Hi there how are you?";
```
Now, we have to encode the String to corresponding Morse code .First we initialize the object.
```dart
MorseCode  meroMorseCode = MorseCode();
var  en = meroMorseCode.enCode(encodingValue);
```

and the corresponding output can be seen
```dart
print("The String '$encodingValue' is encoded to corresponding morse code:");

print("$en\n");
```
print statement is for test purpose we can use it with widgets by passing value to text widget or we can use it with TextField and pass value in onChanged property.

### I had implemented the library here, you can give a look and figure out how to use this library with widgets: https://github.com/Sushil787/MorseCodeTranslator
# Contributing 
Feel for opening a PR  with any suggestions !

