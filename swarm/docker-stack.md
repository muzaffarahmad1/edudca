## Docker Stacks: 
> **Services are capable of running single repicated application across nodes in the cluster, but what if you need to deploy a more complex application consisting of multiple services ?**

> **A Stack is a collection of interrelated services that can be deployed and sclaed as a unit** 

### Create a Stack
```
docker stack deploy -c compose.yml mystack
docker stack ls
docker stack ps mystack
docker stack services mystack
docker stack rm mystack
docker service scale mysvc=3
```