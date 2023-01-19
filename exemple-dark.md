---
marp: true
paginate: true
theme: enib-theme-dark
author: r8blerio@enib.fr
class: lead
footer: enib-theme-light
header: ENIB marp theme
---

<!-- _header: :^) -->
<!-- _footer: (^: -->
# ENIB **theme for Marp presentation**

ENIB: https://www.enib.fr/fr/
MARP: https://marp.app/

![bg left:45% 90%](./images/ENIB-logo-et-signature-blanche-inclinee-cmjn-big.png)

---

# **Exemple of code blocks**

```python
class Path():
	def __init__(self, a1, a2):
		self.line = Line(Point(a1.x, a1.y), Point(a2.x, a2.y))

	def draw(self):
		self.line.setFill(blue)
		self.line.draw(win)
```

# And inline
`Inline block`

---

# **Exemple of list and table**
# Numbered list
1. First point
2. Second
   1. Inside
      1. Again inside
3. End of numbered list

---

# Unumbered list

* First point
* Second
  * Inside
    * Again inside
* End  of unnumbered list

---

# Table

|First row|Second row|
|:-------:|:--------:|
|  (0, 0) |  (0, 1)  |
|  (1, 0) |  (1, 1)  |
|  (2, 0) |  (2, 1)  |