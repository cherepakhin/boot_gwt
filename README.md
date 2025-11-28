Простое SprinBootApplication с каким-то отладочным окном с логами.
Оригинальный проект [https://github.com/zak905/boot-gwt](https://github.com/zak905/boot-gwt)
1. Сначала запустить `mvn spring-boot:run` (`run_step1.sh`)
2. И затем в отдельном shell `mvn gwt:devmode -Pgwt-dev` (`run_step2.sh`)
3. Открыть http://127.0.0.1:8080/index.html
в окне будет строка "Welcome to Gwt with Spring demo"
  

![окно с логом](doc/screen_index_html.png)

Кроме того, будет открыто dev:
![окно с логом](doc/screen_dev_log.png)

# Readme автора [https://github.com/zak905/boot-gwt](https://github.com/zak905/boot-gwt):

## Dev Mode

To run devmode: 

 and then in a different window `mvn gwt:devmode -Pgwt-dev`


## Production
`mvn clean -Pgwt-prod` and then `java -jar target/boot-gwt-0.0.1-SNAPSHOT.jar`