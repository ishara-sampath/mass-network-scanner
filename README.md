**mass-network-scanner**


A high-speed Nmap-based scanner that continuously scans Class A, B, and C public IP ranges, shows live results in an interactive web dashboard, and supports custom IP, subnet, or range scans. A powerful and extensible Linux-based tool for scanning large-scale IP ranges across the internet. mass-network-scanner continuously scans Class A, B, and C public IP spaces using Nmap, and presents live results via a modern web-based dashboard. It also allows users to submit custom IP addresses, subnets, or ranges (e.g., 1.1.1.1, 1.1.1.0/24, 1.1.1.1-25) for on-demand scanning.


✅ **Features**

🔍 Background scanning of Class A, B, and C public IPs

🌐 Reverse DNS resolution for discovered hosts

📡 Live port scanning (customizable ports)

📊 Auto-refreshing HTML dashboard with tabbed views

🧠 Smart filtering by IP or domain in each tab

🖥️ Custom scan input via home page

📁 Exports in HTML, JSON, and CSV formats


📁 **Output Structure**

data/: JSON results for Class A, B, C, and custom scans

output/: HTML tables generated from scan results

web/: Frontend UI with tabs, search, and live updates


⚙️  **Built With**
Bash, Nmap, dig/host

HTML5, CSS3, JavaScript (vanilla)
