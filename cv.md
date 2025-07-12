# **Andrew Maxim**

---

### **Email:** fake_email@gmail.com
### **Phone:** +44 777 777 111
### **GitHub:** <https://github.com/Uixmonster>
### **Discord:** <Uixmonster>

---

## **About me**

I know basics of **Python** and **SQL**, also have experience in creating education projects on **Django and Flask**.
I want to become a *Junior Frontend Developer* and ready to solve complex problems. I am studying computer sciences by myself using courses from leading universities on Coursera and also interested in sound engineering.

---

## **Skills**

#### Programming languages
|Language | Level |
|---|---|
|**Python**  |*Intermediate*|
|**HTML**    | *Basic*|
|**CSS**      | *Basic*|
|**JavaScript** | *Basic*|

#### **Frameworks**
- *Django*        |  [*Basic*]
- *Flask*         |  [*Basic*]

#### *Other skills*
- **Git**  |  [*Basic*]         
- **PyCharm** |  [*Basic*]
- **Visual Studio Code** |  [*Basic*]
- **GitHub** |  [*Basic*]
- **Terminal** |  [*Basic*]
- **Linux** |  [*Basic*]

---

## **Code examples**

```python
# if __name__ == '__main__': --> 'note for me'

class Person:
    def __init__(self, name, surname, age, country) -> None:
        self.name = name
        self.surname = surname
        self.age = age
        self.country = country

        self.adult_ages = {"PL": 18, "USA": 21}

    def is_adult(self):
        if self.adult_ages[self.country]:
            return True

        return False


if __name__ == "__main__":
    person = Person("Andrew", "Maksim", 16, "PL")
    print(person.name)
    print(person.is_adult())
```
