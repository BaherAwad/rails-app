# rails-app
Read me!

The hole code in one file >> rails-app.yaml
The Separated code in rest files.

create the application on namespace "rails-app"

1- Deploy postgres on a deployment.
2- created a secret for the postgres username and password.
3- Deploy redis on a deployment.
4- Create a ConfigMap for the file [.env] or we can use "kubectl create configmap env-file --from-file=.env -n rails-app"
5- Deploy drkiq on a deployment.
6- Deploy sidekiq on a deployment.
7- Deploy Nginx on a deployment.
8- Expose Deployment postgres on service postgres on port 5432
9- Expose Deployment redis on service redis on port 6379
10- Expose Deployment nginx on service nginx on port 8020
