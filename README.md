# Clase para usar shared_preferences

## Intalaciones
- [shared_preferences](https://pub.dev/packages/shared_preferences)

## Modificación
main.dart
````sh
void main() async {
  WidgetsFlutterBinding.ensureInitialized();
  await Preferences.init();
  runApp(const MyApp());
}
````
