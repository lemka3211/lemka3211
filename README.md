#include <HID-Project.h>
#include <HID-Settings.h>

void setup() {
  delay(2000);
}

void loop() {
  for (int i = 0; i < 1000; i++) {
    Mouse.click(MOUSE_LEFT);
    delay(1);
  }
}
