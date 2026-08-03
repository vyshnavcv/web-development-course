# Lesson 04 - HTML Lists

## Learning Objectives

By the end of this lesson, I can:

- Create unordered lists.
- Create ordered lists.
- Create nested lists.
- Choose the correct list type.
- Organize information using lists.

---

# What is a List?

A list is a collection of related items.

Examples:

- Shopping list
- To-do list
- Programming languages
- Recipe ingredients

---

# Types of Lists

HTML has three types of lists.

1. Ordered List (`<ol>`)
2. Unordered List (`<ul>`)
3. Description List (`<dl>`) *(Learn later)*

---

# Unordered List

Used when the order does NOT matter.

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

Output:

- HTML
- CSS
- JavaScript

---

# Ordered List

Used when the order DOES matter.

```html
<ol>
    <li>Wake up</li>
    <li>Go to school</li>
    <li>Study</li>
</ol>
```

Output:

1. Wake up
2. Go to school
3. Study

---

# List Item

Each item inside a list uses:

```html
<li></li>
```

Example:

```html
<ul>
    <li>Apple</li>
    <li>Banana</li>
</ul>
```

---

# Nested Lists

Lists can contain other lists.

Example:

```html
<ul>
    <li>Frontend
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
    </li>

    <li>Backend
        <ul>
            <li>Node.js</li>
            <li>MongoDB</li>
        </ul>
    </li>
</ul>
```

Nested lists organize related information.

---

# When to Use Each List

Use `<ul>` when:

- Order does NOT matter.
- Features
- Skills
- Shopping list

Use `<ol>` when:

- Order matters.
- Instructions
- Recipe steps
- Rankings

---

# Best Practices

✅ Every list item must use `<li>`.

✅ Use `<ol>` only when sequence matters.

✅ Use `<ul>` when order is unimportant.

✅ Place nested lists inside the parent `<li>`.

---

# Common Mistakes

❌ Forgetting `<li>`.

Wrong:

```html
<ul>
HTML
CSS
</ul>
```

Correct:

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>
```

---

❌ Incorrect nesting.

Wrong:

```html
<li>Frontend</li>
<ul>
```

Correct:

```html
<li>
    Frontend
    <ul>
        ...
    </ul>
</li>
```

---

# Real World Uses

Lists are used for:

- Navigation menus
- Feature lists
- Sidebars
- Product features
- Dashboards
- Documentation

---

# AI Tip

Ask AI:

"Review my HTML lists. Tell me if I chose the correct list type and explain why."

---

# Key Tags

<ul>
<ol>
<li>