# Documentation

Here we document various parts of the effort to move monolithic applications to Kubernetes.

Feel free to add documentation as you see fit!

# The Saga

### Chapter 1 (The Application)

During the first round of community calls we looked at the application layer of the effort.
We explored various parts of migrating the application to _some_ cluster.
Our sessions can be found [here](https://www.youtube.com/playlist?list=PLvmPtYZtoXOG4dgpYIU2OJuDryMhEYyPw).

### Chapter 2 (The Cluster)

Now that we have a rough idea of what the application needs to be ran in Kubernetes, we can begin to design the cluster itself.
We have identified the following large topics that need to be addressed in order to run our application in Kubernetes.


# Kubernetes topics

### Cluster Design (Internal)

This is the design of the inner workings of the Kubernetes cluster.
This design doc will answer questions about what Kubernetes primitives need to be in place, and how they fit together.
Will you have deployments?
What will your namespaces be?
What will your RBAC settings look like?

### Cluster Design (External)

This is the design of the external parts of a Kubernetes cluster.
Where will you run your cluster?
How will you install it?
What will your machines look like?
How will you manage upgrading Kubernetes?

### Recoverability

This will highlight what you will do in case of a disaster.
Will you have automation in place?
Will tools will you use?

### Logging and Monitoring

This will define what logging and monitoring tools we will use.
What logging tool?
What monitoring tool?

### CI/CD

This will design the deployment pipeline for our Kubernetes cluster.
What tooling will we use?
What image registry will we use?

### Observability

This will define how we will address observability in our Kubernetes cluster.
Will we use a service mesh?
What about other parts of the stack?


### Security

What will security look like on the Kubernetes cluster?
How will your cluster be configured?