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





![WhatsApp Image 2023-02-18 at 8 13 12 AM](https://user-images.githubusercontent.com/101311420/219941918-26933343-b0a1-4b96-b0e3-200449291936.jpeg)



![WhatsApp Image 2023-02-18 at 8 13 12 AM (1)](https://user-images.githubusercontent.com/101311420/219941903-02c2965b-4e47-441a-96c4-f0ab94e136f0.jpeg)
