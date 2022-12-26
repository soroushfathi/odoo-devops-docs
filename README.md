# odoo-devops-docs
Odoo DevOps

## 1. Docker 
### 1.1 Instalation
The full documentation on how to use Odoo with Docker can be found on the official Odoo [Docker Image](https://hub.docker.com/_/odoo/)
### 1.2 Development
there is two way to use docker on odoo app development.<br>
1. (<b>recommended</b>) use the original odoo image to run it(container), then only things you have to do is adding your custome modules to the image by FTP <i>without modifing the source code</i>, 

| #    | Advantage              | Disadvantage |
| ---- | ---------------------- | ------------ |
| 1    | source won't be change |              |
| 2    | less bugs and errors   |              |



2. dickerize entire source, then run it

| #    | Advantage                               | Disadvantage |
| ---- | :-------------:                         | ------------ |
| 1    | Faster Development                      |              |
| 2    | CI/CD                                   |              |
| 3    | Easy to change server or PaaS services  |              |

## 2. Kuber

## 3. GitLab CI/CD

### 3.1 Gitlab - Kubernetes integration
### 3.2 GitLab Runner

## 4. Github

## 5. IFTTT
