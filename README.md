# bash-laravel-aliases
Aliases for bashrc

#Laravel & Git Aliases
alias pamfs='php artisan migrate:fresh --seed'
alias pam='php artisan migrate'
alias crd='composer run dev'
alias pamm='php artisan make model'
alias gl="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
alias wip="git add . && git commit -m 'wip' && git push"
alias nah="git reset --hard && git clean -df"
alias a="php artisan"
alias paml='php artisan make:livewire'
alias cf="composer format"
alias pa="php artisan"
alias nrb="npm run build"
alias ni="npm run install"
alias gpom="git push origin main"
alias gs="git status"
alias fb="npx prettier --write resources/views"

fix() {
  git add . && git commit -m "fix: $*" && git push
}

feat() {
  git add . && git commit -m "feat: $*" && git push
}
