//Code for Blinking LED//

import RPi.GPIO as GPIO		
import time
LED = 40			        
GPIO.setwarnings(False) 	
GPIO.setmode(GPIO.BOARD)	
GPIO.setup(LED, GPIO.OUT)	

while True:
   
        GPIO.output(LED,GPIO.HIGH)
        time.sleep(1)
        GPIO.output(LED,GPIO.LOW)
        time.sleep(1)


//Code for Traffic Light System//

from gpiozero import Button, TrafficLights, Buzzer    
from time import sleep    
    
buzzer = Buzzer(15)    
button = Button(21)    
lights = TrafficLights(25, 8, 7)    
    
while True:    
           button.wait_for_press()   
           buzzer.on()   
           light.green.on()    
           sleep(1)    
           lights.amber.on()    
           sleep(1)    
           lights.red.on()    
           sleep(1)    
           lights.off()   
           buzzer.off()
