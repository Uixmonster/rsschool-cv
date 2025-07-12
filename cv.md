# **Andrew Maxim**

---

### **Email:** fake_email@gmail.com
### **Phone:** +44 777 777 111
### **GitHub:** <https://github.com/Uixmonster>
### **Discord:** Uixmonster

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

---

## **Experience**

- **Course:** Introduce to Python Programming & Django Backend Web Development.
- **School:** *Teb Education Krakow*.

### HealthTracker – Django Web App
- Final project completed as part of a programming course in *Teb Education School*.
- Implemented Django models, views, templates, CRUD.
- Built dynamic charts with Chart.js to visualize activity statistics.
- Designed interface using HTML, CSS and Bootstrap.

**Used stack:** Python, Django, Bootstrap, SQLite, Chart.js.
**Features:** user registration, activity logging, data visualization with Chart.js, Django Admin.

#### Project demo pictures:
<img width="1555" height="928" alt="Screenshot 2024-05-26 141913" src="https://github.com/user-attachments/assets/24473334-5bd5-4cb3-963a-5b4acae5c7af" />
<img width="1802" height="919" alt="Screenshot 2024-05-26 142627" src="https://github.com/user-attachments/assets/733f7d79-c2d8-4aec-8ca8-82d7d7026e16" />
<img width="1621" height="924" alt="Screenshot 2024-05-26 142739" src="https://github.com/user-attachments/assets/7d01f4e0-ee8c-4fa6-8012-fff1a0e76f8d" />

#### Project code example:
```python
from django import forms
from django.contrib.auth.models import User
from .models import Meal, Activity, WeightEntry
from django.contrib.auth.forms import UserCreationForm, AuthenticationForm


class CustomUserCreationForm(UserCreationForm):
    class Meta:
        model = User
        fields = ['username', 'password1', 'password2']

    def __init__(self, *args, **kwargs):
        super(CustomUserCreationForm, self).__init__(*args, **kwargs)
        for field_name, field in self.fields.items():
            field.widget.attrs['class'] = 'form-control'


class MealForm(forms.ModelForm):
    class Meta:
        model = Meal
        fields = ['date', 'meal_type', 'calories', 'proteins', 'fats']

    def __init__(self, *args, **kwargs):
        super(MealForm, self).__init__(*args, **kwargs)
        for field_name, field in self.fields.items():
            field.widget.attrs['class'] = 'form-control'


class ActivityForm(forms.ModelForm):
    class Meta:
        model = Activity
        fields = ['date', 'activity_type', 'duration', 'calories_burned']

    def __init__(self, *args, **kwargs):
        super(ActivityForm, self).__init__(*args, **kwargs)
        for field_name, field in self.fields.items():
            field.widget.attrs['class'] = 'form-control'


class WeightEntryForm(forms.ModelForm):
    class Meta:
        model = WeightEntry
        fields = ['date', 'weight']

    def __init__(self, *args, **kwargs):
        super(WeightEntryForm, self).__init__(*args, **kwargs)
        for field_name, field in self.fields.items():
            field.widget.attrs['class'] = 'form-control'
```

---

## **Education**

- **School:** *Teb Education*.
- **Course:** Introduce to Python Programming & Django Backend Web Development with CISCO - (2023 - 2024).
- **Location:** Poland, Krakow city.
Studied programming fundamentals with Python, version control with Git, and web technologies HTML/CSS/Bootstrap.
Completed hands-on projects including a full-stack Django web app HealthTracker.

### **Also studied in the course:**

- Data Structure & Algorithms.
- REST APIs.
- SQL, ORM.
- Django, Flask

---

## **Certificates:**

- ### Polish Language Certificate – *B1 Level*.
- ### Certificate of Completion – *Python Program at TEB Edukacja with CISCO*.


## **Languages:**

#### **English – A2 (in progress)**
- Actively improving spoken and written English through self-study and daily practice.

#### **Russian - C2**
- Native language.
  
#### **Ukranian - C2**
- Native language.
  
#### **Polish - B1**
- I use it in my work and everyday life.

