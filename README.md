# 📋 Contact Saver App

## Assignment Information

| Field | Details |
|-------|---------|
| **Author** | 2023-CS-70 |
| **Submitted To** | Ma'am Rabeeya Saleem |
| **Subject** | Mobile Application Development (MAD) |
| **Assignment** | Assignment 7 |

---

## 📌 Overview

Contact Saver is an Android application built using Kotlin and RecyclerView. It allows users to manage their contacts with a clean and user-friendly interface.

---

## ✨ Features

1. **Add Contact** — Save a new contact with name, phone number, and optional profile picture
2. **Profile Image Upload** — Upload a custom profile photo from the gallery; defaults to a placeholder avatar if none is selected
3. **Edit Contact** — Update name, phone number, or profile picture of any saved contact
4. **Delete Contact** — Remove a contact with a confirmation dialog
5. **Search** — Search contacts in real-time by name or phone number
6. **Sort** — Sort contacts alphabetically A→Z or Z→A
7. **Load from Phone** — Import contacts directly from the device's contact list
8. **Two-Tab Navigation** — Separate screens for adding contacts and viewing the contact list

---

## 🗂️ Project Structure

```
app/
└── src/
    └── main/
        ├── java/com/example/contact_app_recycler_view/
        │   ├── MainActivity.kt
        │   ├── AddContactFragment.kt
        │   ├── ContactsFragment.kt
        │   ├── ContactAdapter.kt
        │   ├── Contact.kt
        │   └── SharedContactData.kt
        └── res/
            ├── layout/
            │   ├── activity_main.xml
            │   ├── fragment_add_contact.xml
            │   ├── fragment_contacts.xml
            │   ├── activity_item_contact.xml
            │   └── activity_dialog_edit_item.xml
            ├── menu/
            │   └── bottom_nav_menu.xml
            └── drawable/
                ├── default_avatar.png
                ├── circle_background.xml
                └── input_background.xml
```

---

## 📸 Screenshots

<table>
  <tr>
    <td align="center">
      <img src="C:\Users\Talha\Desktop\UET\SEMESTER 6\MAD\2023-CS-70 MAD Assignment 7\Contact_app_recycler_view\app\src\main\res\screenshots\1.jpeg" width="300"/>
      <br/>
      <b>Add Contact Screen</b>
    </td>
    <td align="center">
      <img src="C:\Users\Talha\Desktop\UET\SEMESTER 6\MAD\2023-CS-70 MAD Assignment 7\Contact_app_recycler_view\app\src\main\res\screenshots\2.jpeg" width="300"/>
      <br/>
      <b>Contacts List Screen</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="C:\Users\Talha\Desktop\UET\SEMESTER 6\MAD\2023-CS-70 MAD Assignment 7\Contact_app_recycler_view\app\src\main\res\screenshots\3.jpeg" width="300"/>
      <br/>
      <b>Edit Contact Dialog</b>
    </td>
    <td align="center">
      <img src="C:\Users\Talha\Desktop\UET\SEMESTER 6\MAD\2023-CS-70 MAD Assignment 7\Contact_app_recycler_view\app\src\main\res\screenshots\4.jpeg" width="300"/>
      <br/>
      <b>Search & Sort Feature</b>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI:** XML Layouts, CardView, RecyclerView, BottomNavigationView
- **Architecture:** Single Activity + Fragments
- **Min SDK:** 21
- **Target SDK:** 34

---

## 🚀 How to Run

1. Clone or download the project
2. Open in **Android Studio**
3. Connect a physical device or start an emulator or download app-debug.apk 
4. Click **Run ▶**

---

## 📝 Notes

- Grant **Contacts Permission** when prompted to load phone contacts
- Grant **Storage Permission** when prompted to upload profile photos
- Profile picture defaults to `default_avatar.png` if none is selected