//C
#include <LiquidCrystal.h>

int RS = 7;
int E  = 8;
int D4 = 9;
int D5 = 10;
int D6 = 11;
int D7 = 12;

LiquidCrystal lcd(RS, E, D4, D5, D6, D7);

void setup()
{
  lcd.begin(16, 2);

  lcd.setCursor(1, 0);
  lcd.print("HELLO WORLD");
}

void loop()
{
}