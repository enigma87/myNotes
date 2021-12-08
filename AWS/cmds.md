

docker inspect -f '{{range $index, $value := .Config.Env}}{{$value}} {{end}}' container_name


