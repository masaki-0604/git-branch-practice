Project: Branch Workshop
Project: Git Branch Practice
# Git Branch Practice
This is the feature/login branch.

## Learned
- ブランチ作成/マージ
- fast-forward マージ
- リモートへの初回 push
## What I practiced
- Create branch / merge (fast-forward)
- Push to remote & track upstream
- (Next) Resolve merge conflicts via PR

## Commands I used
\\\ash
git checkout -b feature/login
git add . && git commit -m "add line in feature/login"
git checkout main && git merge feature/login
git push -u origin main
\\\

## Next
- PR作成→マージの流れ
- コンフリクト解消の体験
- Branch Protection でレビュー必須化


