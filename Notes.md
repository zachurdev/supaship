Commit #1
```bash
npm create vite@latest
# Ok to proceed? y
# Project name: supaship
# Select a framework: React
# Select a variant: TypeScript
cd supaship
npm install
npm run dev
^C
git init -b main
gh repo create --public supaship
git remote add origin https://github.com/zachurdev/supaship
git add .
git commit -m "$(date -u +'%Y%m%dT%H%M%SZ')"
git log
git push -u origin main
```
Commit #2
```bash
touch ~/src/zachurdev/supaship/Notes.md
mkdir -p ~/src/zachurdev/bash/
git clone https://github.com/zachurdev/bash ~/src/zachurdev/bash/
cp ~/src/zachurdev/bash/Autosave.bash ~/src/zachurdev/supaship/
bash Autosave.bash
```