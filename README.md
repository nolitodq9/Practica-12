# Practica-12
Modificación Texto Arduino
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH); // LUZ 13 encendida
  delay(10000); // Wait for 10000 millisecond(s) Espera 10 segundos
  digitalWrite(13, LOW); // Luz 13 apagada
  delay(4000); // Wait for 4000 millisecond(s) Espera 4 segundos
  digitalWrite(12, HIGH); // Luz 12 Encendida
  digitalWrite(11, HIGH); // Luz 11 Encendida
  delay(10000); // Wait for 10000 millisecond(s) Espera 10 segundos
  digitalWrite(12, LOW); // Luz 12 Apagada
  digitalWrite(11, LOW); // Luz 11 apagada
  delay(4000); // Wait for 4000 millisecond(s) Espera 4 segundos
}
