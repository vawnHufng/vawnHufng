<div align="center">
  <h1>Hi 👋, I'm Huong Van Hung</h1>
  <h3>System & Infrastructure Engineer | IT Operations Specialist</h3>

  <p>
    <img src="https://img.shields.io/badge/OS-Windows_Server_%7C_Linux-blue?style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/Virtualization-VMware_ESXi_%7C_Proxmox-607078?style=for-the-badge&logo=proxmox&logoColor=white" />
    <img src="https://img.shields.io/badge/Monitoring-Grafana_%7C_Prometheus-orange?style=for-the-badge&logo=grafana&logoColor=white" />
    <img src="https://img.shields.io/badge/Proxy-Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  </p>
</div>

---

## 👨‍💻 Professional Profile

Tôi là một **System & Infrastructure Engineer** quản trị và vận hành hệ thống hạ tầng máy chủ doanh nghiệp trên các nền tảng hỗn hợp (**Windows Server & Linux Server**).

Có kinh nghiệm thực chiến trong việc triển khai và tối ưu hạ tầng CNTT quy mô lớn đòi hỏi tính sẵn sàng cao (High Availability) và bảo mật nghiêm ngặt. Đặc biệt mạnh về giải pháp hạ tầng cho khối **Y tế (Healthcare IT)**, vận hành mượt mà các hệ thống cốt lõi như **HIS, PACS , Application Server, Database** và các dịch vụ tích hợp liên tuyến.

**Mục tiêu cốt lõi trong công việc:**
- Đảm bảo tính ổn định và liên tục của dịch vụ (99.9% Uptime).
- Tối ưu hóa hiệu suất phần cứng enterprise và kiến trúc ảo hóa.
- Chủ động phát hiện và cảnh báo sớm các sự cố thông qua hệ thống Observability tập trung.

---

## 🏗️ Core Expertise

### 🖥️ Server & System Administration
*   **Windows Server Ecosystem:** Quy hoạch và quản trị Active Directory Domain Services (AD DS), tối ưu Group Policy (GPO), quản lý hạ tầng mạng core (DNS, DHCP). Cấu hình chuyên sâu IIS Web Server và xử lý sự cố Windows Services.
*   **Linux Enterprise:** Thành thạo phân phối Ubuntu Server, tối ưu hóa cấu hình mạng (Netplan, Routing), quản lý dịch vụ qua Systemd và viết script tự động hóa.
*   **Specialized Architectures:** Có kinh nghiệm làm việc và xử lý sự cố phần cứng trên kiến trúc đặc thù như **IBM Power Systems (ppc64le)**.

### 🌐 Application Delivery & Reverse Proxy
*   Triển khai **Nginx Reverse Proxy** và các giải pháp **Load Balancing** để phân phối lưu lượng ứng dụng.
*   Cấu hình bảo mật hóa SSL/TLS, tối ưu HTTP/2, WebSocket và tăng tốc độ phản hồi cho các hệ thống Web Application chạy trên cả IIS và Linux.

### 📊 Monitoring & Observability (Giám sát tập trung)
Xây dựng giải pháp giám sát toàn diện, trực quan hóa dữ liệu thời gian thực (Realtime Dashboard) với hệ sinh thái:
*   **Prometheus & Grafana OSS:** Thu thập chỉ số từ đa nền tảng.
*   **Exporters:** Sử dụng Node Exporter, Windows Exporter, và **SNMP Exporter** để giám sát thiết bị mạng core.
*   **Cảnh báo thông minh:** Thiết lập ngưỡng cảnh báo sớm và tích hợp thông báo tự động qua Telegram/Zalo thông qua Alertmanager.

### 🖥️ Virtualization & Hardware Management
*   **Ảo hóa & Hypervisor:** Vận hành và tối ưu tài nguyên trên môi trường **VMware ESXi (vCenter)** và hệ thống ảo hóa **Proxmox VE**. Mở rộng các cụm tài nguyên (CPU, Memory, Storage Provisioning) linh hoạt.
*   **Enterprise Hardware:** Quản trị trực tiếp hệ thống máy chủ vật lý cao cấp (Dell PowerEdge, HPE, H3C..), am hiểu kiến trúc vi xử lý **AMD EPYC / Intel Xeon** và tối ưu hóa các mảng lưu trữ dung lượng lớn sử dụng Enterprise SSD/NVMe RAID.

