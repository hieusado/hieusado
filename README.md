#include<iostream>
int main() {
float x, y, a;
for (y = 1.5f; y > -1.5f; y -= 0.1f) {
for (x = -1.5f; x < 1.5f; x += 0.05f) {
a = x * x + y * y - 1;
putchar(a * a * a - x * x * y * y * y <= 0.0f ? '*' : ' ');
}
putchar('\n');
}
printf("I Love U <3\n");
return 0;
}
