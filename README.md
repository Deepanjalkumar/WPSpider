# WPSpider- A WordPress Scanner (version 1.0b)
A centralized dashboard for running and scheduling WordPress scans powered by wpscan utility. It has following features:
1. Login Page-
    * Authentication is required to access the application.
2. Dashboard Page-
    * On Demand Scan          : Run scans instantly by either providing a URL or a text file having multiple URL's seprated by a new line as an input.
    * Scan History            : View or delete scan history and reports.
    * Schedule Scan           : Configure scans to run automatically, or on a recurring basis just like a cron job in linux.
    * Scheduled Scan History  : Edit cron rule or delete any scheduled scan.
3. Report Page-
    * View or print the details of vulnerabilities discovered after scan completes.

## Key Features

```
* Performs scan for single or multiple WordPress applications asynchronously
* Supports both on demand and scheduled scans (like a cron job)
* Cross-platform application
```

## How to Setup?

```
* Download and Install Node.js- https://nodejs.org/en/download/
* Install wpscan- https://wpscan.org/
* git clone https://github.com/cyc10n3/WPSpider.git
* cd  WPSpider
* npm install (for installing node modules or dependencies)
* npm start
* Open https://localhost:1337 or https://127.0.0.1:1337 in browser
* Login with default credentials (admin/cyc10n3)
```
![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `It is recommended to change the login password by modifying config.json`[`file`](https://github.com/cyc10n3/WPSpider/blob/master/config.json).

## Screenshots

#### Login
![Login](/static/screenshots/1.png?raw=true "Login")

#### Dashboard: On-demand Scan
![Dashboard: On-demand Scan](/static/screenshots/2.png?raw=true "Dashboard: On-demand Scan")

#### Dashboard: Schedule Scan
![Dashboard: Schedule Scan](/static/screenshots/3.png?raw=true "Dashboard: Schedule Scan")

#### Scan Report
![Scan Report](/static/screenshots/4.png?raw=true "Scan Report")

## Known Issues

```
* Login bruteforce possible
```

## Authors

* **Gaurav Mishra** - *Initial work* - gmishra010@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
