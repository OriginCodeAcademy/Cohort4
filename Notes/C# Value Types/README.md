# C# Value Types

You can read more about value types on the Microsoft Developer Network website here<br />
https://msdn.microsoft.com/en-us/library/ms228360(v=vs.90).aspx

```csharp
// Boolean
bool b 		= true;								// True/False

// Integral Numbers
byte b 		= 255;		 						// 0 to 255
sbyte sb 	= -128;	 							// -128 to 127
int i 		= 2147483647;    					// -2,147,483,648 to 2,147,483,647
uint ui 	= 4294967295; 						// 0 to 4294967295
short s 	= 32767;	 						// -32,768 to 32767
ushort us 	= 65535;							// 0 to 65535
long l 		= 9223372036854775807;				// -9223372036854775808 to 9223372036854775807
ulong ul 	= 18446744073709551615; 			// 0 to 18446744073709551615

// Floating Point Numbers
float f  	= 3.141592F;						// -3.402823e38 to 3.402823e38
double d 	= 3.14159265358979;					// -1.79769313486232e308 to 1.79769313486232e308
decimal m   = 3.1415926535897932384626433832; 	// 	±1.0 × 10e−28 to ±7.9 × 10e28

// Text
char c 		= 'c';								// Any unicode symbol used in text
string s    = "Origin Code Academy";			// !!Must be surrounded by double quotes!!

// Objects
object o = new object();						// Don't worry about this just yet......
```