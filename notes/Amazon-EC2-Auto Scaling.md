# Amazon EC2 Auto Scaling
 Escalar a quantidade de servidores de forma automática. (Cria novos servidores automaticamente)
- Adiciona ou remove automaticamente instancias do EC2 de acordo com condiçoes definidas pelo cliente.
- Scaling **dinâmico** ( acompanha a métrica do uso de CPU) e **preditivo** (através de Marchine Learning aprende o comportamento do uso daquela aplicação).

Ao definir o grupo de Auto Scaling define a capacidade minima e maxima, podendo o desejado também.

> Ex: Black Friday cria nonos servidores pois o site terá mais acessos **(alta demanda)**, passando a data ele tira os servidores que não é mais necessário, deixando um só novamente.

___
___

[⬅ Voltar ao índice](../README.md##estrutura)