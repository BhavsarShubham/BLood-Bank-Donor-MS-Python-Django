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
cd BLood-Bank-Donor-MS-Python-Django\BLood-Bank-Donor-MS-Python-Django\bbdms\bloodbanksystem
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

---

### 10. Configure `settings.py` for MySQL

Add the following lines in your `settings.py`:

```python
import pymysql
pymysql.install_as_MySQLdb()
```

---

### 11. Verify MariaDB Version

Open **Command Prompt (cmd)** and run:

```bash
mysql -u root -p
```

Enter the password, then run:

```sql
SELECT VERSION();
```

Expected output:
```
10.5.24-MariaDB
```

---

### 12. Fix PATH or Multiple Install Conflicts (if any)

---

### 13. Run the Project in Browser

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