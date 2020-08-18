# Test exam attempt 1

1. You are a project owner and need your co-worker to deploy a new version of your application to App Engine. You want to follow Google’s recommended practices. Which IAM roles should you grant your co-worker?
   - [Answer 01](img/test-exam/q01.png)
   - [Feedback 01](https://cloud.google.com/iam/docs/understanding-roles)
2. Your company has reserved a monthly budget for your project. You want to be informed automatically of your project spend so that you can take action when you approach the limit. What should you do?
   - [Feedback 02 a](https://cloud.google.com/appengine/pricing#spending_limit)
   - [Feedback 02 b](https://cloud.google.com/billing/docs/how-to/budgets)
3. You have a project using BigQuery. You want to list all BigQuery jobs for that project. You want to set this project as the default for the bq command-line tool. What should you do?
   [Feedback](https://cloud.google.com/bigquery/docs/reference/bq-cli-reference)
   [Feedback](https://cloud.google.com/sdk/gcloud/reference/config/set)
4. Your project has all its Compute Engine resources in the europe-west1 region. You want to set europe-west1 as the default region for gcloud commands. What should you do?
   [Feedback](https://cloud.google.com/compute/docs/regions-zones/changing-default-zone-region)

5. You developed a new application for App Engine and are ready to deploy it to production. You need to estimate the costs of running your application on Google Cloud Platform as accurately as possible. What should you do?
   [Feedback]()
6. Your company processes high volumes of IoT data that are time-stamped. The total data volume can be several petabytes. The data needs to be written and changed at a high speed. You want to use the most performant storage option for your data. Which product should you use?
   [Feedback](https://cloud.google.com/bigtable/docs/schema-design-time-series)
7. Your application has a large international audience and runs stateless virtual machines within a managed instance group across multiple locations. One feature of the application lets users upload files and share them with other users. Files must be available for 30 days; after that, they are removed from the system entirely. Which storage solution should you choose?
   [Feedback]()
8. You have a definition for an instance template that contains a web application. You are asked to deploy the application so that it can scale based on the HTTP traffic it receives. What should you do?
   [Feedback](https://cloud.google.com/compute/docs/instance-groups/#managed_instance_groups_and_autoscaling)
   [Feedback](https://cloud.google.com/compute/docs/images/export-image)
   [Feedback](https://cloud.google.com/compute/docs/load-balancing/http/adding-a-backend-bucket-to-content-based-load-balancing)
9. You are creating a Kubernetes Engine cluster to deploy multiple pods inside the cluster. All container logs must be stored in BigQuery for later analysis. You want to follow Google-recommended practices. Which two approaches can you take?
   - [Feedback](https://cloud.google.com/kubernetes-engine/docs/how-to/logging)
   - [Feedback](https://cloud.google.com/logging/docs/export/configure_export_v2)
   - [Feedback](https://kubernetes.io/docs/reference/labels-annotations-taints/)
10. You need to create a new Kubernetes Cluster on Google Cloud Platform that can autoscale the number of worker nodes. What should you do?
    [Feedback](https://cloud.google.com/kubernetes-engine/docs/concepts/cluster-autoscaler)

11. You have an application server running on Compute Engine in the europe-west1-d zone. You need to ensure high availability and replicate the server to the europe-west2-c zone using the fewest steps possible. What should you do?
12. Your company has a mission-critical application that serves users globally. You need to select a transactional, relational data storage system for this application. Which two products should you consider
13. You have a Kubernetes cluster with 1 node-pool. The cluster receives a lot of traffic and needs to grow. You decide to add a node. What should you do?
14. You created an update for your application on App Engine. You want to deploy the update without impacting your users. You want to be able to roll back as quickly as possible if it fails. What should you do?
    [Feedback](https://cloud.google.com/appengine/docs/admin-api/migrating-splitting-traffic)
15. You have created a Kubernetes deployment, called Deployment-A, with 3 replicas on your cluster. Another deployment, called Deployment-B, needs access to Deployment-A. You cannot expose Deployment-A outside of the cluster. What should you do?
    [Feedback](https://kubernetes.io/docs/concepts/services-networking/service/)
16. You need to estimate the annual cost of running a Bigquery query that is scheduled to run nightly. What should you do?

17. You want to find out who in your organization has Owner access to a project called "my-project".What should you do?

18. You want to create a new role for your colleagues that will apply to all current and future projects created in your organization. The role should have the permissions of the BigQuery Job User and Cloud Bigtable User roles. You want to follow Google’s recommended practices. How should you create the new role?
19. You work in a small company where everyone should be able to view all resources of a specific project. You want to grant them access following Google’s recommended practices. What should you do?
    [Feedback](https://cloud.google.com/sdk/gcloud/reference/iam/)
20. You need to verify the assigned permissions in a custom IAM role. What should you do?
    [Feedback](https://cloud.google.com/iam/docs/understanding-roles)
    [Feedback](https://cloud.google.com/iam/docs/creating-custom-roles)
