پروژه روشن و خاموش شدن دو چراغ به صورت همزمان
int led = 9;
int led2 = 13;
void setup() {
  // put your setup code here, to run once:
pinMode(led,OUTPUT);
pinMode(led2,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(led,HIGT);
digitalWrite(led2,HIGT);
delay(5000);
digitalWrite(led,LOW);
digitalWrite(led2,LOW);
delay(500);
}
در این کد هم زمان led1 و led2 1 یک ثانیه روشن و یک ثانیه خاموش میشوند
int led = 9;
int led2 = 13;
void setup() {
  // put your setup code here, to run once:
pinMode(led,OUTPUT);
pinMode(led2,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(led,HIGT);
digitalWrite(led2,HIGT);
delay(5000);
digitalWrite(led,LOW);
digitalWrite(led2,LOW);
delay(500);
}
در این کد هم زمان led1 و  led2 پنج ثانیه روشن و نیم ثانیه خاموش میشوند
