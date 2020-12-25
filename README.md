ветка fix

в файле .gitignore описаны исключения файлов:

1) tfstate, tfvars - файлы с перечисленными расширениями
2) crash.log, override.tf, override.tf.json, terraform.rc, .terraformrc - файлы с перечисленными именами
3) *.tfstate.* - файлы в имени которых есть .tfstate. 
4) *_override.tf, *_override.tf.json - все файлы, имена которых оканчиваются на _override.tf или _override.tf.json
