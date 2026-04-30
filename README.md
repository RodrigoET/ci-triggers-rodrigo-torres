# ci-triggers-rodrigo-torres

📌 Proyecto: Workflows GitHub Actions
👤 Nombre

Rodrigo Torres

⚙️ Workflows implementados
1. Push
Se ejecuta al hacer push a main
✔ Imprime: "Workflow activado por push"
![Workflow Push](docs/img/00-push.png)

2. Pull Request
Se ejecuta al abrir PR
✔ Imprime: "Pull request detectado"
![Workflow PullRequest](docs/img/01-pull-request.png)

3. Issues
Se ejecuta al crear issue
✔ Imprime: "Nuevo issue creado"
![Workflow Issue](docs/img/02-issue.png)

4. Issue Comment
Se ejecuta al comentar en PR
✔ Filtrado para PR
✔ Imprime: "Comentario en PR detectado"
![Workflow Issue Comment](docs/img/03-issue-comment.png)

5. Manual (workflow_dispatch)
Se ejecuta manualmente
✔ Input: nivel (bajo/medio/alto)
✔ Imprime valor seleccionado
![Workflow Manual](docs/img/04-manual.png)
![Workflow Manual](docs/img/05-manual.png)

6. Schedule
Se ejecuta automáticamente cada 5 minutos
✔ Imprime: "Ejecución programada"
![Workflow Schedule](docs/img/06-schedule.png)