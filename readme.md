# Local First - Learning git-hub - UIC common class 23

This is some text in my Readme

PAT; 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

# Check version of git in Terminal
git --version

# Configure git
library(usethis)
use_git_config(user.name = "federica", user.email = "fusi.fede@gmail.com")

#After you created a new local project, this is how to configure git
library(usethis)
use_git()
## check the git tab close to history/connections

#Connect RStudio and GitHUb
library(usethis)
create_github_token() #Create a Personal Access Token to connect the two

library(gitcreds)
gitcreds_set() #Insert the PAT

#Change the name of the main branch
library(usethis)
git_default_branch() #check the name of the main branch
git_default_branch_rename()

