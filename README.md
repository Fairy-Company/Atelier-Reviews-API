#Atelier Reviews API 

Create a dedicated micro-service with modern architecture to boost performance and reliability of legacy API 

## Installation Instructions: 

- [ ] **Git Clone:** `git clone https://github.com/Fairy-Company/Atelier-Reviews-API.git`


- [ ] **Install the dependencies:**
`npm install`


- [ ] **Create DB:**
`Run the schema with ETL inside postgresql terminal`


- [ ] **Run the service:**
`npm run server-dev`

## Service Information: 

`1. Design a PostgreSQL schema for the reviews service` 

`2. Transform existing application data and load it into the database`

`3. Design and build an API server to provide data to the client in the format specified by the legacy API documentation`

`4. Optimize the service by analyzing query times and server responses`

`5. Deploy service on AWS` 

`6. Measure and improve the performance of the service at scale`

## Loaderio 
**No Optimization (1500 users per sec):**
![alt text]((https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6cb6286c-597e-48ad-a299-d0f1bcdda8f2/Screen_Shot_2022-08-06_at_3.54.54_PM.png)

**Load Balancer(2000 users per sec):**
![Screen Shot 2022-08-06 at 7.37.24 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/782730e0-2439-4af8-8fd5-e8ef6811d550/Screen_Shot_2022-08-06_at_7.37.24_PM.png)

**Load Balancer + Caching (2000 users per sec):**
![Screen Shot 2022-08-07 at 11.12.08 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/393debe1-8d8d-4570-a649-3b692485b4eb/Screen_Shot_2022-08-07_at_11.12.08_AM.png)




