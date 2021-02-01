# dataArt-challange

## Contents
 - [Tech Stack](#stack)
 - [How to use it](#como-utilizarlo)
 - [Tech Debt](#tech-deb)
 
 ## Tech Stack
 
 1. [Docker](https://www.docker.com/ 
 2. Back Go 1.15 (#stack)
 3. Swagger with [Swag](https://github.com/swaggo/swag)
 4. Routing [Gorilla](https://github.com/gorilla)
 
 ## How to use it
 1. Download dataArt-challange executing command (#como-utilizarlo).
 ```sh
 $ go get -u https://github.com/miguelapabenedit/dataArt-challange
 ```
 2.in the root execute 
 ```sh
 $ docker run -p 8080:5000 data-art-challange
 ```
 2.in the root execute 
 ```sh
 $ docker build . -t data-art-challange
  ```
 4.Whait for docker to run and run swagger 
 ```sh
http://localhost:8080/swagger/index.html
 ```
 5.Configurations take place on
 ```sh
 ./Dockefile -- Go Api
  ```
  
  ## Tech Debt (#tech-deb)
  
  --Implement replace mockCache for a real Cache, and that will let us put an expiration time between requests.
 
 
