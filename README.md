# GTrends Energy Project

## 📌 Descrição
This project analyzes search terms from Google Trends related to energy and the Brazilian energy sector. It processes JSON files extracted from the platform and transforms them into structured DataFrames, ensuring that the data is correctly formatted for analysis.

The project's focus is to enable the extraction and standardization of search trend information, allowing for insights into studies and reports in the energy sector.

## 🛠 Features
### 🔹 Data Extract
- Reads JSON files exported from Google Trends.
- Validates the data structure to ensure it contains relevant information.
- Confirms whether the data structure includes at least 12 months of records.

### 🔹 Processing and Transformation
- Organizes extracted values into Pandas DataFrames.
- Removes inconsistencies and standardizes data.
- Stores structured data for future analysis.

### 🔹 Storage
- Saves the generated DataFrames in the ./DataFrames/ folder.
- Ensures that files are not unintentionally overwritten.
- Automatically creates necessary directories if they do not exist.

## 🚀 Technologies Used
- **Python 3**
- **Pandas** for data manipulation and analysis.
- **OS** for directory and file management.
- **JSON** for reading and handling extracted data.
- **Datetime** for date handling.
- **RE (Regex)** for string processing and data standardization.

## ▶️ How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/nome-do-projeto.git

2. Install the required dependencies:
   ```sh
   git clone https://github.com/your-username/nome-do-projeto.git

3. Run the main script to process the data:
   ```sh
   git clone https://github.com/Victorlima1488/GTrends-Energy-Project.git