
# 🛡️ VBS / Hyper-V Disabler Tool

> [!WARNING]
> ### 🛑 CRITICAL STEP: REMOVE YOUR PASSWORD
> You **MUST** remove your Windows PIN,Face ID / Windows Hello **BEFORE** running this script. If you skip this, you could potentional  be locked out of your account after the reboot.

---


<img width="1050" height="670" alt="image" src="https://github.com/user-attachments/assets/3846723f-21f5-4e89-a6e5-bd20ace79d26" />

## 🚀 How to Use

**Download** [dgreadiness_v3.6](https://github.com/end-modera/Disabling-Hyper-V-And-VBS/releases/download/Disabling-Hyper-V-And-VBS/dgreadiness_v3.6.1.zip)


**1.Run** **DisableAll.bat.**
**After restart don't forget to press F3, accept changes.**


<img width="1050" height="670" alt="2026-02-10_18-10-46" src="https://github.com/user-attachments/assets/126c6522-6ac0-4eec-837c-2e7e6d535cdc" />


---

## ⚠️ THE REBOOT PROCESS (DO NOT SKIP)
Once your computer restarts, it will boot into a firmware-level screen (usually blue or black text). **You must perform these actions manually:**

### STEP 1: Disable Feature
When prompted on the screen, press the **[ F3 ]** key. 
*(This confirms you want to disable Device Guard/Credential Guard).*

### STEP 2: Confirm and Boot
Immediately after pressing F3, you will be asked to confirm one last time.
Press **[ ANY KEY ]** (Spacebar, Enter, etc.) to finish the process and boot into Windows.

| Step | Action | Key |
| :--- | :--- | :--- |
| **1** | **Confirm Disable** | `F3` |
| **2** | **Continue to Windows** | `Any Key` |

---

## 🛠️ Troubleshooting
* **Script closes immediately:** Ensure the PowerShell script is named exactly `DG_Readiness_Tool_v3.6.ps1`.
* **"File not found":** Ensure you unzipped the files. Do not run the script from inside a `.zip` archive.
* **No F3 prompt:** If your PC boots directly to Windows without showing a blue/black screen, the tool did not trigger correctly. Ensure you ran the `.bat` as Administrator.

---

# 🛡️ Инструмент для отключения VBS / Hyper-V

> [!WARNING]
> ### 🛑 КРИТИЧЕСКИЙ ШАГ: УДАЛИТЕ ВАШ ПАРОЛЬ
> Вы **ОБЯЗАНЫ** удалить ваш Windows PIN-код, Face ID / Windows Hello **ПЕРЕД** запуском этого скрипта. Если вы пропустите этот шаг, вы можете потенциально потерять доступ к своей учетной записи после перезагрузки.

---

<img width="1050" height="670" alt="image" src="https://github.com/user-attachments/assets/3846723f-21f5-4e89-a6e5-bd20ace79d26" />

## 🚀 Как использовать

**Скачать** [dgreadiness_v3.6](https://github.com/end-modera/Disabling-Hyper-V-And-VBS/releases/download/Disabling-Hyper-V-And-VBS/dgreadiness_v3.6.1.zip)

**1. Запустите** **DisableAll.bat.**
**После перезагрузки не забудьте нажать F3, чтобы принять изменения.**

<img width="1050" height="670" alt="2026-02-10_18-10-46" src="https://github.com/user-attachments/assets/126c6522-6ac0-4eec-837c-2e7e6d535cdc" />

---

## ⚠️ ПРОЦЕСС ПЕРЕЗАГРУЗКИ (НЕ ПРОПУСКАТЬ)
После перезагрузки компьютера он загрузится в экран на уровне прошивки (обычно синий или черный текст). **Вы должны выполнить эти действия вручную:**

### ШАГ 1: Отключить функцию
При появлении запроса на экране нажмите клавишу **[ F3 ]**.
*(Это подтверждает, что вы хотите отключить Device Guard/Credential Guard).*

### ШАГ 2: Подтверждение и загрузка
Сразу после нажатия F3 вас попросят подтвердить действие в последний раз.
Нажмите **[ ЛЮБУЮ КЛАВИШУ ]** (Пробел, Enter и т. д.), чтобы завершить процесс и загрузиться в Windows.

| Шаг | Действие | Клавиша |
| :--- | :--- | :--- |
| **1** | **Подтвердить отключение** | `F3` |
| **2** | **Продолжить загрузку Windows** | `Любая клавиша` |

---

## 🛠️ Устранение неполадок
* **Скрипт закрывается сразу:** Убедитесь, что скрипт PowerShell назван именно `DG_Readiness_Tool_v3.6.ps1`.
* **"Файл не найден":** Убедитесь, что вы распаковали файлы. Не запускайте скрипт из `.zip` архива.
* **Нет запроса F3:** Если ваш компьютер загружается сразу в Windows без синего/черного экрана, инструмент не сработал корректно. Убедитесь, что вы запустили `.bat` файл от имени администратора.

