# 🇮🇷 Iranian National ID (Melli Code) Prefixes

This repository contains a comprehensive and structured JSON file that maps the three-digit prefixes of the Iranian National ID (known as *Melli Code*) to their corresponding city and province of issuance.

This dataset is invaluable for developers, data analysts, and anyone needing to validate or determine the geographical origin of an Iranian National ID.
---

## 📊 Data Structure

The main file, `mali-list.json`, is a JSON object where each key represents a province. The value for each province contains a list of its cities and their corresponding National ID prefixes.

- **Root Key**: `ProvinceName (نام استان)`
- **City Object**:
  - `city_en`: The English name of the city/region.
  - `city_fa`: The Persian name of the city/region.
  - `codes`: An array of string prefixes associated with that city.

**Example Snippet:**

```json
{
  "Tehran (تهران)": {
    "cities": [
      {
        "city_en": "Tehran",
        "city_fa": "تهران",
        "codes": [
          "001",
          "002",
          "004",
          "005",
          "006",
          "007",
          "008"
        ]
      },
      {
        "city_en": "Shemiranat",
        "city_fa": "شمیرانات",
        "codes": [
          "003"
        ]
      }
    ]
  },
  "Isfahan (اصفهان)": {
    "cities": [
      {
        "city_en": "Isfahan",
        "city_fa": "اصفهان",
        "codes": [
          "128",
          "129"
        ]
      },
      {
        "city_en": "Kashan",
        "city_fa": "کاشان",
        "codes": [
          "041",
          "042"
        ]
      }
    ]
  }
}
```


```
📊 Statistics for Iranian National ID Prefixes
-------------------------------------------------
✔️ Total Provinces Defined: 31
✔️ Total Cities/Regions Defined: 295
✔️ Total Prefixes Available: 340
```

---

## 🤝 Contributing

Contributions are welcome! If you find any inaccuracies, have suggestions for improvements, or want to add more examples (e.g., in JavaScript, Java, etc.), please feel free to open an **Issue** or submit a **Pull Request**.

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
