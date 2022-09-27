import random
from time import sleep

def generate_values():
  temperature = random.randint(10, 50)
  humidity = random.randint(10, temperature)
  return humidity, temperature

humidity = temperature = 0

while temperature < 45:
  humidity, temperature = generate_values()
  print('Humidity:', humidity, 'Temperature:', temperature)
  sleep(0.50)

print('High Temperature Detected')
