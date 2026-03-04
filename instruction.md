## Task: Fix Incorrect Output in Dockerized Application

You are given a Dockerized Python application located in /app/.

The Docker image builds successfully.

However, when the container runs, the generated output.json contains incorrect values.

Your objectives:

1. Identify and fix the logic error in the application.
2. Ensure the Docker image builds successfully.
3. Ensure running the container generates /app/output.json.
4. The correct output must contain:
   - count = 3
   - total = 60

Constraints:
- Do not modify input.json.
- Do not modify test files.
- Only modify application code if necessary.
- Ensure deterministic behavior.
