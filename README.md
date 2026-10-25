# Задание 1
тфлинт:
<img width="1632" height="757" alt="image" src="https://github.com/user-attachments/assets/38a0b267-5216-4d86-9663-68c6fe5b6417" />
чеков:
<img width="1917" height="1052" alt="image" src="https://github.com/user-attachments/assets/e9e56406-15c0-449d-8145-b649651533d2" />
<img width="1907" height="792" alt="image" src="https://github.com/user-attachments/assets/647b1d06-b85d-434d-a48d-0ca4bd7863bf" />
<img width="1897" height="1007" alt="image" src="https://github.com/user-attachments/assets/aed00cae-f6e0-4223-90dc-6761333c11c6" />
Список обнаруженных типов ошибок:
1. **`terraform_required_providers` (tflint):** В блоке `required_providers` для провайдера `yandex` не зафиксирована версия (`version`).
2. **`terraform_unused_declarations` (tflint):** Переменные объявлены в файле `variables.tf`, но нигде не используются в манифестах инфраструктуры (`vms_ssh_root_key`, `vm_web_name`, `vm_db_name`).
3. **`CKV_TF_1: Ensure Terraform module sources use a commit hash` (checkov):** Источник внешнего Git-модуля привязан к имени ветки (`?ref=main`), а не к конкретному неизменяемому коммит-хэшу (SHA-1 commit hash), что создаёт риск подмены или нестабильности версий.
4. **`CKV_TF_2: Ensure Terraform module sources use a tag with a version number` (checkov):** Источник внешнего Git-модуля не зафиксирован через конкретный семантический тег версии (например, `?ref=v1.0.0`).
# Задание 2
<img width="1467" height="557" alt="image" src="https://github.com/user-attachments/assets/b778ae8c-a784-48d4-8458-3e5f57e486f6" />
<img width="1417" height="276" alt="image" src="https://github.com/user-attachments/assets/0f418672-6b8e-4990-911c-dcdc1e130e85" />
<img width="1886" height="852" alt="image" src="https://github.com/user-attachments/assets/3788e7e4-ca3b-42a5-97a8-f485cb92eefd" />
<img width="1377" height="540" alt="image" src="https://github.com/user-attachments/assets/695c072e-56ed-4862-86ad-a85cfd47af2e" />
<img width="1421" height="312" alt="image" src="https://github.com/user-attachments/assets/7fdb2611-dfb7-4617-857f-ee58f2da0d16" />

# Задание 3
<img width="935" height="51" alt="image" src="https://github.com/user-attachments/assets/bd74b9ef-f15f-4b3f-bd5d-c2b1dafc23d7" />

# Задание 4
