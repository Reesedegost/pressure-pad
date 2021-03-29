# limit-switch

int Light = 22; 

void setup(){
  pinMode(Light, OUTPUT); 
}

void loop(){
 do{
     digitalWrite(Light, HIGH);
  }while(!waitMilliseconds(20);
    digitalWrite(Light, LOW);
  }
  
  
