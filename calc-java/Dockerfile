FROM openjdk:11
LABEL author="Tolkachev"
WORKDIR /app
COPY calc.java /app/calc.java
RUN javac calc.java
CMD ["java", "calc"]