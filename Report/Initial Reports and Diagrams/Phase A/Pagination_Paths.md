# Test Paths (Set Theory)
### Set of All Independent Paths

P = {p1, p2, p3, p4, p5, p6}
Where each path is defined as:

---
### p1

p1 = { n1, n2, n3, n4, n5, n6, n7, n8, n21 }
**Description:**  
fileContent is null or empty

---
### p2

p2 = { n1, n2, n3, n4, n5, n6, n9, n10, n20, n21 }
**Description:**  
fileContent is valid but has length 0

---
### p3

p3 = { n1, n2, n3, n4, n5, n6, n9, n10, n11, n12, n13, n17, n19, n16, n10, n20, n21 }
**Description:**  
pageContent reaches pageSize exactly

---
### p4

p4 = {n1, n2, n3, n4, n5, n6, n9, n10, n11, n12, n14, n15, n18, n19, n16, n10, n20, n21 }
**Description:**  
last character of fileContent, pageContent < pageSize

---
### p5

p5 = { n1, n2, n3, n4, n5, n6, n9, n10, n11, n12, n14, n16, n10, n20, n21 }
**Description:**  
middle character, pageContent < pageSize, not last char

---
### p6

p6 = { n1, n2, n3, n4, n5, n6, n9, n10, n11, n12, n13, n17, n19, n16, n10, n11, n12, n14, n15, n18, n19, n16, n10, n20, n21 }
**Description:**  
multiple pages: one full page + remaining content on last iteration

