# python_starlette

```json
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            // Uses uvicorn as a module to launch a Starlette application. The
            // application must be in a file called main.py and must be called
            // "app". Change "args" in this launch config if using something
            // else for the filename or app variable name.
            "name": "Launch Starlette application",
            "type": "python",
            "request": "launch",
            "module": "uvicorn",
            "justMyCode": true,
            "args": [
                "main:app"
            ]
        }
    ]
}
```

![image](https://user-images.githubusercontent.com/7719209/178388674-00eef247-c1b2-4b34-b5aa-bc33354f1df4.png)
