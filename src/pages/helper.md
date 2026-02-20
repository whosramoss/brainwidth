---
title: Helper
description: Explore markdown content.
layout: ../layouts/Layout.astro
---

# H1 — Main Title

## H2 — Subtitle

### H3 — Section

#### H4 — Subsection

##### H5 — Detail

###### H6 — Note

---

## Paragraph and Emphasis

This is a normal paragraph with **strong text**, _italic text_, ~~strikethrough text~~, `inline code`, and an [example link](https://example.com).

We can also mix **bold with _italic inside_** the same sentence.

---

## Unordered List

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
    - Subitem 2.2.1
- Item 3

---

## Ordered List

1. First
2. Second
3. Third
   1. Numbered subitem
   2. Another subitem

---

## Task List (GitHub Flavored Markdown)

- [x] Completed task
- [ ] Pending task
- [ ] Another task

---

## Blockquote

> "Simplicity is the ultimate sophistication."
>
> — Leonardo da Vinci

---

## Inline Code

Use `npm install` to install the dependencies.

---

## Code Block

```javascript
function sum(a, b) {
  return a + b;
}

console.log(sum(2, 3));
```

```bash
git add .
git commit -m "feat: add markdown"
git push
```

---

## Table (GFM)

| Name    | Role               | Status   |
| ------- | ------------------ | -------- |
| Gabriel | Frontend Developer | Active   |
| Ana     | Product Designer   | Active   |
| Lucas   | Backend Developer  | Inactive |

---

## Image

![Example image](https://via.placeholder.com/600x300)

---

## Horizontal Rule

---

## Subscript / Superscript

H<sub>2</sub>O is water  
E = mc<sup>2</sup>

---

## KBD

Press <kbd>Ctrl</kbd> + <kbd>S</kbd> to save.

---

## Details / Summary

<details>
  <summary>Click to expand</summary>

Hidden content that can be expanded.

- Internal item
- Another item

</details>

---

## Figure with Caption

<figure>
  <img src="https://via.placeholder.com/400x200" alt="Illustrative image" />
  <figcaption>Image caption</figcaption>
</figure>
