## Covered Tech

- .NET Core (ASP.NET)
- React.js
- Angular
- Node.js (Express)
- Java (Spring Boot)
- Go (Golang)
- Python (Flask & Django)

---

## 1 .NET Core (ASP.NET)

### Install Dependencies

dotnet restore

### Run Project

dotnet run

### Folder Structure
```
MyApp/
├── Controllers/         
├── Models/              
├── Views/               
├── Program.cs           
├── Startup.cs           
├── appsettings.json
```   

## 2. React
### Install Dependencies

npm install
### Run Project

npm start
### Folder Structure
```
my-react-app/
├── src/
│   ├── components/      
│   ├── App.js           
│   └── index.js        
├── public/
│   └── index.html       
├── package.json
```      

## 3. Angular
### Install Dependencies

npm install
### Run Project

ng serve
### Folder Structure
```
my-angular-app/
├── src/
│   ├── app/
│   │   ├── components/   
│   │   └── app.component.ts
│   └── index.html        
├── angular.json          
├── package.json
```
## 4. Node.js (Express)
###  Install Dependencies

npm install
### Run Project

node index.js
# or
nodemon index.js
### Folder Structure

my-node-app/
├── routes/              
├── server.js            
├── package.json         

## 5. Java (Spring Boot)
### Install Dependencies

# Maven
mvn install

# or Gradle
./gradlew build
##  Run Project

# Maven
mvn spring-boot:run

# or Gradle
./gradlew bootRun
### Folder Structure

my-spring-app/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/demo/
│       │       ├── DemoApplication.java   
│       │       └── Controller.java        
│       └── resources/
│           └── application.properties     
├── pom.xml  

## 6. Go (Golang)
### Install Dependencies

go mod tidy
### Run Project

go run main.go
### Folder Structure

my-go-app/
├── main.go           
├── go.mod               
## 7. Python
### Install Dependencies

pip install -r requirements.txt
### Run Project
# flask
flask run
# Django
python manage.py runserver



### Folder Structures
# Flask
```
my-flask-app/
├── app.py              
├── templates/           
├── static/              
├── requirements.txt    
```

# Django
```
my-django-app/
├── manage.py            # CLI tool
├── myproject/           # Main settings folder
│   └── settings.py
├── myapp/               # Business logic here
│   └── views.py
```

## Notes
Always check if you have required versions of tools like Node.js, Python, Go, JDK, .NET SDK, etc.

Use .env files to manage environment variables securely.

Dockerize your app for consistent deployment environments.

Use linters and formatters for clean code in each language.
