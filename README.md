# A lineageos archive

For more please see https://github.com/biop0765/lineageosbackup

## Releases

See releases for images of various devices


## To upload

```bash
##go get github.com/github-release/github-release

github-release  --security-token

# create the tag in web browser before running next command

github-release upload  --user gh_user_name \
--repo gh_repo \
--tag v0.2.0  \
--name "remote_file_name_to_display" \
--file  local_file.extension
```


