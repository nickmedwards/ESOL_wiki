callback function to call if your script crashes add

# Example
```
import atexit

def _on_exit(db: DBManager):
    db.close_connections()

# an object that you'd like to clean up regardless of how your ends, eg a database manager
db_manager = DBManager()

atexit.register(_on_exit, db_manager)
```