# Flights

### ❓ Problem Statement
Our client has built two databases, each containing a few tables, but has run into an issue of combining the information across databases. The have supplied us with the data contained
in each of the tables and have asked us to create a way to merge the two datasets. We have informed them that each row will not be a 100% perfect match, but we can give them our
best guess.

---

### 🗄️ Files
* `factset_address.csv` - A table from the factset database containing address information
* `factset_coverage.csv` - A table from the factset database containing coverage information
* `factset_structure.csv` - A table from the factset database containing structure information
* `mdl_geo.csv` - A table from the mdl database containing geographic information
* `mdl_vendor.csv` - A table from the mdl database containing vendor information

---

### 🖨️ Expected output
A .csv file containing three columns: `Factset_id`, `MDL_id`, and `confidence`. The first column is the factset row id, the second column is the mdl row id, and the third is the
level of confidence value that has been scaled to be a measure between 0 and 100.

---

### 👩‍💻 Concepts being evaluated
1. Programming concepts
2. Exploratory data analysis
3. Unsupervised clustering
4. Levenshtein, Hamming, Cosign distances
5. NLP knowledge
6. Ensemble modeling
