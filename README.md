# Comparing Multi-cluster Service Meshes

A website that compares the multi-cluster architectures and features of Kubernetes service meshes.

**NOTE**: This project is a prototype created as part of a master’s thesis and does not represent a fully functional and complete website, but should be seen as a work in progress.

## Supported Service Meshes 
Three service mesh solutions are current compared on the website.

| Service Mesh   | Version       |
| -------------  |:-------------:| 
| [Istio](https://istio.io/latest/)      | v1.10         | 
| [Consul Connect](https://www.consul.io/docs/connect) | v1.9          |  
| [Linkerd](https://linkerd.io/)        | v2.10         | 

## Feature Comparison
The feature comparison for each service mesh comprises four main categories, with each category consisting of multiple sub-categories.

| Primary Categories                      | Sub-categories                                                  |
| -------------                           |:---------------------------------------------------------------:| 
| Installation and Operational Management | Installation<br>Management<br>Mesh Expansion                    | 
| Traffic Management                      | Network Resilience<br>Load Balancing<br>Traffic Splitting       |  
| Service Discovery                       | Service Registration<br>DNS Naming Conventions<br>Health Checks | 
| Security                                | Authentication<br>Authorisation<br>Certificate Management       | 


## Contributing
Service meshes are evolving fast, with new versions releases regularly. To keep the website up-to-date, contributions via pull requests (however small) are welcome, and encouraged. Specific features, categories (or even service meshes) can be requested by creating a new issue, as can improvements to the website.
