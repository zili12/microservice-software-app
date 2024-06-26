# Microservices Architecture with Docker: A Modular Approach for Diet and Meal Management
<h3>Developed a microservices-based architecture using `Docker` containers for a diet and meal management system. </h3>
<ol>
The architecture consists of four services:
  <li style="text-decoration: underline;"><strong>Diets</strong></li>
  <li><strong>Meals</strong></li>
  <li><strong>NGINX</strong></li>
  <li><strong>MongoDB</strong></li>
</ol>
Each service operates within its own package and contributes to the overall functionality. 

_Diets_ and _Meals_ are `Flask` applications, _NGINX_ acts as a `reverse-proxy server`, and _MongoDB_ is used as the `database`. 

The services are connected through a bridge network, enabling seamless communication and data management. 
The architecture offers scalability, modularity, and easy deployment, providing an efficient solution for managing diets and meals.
