.PHONY: init
init: init-secret

.PHONY: init-secret
init-secret: 
	mkdir -p .secret/__envrc.d
	cp -rf $(HOME)/.kcde/var/secret/keplercheuvreux/kc-dataengineering/data-elastic/__envrc.d .secret/
	cp -rf $(HOME)/.kcde/var/secret/keplercheuvreux/kc-dataengineering/data-elastic/_ops_data_elastic_elasticsearch .secret/
	cp -rf $(HOME)/.kcde/var/secret/keplercheuvreux/kc-dataengineering/data-elastic/_ops_data_elastic_kibana .secret/
