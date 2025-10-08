### **Basic iTunes API Request**

A simple Python project demonstrating how to interact with the **iTunes Search API** to retrieve data.

This notebook uses the `requests` library to fetch a list of songs by a specified artist (**Tame Impala** in the current example) and then processes the JSON response to display the song titles and their respective albums.

**Key Features:**
* **API Interaction:** Performs a basic HTTP GET request to a public API endpoint.
* **Parameterization:** Utilizes query parameters (`term`, `media`, `entity`, `limit`) to refine the search.
* **JSON Parsing:** Converts the API's JSON response into a usable Python dictionary.
* **Data Extraction:** Prints extracted song names and album titles from the results.

**Technologies Used:**
* **Python**
* **`requests` library**
* **iTunes Search API**
* **Jupyter Notebook**
This project serves as a foundational example for making and handling simple API requests in Python.
