# minikube コマンド
- minikube start
    - kubernetesの実行環境を作成
- minikube status
- minikube delete 
- kubectl get pod
    - podの状態を確認 
- eval $(minikube docker-env) 
    - dockerコマンドをminikubeの仮想環境で実行できるように設定する。
- kubectl delete -f app.yaml
# skaffold
- skaffold init --force
- skaffold dev --port-forward
- skaffold run --port-forward


