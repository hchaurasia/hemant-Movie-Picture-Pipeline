# Movie Picture Pipeline

You've been brought on as the DevOps resource for a development team that manages a web application that is a catalog of Movie Picture movies. They're in dire need of automating their development workflows in hopes of accelerating their release cycle. They'd like to use Github Actions to automate testing, building and deploying their applications to an existing Kubernetes cluster.

The team's project is comprised of 2 applications.

1. A frontend UI written in Typescript, using the React framework
2. A backend API written in Python using the Flask framework.

There are two folders(Backend and Frontend) under starter having Application code


###  Deliverables

### Frontend

1. A Continuous Integration workflow Frontend Application.
     a. Lint and Test Jobs are running parallelly.
     b. All tests are passed
     c. Pipeline is executing automatically on pull_request
     d. Pipeline is executing manually as well without any error
     e. No output failures, screenshpts are attached

3. A Continuous Deployment workflow for Frontend Application
     a. Lint and Test Jobs are running parallelly.
     b. All tests are passed
     c. Pipeline is executing automatically on every push 
     d. Pipeline is executing manually as well without any error
     e. No output failures, screenshpts are attached

### Backend

1. A Continuous Integration workflow backend Application.
     a. Lint and Test Jobs are running parallelly.
     b. All tests are passed
     c. Pipeline is executing automatically on pull_request
     d. Pipeline is executing manually as well without any error
     e. No output failures, screenshpts are attached

3. A Continuous Deployment workflow for backend Application
     a. Lint and Test Jobs are running parallelly.
     b. All tests are passed
     c. Pipeline is executing automatically on every push 
     d. Pipeline is executing manually as well without any error
     e. No output failures, screenshpts are attached
   
### Frontend and Backend service URLs from K8s Cluster

- Frontend service URL: http://a0ccdf2c1f2e74fe4af7ba625f288e79-2130058383.us-east-1.elb.amazonaws.com

- Backend service URL: http://aaa5bd9a860964dbf8b8a99835e4528e-1367412076.us-east-1.elb.amazonaws.com

### K8s commands output for cluster

1. kubectl cluster-info
     - Kubernetes control plane is running at https://329BC3EE9BFA96332D4E25C2D1F2C86A.gr7.us-east-1.eks.amazonaws.com
     - CoreDNS is running at https://329BC3EE9BFA96332D4E25C2D1F2C86A.gr7.us-east-1.eks.amazonaws.com/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy
2. kubectl get svc
    - backend ->  aaa5bd9a860964dbf8b8a99835e4528e-1367412076.us-east-1.elb.amazonaws.com 
    - frontend    a0ccdf2c1f2e74fe4af7ba625f288e79-2130058383.us-east-1.elb.amazonaws.com  
 

 




