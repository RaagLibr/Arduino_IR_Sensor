# Arduino_IR_Sensor
    Obstacle Detector Using IR (InfraredSensor) .


  >int counter=0;
  void setup()
  >>{
      Serial.begin(9600);//Baud Rate of communicating Arduino with PC 
      pinMode(7,OUTPUT);
      pinMode(2,INPUT); 
       Serial.print("*** Project to Count Number of Persons Entering ***");
      Serial.print("\n");
      Serial.print("*** Created by: RLT College Students ***");
      Serial.print("\n");
      Serial.print("*** MSc II Year, 2022 ***");
      Serial.print("\n");
       Serial.print("-------------------------");
      Serial.print("\n");
    }
  >void loop()
   >>{
        if(digitalRead(2)==LOW)
        {
           counter++;
          Serial.print("Number of Persons Entering:");
    Serial.println(counter);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);    
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);    
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);    
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);    
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);
    digitalWrite(7,HIGH);
    delay(100);
    digitalWrite(7,LOW);
    delay(100);    
    delay(2000);
  }
  else
  digitalWrite(7,LOW);
}

