# TkinterYamlPlugin
TkinterYamlPlugin: Simplify tkinter application development by using YAML files for human-readable UI configuration and enhancing code readability.

```markdown
# TkinterYamlPlugin

**TkinterYamlPlugin** is a Python library that enhances the development of tkinter applications by allowing developers to create UI configurations in YAML files, making code more readable and separating UI from logic.

## Goals

The primary goals of adding YAML files to tkinter applications using TkinterYamlPlugin are:

1. **Human-Readable UI Configuration**: Create UI configurations in a human-readable YAML format to enhance the clarity of your tkinter application code.

2. **Separation of Logic and UI**: Facilitate the separation of logic and UI in your tkinter application code, leading to cleaner and more maintainable code.

3. **Improved Code Readability**: Make tkinter application code more readable and comprehensible, reducing complexity.

4. **Empower tkinter Users**: Empower tkinter users with a more robust and user-friendly module, making it easier to create graphical interfaces.

5. **Simplicity with YAML**: Use YAML files seamlessly with tkinter applications for UI configuration.

6. **Alternative Development Option**: Provide developers with an alternative option for developing tkinter applications, introducing a new concept alongside traditional methods like tclsh, wish, and script.

**Note**: TkinterYamlPlugin is not a replacement for Python script-based tkinter development; it is an add-on/plugin designed to improve code readability by separating UI and logic.

## Requirements

To use TkinterYamlPlugin, you'll need the following:

- **PyYAML**: The PyYAML library for YAML file handling.
- **Tkinter**: The tkinter library for creating graphical user interfaces in Python.
- **TkinterYamlPlugin**: TkinterYamlPlugin itself.

## How to Use

Using TkinterYamlPlugin is straightforward:

1. Create a separate `.yaml` file based on the YAML rules and the TkinterYamlPlugin.
2. Import the TkinterYamlPlugin into your codebase.
3. Use the provided methods to load and configure your tkinter UI.

### TkinterYamlPlugin Class

TkinterYamlPlugin offers the following methods:

- `config()`: Override this config file if you need specific configurations.
- `load_file(filename)`: Load a YAML file by specifying its filename.
- `run()`: Automatically load the YAML file and run the mainloop for your tkinter application.

Here's an example of how to use TkinterYamlPlugin:

```python
import TkinterYamlPlugin

class TestApp(TkinterYalmPlugin):
    YAMLFILE = ["ui.yaml"]

    def build(self):
        return MyApp() # This is the entry point of the application.

# Alternative: You can handle all the tasks by yourself as well.

import tkinter as tk
from TkinterYamlPlugin import load_yaml

root = tk.Tk()

load_yaml("name_of_the_yaml_file")

# Your Logic:

root.mainloop()

if __name__ == "__main__":
    TestApp().run()
```

## Contribution

Contributions to this project are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Happy coding!
