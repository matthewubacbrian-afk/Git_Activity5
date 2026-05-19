Project-Nova/                   ← [Ubac] git init · remote setup · invite madzamador
├── auth-service.js              ← [Lazaro] CREATE · git add · initial commit
├── payment-gateway.js          ← [Lazaro] CREATE on feature/payment-gateway branch · push --set-upstream
├── config.js                    ← [Domingo] CREATE · deliberately add conflict content · push to main so merge fails
├── styles.css                   ← [Domingo] CREATE · simulate "forgot a file" scenario · git commit --amend --no-edit
├── index.html                   ← [Canguit] CREATE · break it · simulate "I hate these changes" · git restore
├── .env                         ← [Domingo] CREATE with fake passwords · git add . → git restore --staged .env
├── README.md                   ← [Ubac] MODIFY · document all Part 2 emergency fixes with commands
├── .gitignore                   ← [Ubac] CREATE · add .env to gitignore after P2 fix #1
├── branch: feature/payment-gateway ← [Lazaro] checkout · push · pull · resolve conflict in config.js
├── branch: feature/new-feature    ← [Lazaro] simulate wrong-branch scenario (git branch new-feature + reset HEAD~3)
├── branch: recovery-branch        ← [Canguit] simulate detached HEAD · git switch -c recovery-branch
└── branch: testing-junk           ← [Ubac] push then delete via git push origin --delete testing-junk