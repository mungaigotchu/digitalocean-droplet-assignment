# digitalocean-droplet-assignment
doctl compute droplet create moodle-droplet \
  --region nyc1 \
  --size s-2vcpu-4gb \
  --image ubuntu-22-04-x64 \
  --enable-backups \
  --enable-monitoring \
  --ssh-keys <your-key-fingerprint> \
  --tag-names moodle-assignment
https://github.com/your-username/digitalocean-droplet-assignment
1. Differences between Control Panel and CLI:
Control Panel is more visual and easier for beginners. CLI is faster once you're familiar.

2. Which method was more efficient and why?
CLI was more efficient because I could set everything with one command.

3. Why SSH key-based authentication is recommended:
It’s more secure and prevents password-based attacks.

4. What value do backups and monitoring add:
Backups protect my data; monitoring keeps me informed about server performance
