# my-kubeflow
kubeflow

images
docker pull gcr.azk8s.cn/kubeflow-images-public/ingress-setup:latest
docker pull gcr.azk8s.cn/kubeflow-images-public/admission-webhook:v20190520-v0-139-gcee39dbc-dirty-0d8f4c
docker pull gcr.azk8s.cn/kubeflow-images-public/kubernetes-sigs/application:1.0-beta
docker pull gcr.azk8s.cn/kubeflow-images-public/centraldashboard@sha256:4299297b8390599854aa8f77e9eb717db684b32ca9a94a0ab0e73f3f73e5d8b5
docker pull gcr.azk8s.cn/kubeflow-images-public/jupyter-web-app:9419d4d
docker pull gcr.azk8s.cn/kubeflow-images-public/katib/v1alpha3/katib-controller:v0.7.0
docker pull gcr.azk8s.cn/kubeflow-images-public/katib/v1alpha3/katib-manager:v0.7.0
docker pull gcr.azk8s.cn/kubeflow-images-public/katib/v1alpha3/katib-ui:v0.7.0
docker pull gcr.azk8s.cn/kubebuilder/kube-rbac-proxy:v0.4.0
docker pull gcr.azk8s.cn/kubeflow-images-public/metadata:v0.1.11
docker pull gcr.azk8s.cn/ml-pipeline/envoy:metadata-grpc
docker pull gcr.azk8s.cn/tfx-oss-public/ml_metadata_store_server:0.15.1
docker pull gcr.azk8s.cn/kubeflow-images-public/metadata-frontend:v0.1.8
docker pull gcr.azk8s.cn/ml-pipeline/api-server:0.1.31
docker pull gcr.azk8s.cn/ml-pipeline/visualization-server:0.1.27
docker pull gcr.azk8s.cn/ml-pipeline/persistenceagent:0.1.31
docker pull gcr.azk8s.cn/ml-pipeline/scheduledworkflow:0.1.31
docker pull gcr.azk8s.cn/ml-pipeline/frontend:0.1.31
docker pull gcr.azk8s.cn/ml-pipeline/viewer-crd-controller:0.1.31
docker pull gcr.azk8s.cn/kubeflow-images-public/notebook-controller@sha256:6490f737000bd1d2520ac4b8cbde2b09749cdb291b1967ddda95d05131db49db
docker pull gcr.azk8s.cn/kubeflow-images-public/profile-controller@sha256:9b834c9d44f9e4e8d5b9f8f01645afb84d5b3debcb177f3e49eac8ee46ae239d
docker pull gcr.azk8s.cn/kubeflow-images-public/kfam@sha256:3b0d4be7e59a3fa5ed1d80dccc832312caa94f3b2d36682524d3afc4e45164f0
docker pull gcr.azk8s.cn/kubeflow-images-public/pytorch-operator:v0.7.0
docker pull gcr.azk8s.cn/kubeflow-images-public/tf_operator:v0.7.0
docker pull gcr.azk8s.cn/kfserving/kfserving-controller@sha256:180d06026c4dd6c2d3ce4748efc896751b9bb6108b67a9eaa0e50158d6e10f1e
docker pull gcr.azk8s.cn/google_containers/spartakus-amd64:v1.1.0

docker pull docker.io/argoproj/workflow-controller:v2.3.0
docker pull docker.io/tensorflow/tensorflow:1.8.0
docker pull docker.io/seldonio/seldon-core-operator:0.4.1
docker pull docker.io/metacontroller/metacontroller:v0.3.0
docker pull docker.io/argoproj/argoui:v2.3.0
docker pull minio/minio:RELEASE.2018-02-09T22-40-05Z
docker pull mysql:5.6
docker pull mysql:8.0.3
