# 📝 Go CLI Todo App

A simple Command Line Todo application built with Go.

---

## 🚀 Features

- ✅ Add todos
- ✏️ Edit todos
- 🔄 Toggle completion
- 🗑 Delete todos
- 📋 List todos in a formatted table

---

## 📦 Steps to execute

Clone & install dependencies:
```
git clone https://github.com/gurunath-pujar-dev/golang-cli-todo.git
cd golang-cli-todo
go mod tidy
```

Run commands: Open current directory in cmd/bash
```
go run ./ --help  #list all commands
go run ./ -list  #list all todos
go run ./ -add [todo-item]  #add new todo-item
go run ./ -del [todo-item-no]  #delete todo-item by index
go run ./ -toggle [todo-item-no]  #toggle todo-item completion by index
go run ./ -edit [id:new-todo-item]  #edit todo-item with new todo
```



