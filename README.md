# Food 2 Vec

Running word2vec using the BBC food recipe archive.

11 de Septiembre del 2017.

Mis notas

Este proyecto usa deeplearning4j y gradle para compilar y crear el jar, por lo que crearé un proyecto con maven y las dependencias necesarias. Mientras, usaré este comando para lanzar una spark-shell

aroman@aroman:~/spark-distros/spark-2.2.0-bin-hadoop2.7$ clear && bin/spark-shell --driver-memory 1g --packages "org.deeplearning4j:deeplearning4j-core:0.9.1,org.deeplearning4j:deeplearning4j-ui:0.6.0,org.deeplearning4j:deeplearning4j-nlp:0.9.1,org.nd4j:nd4j-native:0.9.1,com.typesafe.scala-logging:scala-logging_2.11:3.7.2"
