# graphql-psql-k8s
Prisma/PostgreSQL on Kubernetes

## TL;DR

```
# Create PostgreSQL and Prisma instance on k8s
cd graphql-psql-k8s
kubectl create -f /k8s

# Create tables via Prisma
prisma deploy
cd ..

# Start GraphQL server on port 4010
cd graphql-yoga
yarn install
node src/index.js
```

## ToDo

- graphql-yoga on k8s