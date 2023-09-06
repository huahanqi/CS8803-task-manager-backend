#### Project Setup

Run this command to start running our backend server on localserver (default port 8080)

```bash
npm install && npm start
```

Swagger UI

```yaml
/tasks/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the task id
```

You can go to http://localhost:8080/api-docs/ (assuming you are running on port 8080) to look at APIs documentation