### 🗄️ Database Administration
*   **Microsoft SQL Server:** Thực hiện các tác vụ quản trị cốt lõi bao gồm Backup/Restore chiến lược, lập lịch Database Maintenance, giám sát hiệu năng truy vấn, cấu hình SQL Agent Jobs và thực hiện migration dữ liệu an toàn.

### 🏥 Healthcare IT Support
*   Đảm bảo hạ tầng luôn sẵn sàng cho hệ thống thông tin bệnh viện (**HIS**).
*   Giám sát và duy trì hoạt động ổn định của hệ thống **PACS** ở tầng hạ tầng (Kiểm tra dung lượng lưu trữ hình ảnh, check logs, đảm bảo kết nối mạng thông suốt và dịch vụ hoạt động liên tục).

### 🔐 Network & Security
*   Vận hành và cấu hình thiết bị tường lửa/định tuyến chuyên dụng: **FortiGate**, **MikroTik**, Cisco Switching.
*   Triển khai phân tách mạng qua VLAN, thiết lập Policy Rules, cấu hình NAT, và xây dựng các kênh truyền bảo mật **VPN Site-to-Site** kết nối các chi nhánh về Headquarters.

### ⚙️ Automation & Scripting
*   Ứng dụng **PowerShell**, **Bash Script** và **Python** để tự động hóa các công việc lặp đi lặp lại: sao lưu dữ liệu, kiểm tra sức khỏe hệ thống định kỳ (Health-check) và thu thập log tự động.

---

## 🚀 Featured Projects

### 🤖 Prometheus Discord Bot (Infrastructure Monitoring via ChatOps)
*   **Mô tả:** Thiết kế và phát triển công cụ ChatOps dưới dạng một **Discord Bot bằng JavaScript (Node.js)** để truy vấn trực tiếp trạng thái hạ tầng từ xa.
*   **Giải pháp:** Tận dụng hệ thống Slash Commands (`deploy-commands.js`) để kết nối API của Prometheus, truy vấn realtime các số liệu PromQL về tài nguyên máy chủ (CPU, RAM, Disk, Uptime) của cụm máy chủ ảo hóa và máy chủ vật lý, xuất dữ liệu trực quan ra định dạng Discord Embed.
*   **Kết quả:** Giảm thiểu thời gian truy cập cổng quản trị tập trung, giúp đội ngũ kỹ thuật có thể check nhanh tình trạng máy chủ trực tiếp ngay trên kênh chat Discord của team.

---

## 🛠️ Tech Stack

| Phân mục | Công nghệ & Công cụ |
| :--- | :--- |
| **Operating Systems** | Windows Server (2016-2022), Ubuntu Server, Linux ppc64le |
| **Virtualization & Hardware** | VMware ESXi, vCenter, Proxmox VE, Dell PowerEdge, IBM Power Systems, HPE, H3C, Supermicro |
| **Monitoring / Observability** | Prometheus, Grafana OSS, Alertmanager, SNMP/Node/Windows Exporters |
| **Networking & Security** | FortiGate Firewalls, MikroTik RouterOS, Cisco Switches, VPN Site-to-Site, VLAN |
| **Databases & Web Servers** | MS SQL Server, Nginx, IIS |
| **DevOps & Scripting** | Docker, Docker Compose, Git, JavaScript (Node.js), PowerShell, Bash, Python |

---

## 📫 Connect with me:

<p align="left">
  <a href="mailto:huongvanhungit@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
</p>

<h3 align="left">Languages and Tools Badges:</h3>

<p align="left">
  <img src="https://img.shields.io/badge/Windows_Server-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white" />
  <img src="https://img.shields.io/badge/Proxmox-E74C3C?style=for-the-badge&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/FortiGate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white" />
</p>
