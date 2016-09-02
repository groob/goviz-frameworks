Overview
---
I used [goviz](github.com/hirokidaichi/goviz) to vizualize the dependency graphs of various Go http frameworks/libraries.
Here are the results.
What would be even more interesting is to vizualize some of the projects which are using these frameworks. 
I saved a few of the graphs in the [Sample Applications] section below.


Web frameworks
---

## Gin

https://gin-gonic.github.io/gin/
![Gin](svg/gin.svg)

## Beego

http://beego.me/
![Beego](svg/beego.svg)

## Goji

https://github.com/zenazn/goji
![Goji](svg/goji.svg)

## Revel

https://revel.github.io/
![Goji](svg/revel.svg)

Microservice Frameworks
---

## Go Kit

http://gokit.io/
![Go Kit](svg/gokit-http.svg)

## Kite

https://github.com/koding/kite
![Kite](svg/kite.svg)

## Micro

https://github.com/micro/go-micro
![Kite](svg/micro.svg)

Sample Applications
---

## Built with net/http

- Vault https://github.com/hashicorp/vault
![Vault](svg/vault.svg)

## Built with go-kit


- Domain Drive Design Sample App https://github.com/marcusolsson/goddd
![goddd](svg/goddd.svg)

- SCEP Server (a single go-kit service) https://github.com/micromdm/scep
![SCEP Server](svg/scepserver.svg)

- MicroMDM (a collection of microservices packaged together)
![micromdm](svg/micromdm.svg)

## Built with Gin

- Drone CI https://github.com/drone/drone
![Drone](svg/drone.svg)



