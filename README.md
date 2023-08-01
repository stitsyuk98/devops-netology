В директории ./terraform будут проигнорированы следующие файлы:
```
	**/.terraform/* - все файлы в директории .terraform где бы в репозитории она не находилась

	*.tfstate - будут проигнорированы файлы с расширением .tfstate в этой директории
	*.tfstate.* - будут проигнорированы файлы имеющие .tfstate. в составе имени с любым расширением в этой директории

	crash.log - игнорирование файла crash.log
	crash.*.log - игнорирование файлов, которые начинаются crash. и заканчиваются на .log

	*.tfvars - будут проигнорированы файлы с расширением .tfvars в этой директории
	*.tfvars.json - будут проигнорированы файлы оканчивающиеся на .tfvars.json с расширением .json в этой директории

	override.tf - игнорирование файла override.tf 
	override.tf.json - игнорирование файла override.tf.json
	*_override.tf - будут проигнорированы файлы оканчивающиеся на _override.tf с расширением .tf в этой директории
	*_override.tf.json - будут проигнорированы файлы оканчивающиеся на _override.tf.json с расширением .json в этой директории

	.terraformrc - игнорирование файла .terraformrc 
```