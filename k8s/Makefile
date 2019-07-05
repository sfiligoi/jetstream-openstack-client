.PHONY: configmap

all: configmap

configmap:
	-kubectl delete configmap jetstream-client -n isfiligoi
	kubectl create configmap jetstream-client -n isfiligoi \
             --from-file=TG-PHY190028-openrc.sh --from-file=iu-TG-PHY190028-openrc.sh

