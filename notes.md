
% in print can display a variable

 -- Variables --

int - integer -- 25 %d, 4 bytes
float - float -- 25.5 -> in print statement, %f, %.2f == 2 numbers after decimal point, 4 bytes
double - 15,16 digits after decimal %lf, 8 bytes
char - character, single quotes '', %c, 1 byte
strings - char variable_name[] = "string", %s, varies
bool - boolean, 0 or 1 / true or false, %d, 1 byte, requires <stdbool.h>

%3d -- specifies the width of an integer, adds space before number, or %-3d which adds spaces after
%03d -- adds zeroes instead of spaces
%+d -- checks if the number is negative

