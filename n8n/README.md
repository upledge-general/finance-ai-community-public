# 🚀 n8n temporary setup Template

Step 1. Use a Ready-Made Template (No Coding!)
1. Click this link: github.com/therestart-ai/n8n-self-hosted_therestart-ai_2 
2. Look for the green button that says "Use this template"
3. Click it, then select "Create a new repository"
4. Name it something like my-n8n-studio (any name works)
5. Make sure it's Public (it's free - private costs money)
6. Click "Create repository from template"

Step 2. Set the Docker API Version
1. **Click "Use this template"** on GitHub
2. **Open in GitHub Codespace** (green "Code" button → Codespaces tab)
3. **Wait ~30 seconds** for automatic setup ⚡

Step 3: Adjusting versions and start
1. In the bash terminal, Run this command: export DOCKER_API_VERSION=1.43
2.  In the bash terminal, Run this command: docker-compose up -d
3. **Access n8n** via the forwarded port notification or `http://localhost:5678`

Step 4: Adding Workflows
1. Export your workflows from an existing n8n instance as JSON
2. Place the `.json` files in the `/workflows` folder
3. Restart the Codespace or run `bash init.sh` to import them (in parallel!)
