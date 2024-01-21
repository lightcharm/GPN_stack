# GPN_stack
A monitoring the system using containers Grafana, Prometheus, Node Exporter

## Install
Clone this repository and change workdir
```bash
git clone https://github.com/lightcharm/GPN_stack.git
```
```bash
cd GPN_stack
```

Enter in the browser
```bash
http://localhost:3000/
```

***Log in***

![Host](https://github.com/lightcharm/GPN_stack/blob/main/screenshots/Login.png)

In the config.env file, you can change the password to log in to Grafana
```yaml
GF_SECURITY_ADMIN_USER=admin
GF_SECURITY_ADMIN_PASSWORD=changeme
GF_USERS_ALLOW_SIGN_UP=false
```

We can select ready-made dashboards (4 units) in menu and view the data

***My plans:***
* I'll add screenshots later
* I'll make my dashboards later
