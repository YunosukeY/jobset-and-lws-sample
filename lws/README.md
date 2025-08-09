# LeaderWorkerSet の検証

クラスタ作成

```
kind create cluster --config=kind.yaml
```

LWS インストール

```
kubectl apply --server-side -f https://github.com/kubernetes-sigs/lws/releases/download/v0.6.3/manifests.yaml
```

LWS デプロイ

```
kubectl apply -f lws.yaml
```
