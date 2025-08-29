# Webhook SQL Solver

## Configure
Edit `src/main/resources/application.yml`:
- app.name
- app.regNo
- app.email

## Solve SQL
Edit `QuestionSolver.java` → replace SQL in:
- sqlForQuestion1()
- sqlForQuestion2()

## Build
```bash
mvn -DskipTests package
