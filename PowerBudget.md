Battery:
2080mAh als capaciteit

## Particle sensor
=> measurement: 72mA voor 28,9u dan is deze leeg
=> sleepmode: 5,07mA voor 410,26u dan is deze leeg

Bij ons is de measurement tijd 15s en de sleepmode tijd is 45s dus de totale tijd is 1 minuut. dus de sensor is 25 % van de tijd bezig met meten.
 
Dan zou sensor van 72mA die voor 25% van de tijd meet en voor 75% van de tijd in sleep is kunnen we voor u kunnen poweren.

Dus het gemiddelde verbruik is 21,8 mA (25 procent van 72 + 75 procent van 5,07 mA), Dus => 95,41u
-------------------------------------


Sensor die 15s (72mA) actief en 45s in sleep is (5,07mA).


72mA x 900s (25% van 3600s = 15 minuten) (totale tijd actief in 1u) = 64800mAs

5,07 x 2700s (75% van 3600s = 45 minuten) (totale tijd standby in 1u) = 13689mAs

64800mAs + 13689mAs = 78489mAs

78489mAs / 3600[s/h] = 21,8mAh

-------------------------------------

2080mAh - 21,8mAh = 2058,2mAh over na 1u

-------------------------------------------------------

## TPH-sensor

=> Humidity: 461µA voor 4511,93u dan is deze leeg.  Tijdsduur = 10ms
=> Temperature: 475µA voor 4378,95u dan is deze leeg. Tijdsduur = 10ms
=> Pressure: 474µA voor 4388,19u dan is deze leeg. Tijdsduur = 10ms
=> Sleep: 419µA voor 4964,2u dan is deze leeg.

Total measurecyclus: 30ms 

Totale tijd meet cyclus = 2700 ms (2,7s)

Dus het gemiddelde verbruik is 419,6132µA (0.37037% van 461µA  +  0.37037% van 475µA + 0.37037% van 474µA + 98.9% 419µA), 
Dus => 4956,95u

-------------------------------------

Sensor die 30ms actief is en 2670ms in seep is (419µA).

461µA x 13,33s (0.37037% van 3600s) = 6,14513mAs 
475µA x 13,33s (0.37037% van 3600s) = 6,33175mAs
474µA x 13,33s (0.37037% van 3600s) = 6,31842mAs
419µA x 3560,4s (98,9% van 3600)= 1491,8076mAs

6,14513mAs + 6,33175mAs + 6,31842mAs + 1491,8076mAs = 1510,6029mAs

1510,6029mAs / 3600[s/h] = 0,4196119mAh

-------------------------------------

2058,2mAh - 0,4196119mAh = 2057.78mAh over na 1u

-------------------------------------------------------




