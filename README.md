__WiFi Security & Monitoring Auditor__

A Django-based toolkit for auditing WiFi security, tracking connected devices, and monitoring signal strength & speed. This project is designed for ethical use to help users improve their WiFi security and monitor network activity.

__Features__

*WiFi Security Auditor*

    1. Retrieve saved WiFi passwords (admin access required).

    2. Analyze password strength using a hash-based checker.

    3. Detect open (unsecured) WiFi networks.

*WiFi Connected Device Tracker*

    1. Scan and list all devices connected to a WiFi network.

    2. Detect unauthorized devices in real-time.

    3. Uses Scapy or ARP-scan for network discovery.

*WiFi Signal Strength & Speed Monitor*

    1. Display real-time WiFi signal strength.

    2. Run speed tests using speedtest CLI.

    3. Works with iwconfig (Linux) or netsh (Windows).

*Tech Stack*

    1. Backend: Django, Python

    2. Network Scanning: Scapy, ARP-scan

    3. Speed & Signal Monitoring: Speedtest CLI, iwconfig/netsh

    4. Frontend: HTML, CSS, TailwindCSS, Django Templates

__Installation & Setup__

    Clone the Repository

        git clone https://github.com/Stephen842/Wi-Fi_Auditor.git
        cd Wi-Fi_Auditor

    Install Dependencies

        pip install -r requirements.txt

    Run Migrations

        python manage.py makemigrations
        python manage.py migrate

    Start the Server

        python manage.py runserver

    Access the Web App

        Go to http://127.0.0.1:8000/ in your browser.

__Usage__

    1. WiFi Security Audit

        Run the WiFi Security Auditor to analyze stored WiFi passwords and detect open networks:

        python manage.py wifi_audit

    2. Scan Connected Devices

        Find all devices currently connected to your WiFi network:

        python manage.py scan_devices

    3. Monitor Signal Strength & Speed

        Check WiFi signal quality and internet speed:

        python manage.py wifi_monitor


__⚠ Disclaimer__

    This project is intended for ethical purposes only. Use it only on networks you own or have permission to test. Unauthorized scanning of networks without consent may be illegal in your country.

__Contributing__

    Contributions are welcome! To contribute:

    1. Fork the repository.

    2. Create a new branch: git checkout -b feature-name.

    3. Commit your changes: git commit -m 'Add new feature'.

    4. Push the changes: git push origin feature-name.

    5. Open a pull request.

__License__

    This project is licensed under the MIT License.

