
```sh
k get deploy -owide
NAME       READY   UP-TO-DATE   AVAILABLE   AGE   CONTAINERS   IMAGES                     SELECTOR
postgres   1/1     1            1           79s   postgres     postgres:13.4-alpine3.14   app=postgres
redmine    1/1     1            1           79s   redmine      redmine:4.1.1              app=redmine
```
```sh
k get po -owide
NAME                        READY   STATUS    RESTARTS   AGE   IP              NODE                               NOMINATED NODE   READINESS GATES
postgres-55bb9b6498-g8sx8   1/1     Running   1          47s   10.100.219.16   kubernetes-gb-default-group-gb-0   <none>           <none>
redmine-74cf6f5bf5-kvk42    1/1     Running   0          47s   10.100.219.15   kubernetes-gb-default-group-gb-0   <none>           <none>
```
