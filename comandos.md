Comandos uteis Docker 
===================

docker container exec **{Id_CONTAINER} ** sh -c **"{comandoInterno}"**
**Exemplo:** **docker container exec 21b102e0fdc8 sh -c "cd /usr/share/java/kafka-connect-jdbc && ls -g"**

https://stackedit.io/editor

--docker logs conect
--docker logs schema_registry

docker exec -it -e KAFKA_OPTS="" connect kafka-avro-console-consumer --topic nomecontainer --from-beginning --bootstrap-server broker:29092 --property schema.registry.url=http://schema-registry:8081                                                                                              
