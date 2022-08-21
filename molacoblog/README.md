### Workflow

1. Create new post
  ``` hugo new post/NEW_POST_NAME/index.md```

2. Generate static files (under /blog)
  ``` hugo -t hugo-theme-stack ```

3. Commit changes (under /blog/public)
  ``` 
  git status
  git add .
  git commit -m "commit"
  git push origin main
  ```
