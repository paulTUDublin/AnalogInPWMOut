# AnalogInPWMOut

The project included here is the basic operation of the analog-to-digital converter (ADC) on the STM32L432KC. Helper functions have been provided that handle the configuration of the pin modes (pinMode()), initialisation fo the ADC (initADC()), and reading of the ADC (readADC()). 
Please ensure you reveiw these function before uplaoding the code to your board.
This builds upon the work in [AnalogIn](https://github.com/paulTUDublin/AnalogIn) and uses the analog input value to modulate the the duty cycle of PWM output.

# Studio task/activity #2

Analog input and PWM out.

- [X] Copy or clone this [repository](https://github.com/paulTUDublin/AnalogInPWMOut) and open as a platformIO project.
- [ ] Verify the board is working as you alter the voltage at the input pin using the potentiometer on the board. Does the onboard LED (PB3 illuminate at the correct input voltage?)
- [ ] Use the oscilloscope to view the voltage at the PWM output pin.
- [ ] Add an LED and current limiting resistor to the PWM output pin and see those the LED's briightness change as the input voltage changes.
- [ ] Document any progress/changes in the README.md file (use [Markdown](https://www.markdownguide.org/cheat-sheet/) to format this document.) and upload your project to your GitHub repo.
