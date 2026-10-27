# Challenge

## 1.htop
Command: sudo apt install -y htop,then htop
Answer: htop shows live CPU and memory usagr.

## 2. apache2 version
Command: apt show apache2 | head -4
Answer: Version is 2.4.66-2ubuntu2.6

## 3. Installed packages
Command: apt list --installed | wc -1
Answer: 733 packages

## 4.Alpine
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: It printed Hello from Alpine.

## 5. Docker file paths
Command: ls /etc/apt/keyrings/ and ls /etc/apt/sources.list.d/
Answer: Key: /etc/apt/keyrings/docker.asc
Sources: /ets/apt/sources.list.d/docker.sources

## 6. Remove htop
Command: sudo apt remove -y htop. hash -r, htop
Answer: htop is removed, and it says command not found.
