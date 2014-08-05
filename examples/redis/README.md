cluster/kubecfg.sh -c examples/redis/redis-master.json create pods
cluster/kubecfg.sh -c examples/redis/redis-master-service.json create services
cluster/kubecfg.sh -c examples/redis/redis-master-service-external.json create services
cluster/kubecfg.sh -c examples/redis/redis-slave-controller.json create replicationControllers
cluster/kubecfg.sh -c examples/redis/redis-slave-service.json create services
