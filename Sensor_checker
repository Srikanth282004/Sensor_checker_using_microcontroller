#define ch_1 0
#define ch_2 1
#define ch_3 2
#define ch_4 3
#define ch_5 4
#define ch_6 5
#define ch_7 6
#define ch_8 7

void setup() {
  Serial.begin(9600);
  pinMode(ch_1, INPUT_PULLUP);
  pinMode(ch_2, INPUT_PULLUP);
  pinMode(ch_3, INPUT_PULLUP);
  pinMode(ch_4, INPUT_PULLUP);
  pinMode(ch_5, INPUT_PULLUP);
  pinMode(ch_6, INPUT_PULLUP);
  pinMode(ch_7, INPUT_PULLUP);
  pinMode(ch_8, INPUT_PULLUP);

}

void loop() {
  int value1 = digitalRead(ch_1);
  int value2 = digitalRead(ch_2);
  int value3 = digitalRead(ch_3);
  int value4 = digitalRead(ch_4);
  int value5 = digitalRead(ch_5);
  int value6 = digitalRead(ch_6);
  int value7 = digitalRead(ch_7);
  int value8 = digitalRead(ch_8);

  if (value1 == HIGH) {
    Serial.println("value1");
    delay(1000);
  } else if (value2 == HIGH) {
    Serial.println("value2");
    delay(1000);
  } else if (value3 == HIGH) {
    Serial.println("value3");
    delay(1000);
  } else if (value4 == HIGH) {
    Serial.println("value4");
    delay(1000);
  } else if (value5 == HIGH) {
    Serial.println("value5");
    delay(1000);
  }
  else if (value6 == HIGH) {
    Serial.println("value6");
    delay(1000);
  } 
  else if (value7 == HIGH) {
    Serial.println("value7");
    delay(1000);
  } 
  else if (value8 == HIGH) {
    Serial.println("value8");
    delay(1000);
  }
}
