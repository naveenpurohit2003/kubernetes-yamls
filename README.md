Oracle VirtualBox:  https://www.virtualbox.org/

Link to download VM images: http://osboxes.org/

Link to kubeadm installation instructions: https://kubernetes.io/docs/setup/independent/install-kubeadm/



Important Notice!! 
If you are following along with your own setup, make sure to use the below command for setting up Networking with Flannel. The command in the Kubernetes Documentation web site seems to be having an issue.

kubectl create -f https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml
