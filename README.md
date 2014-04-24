Binary
```
gpg --output private.doc.gpg --encrypt --recipient user@mail private.doc 
gpg --output private.doc --decrypt private.doc.gpg
```

ASCII
```
gpg --output private.doc.asc -ea -r user@domain.org private.doc
gpg -d private.doc.asc > private.doc
```
