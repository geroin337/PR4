FROM openjdk:11
LABEL author="Tolkachev"
WORKDIR /app
COPY game.java /app/game.java
RUN javac game.java
CMD ["java", "game"]