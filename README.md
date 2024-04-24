# vulnerable-lab
vulnerable docker lab

# Setup
1. clone repo
```
git clone https://github.com/miko550/vulnerable-lab.git
cd vulnerable-lab
```
2. Start lab
```
docker compose up -d
```
3. To stop lab
```
docker compose down
```

# Lab Range
## Juice Shop
```
http://<vps IP>:3000
```
## DVWA
```
http://<vps IP>:8080
```
## Metasploitable2
```
ssh root:<vps IP>
nmap 10.10.6.10
```

