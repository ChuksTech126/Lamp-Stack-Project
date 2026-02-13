# **TCP and UDP**

## **What is TCP?**

**TCP (Transmission Control Protocol)** is a **connection-oriented** communication protocol used to transmit data over a network reliably.

It ensures:

* Data is delivered in the correct order
* No data is lost
* Errors are detected and corrected
* Data transmission is reliable

TCP establishes a connection using a **three-way handshake** before sending data.

**Common uses of TCP:**

* Web browsing (HTTP/HTTPS)
* File transfers (FTP, SFTP)
* Remote login (SSH)
* Email services

---

## **What is UDP?**

**UDP (User Datagram Protocol)** is a **connectionless** communication protocol.

It:

* Does not establish a connection before sending data
* Does not guarantee delivery
* Does not guarantee order
* Is faster than TCP

UDP is used where speed is more important than reliability.

**Common uses of UDP:**

* Live streaming
* Online gaming
* DNS queries
* Voice over IP (VoIP)

---

## **Key Differences Between TCP and UDP**

| Feature         | TCP                 | UDP               |
| --------------- | ------------------- | ----------------- |
| Connection Type | Connection-oriented | Connectionless    |
| Reliability     | Reliable            | Not guaranteed    |
| Speed           | Slower              | Faster            |
| Error Checking  | Yes                 | Basic             |
| Data Order      | Guaranteed          | Not guaranteed    |
| Use Case        | Web, file transfer  | Streaming, gaming |

---

# **Common Web Ports**

Below are the most commonly used ports in web and network communication:

| Service | Protocol | Default Port |
| ------- | -------- | ------------ |
| HTTP    | TCP      | 80           |
| HTTPS   | TCP      | 443          |
| SSH     | TCP      | 22           |
| Telnet  | TCP      | 23           |
| FTP     | TCP      | 21           |
| SFTP    | TCP      | 22           |

### Notes:

* **HTTP (80)** – Used for standard web traffic.
* **HTTPS (443)** – Secure web traffic using SSL/TLS.
* **SSH (22)** – Secure remote server access.
* **Telnet (23)** – Remote login (not secure).
* **FTP (21)** – File transfer protocol.
* **SFTP (22)** – Secure file transfer over SSH.
