# GitHub Action Repo (Webhook Testing)

This is a dummy GitHub repo used to trigger webhook events (Push, Pull Request, Merge) for integration testing with a Flask webhook receiver.

### 🔧 Actions Covered
- ✅ Push commits
- ✅ Create and merge pull requests
- ✅ Trigger GitHub webhooks using real events

### 🧪 How it was used
1. Made dummy commits and pushed to main
2. Created a feature branch and opened a Pull Request
3. Merged the PR to main

All these events triggered the webhook to store data in MongoDB.

