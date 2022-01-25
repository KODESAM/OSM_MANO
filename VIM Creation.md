VIM Account addition in MANO

````
osm vim-create --name aws-site-default --account_type aws --auth_url https://ec2.eu-central-1.amazonaws.com --user AKIAZOAMNP7 --password lBlqEgXDSLIFWQr0uEmSBBPe6TTG --tenant osm2 --description "AWS VIM"  --config '{key_pair: nms, region_name: eu-central-1, flavor_info: "{t2.nano: {cpus: 1, disk: 100, ram: 512}, t2.micro: {cpus: 1, disk: 100, ram: 1024}, t2.small: {cpus: 1, disk: 100, ram: 2048}, t2.medium: {cpus: 2, disk: 100, ram: 4096}}"}'
````
