### Usage
To use the JSONMapper class, you need to follow these steps:

Import the JSONMapper class into your Python script.
Create an instance of the JSONMapper class, passing the path to the input JSON file as an argument.
Load the JSON data from the file using the load_json_data() method.
Filter the JSON data to select specific fields using the filter_json_data() method.


### Methods
__init__(self, json_file)
Constructor method for the JSONMapper class.

**Parameters:**
json_file (str): The path to the input JSON file.
load_json_data(self)
Load JSON data from the input file and store it in the data attribute.

**Raises:**
FileNotFoundError: If the input JSON file is not found.
json.JSONDecodeError: If there is an issue decoding the JSON data.
filter_json_data(self)
Filter the loaded JSON data and return a dictionary with selected fields.

**Returns:**

dict: A dictionary containing selected fields from the JSON data.
Raises:

ValueError: If the JSON data is not loaded using the load_json_data() method.
