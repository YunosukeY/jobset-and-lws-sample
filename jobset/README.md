# JobSet の検証

クラスタ作成

```
kind create cluster --config=kind.yaml
```

JobSet インストール

```
kubectl apply --server-side -f https://github.com/kubernetes-sigs/jobset/releases/download/v0.8.2/manifests.yaml
```

JobSet デプロイ

```
kubectl apply -f jobset.yaml
```
