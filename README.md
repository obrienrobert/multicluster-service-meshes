# Comparing Multi-cluster Service Meshes

A website that compares the multi-cluster architectures and features of Kubernetes service meshes.

**NOTE**: This project is a prototype created as part of a master’s thesis and does not represent a fully functional and complete website, but should be seen a work in progress.

## Supported Service Meshes 
Three service mesh solutions are current compared on the website.

| Service Mesh   | Version       |
| -------------  |:-------------:| 
| Istio          | v1.10         | 
| Consul Connect | v1.9          |  
| Linkerd        | v2.10         | 

## Features Comparison
The feature comparison for each service mesh comprises four main categories, with each category consisting of multiple sub-categories:

| Primary Categories                      | Sub-categories                                                  |
| -------------                           |:---------------------------------------------------------------:| 
| Installation and Operational Management | Installation<br>Management<br>Mesh Expansion                    | 
| Traffic Management                      | Network Resilience<br>Load Balancing<br>Traffic Splitting       |  
| Service Discovery                       | Service Registration<br>DNS Naming Conventions<br>Health Checks | 
| Security                                | Authentication<br>Authorisation<br>Certificate Management       | 

## Contributing
Service meshes are evolving fast, with new versions releases regularly. To keep the website up-to-date, contributions via pull requests (however small) are welcome, and encouraged.