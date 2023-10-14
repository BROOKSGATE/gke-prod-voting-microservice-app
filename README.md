# gke-prod-voting-microservice-app
gke-prod-voting-microservice-app

37  gcloud container clusters get-credentials dev-prod-cluster --zone northamerica-northeast1-a --project celestial-gist-401022
   38  kubectl get nodes
   39  gcloud container clusters get-credentials dev-prod-cluster --zone northamerica-northeast1-a --project celestial-gist-401022
   40  kubectl get nodes
   41  ls
   42  git clone https://github.com/BROOKSGATE/gke-prod-voting-microservice-app.git
   43  ls
   44  cd gke-prod-voting-microservice-app/
   45  ls
   46  ll
   47  kubectl get ns
   48  kubectl get all
   49  kubectl create ns votingapp-dev
   50  kubectl get ns
   51  ll
   52  kubectl apply -f postgres-deployment.yml -n votingapp-dev
   53  ls
   54  cd gke-prod-voting-microservice-app/
   55  ll
   56  kubectl apply -f postgres-deployment.yml -n votingapp-dev
   57  kubectl get pods
   58  kubectl get po
   59  kubectl get po -n votingapp-dev
   60  ls
   61  kubectl apply -f . -n votingapp-dev
   62  kubectl get po -n votingapp-dev
   63  kubectl get deploy -n votingapp-dev
   64  kubectl get svc -n votingapp-dev
