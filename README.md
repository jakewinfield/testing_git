# testing_git
The code below sets up one's RStudio to interface with GitHub. Be sure to install Git before running these lines. You should do them one at a time so that you can copy the access token you create using `usethis::create_github_token()` to set the token with `gitcreds:;gitcreds_set()`.
```
usethis::use_git_config(user.name = 'Name', 
                        user.email = 'Email@detroitk12.org')
                        
usethis::create_github_token() #Takes you to github to create a personal access token (PAT)

gitcreds::gitcreds_set() #Sets token in the console
```


Victoria testing push
