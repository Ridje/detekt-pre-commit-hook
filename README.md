# Detekt pre-commit hook example

## Description
It pre-commit hook example that uses detekt to reveal [code smells](https://en.wikipedia.org/wiki/Code_smell) and aims to improve your code readability. 


## Installation
1. Install [detekt CLI](https://detekt.dev/docs/gettingstarted/cli)
2. [Optional] Put your custom detekt rules to ${prjectDir}/config/detekt/config.yml directory.
3. Put file [pre-commit](https://github.com/Ridje/detekt-pre-commit-hook/blob/master/pre-commit) in your ${projectDir}/.git/hooks directory
4. Mark pre-commit file as executable: `chmod +x ${projectDir}/.git/hooks/pre-commit`
