# IP Tracer

![Bash Script](https://img.shields.io/badge/Bash-Script-green.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)
![Version](https://img.shields.io/badge/version-1.0-orange.svg)

![ip-tracer](https://github.com/user-attachments/assets/15212a40-cb4b-4c6f-9004-bcf7d4b1dd06)

IP Tracer is a powerful Bash script that allows you to trace and gather comprehensive information about IP addresses. It leverages multiple APIs to provide detailed insights about the target IP address.

## 👨‍💻 Developer and Creator

This project was developed and created by [Linuztx](https://github.com/linuztx). As the sole creator, Linuztx maintains full control and ownership of this project.

## 🚀 Features

- 🔍 Trace information for any given IP address
- 🌐 Option to trace your own public IP address
- 🔄 Utilizes three different IP information APIs:
  - [ipapi.co](https://ipapi.co/)
  - [ip-api.com](https://ip-api.com/)
  - [ipinfo.io](https://ipinfo.io/)
- 🎨 Colorful and user-friendly output
- 🗺️ Provides Google Maps links for geographic locations
- ⏱️ Shows execution time

## 🛠️ Prerequisites

- Bash shell
- `curl` command-line tool
- `jq` command-line JSON processor

## 📥 Installation

1. Clone the repository:
   ```
   git clone https://github.com/WhizBytes/ip-tracer.git
   ```

2. Change to the project directory:
   ```
   cd ip-tracer
   ```

3. Make the script executable:
   ```
   chmod +x iptracer
   ```

## 🖥️ Usage

### Basic usage:

```
./iptracer -t <IP_ADDRESS>
```

### Trace your own IP:

```
./iptracer -m
```

### Run without clearing the screen:

```
./iptracer -t <IP_ADDRESS> -n
```

### Options:

- `-t <IP_ADDRESS>`: Specify the target IP address to trace
- `-m`: Trace your own public IP address
- `-n`: Do not clear the screen before running (useful for debugging or logging)

### Examples:

1. Trace a specific IP address:
   ```bash
   ./iptracer -t 8.8.8.8
   ```

2. Trace your own IP address:
   ```bash
   ./iptracer -m
   ```

3. Trace an IP address without clearing the screen:
   ```bash
   ./iptracer -t 1.1.1.1 -n
   ```

4. Trace your own IP address without clearing the screen:
   ```bash
   ./iptracer -m -n
   ```

## 📊 Example Output

```
./iptracer -t 8.8.8.8
```

This command will display detailed information about the IP address 8.8.8.8 (Google's public DNS server), including:

- Provider information
- Geographic location (country, city, region)
- ISP details
- Latitude and longitude
- Google Maps link
- Additional data from each API source

## 📄 License

This project is proprietary software. See the [LICENSE](LICENSE) file for details. Unauthorized copying, modification, distribution, or use of this software, in whole or in part, is strictly prohibited.

## 🙏 Acknowledgements

- [ipapi.co](https://ipapi.co/)
- [ip-api.com](https://ip-api.com/)
- [ipinfo.io](https://ipinfo.io/)

## 🆘 Support

If you find this project helpful, consider supporting the developer:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/linuztx)

---

<p align="center">Developed with ❤️ by Linuztx</p>
