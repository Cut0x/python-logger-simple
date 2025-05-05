# Logger Module
A simple <a href="[https://nodejs.org/en](https://pypi.org/project/python-logger-simple/)" target="_blank"><strong>Python</strong></a> module with configurable options.

# 📥 Installation
```bash
pip install python-logger-simple
```

[x] Head to [logger-simple.com](https://logger-simple.com/) to retrieve the required information, and to view the logs.

# ✏️ Usage
```js
# Python
from python_logger_simple import Logger

logger = Logger(app_id="your_app_id", api_key="your_api_key")
logger.log_success("Test from Python")
```

# 📣 Options
Initialize the Logger with the following options:
- `app_id` : Your application ID *(required)*.
- `api_key`: Your application key *(required)*.

# 📜 Methods
- `log_error('An error has occurred.')` - Logs an error message.
- `log_success('Succes message.')` - Logs an succes message.
- `log_info('Important information.')` - Logs an info message.
