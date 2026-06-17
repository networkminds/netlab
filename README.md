# How to install Netlab and create topology yaml files

### 1. To install Netlab we need python installed Ubuntu OS (22.0.4 or 24.0.4).

### 2. Create python virtual environment using python3 and activate it. 
```bash
$ python3 -m venv netlab
$ source netlab/bin/activate
```

### 3. Install netlab using pip3 command.
```bash
$ pip3 install networklab
```

### 4. Check netlab installed version
```bash
$ netlab version
```
<img width="826" height="416" alt="image" src="https://github.com/user-attachments/assets/428e0ed5-80b3-466c-a9dd-7c1a5940ead3" />

### 5. Check which additional softwares should we install to netlab:
```bash
$ netlab install
```
<img width="639" height="203" alt="image" src="https://github.com/user-attachments/assets/5cb8b9bb-765e-46c4-a5a6-65b5da86755b" />

According to the list, we need to install following softwares:
```bash
$ netlab install ubuntu
$ netlab install containerlab
$ netlab install ansible
```
