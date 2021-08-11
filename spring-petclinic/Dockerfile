FROM maven
RUN git clone https://github.com/spring-projects/spring-petclinic.git
RUN cd spring-petclinic
EXPOSE 8080
CMD ./mvnw package
CMD java -jar target/*.jar


#FROM python
#RUN git clone https://github.com/anfederico/Flaskex
#RUN cd /Flaskex && pip install -r requirements.txt
#EXPOSE 5000
#CMD ["python", "/Flaskex/app.py"]


#git clone https://github.com/anfederico/Flaskex
#cd Flaskex
#pip install -r requirements.txt
#python app.py


#FROM openjdk:11.0.1-jre-slim-stretch
#EXPOSE 8080
#ARG JAR=spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar
#COPY target/$JAR /app.jar
#ENTRYPOINT ["java","-jar","/app.jar"]
