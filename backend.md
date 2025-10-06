# 🧠 Backend Overview

The OpenCode backend powers all the logic behind your IDE — running code, executing commands, and managing functions.

---

## 🧩 Core Components
| File | Description |
|------|--------------|
| `server.py` | Main Flask backend that runs commands |
| `interpreter.py` | Parses and executes `.oc` files |
| `/functions/` | Stores built-in OC functions like `add`, `print`, etc. |

---

## 🚀 Running the Backend
```bash
cd backend
python server.py
