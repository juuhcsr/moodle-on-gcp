# Modern Moodle on Google Cloud Platform (GCP)

**Welcome to a modern version of Moodle for GCP!**

<p align="center">
    <img src="../moodle-on-gcp/img/moodle-gcp.png">
</p>

This repo groups a set of resources designed by Google Cloud's Engineers specialized in Education that allow organizations to deploy [Moodle](https://moodle.com/) on top of GCP's high-scalable services, unlocking the prime benefits of a modern cloud native architecture (based on containers and [Kubernetes](https://kubernetes.io/) for one of the most utilized eLearning platforms around the World.

Below you can find the documentation that outlines all the different aspects related to the solution, like installation, details about tests and performance, initial vision about costs, and so on.

## Documentation (coming soon)

1. Project overview
2. Architecture
3. Repository organization
4. Deployment
   1. Pre-requisites
   2. File "env.sh"
   3. Deploying infrastructure
   4. Deploying persistent volume
   5. Deploying Moodle's namespace
   6. Deploying a persistent volume claim
   7. Building Moodle's container image
   8. Installing Moodle with Helm
   9. Deploying backend config
   10. Configuring SSL and forcing HTTPS redirect
   11. Deploying ingress
       1.  Google Cloud Load Balancer
       2.  NGINX
5.  Configuring Redis Cache with Moodle
6.  Running benchmark to check results