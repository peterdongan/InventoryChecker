# InventoryChecker
Java Spring Boot project designed to be [easily] split into microservices. The features are arbitrary and minimalist. The main objective was to make it as easy as possible to split it into microservices in order to facilitate learning.

The repo includes an API and a Web client in separate Maven projects, along with dockerfiles and a docker-compose file. This provides a framework to help you to refactor the API into microservices. A SQLite database is included which is only read from (not written to). This should also be split to provide individual databases for the Microservices.

Code was based on https://gitlab.com/cpit490/product-shipping-app and is licenced under the MIT licence. That repo is part of the lab published here: https://cpit490.gitlab.io/labs/lab-8/. The linked lab is a useful reference for refactoring this project.

