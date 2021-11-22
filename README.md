# Configmap-example
Configmap-example for the CI/CD user guide.
A ConfigMap is an API object used to store non-confidential data in key-value pairs. Kubernetes provides these values to your containers.
A ConfigMap allows you to decouple environment-specific configuration from your container images, so that your applications are easily portable.
When you write a configmap and give the PORT env a value, you should know you don't need to give different services different ports. you can put them all to default 3000. Remember to modify it in the values.yaml you write as well.
