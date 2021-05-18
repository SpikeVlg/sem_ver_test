# sem_ver_test

git init
// git config core.sshCommand "ssh -i C:/Users/Andrey_Lakhmanets/.ssh/id_ed25519_github"
npm init -> will create package.json
npm install --save-dev semantic-release


npm install @semantic-release/git -D


npx semantic-release-cli setup
npx semantic-release

npx semantic-release --ci=false --debug=true --dry-run=true


# Drawbacks
1. Need to specify git url - can't work locally
2. Need to specify npm registry



a new commit