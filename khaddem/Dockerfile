# Utilisez une image de base Java
FROM openjdk:11

  # Définissez le répertoire de travail dans le conteneur
WORKDIR /app

  # Exposez le port sur lequel votre application Spring Boot écoute
EXPOSE 8089
  # Copiez le fichier JAR de votre application dans le conteneur
ADD target/khaddem-4.0.jar khaddem-4.0.jar


  # Commande pour exécuter votre application Spring Boot
CMD ["java", "-jar", "khaddem-4.0.jar"]
