# deployed-apps-using-fluxcd
Solution

I Deployed the apps using Fluxcd.
I created a vpc, kubernetes cluster, nodes amd lets encrypt certificates using terraform.
I built a website with a backend and Deployed with Docker, built the images and pushed to Dockerhub.
I then used the image in kubernetes to Deploy the app using fluxcd. 
I Deployed the sock app using fluxcd.
Also set up monitoring with prometheus and grafana and logging with loki to scape metrics.
I set up alerts and notifications for slack. I also set up http_responses for prometheus.
All these was Deployed with flux and kubernetes and terraform to build my infrastructures.
I also created an nginx ingress for my portfolio app.

Created a loadbalancer for my app and registered my domain in route53 to route traffic to my Loadbalancers.


![sockshop](https://github.com/gladysgodwin/deployed-apps-using-fluxcd/assets/99274632/90c512ee-7979-4618-9eb3-57df1d35dd10)
