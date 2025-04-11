Ось англійський переклад вашого тексту:

---

# **Introduction to HTML: First Lesson**

HTML (HyperText Markup Language) is a markup language used to create web pages. It defines the **structure** of the content, but it doesn't handle design (that's done by CSS) or logic (that's JavaScript).

---

## **1. What is HTML?**
HTML consists of **tags** that define different elements on a page. For example:  
- `<h1>` — heading  
- `<p>` — paragraph  
- `<a>` — link  
- `<img>` — image  

Every HTML document has a basic structure.

---

## **2. Basic HTML Structure**  
Here is the simplest HTML document:

```html
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    <h1>Hello, world!</h1>
    <p>This is my first HTML document.</p>
</body>
</html>
```

### **Code Explanation:**
- `<!DOCTYPE html>` — declares that this is an HTML5 document.  
- `<html>` — the root element of the page.  
- `<head>` — contains technical info (title, encoding, links to CSS/JS).  
- `<body>` — contains all visible content.

---

## **3. Basic HTML Tags**  
| Tag | Description | Example |
|-----|-------------|---------|
| `<h1>...<h6>` | Headings (from most to least important) | `<h1>Main Heading</h1>` |
| `<p>` | Paragraph | `<p>This is a paragraph.</p>` |
| `<a>` | Link | `<a href="https://google.com">Google</a>` |
| `<img>` | Image | `<img src="photo.jpg" alt="Description">` |
| `<ul>`, `<ol>`, `<li>` | Lists (unordered and ordered) | `<ul><li>Item 1</li></ul>` |
| `<div>` | Block container | `<div>This is a block</div>` |

---

## **4. How to Create an HTML File?**  
1. Open **Notepad** (Windows) or **TextEdit** (Mac).  
2. Paste the HTML code.  
3. Save the file with a `.html` extension (e.g., `index.html`).  
4. Open it in a browser (Chrome, Firefox).

---

## **5. Practice: First Page**  
Create a file named `index.html` with the following code:

```html
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>My Website</title>
</head>
<body>
    <h1>My First Web Page</h1>
    <p>HTML is easy!</p>
    <a href="https://google.com">Go to Google</a>
    <img src="https://via.placeholder.com/150" alt="Sample image">
</body>
</html>
```

Open it in a browser — and you’ll see your first web page! 🎉

---

## **6. What’s Next?**
- **CSS** — for styling (colors, fonts, sizes).  
- **JavaScript** — for interactivity (buttons, forms).  
- **More HTML Tags** — tables, forms, media.

**💡 Tip:** Use [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) for deeper learning.

---

Now you know the basics of HTML! 🚀 Start experimenting with code to understand it better.
