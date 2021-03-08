# spring-boot-demo con Security CI/CD
Demo project

Para verificacion simple:

```bash
mvnw verify
```

Para compilar se incluye el plugins de docker para empaquetar todo el proyecto:

```bash
mvnw clean package jib:dockerBuild
```

Para levantar el contenedor de la aplicacion, además de las dependencias; se debe ubicarse en el directorio donde se encuentra el archivo docker-compose.yml y ejecutar

```bash
docker-compose up
```

Lista de plugins de jenkins
- Folders Plugin (cloudbees-folder): 6.15
- Trilead API Plugin (trilead-api): 1.0.13
- OWASP Markup Formatter Plugin (antisamy-markup-formatter): 2.1
- Structs Plugin (structs): 1.22
- Pipeline: Step API (workflow-step-api): 2.23
- Token Macro Plugin (token-macro): 2.13
- Build Timeout (build-timeout): 1.20
- Credentials Plugin (credentials): 2.3.15
- Plain Credentials Plugin (plain-credentials): 1.7
- SSH Credentials Plugin (ssh-credentials): 1.18.1
- Credentials Binding Plugin (credentials-binding): 1.24
- SCM API Plugin (scm-api): 2.6.4
- Pipeline: API (workflow-api): 2.41
- Timestamper (timestamper): 1.11.8
- Script Security Plugin (script-security): 1.76
- Plugin Utilities API Plugin (plugin-util-api): 2.0.0
- Font Awesome API Plugin (font-awesome-api): 5.15.2-2
- Popper.js API Plugin (popper-api): 1.16.1-2
- JQuery3 API Plugin (jquery3-api): 3.5.1-3
- Bootstrap 4 API Plugin (bootstrap4-api): 4.6.0-2
- Snakeyaml API Plugin (snakeyaml-api): 1.27.0
- Jackson 2 API Plugin (jackson2-api): 2.12.1
- ECharts API Plugin (echarts-api): 5.0.1-1
- Display URL API (display-url-api): 2.3.4
- Pipeline: Supporting APIs (workflow-support): 3.8
- Pipeline: Job (workflow-job): 2.40
- Checks API plugin (checks-api): 1.5.0
- JUnit Plugin (junit): 1.48
- Matrix Project Plugin (matrix-project): 1.18
- Resource Disposer Plugin (resource-disposer): 0.15
- Workspace Cleanup Plugin (ws-cleanup): 0.39
- Ant Plugin (ant): 1.11
- Durable Task Plugin (durable-task): 1.35
- Pipeline: Nodes and Processes (workflow-durable-task-step): 2.38
- Command Agent Launcher Plugin (command-launcher): 1.5
- Oracle Java SE Development Kit Installer Plugin (jdk-tool): 1.5
- bouncycastle API Plugin (bouncycastle-api): 2.20
- JavaScript GUI Lib: ACE Editor bundle plugin (ace-editor): 1.1
- Pipeline: SCM Step (workflow-scm-step): 2.12
- Pipeline: Groovy (workflow-cps): 2.90
- Mailer Plugin (mailer): 1.32.1
- Apache HttpComponents Client 4.x API Plugin (apache-httpcomponents-client-4-api): 4.5.13-1.0
- Pipeline: Basic Steps (workflow-basic-steps): 2.23
- Gradle Plugin (gradle): 1.36
- Pipeline: Milestone Step (pipeline-milestone-step): 1.3.2
- Pipeline: Input Step (pipeline-input-step): 2.12
- Pipeline: Stage Step (pipeline-stage-step): 2.5
- Pipeline Graph Analysis Plugin (pipeline-graph-analysis): 1.10
- Pipeline: REST API Plugin (pipeline-rest-api): 2.19
- JavaScript GUI Lib: Handlebars bundle plugin (handlebars): 1.1.1
- JavaScript GUI Lib: Moment.js bundle plugin (momentjs): 1.1.1
- Pipeline: Stage View Plugin (pipeline-stage-view): 2.19
- Pipeline: Build Step (pipeline-build-step): 2.13
- Pipeline: Model API (pipeline-model-api): 1.8.4
- Pipeline: Declarative Extension Points API (pipeline-model-extensions): 1.8.4
- JSch dependency plugin (jsch): 0.1.55.2
- Git client plugin (git-client): 3.6.0
- GIT server Plugin (git-server): 1.9
- Pipeline: Shared Groovy Libraries (workflow-cps-global-lib): 2.18
- Branch API Plugin (branch-api): 2.6.2
- Pipeline: Multibranch (workflow-multibranch): 2.22
- Pipeline: Stage Tags Metadata (pipeline-stage-tags-metadata): 1.8.4
- Pipeline: Declarative (pipeline-model-definition): 1.8.4
- Lockable Resources plugin (lockable-resources): 2.10
- Pipeline (workflow-aggregator): 2.6
- Java JSON Web Token (JJWT) Plugin (jjwt-api): 0.11.2-9.c8b45b8bb173
- OkHttp Plugin (okhttp-api): 3.14.9
- GitHub API Plugin (github-api): 1.123
- Git plugin (git): 4.6.0
- GitHub plugin (github): 1.33.1
- GitHub Branch Source Plugin (github-branch-source): 2.9.7
- Pipeline: GitHub Groovy Libraries (pipeline-github-lib): 1.0
- SSH Build Agents plugin (ssh-slaves): 1.31.5
- Matrix Authorization Strategy Plugin (matrix-auth): 2.6.5
- PAM Authentication plugin (pam-auth): 1.6
- LDAP Plugin (ldap): 1.26
- Email Extension Plugin (email-ext): 2.82
- Locale plugin (locale): 1.4
- OWASP Dependency-Check Plugin (dependency-check-jenkins-plugin): 5.1.1
- Official OWASP ZAP Jenkins Plugin (zap): 1.1.0
- H2 API Plugin (h2-api): 1.4.199
- Config File Provider Plugin (config-file-provider): 3.7.0
- Pipeline Maven Integration Plugin (pipeline-maven): 3.10.0
- HTML Publisher plugin (htmlpublisher): 1.25
- Summary Display Plugin (summary_report): 1.15
- jQuery plugin (jquery): 1.12.4-1
- JUnit Attachments Plugin (junit-attachments): 1.6
- JaCoCo plugin (jacoco): 3.1.1
- Report Info Plugin (report-info): 1.0
- SonarQube Scanner for Jenkins (sonar): 2.13
- DataTables.net API Plugin (data-tables-api): 1.10.23-3
- Forensics API Plugin (forensics-api): 1.0.0
- Analysis Model API Plugin (analysis-model-api): 9.8.1
- Warnings Next Generation Plugin (warnings-ng): 8.10.0