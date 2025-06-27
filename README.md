# 🎓 CertifyGo by shraman_sc

**CertifyGo** is a GUI-based certificate generator that automates the process of creating personalized certificates from a PowerPoint template and Excel data file.

✅ Built for Windows • 🖱 No Python required • 📄 Drag-and-drop interface

---

## 📦 Features

- 📊 **Excel-Based Input**: Includes recipient name, guardian name, and a third customizable field
- 🎨 **Font Styling**: Customize font face, size, and color (name or hex)
- 📝 **Placeholder System**: Auto-replaces fields like `<<variable_0>>`, `<<variable_1>>`, `<<variable_2>>`, `<<COURSE_NAME>>`, `<<CERTIFICATE_NO>>`, and `<<DATE>>`
- 🖼 **Custom Template Support**: Uses `.pptx` files as the certificate layout
- ⚡ **Batch Generation**: Generate all slides in one click
- 🧠 **Preview Fonts**: Select and preview any installed system font
- 🖥️ **Taskbar Icon**: Custom logo used as app icon in taskbar and window

---

## 📁 Excel File Format

Your `.xlsx` should look like:

| Name          | Guardian Name | Custom Info     |
|---------------|----------------|------------------|
| Tom Brown     | John Brown     | Scouts Group A  |
| Linus Evans    | Austin Evans     | Scouts Group B  |

These columns map to:
- `<<variable_0>>`
- `<<variable_1>>` *(optional)*
- `<<variable_2>>` *(optional)*

---

## 📝 PowerPoint Template Format

Use a `.pptx` file with placeholders such as:
 - `<<variable_0>>`
- `<<variable_1>>` *(optional)*
- `<<variable_2>>` *(optional)*

---

## 🚀 How to Use

1. 🖥️ **Open `CertifyGo.exe`**
2. 📂 **Select your PowerPoint template** (.pptx)
3. 📊 **Select your Excel file** (.xlsx)
4. ✏️ Customize optional fields:
   - Certificate number prefix (e.g., C-)
   - Course name
   - Issue date
   - Font name, size, and color
5. ✅ Click **Generate Certificates**
6. 🎉 Find `Generated_Certificates.pptx` in the same folder

---

## 📌 System Requirements

- Windows 10/11
- No internet connection needed
- Standalone executable – does **not** require Python

---

## 🔧 Installation (Optional EXE Installer)

You can run the `.exe` directly or install via the optional installer if provided.

---

## 🔓 License

MIT License

---

## 👤 Author

**Shraman Chaudhuri**  
Made with ❤️ for educators and event organizers.  
GitHub: [shraman-chaudhuri](https://github.com/shraman-c)  
LinkedIn: [shraman-chaudhuri](https://www.linkedin.com/in/shraman-chaudhuri-962182370/)
