web: envsubst < ./prometheus.yml > ./prometheus-injected.yml; envsubst < ./web.yml > ./web-injected.yml; envsubst < ./certs/console_prometheus_helium_wtf.crt > ./certs/console_prometheus_helium_wtf-injected.crt; envsubst < ./certs/console_prometheus_helium_wtf.key > ./certs/console_prometheus_helium_wtf-injected.key; /app/bin/prometheus --config.file=./prometheus-injected.yml --web.config.file=./web-injected.yml --web.listen-address=:$PORT
