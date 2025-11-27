# n8n_automations
A brief collection of my n8n automation workflows

## Setup Instructions

### Using Docker Compose

1. Ensure you have Docker and Docker Compose installed on your machine.
2. Create a `.env` file in the root directory of the project and populate it with the necessary environment variables. You can copy the `.env.example` file for guidance.
3. Run the following command to start the services:
   ```bash
   docker compose up -d
   ```
4. Access n8n at `http://localhost:5678` in your web browser with the n8n main interface after the services are up and running.

### To get workflows into n8n

1. Open n8n in your web browser.
2. Import the desired JSON workflows from the `workflows` directory using the n8n import feature.
3. Open each workflow and update any necessary credentials or configurations specific to your environment.
4. Activate the workflows as needed.
