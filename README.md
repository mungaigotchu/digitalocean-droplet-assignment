# digitalocean-droplet-assignment
doctl compute droplet create moodle-droplet \
  --region nyc1 \
  --size s-2vcpu-4gb \
  --image ubuntu-22-04-x64 \
  --enable-backups \
  --enable-monitoring \
  --ssh-keys <your-key-fingerprint> \
  --tag-names moodle-assignment
