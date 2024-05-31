# proba
Proxecto de TIC I
Práctica 4. Ventilación con sensor de temperatura e humidade.
Utilizaremos un sensor DHT11 que mide temperatura e humidade para facer funcionar un ventilador que está é accionado por un relé.

Esta vez a automatización farémola completamente cos nodos de Node-Red, de tal maneira que cando a temperatura ou a humidade pasen dun determinado valor o relé activarase, facendo que o ventilador comece a funcionar.
O circuíto e o fluxo son os das imaxes.


Material necesario:
    • ESP32 WROOM + shield 
    
    • Sensor DHT11
    
    • Relé
    
    • Placa de conexións
    
    • Cables M-F
    
Pasos a seguir:
    1. O sensor e ventilador conectado ao relé están instalados nas maquetas.
    2. Abrimos o programa Practica5_DHT11_Rele.ino no IDE de Arduino e facemos todas as modificacións necesarias para que funcione no noso servidor e co noso equipo:
        1. Datos rede wifi.

![maqueta24(1)](https://github.com/tecnoteis/proba/assets/126872606/b2b6c308-a8da-4a58-bbef-312feeab9f68)

        
