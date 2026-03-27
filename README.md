hello netology
Файл .gitignore в директории terraform скрывает:
1. Полностью директорию .terraform
2. Файлы которые заканчиваются на .tfstate
3. Файлы содержащие .tfstate.
4. Файл crash.log
5. Файл содержащие crash.(любое содержимое).log (пример crash.after_update.log)
6. Файлы которые заканчиваются на .tfvars
7. Файлы которые заканчиваются на .tfvars.json
8. Файл override.tf
9. Файл override.tf.json
10. Файлы которые заканчиваются на _override.tf
11. Файлы которые заканчиваются на _override.tf.json
12. Файл .terraform.tfstate.lock.info
13. Файл .terraformrc
14. Файл terraform.rc

some tests