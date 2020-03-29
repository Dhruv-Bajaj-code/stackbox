<h1 align="center">
  StackBox
</h1>

<p align="center">
  <a href="https://github.com/Stack-Box/StackBox/workflows/Vue" alt="Vue">
        <img src="https://github.com/Stack-Box/StackBox/workflows/Vue/badge.svg" /></a>
  <a href="https://github.com/Stack-Box/StackBox/workflows/Flask/" alt="Flask">
        <img src="https://github.com/Stack-Box/StackBox/workflows/Flask/badge.svg" /></a>
  <a href="https://github.com/Stack-Box/StackBox/workflows/Rails/" alt="Rails">
        <img src="https://github.com/Stack-Box/StackBox/workflows/Rails/badge.svg" /></a>
  <a href="https://stackboxworkspace.slack.com/" alt="Slack">
        <img src="https://img.shields.io/badge/slack-@stackboxworkspace-purple.svg?logo=slack" /></a>
  </br>
  </br>
  
  <a href="https://github.com/Stack-Box/StackBox#to-be-added-services-and-clients"/>
  📢 Contributors needed!! 📢
  </a>
 </p>
 <br/>

Stackbox helps you create app stacks loaded with all your favourite clients, services and infra in under 5 mins. The aim of the project is to help developers setup quick infra and boilerplates to start the dev work asap. Ideally this project is to help rapid prototyping, building PoCs or writing code for hackathons.

> Wiki is a good place to start!

1. [**About**](https://github.com/Stack-Box/StackBox/wiki)
2. [**Get Started**](https://github.com/Stack-Box/StackBox/wiki/Get-started)
3. [**Working**](https://github.com/Stack-Box/StackBox/wiki/Working)
4. [**Debugging**](https://github.com/Stack-Box/StackBox/wiki/Debugging)

# Get Started
## Run

### Brew installation

```
brew tap Stack-Box/tap
brew install stackbox
```
**Run**

```
stackbox
```

Creates a folder names `stackbox` in the current directory with all source.

### From source

```
sh stackbox.sh
```

Follow the menu options to select clients and services for your stack.

Jump to [_**example-stacks**_](https://github.com/Stack-Box/StackBox/blob/master/README.md#example-stacks) to quickly try a run

## Support

| Clients/Services | mysql | elasticsearch | kibana | nginx | kafka | zookeper | s3 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **flask** | ✅ | ✅ | na | na | ✅ | na | ✅ |
| **vue** | ✅ | ✅ | na | na | ❌ | na | ❌ |
| **rails** | ✅ | ❌ | na | na | ❌ | na | ❌ |

## Example Stacks

The following is a list of example stacks you could spin-up using Stackbox and quickly get-started with your development.

### 1. Flask-Vue-Mysql-Elasticsearch
#### Run

Run from source - `sh stackbox.sh` 

or

Run from Brew installation -  `stackbox`

Choose vue for frontend, flask for backend. Choose mysql and elasticsearch (with/without kibana) for services.

#### Test
After the run is finished, the final log should look like the one below.

```
flask is up at http://localhost:80
vue is up at http://localhost:8080
elasticsearch is up at http://localhost:9200
mysql is up at http://localhost:3306
```

Now you can visit http://localhost:8080 to view the Vue frontend. From there you can click on Mysql/Elasticsearch links to view the preloaded data from mysql/elasticsearch containers being rendered.

**Visit [Working](https://github.com/Stack-Box/StackBox/wiki/Working) or [Debugging](https://github.com/Stack-Box/StackBox/wiki/Debugging)  pages to know more about internal details.**

## To be added Services and Clients

📢 **Contributors needed!!** 📢

**Aux Services**
- [ ] Dynamo
- [x] S3
- [ ] Postgres
- [ ] CouchDB
- [ ] MongoDB
- [x] Kafka
- [ ] Hadoop

**Frontend clients**
- [ ] Angular
- [ ] React

**Backend services**
- [x] Rails
- [ ] Django
- [ ] Springboot
- [ ] Golang
