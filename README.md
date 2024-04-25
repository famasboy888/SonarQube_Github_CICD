# SonarQube with Github Actions - CICD
We will use our previous setup from [my SonarQube deployment](https://github.com/famasboy888/SonarQube_docker)

## Setup Steps

### 1) Create a new project in SonarQube server

#### 1.1) Create a local project. Rememer the `Project key`.

I will use `my-Java-web-app`.

<p align="left">
  <img width="40%" height="40%" src="https://github.com/famasboy888/SonarQube_Github_CICD/assets/23441168/e5fd05e8-e48f-448b-bae1-1f7f1443fc63">
</p>

#### 1.2) Use the global setting

#### 1.3) Chose `GitHub Actions`.

#### 1.4) Generate a `New Token`. Save and copy it for later.

#### 1.5) Copy `Host URL`. Save it for later.

---

### 2) Save Token to Github Actions Secrets.

In Github repository, go to:

`Settings` > `Secrets and variables` > `Actions` > `Secrets tab` > `New Repository Secret`

Add `SONAR_TOKEN`

Add `SONAR_HOST_URL`

<p align="left">
  <img width="40%" height="40%" src="https://github.com/famasboy888/SonarQube_Github_CICD/assets/23441168/2fb30256-6c1a-4125-b47d-4ed411a75c57">
</p>


