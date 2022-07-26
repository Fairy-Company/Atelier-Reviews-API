## Atelier Reviews API

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

`2. Transform legacy data, approximately 6 million records, and load it into the database`

`3. Design and build an API server to provide data to the client in the format specified by the legacy API documentation`

`4. Optimize the service by analyzing query times and server responses`

`5. Deploy service on AWS`

`6. Measure and improve the performance of the service at scale`

## Loaderio
`Last 10% of all reviews route`
</br>
### **No Optimization BottleNeck(1500 requests per sec):**

<p align="center">
<img src="/assets/1500RPS-NO.png" alt="1500 requests per sec with No optimization" width="70%"/>
</p>

### **Load Balancer + 2 Servers (2000 requests per sec):**
<p align="center">
<img src="/assets/2LB2000RPS.png" alt="2000 requests per sec with Load Balancer(NGINX) and two servers" width="70%"/>
</p>

### **Load Balancer + 2 Servers + Caching (3500 requests per sec):**
<p align="center">
<img src="/assets/2LBC3500RPS.png" alt="3500 requests per sec with Load Balancer(NGINX), two servers, and NGINX caching" width="70%"/>
</p>

### **CPU Utilization Load Balancer + 2 Servers + Caching @ (4000 requests per sec)**
<p align="center">
<img src="/assets/CPU-U-2LBC.png" alt="CPU Utilization Load Balancer + 2 Servers + Caching @ (4000 requests per sec)" width="70%"/>
</p>

### **Future Optimizations**

- Horizontally scale the database and loadbalancer 


## Technologies Used:

- Express v4.18.1
- PostgreSQL v8.7.3
- PostgreSQL v1.0.4
- K6
- Loader io


