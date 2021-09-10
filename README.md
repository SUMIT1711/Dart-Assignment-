# Dart-Assignment-
Operators
void main() {
  int a = 4;
  int b = 5;
  int a2 = 6;
  int b2 = 8;

  // Adding a and b
  var c = a + b;
  var c2 = a2 + b2;
  print("Sum of a and b is $c");
  print("Sum of a2 and b2 is $c2");

  // Subtracting
  var d = a - b;
  var d2 = a2 - b2;
  print("The difference between a and b is $d");
  print("The difference between a2 and b2 is $d2");

  // Using unary minus
  var e = -d;
  var e2 = -d2;
  print("The negation of difference between a and b is $e");
  print("The negation of difference between a2 and b2 is $e2");

  // Multiplication
  var f = a * b;
  var f2 = a2 * b2;
  print("The product of a and b is $f");
  print("The product of a2 and b2 is $f2");

  // Division
  var g = b / a;
  var g2 = b2 / a2;
  print("The quotient of a and b is $g");
  print("The quotient of a2 and b2 is $g2");
  // Remainder of a and b
  var i = b % a;
  var i2 = b2 % a2;
  print("The remainder of a and b is $i");
  print("The remainder of a2 and b2 is $i2");

  // Greater between a and b
  var h = a > b;
  var h2 = a2 > b2;
  print("a is greater than b is $h");
  print("a2 is greater than b2 is $h2");

  // Smaller between a and b
  var y = a < b;
  var y2 = a2 < b2;
  print("a is smaller than b is $y");
  print("a2 is smaller than b2 is $y2");

  // Greater than or equal to between a and b
  var z = a >= b;
  var z2 = a2 >= b2;
  print("a is greater than b is $z");
  print("a2 is greater than b2 is $z2");

  // Less than or equal to between a and b
  var x = a <= b;
  var x2 = a2 <= b2;
  print("a is smaller than b is $x");
  print("a2 is smaller than b2 is $x2");

  // Equality between a and b
  var q = b == a;
  var q2 = b2 == a2;
  print("a and b are equal is $q");
  print("a2 and b2 are equal is $q2");

  // Unequality between a and b
  var s = b != a;
  var s2 = b2 != a2;
  print("a and b are not equal is $s");
  print("a2 and b2 are not equal is $s2");

  // Performing Bitwise AND on a and b
  var r = a & b;
  var r2 = a2 & b2;
  print(r);
  print(r2);

  // Performing Bitwise OR on a and b

  var t = a | b;
  print(t);
  var t2 = a2 | b2;
  print(t2);

  // Performing Bitwise XOR on a and b
  var u = a ^ b;
  print(u);
  var u2 = a2 ^ b2;
  print(u2);

  // Performing Bitwise NOT on a
  var f1 = ~a;
  print(f1);

  // Performing left shift on a
  var g1 = a << b;
  var g3 = a2 << b2;
  print(g1);
  print(g3);

  // Performing right shift on a
  var h1 = a >> b;
  print(h1);
  var h3 = a2 >> b2;
  print(h3);

  // Using And Operator
  bool c1 = a > 10 && b < 10;
  bool c3 = a2 > 10 && b2 < 10;
  print(c1);
  print(c3);

  // Using Or Operator
  bool d1 = a > 10 || b < 10;
  print(d1);

  // Using Not Operator
  bool e1 = !(a > 10);
  print(e1);

  // Assigning value to variable c
  var c4 = a * b;
  print(c4);
  var c5 = a2 * b2;
  print(c5);

  // Type Test operators
  var num = 10;
  var name = "Dart";
  print(num is int);
  print(name is! String);

// Conditional Operator
  var x1 = null;
  var y1 = 20;
  var val = x1 ?? y1;
  print(val);

  var a1 = 30;
  var output =
      a1 > 52 ? "value greater than 10" : "value lesser than equal to 30";
  print(output);
}
