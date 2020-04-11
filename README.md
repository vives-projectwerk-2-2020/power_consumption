# Particula powerconsumtion
This is a repository where we put information about how much energy every sensor uses.

## Particle sensor

![](img/particleSensor.png)

### Powerconsumption SDS011

|Technical Parameters   |   |Practical   |   |
|---|---|---|---|
|Rated voltage:   |5V   |Rated voltage:   |5V   |   |
|Rated Current:   |70mA±10mA  |Rated Current:   |91,5mA   |   |
|Sleep Current:   |<4 mA   |Sleep Current:   |5,07mA   |   |



### Practical

measurement setup:

![](./img/practicalParticleSenor.PNG)

### measure results

![](img/INandOUTsleep.png )

1 cycle takes 1 minute. In the red graph the sensor don't use the funtion sleepmode. In the green graph the sensor uses the function sleepmode. The sensor is 15s in working and 45s in sleepmode.

We see that the red graph consumes a power of 5,8 mWh.
The green graph consumes a power of 1,77 mWh. this is 70% less.

|   |1 hour   |1 day   |1 Week   |2 weeks   |
|---|---|---|---|---|
|Without sleepmode   |348mWh|8352mWh|58464mWh|116,9Wh|
|with sleepmode   |106mWh|2548,8mWh|17841mWh|35,7Wh|


## TPH senor

![](./img/BME280.PNG)

### Powerconsumption BME280

|Technical Parameters   |   |Practical   |   |
|---|---|---|---|
|Rated voltage:   |3V   |Rated voltage:   |3V   |
|Idd normal:   |94,9µA |Idd normal:   |445µA   |
|Sleep Current:   |0,1µA  |Sleep Current:   |419µA  |

### Practical

![](img/BME20ValueMeting.png)

![](img/BME280Powerconsumtion.png)

AVG current ≈ 438µA




