# IoG_Version1

Desenvolver um sistema de interface de comunicação entre Gateway LoRa com Medidor Zeus8021.


Algumas características importantes desse sistema:
 -> Dispositivo Classe B, manda um pacote ao GW e só assim o GW irá mandar um frame DLMS/COSEM e iniciar o processo de comunicação;
 -> Transparente ao Protocolo DLMS/COSEM;
 -> Modo Sleep em torno de 330uA(Durabilidade de 727,28hs no modo de baixo consumo);
 -> Opção de modo fábrica, onde envia o Deveui para um PC, recebe outros parâmetros OTTA e grava no firmware. 
 
 
