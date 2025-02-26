# json-mdtable

Flattens JSON and outputs half a markdown table for documenting JSON mapping transformations

## Sample JSON Input

```json
{
  "library": {
    "books": [
      {
        "title": "Structure and Interpretation of Computer Programs",
        "authors": ["Abelson", "Sussman"],
        "isbn": "9780262510875",
        "price": 38.9,
        "copies": 2
      },
      {
        "title": "The C Programming Language",
        "authors": ["Kernighan", "Richie"],
        "isbn": "9780131103627",
        "price": 33.59,
        "copies": 3
      },
      {
        "title": "The AWK Programming Language",
        "authors": ["Aho", "Kernighan", "Weinberger"],
        "isbn": "9780201079814",
        "copies": 1
      },
      {
        "title": "Compilers: Principles, Techniques, and Tools",
        "authors": ["Aho", "Lam", "Sethi", "Ullman"],
        "isbn": "9780201100884",
        "price": 23.38,
        "copies": 1
      }
    ],
    "loans": [
      {
        "customer": "10001",
        "isbn": "9780262510875",
        "return": "2016-12-05"
      },
      {
        "customer": "10003",
        "isbn": "9780201100884",
        "return": "2016-10-22"
      },
      {
        "customer": "10003",
        "isbn": "9780262510875",
        "return": "2016-12-22"
      }
    ],
    "customers": [
      {
        "id": "10001",
        "name": "Joe Doe",
        "address": {
          "street": "2 Long Road",
          "city": "Winchester",
          "postcode": "SO22 5PU"
        }
      },
      {
        "id": "10002",
        "name": "Fred Bloggs",
        "address": {
          "street": "56 Letsby Avenue",
          "city": "Winchester",
          "postcode": "SO22 4WD"
        }
      },
      {
        "id": "10003",
        "name": "Jason Arthur",
        "address": {
          "street": "1 Preddy Gate",
          "city": "Southampton",
          "postcode": "SO14 0MG"
        }
      }
    ]
  }
}
```

## Output Markdown Table

| X API Field (Destination)               | Y API Field (Source)  | Notes |
| --------------------------------------- | --------------------- | ----- |
| `library.books[i].title`                | TODO: Map from source | n/a   |
| `library.books[i].authors[i]`           | TODO: Map from source | n/a   |
| `library.books[i].isbn`                 | TODO: Map from source | n/a   |
| `library.books[i].price`                | TODO: Map from source | n/a   |
| `library.books[i].copies`               | TODO: Map from source | n/a   |
| `library.loans[i].customer`             | TODO: Map from source | n/a   |
| `library.loans[i].isbn`                 | TODO: Map from source | n/a   |
| `library.loans[i].return`               | TODO: Map from source | n/a   |
| `library.customers[i].id`               | TODO: Map from source | n/a   |
| `library.customers[i].name`             | TODO: Map from source | n/a   |
| `library.customers[i].address.street`   | TODO: Map from source | n/a   |
| `library.customers[i].address.city`     | TODO: Map from source | n/a   |
| `library.customers[i].address.postcode` | TODO: Map from source | n/a   |
