Aqui está a sua documentação reformulada em **Markdown** com emojis, seções bem organizadas e uma leitura mais agradável para um README no GitHub:

````markdown
# 🚀 Run Multiple Applications with a Single Command  

**HELLO EVERYONE!** 😄  

This project provides a solution to run **multiple applications in sequence** using just **one command** via [TRIGGERcmd](https://www.triggercmd.com/).  

In this repository, you'll find:  
- 📄 **Executable** (`.exe`)  
- 📜 **Source code** (`.waj`) — requires a **WinAutomation license** to modify  

---

## ⚙️ How It Works  

Using the executable, you can run several applications **in sequence** by passing them as parameters in a single TRIGGER CMD call.  

💡 **Example:**  
```bash
C:\...\automation_run_application.exe "C:\...\Teams.exe" "C:\...\WinAutomation.Console.exe" "C:\...\Ssms.exe"
````

**Important:**

* Enclose each parameter in `"double quotes"` to avoid issues with file paths containing spaces.
* To add a delay between applications, append `%<seconds>` after the file name.

  * Example:

    ```bash
    WinAutomation.Console.exe%10
    ```

    This waits **10 seconds** before running the next application.

---

## 📦 How to Use

1. ⬇️ **Download** the `.exe` file.
2. 💾 Save it in any directory you prefer.
3. ⚡ In TRIGGER CMD, create a new trigger pointing to the `.exe` file path.
4. ✅ Enable the **parameter option** in TRIGGER CMD.
5. ▶️ Pass the applications you want to run as parameters.

---

## 🗣️ Alexa Integration

You can make this even cooler by controlling it with **Alexa**! 🤖💬

Steps:

1. Search for **TRIGGER CMD** in your browser.
2. Follow the setup instructions.
3. Connect it to Alexa using the available plug-ins.

---

## 💡 Why Use This?

If you’ve used TRIGGER CMD before, you know it can only trigger **one command per minute**.
I built this to bypass that limitation by allowing **multiple apps to open at once** with just **one trigger**.

📌 My main goal was to open **all my daily applications** instantly, without waiting 60 seconds between each.

---

## 📬 Questions?

Feel free to reach out via my LinkedIn:
🔗 [Lucas Sampaio](https://www.linkedin.com/in/lucasdjsampaio/)

```

Se quiser, também posso criar **uma versão com GIFs ou imagens** para mostrar o fluxo de uso e deixar o README ainda mais chamativo. Isso ajuda bastante a prender a atenção de quem visitar o repositório.
```
