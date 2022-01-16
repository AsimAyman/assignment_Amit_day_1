# assignment_Amit_day_1
import 'dart:io';

main() {
  try {
    print('please Enter your Name....');
    String name = stdin.readLineSync()!;
    print('please Enter your Age....');
    int age = int.parse(stdin.readLineSync()!);
    int date = 100 + (DateTime.now().year - age);
    print('You will be 100 years Old by $date');
  } catch (_) {
    print('Enter only numbers');
  }
}
