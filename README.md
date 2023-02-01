# Nuvolar-Works-Part-2-Tecnical-Exercise-
# The file will deploy the three microservices in a Kubernetes cluster
# The Deployment resource defines how to deploy the three microservices and how many replicas to run.

# The Service resource defines how to expose the microservices to the network.

# The api-gateway-service is of type LoadBalancer which creates a load balancer in the cloud provider to access the service publicly.

# The order-service-service and customer-service-service are of type ClusterIP which creates a cluster-internal IP to access the services from within the cluster.

# Note: This YAML file assumes that the microservices listen on port 80. 


