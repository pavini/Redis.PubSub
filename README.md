# Mensageria Publish-Subscribe em .NET com Canais Redis


E aí, o que é o tal do padrão Publish-Subscribe?

Então, basicamente o Publish-Subscribe é um padrão de mensagens, onde um publicador manda mensagens para um canal compartilhado, e a galera que se inscreveu (os assinantes) pode escutar as mensagens que aparecem por lá. Normalmente temos um único publicador e vários assinantes. Se você tá montando um sistema distribuído, muito provavelmente vai ter que lidar com o Publish-Subscribe.

Este código é um exemplo do Pub-Sub em .Net 7 utilizando canais do Redis.