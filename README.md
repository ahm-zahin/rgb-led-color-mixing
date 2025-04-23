```cpp

//color mixing in arduino uno
//zahin ahmed

const int red_light_pin= 11; //Selecting pin for red terminal of RGB LED
const int green_light_pin = 10; //Selecting pin for green terminal of RGB LED
const int blue_light_pin = 9; //Selecting pin for blue terminal of RGB LED

void setup() {
	pinMode(red_light_pin, OUTPUT); 
	pinMode(green_light_pin, OUTPUT); 
	pinMode(blue_light_pin, OUTPUT); 
}

void loop() {
	RGB_color(255, 0, 0); //Red colour
	delay(1000);
	RGB_color(0, 255, 0); //Green colour
	delay(1000);
	RGB_color(0, 0, 255); //Blue colour
	delay(1000);
	RGB_color(255, 255, 125); //Raspberry colour
	delay(1000);
	RGB_color(0, 255, 255); //Cyan colour
	delay(1000);
	RGB_color(255, 0, 255); //Magenta colour
	delay(1000);
	RGB_color(255, 255, 0); //Yellow colour
	delay(1000);
	RGB_color(255, 255, 255); //White colour
	delay(1000);
}

//User defined function to take data from the loop() function
void RGB_color(int red_light_value, int green_light_value, int blue_light_value) {
	analogWrite(red_light_pin, red_light_value);
	analogWrite(green_light_pin, green_light_value);
	analogWrite(blue_light_pin, blue_light_value);
}
