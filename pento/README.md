# Pento

## yaml以外

docker ps -a
ls /etc/kubernetes/pki/
--client-ca-file=/etc/kubernetes/pki/ca.crtに書き換え
ちょっと待つ
nodeをスケジュール可能にする(cordon <=> uncordon)
kubectl uncordon node01
kubectl -n kube-system set image deploy coredns coredns=k8s.gcr.io/coredns:1.6.7
