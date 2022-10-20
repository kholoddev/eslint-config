# eslint-config

## Install

```cmd
npm i -D eslint
npm i -D typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin
npm i -D prettier eslint-config-prettier eslint-plugin-prettier
```

## root

```json
{
  "root": true
}
```

eslint каскадно ищет свой конфиг, спускаясь до корня файловой системы. Параметр `root` указывает на корневой конфиг файл, глубже eslint спускаться не будет

---

## env

<https://eslint.org/docs/latest/user-guide/configuring/language-options#specifying-environments>

```json
{
  "env": {}
}
```
