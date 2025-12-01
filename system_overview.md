# System Architecture

## Core Services
- **API Gateway** (Node.js + Express)
- **Auth Service** (OAuth2 + JWT)
- **Database** (PostgreSQL with read replicas)
- **Cache Layer** (Redis)

## Deployment
- Kubernetes cluster (3 nodes)
- AWS EKS + RDS
- Auto-scaling enabled
EOF
