# 🍯 HoneyPhoto

**HoneyPhoto** is a lightweight Windows desktop application for viewing, editing, resizing, converting, and exporting images.

Built with **C# and .NET 8**, HoneyPhoto provides commonly used image operations through a simple and easy-to-use Windows Forms interface.

## ✨ Features

### 🖼️ Image Management

* Open images from your computer
* Preview images inside the application
* Display image dimensions and file information
* Reset changes and return to the original image
* Open the original image location in File Explorer

### 📐 Image Resizing

HoneyPhoto allows you to resize images by specifying custom dimensions.

The application uses high-quality image interpolation when resizing to maintain good image quality.

### 🔄 Image Editing

Basic image editing operations include:

* Rotate image left
* Flip image horizontally
* Reset all changes
* Preview modifications before saving

The original image is preserved while editing, allowing changes to be reset when needed.

### 🔁 Image Conversion

Images can be saved in multiple formats:

* PNG
* JPG
* JPEG
* JFIF
* BMP
* GIF
* TIFF
* ICO

This makes HoneyPhoto useful for quickly converting images between commonly used formats.

### 📤 Export & Integration

HoneyPhoto provides several ways to export or share the current image:

* 📄 Export to PDF
* 📋 Copy to Clipboard
* 🖌️ Open in Microsoft Paint
* 🖼️ Open in Windows Photos
* 📝 Export to Microsoft Word
* 📊 Export to Microsoft PowerPoint
* ✉️ Export to Microsoft Outlook

Microsoft Office integrations allow images to be quickly transferred into Word documents, PowerPoint presentations, or Outlook emails.

### ⌨️ Keyboard Shortcuts

| Shortcut   | Action            |
| ---------- | ----------------- |
| `Ctrl + O` | Open image        |
| `Ctrl + S` | Save image        |
| `Ctrl + R` | Reset image       |
| `Ctrl + L` | Rotate left       |
| `Ctrl + F` | Flip horizontally |
| `Ctrl + E` | Export            |
| `Ctrl + I` | Show information  |

## 🛠️ Technologies

HoneyPhoto is built using:

* **C#**
* **.NET 8**
* **Windows Forms**
* **System.Drawing**
* **PDFsharp**
* **Microsoft Office Interop**

The project targets:

```text
net8.0-windows
```

## 📦 Requirements

To build and run HoneyPhoto, you need:

* Windows
* .NET 8 SDK
* Visual Studio 2022 or newer
* Windows Forms support

For Microsoft Office export functionality, the required Microsoft Office applications should be installed on the system.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/fazilmemmedzade/HoneyPhoto.git
```

Open the solution:

```text
HoneyPhoto.sln
```

Then build and run the project using Visual Studio.

## 📖 Usage

### Open an Image

Open an image using the **Open** button or press `Ctrl + O`.

After selecting an image, HoneyPhoto displays it in the main interface along with its basic information.

### Edit the Image

Use the available editing tools to:

* Resize the image
* Rotate it
* Flip it horizontally
* Reset your changes

The edited image can then be saved or exported.

### Save & Convert

Choose the desired output format and save the image to your preferred location.

HoneyPhoto can be used as a simple image converter when no editing is required.

### Export

The export functionality provides quick access to PDF, Clipboard, Paint, Photos, Word, PowerPoint, and Outlook.

## 📁 Project Structure

```text
HoneyPhoto/
│
├── Properties/
├── Resources/
│
├── MainForm.cs
├── MainForm.Designer.cs
├── MainForm.resx
│
├── InformationForm.cs
├── InformationForm.Designer.cs
├── InformationForm.resx
│
├── Program.cs
├── HoneyPhoto.csproj
├── HoneyPhoto.sln
└── README.md
```

## 🎯 Project Purpose

HoneyPhoto was created to provide a straightforward desktop solution for everyday image operations.

Instead of using a large and complex image-editing application for simple tasks, HoneyPhoto focuses on the operations that are commonly needed:

**open → edit → resize → convert → save → export**

The application is designed to remain lightweight and simple while providing useful Windows and Microsoft Office integrations.

## 👨‍💻 Author

**Fazil Məmmədzadə**

<a href="https://github.com/fazilmemmedzade">Github</a>
<a href="https://fazilmemmedzade.github.io/Portfolio">Portfolio</a>

## ⭐ Support

If you find HoneyPhoto useful, consider giving the repository a ⭐ on GitHub.

## 📸 Screenshots

<img src="Annotation 2026-06-30 08394533.png" alt="HoneyPhoto" width="1000"/>
