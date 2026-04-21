# Add Gokarna theme as submodule

Run these from the repository root after cloning:

```bash
git submodule add https://github.com/gokarna-theme/gokarna-hugo.git themes/gokarna
git submodule update --init --recursive
git add .gitmodules themes/gokarna
git commit -m "Add Gokarna theme submodule"
git push origin <your-branch>
```
