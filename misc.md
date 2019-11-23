[you can remove the comments](https://www.packer.io/guides/workflow-tips-and-tricks/use-packer-with-comment.html) from the packer templates if needed with `jq 'walk(if type == "object" then del(._comment) else . end)' commented_template.json > uncommented_template.json
`
