# Python APIs and JSON

Programs often need information from another program. An API is a structured way for software to communicate.

A common API response format is JSON.

## Understanding JSON

JSON looks similar to Python dictionaries:

```json
{
  "name": "TeenCode",
  "level": 1
}
```

Python can work with JSON using the built-in `json` module.

```python
import json

data = '{"name": "TeenCode", "level": 1}'
student = json.loads(data)

print(student["name"])
```

`loads` converts JSON text into Python data.

## API requests

Real applications often use an HTTP library such as `requests`.

Conceptually:

1. Your program sends a request.
2. A server receives it.
3. The server processes it.
4. The server sends a response.
5. Your program reads the response.

Only use APIs you are allowed to access, and never put private keys or passwords directly into public code.

## Practice

Create a JSON string containing a user's name, age, and favorite subject. Convert it into Python data and print the values.

## Challenge

Choose a public educational API and write down:
- what URL you would request
- what information it returns
- what your program would do with that information

Do not publish API keys.
