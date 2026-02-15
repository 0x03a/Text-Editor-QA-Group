## 3. Test Paths (Set Theory)

### Set of All Independent Paths


P ={p1, p2, p3, p4, p5, p6, p7, p8}

Each path is defined as a tuple of nodes:

---

### p1

p1 = { n1, n2, n3, n4, n5, n20 }

**Description:** 
Keyword length < 3 → Exception thrown.

---

### p2
p2 = { n1, n2, n3, n4, n6, n19, n20 }

**Description:** 
No documents to process.

---

### p3

p3 = {n1, n2, n3, n4, n6, n7, n8, n9, n7, n6, n19, n20}

**Description:** 
Page does not contain keyword.

---

### p4

p4 = { n1, n2, n3, n4, n6, n7, n8, n9, n10, n11, n12, n11, n7, n6, n19, n20}

**Description:** 
Word does not match (case-insensitive check fails).

---

### p5

p5 = { n1, n2, n3, n4, n6, n7, n8, n9, n10, n11, n12, n13, n15, n16, n17, n18, n6, n19, n20 }

**Description:** 
Word matches at i = 0 → prefix is empty.

---

### p6

p6 = { n1, n2, n3, n4, n6, n7, n8, n9, n10, n11, n12, n13, n14, n16, n17, n18, n6, n19, n20 }

**Description:** 
Word matches at i > 0 → prefix is words{i-1}.

---

### p7

p7 = {langle n1, n2, n3, n4, n6, n7, n8, n9, n10, n11, n12, n13, n14, n16, n17, n18, n6, n7, n8, n9, n7, n6, n19, n20 }

**Description:** 
Multiple documents/pages — word found, then next page has no match.

---

### p8

p8 = { n1, n2, n3, n4, n6, n7, n8, n9, n10, n11, n12, n11, n12, n13, n14, n16, n17, n18, n6, n19, n20}


**Description:** 
Multiple words checked before match is found.

---

## Conclusion

Total Independent Paths = **8**



