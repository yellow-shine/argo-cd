run:
	kubectl create -f guestbook-applicationset.yaml -n argocd
	kubectl create -f starwars-applicationset.yaml -n argocd
destroy:
	kubectl delete -f guestbook-applicationset.yaml -n argocd
	kubectl delete -f starwars-applicationset.yaml -n argocd
