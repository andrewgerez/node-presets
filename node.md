# Chore: Node.js setup (with TypeScript)

## init
* npm init -y

## dependencies
* npm i typescript -> npx tsc --init
* npm i -D @types/node
* npm i tsx -D
* npm i tsup -D

## run
* "dev": "tsx watch src/server.ts"
* "prd": "npx tsc src/server.ts && node src/server.js"
