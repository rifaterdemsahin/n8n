packcaged mode

To run **n8n** in Docker, follow these steps:

### **1. Install Docker**
Make sure Docker is installed on your machine. If not, download and install it from [Docker's official site](https://www.docker.com/).

### **2. Pull the n8n Docker Image**
Run the following command to pull the latest **n8n** Docker image:

```sh
docker pull n8nio/n8n
```

### **3. Run n8n in Docker**
You can run **n8n** using a simple command:

```sh
docker run -it --rm -p 5678:5678 n8nio/n8n
```
- `-it`: Runs the container in interactive mode.
- `--rm`: Removes the container after stopping it.
- `-p 5678:5678`: Maps port 5678 on the host to the container.
- `n8nio/n8n`: The Docker image.

Now, open **http://localhost:5678** in your browser to access the n8n UI.

---

### **4. Persistent Data (Optional)**
To avoid losing data when restarting, create a volume for **n8n**:

```sh
docker run -it --rm -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n
```
This stores n8n configuration in `~/.n8n`.

---

### **5. Run in Detached Mode (Background)**
To keep **n8n** running even after you close the terminal:

```sh
docker run -d --name n8n -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n
```
- `-d`: Runs in the background.
- `--name n8n`: Names the container `n8n`.

To stop it later:

```sh
docker stop n8n && docker rm n8n
```

---

### **6. Running with Environment Variables**
If you need **authentication** or external databases, pass environment variables:

```sh
docker run -d --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  -e N8N_BASIC_AUTH_ACTIVE=true \
  -e N8N_BASIC_AUTH_USER=admin \
  -e N8N_BASIC_AUTH_PASSWORD=password \
  n8nio/n8n
```
Now, n8n will require authentication with `admin:password`.

---

Would you like help setting up n8n with **Docker Compose** for easier management? 🚀