backend-repo/
├─ auth-service/
│  ├─ main.py
│  ├─ requirements.txt
│  └─ Dockerfile
├─ data-service/
│  ├─ main.py
│  ├─ requirements.txt
│  └─ Dockerfile
├─ nginx/
│  └─ default.conf
├─ docker-stack.yml   # stack file (Compose v3) used by Swarm
├─ .github/workflows/ci-cd.yml
├─ secrets/           # for local demo only (do NOT commit secrets)
│  └─ example.env
└─ README.md
