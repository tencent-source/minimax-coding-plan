# Deploy to ai-coding-api Organization

Once you've created the `ai-coding-api` organization at:
https://github.com/organizations/plan

Run these commands from this directory:

```bash
cd /Users/ares/minimax-referral

# Add remote for new org (you'll be prompted for org membership approval)
git remote add origin https://github.com/ai-coding-api/minimax-coding-plan.git

# Push to new org
git push -u origin main
```

Then enable GitHub Pages:
1. Go to: https://github.com/ai-coding-api/minimax-coding-plan/settings/pages
2. Source: Deploy from a branch → main → / (root)
3. Save

Your site will be live at:
https://ai-coding-api.github.io/minimax-coding-plan/

---

# Delete Temp Repos

After deploy is working, delete these from your personal account:
- https://github.com/tencent-source/minimax-referral/settings
- https://github.com/tencent-source/minimax-coding-plan/settings
