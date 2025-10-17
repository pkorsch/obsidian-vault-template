---
type: moc
title: "{{title}}"
created: "{{date: DD-MM-YYYY}} {{time}}"
updated:
tags:
  - moc
  - index
  - overview
aliases:
  - MoC {{title}}
description: Map of Content for {{title}} — central hub of connected notes and topics.
---

# 🗺️ {{title}} – Map of Content

> This note serves as a **central hub** for navigating all related notes, concepts, and resources about **{{title}}**.

---

## 🧩 Overview

Short summary of what this topic covers:

> 

---

## 🗂️ Key Topics

- [[<related_topic_1>]]
- [[<related_topic_2>]]
- [[<related_topic_3>]]

---

## 📘 Core Notes

- [[<main_concept_1>]] – 
- [[<main_concept_2>]] – 
- [[<main_concept_3>]] – 

---

## 🧠 Insights & Ideas

- [[<idea_1>]]
- [[<note_1>]]
- [[<experiment_or_reflection>]]

---

## 📚 Reading & References

- [[<book_or_article>]]
- [[<author_profile>]]
- External links:
  - [ ] [Official Documentation](https://)
  - [ ] [Blog Post](https://)
  - [ ] [Video / Talk](https://)

---

## 🧰 Tools & Resources

| Tool / Resource | Description | Link |
|-----------------|--------------|------|
| | | |
| | | |

---

## 🔗 Related MOCs

- [[MOC - DevOps]]
- [[MOC - GCP]]
- [[MOC - Learning]]
- [[MOC - Books]]

---

## 🧾 Dataview Example (Optional)

If you use the **Dataview plugin**, you can automatically list all notes tagged under this topic:

```dataview
table file.mtime as "Last Modified", tags
from "notes/"
where contains(tags, "{{title | lower}}")
sort file.mtime desc
