# Docker

alias up="docker-compose up -d"

alias down="docker-compose down --remove-orphan"

alias kafkaup="docker-compose -f docker-compose-kafka.yml up -d"

alias restart="down && up"

# Git

alias s="git status"

# PHP scripts and containers

alias phpunit="./phpunit.sh"

alias composer="./composer.sh"

alias coverage="./phpunit.sh --coverage-html tests/.coverage"
