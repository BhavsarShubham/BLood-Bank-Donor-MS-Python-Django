# Blood Bank Donor Management System (Python Django + MySQL)

## Setup Instructions

### 1. Open MySQL

- Create a database named `bbdmspythondb`.

### 2. Import SQL File

- Import the SQL file available in the `SQL File` folder.  
  *(Note: For MySQL, we use the XAMPP server.)*

---

### 3. Install Django

```bash
pip install Django
```

---

### 4. Navigate to the Project Directory

```bash
cd project_path
cd bbdms\bloodbanksystem
```

---

### 5. Now Navigate to the `bloodbanksystem` Folder

```bash
cd bloodbanksystem
```

---

### 6. Run the Project

```bash
python manage.py runserver
```

---

### 7. Install MySQL Clients

```bash
pip install mysqlclient
pip install pymysql
```

---

### 8. Apply Migrations

```bash
python manage.py makemigrations bbdmsapp
python manage.py migrate
```

---

### 9. Run Server Again

```bash
python manage.py runserver
```

### 10. Run the Project in Browser

Click the URL:

[http://127.0.0.1:8000](http://127.0.0.1:8000)

The project will now run.

---

## Login Details

### Admin

- **Username:** `admin`  
- **Password:** `Test@123`

### Donor

- **Username:** `test123`  
- **Password:** `Test@123`  
  OR  
- Register a new donor

---
