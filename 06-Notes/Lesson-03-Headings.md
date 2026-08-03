# Lesson 03 - HTML Headings, Paragraphs, Text Formatting & Comments

## Learning Objectives

By the end of this lesson, I can:

- Use headings correctly.
- Write paragraphs.
- Format text.
- Use line breaks and horizontal rules.
- Write HTML comments.
- Structure readable webpages.

---

# HTML Headings

HTML has six heading levels.

```html
<h1>Main Title</h1>
<h2>Section</h2>
<h3>Subsection</h3>
<h4>Subheading</h4>
<h5>Small Heading</h5>
<h6>Smallest Heading</h6>
```

### Best Practices

- Use only ONE `<h1>` per webpage.
- Use headings in order.
- Headings define the structure of a webpage.

Example:

```
Book Title
 └── Chapter
      └── Topic
           └── Subtopic
```

Equivalent HTML:

```
<h1>
<h2>
<h3>
<h4>
```

---

# Paragraph

Paragraphs are created using:

```html
<p>This is a paragraph.</p>
```

The browser automatically adds spacing between paragraphs.

---

# Text Formatting

## Strong

```html
<strong>Important</strong>
```

Meaning:
- Text is important.
- Appears bold.

---

## Bold

```html
<b>Bold Text</b>
```

Meaning:
- Only changes appearance.
- Does NOT indicate importance.

Use `<strong>` whenever the text is actually important.

---

## Emphasis

```html
<em>Important text</em>
```

Meaning:
- Adds emphasis.
- Usually appears italic.

---

## Italic

```html
<i>Italic text</i>
```

Meaning:
- Only changes appearance.
- Does NOT indicate emphasis.

Prefer `<em>` over `<i>` when the text is meant to be emphasized.

---

# Line Break

```html
<br>
```

Moves the text to the next line.

Example:

```html
Hello<br>
World
```

Output:

Hello
World

---

# Horizontal Rule

```html
<hr>
```

Creates a horizontal line.

Used to separate sections of a webpage.

---

# HTML Comments

```html
<!-- This is a comment -->
```

Comments:

- Are NOT displayed in the browser.
- Help developers understand the code.

Example:

```html
<!-- Navigation -->

<!-- Footer -->
```

---

# Best Practices

✅ One `<h1>` per page.

✅ Use headings in order.

✅ Use `<strong>` for important text.

✅ Use `<em>` for emphasis.

✅ Use `<br>` only when a line break is actually needed.

✅ Use `<hr>` to separate sections.

✅ Write comments when they improve readability.

---

# Common Mistakes

❌ Using headings only to make text larger.

❌ Using many `<br>` tags for spacing.

❌ Forgetting to close tags.

---

# AI Tip

Ask AI:

"Review my HTML for semantic correctness. Explain improvements without rewriting my code."

---

# Key Tags

<h1> to <h6>
<p>
<strong>
<b>
<em>
<i>
<br>
<hr>
<!-- -->