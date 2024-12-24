---
name: Bug report
title: '[BUG] '
labels: bug
assignees: ''
---

**Describe the bug**
Description of the bug.

**To Reproduce**
1. Step 1
2. Step 2
3. See error

**Expected behavior**
What should happen.

**Screenshots**
If applicable.

**Environment:**
 - OS: [e.g. Windows]
 - Browser: [e.g. Chrome]
 - Version: [e.g. 22]
EOL

cat > .env.example << 'EOL'
# App
PUBLIC_APP_URL=http://localhost:5173

# Auth
LINKEDIN_CLIENT_ID=
LINKEDIN_CLIENT_SECRET=

# AI
ANTHROPIC_API_KEY=

# Video
HMS_APP_SECRET=
HMS_TEMPLATE_ID=

# Database
DATABASE_URL=

# Redis
UPSTASH_REDIS_URL=
UPSTASH_REDIS_TOKEN=