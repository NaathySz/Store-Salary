# [Store module] Salary
Salary module for Store: Players can redeem a salary based on their flags or group.

# Config
Config will be auto generated. Default:
```json
{
  "wages": {
    "@css/generic": {
      "salary": 2000,
      "cooldown_minutes": 60
    },
    "@css/slay": {
      "salary": 3000,
      "cooldown_minutes": 120
    },
    "@css/vip": {
      "salary": 5000,
      "cooldown_minutes": 1440
    },
    "#admin": {
      "salary": 6000,
      "cooldown_minutes": 1440
    }
  },
  "salary_command": [
    "salary"
  ],
  "database_host": "localhost",
  "database_port": 3306,
  "database_name": "name",
  "database_user": "root",
  "database_password": "password"
}
```
