deploy:
	kubectl apply -f nats/
	kubectl apply -f kubeless/
	kubectl apply -f network-policy.yaml
	kubectl apply -f .

clean:
	kubectl delete -f kubeless/
	kubectl delete -f nats/
	kubectl delete -f .
