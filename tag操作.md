# 在当前提交上，打标签foo   
`git tag foo`

# 在当前提交上，打标签foo，并给message信息注释   
`git tag foo -m "message" `  

# 在当前提交之前的第4个版本上，打标签foo   
`git tag foo HEAD~4`

# 列出所有标签   
`git tag `    

# 删除标签foo   
`git tag -d foo`

# 把标签推送到远程仓库    
`git push origin --tags`

# 把标签推送到远程仓库    
`git push origin v0.1`    
