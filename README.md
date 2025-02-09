Inventory Management Script

Overview:

This Python script processes inventory data from an Excel file (inventory.xlsx) using openpyxl. It calculates:

The number of products per supplier.

The total inventory value per supplier.

Products with inventory less than 10 units.

Updates and saves the Excel file with total inventory values.



Requirements:

Python 3.x
openpyxl library



Installation:
pip install openpyxl




How It Works:

Load Data: Opens inventory.xlsx and reads Sheet1.

Process Inventory:

Counts products per supplier.

Computes total inventory value per supplier.

Identifies low-stock products.

Updates total inventory value in the sheet.

Save Results: Creates inventory_with_total_value.xlsx.

Display Summary: Prints processed data.


Usage:

Run the script:

python inventory_script.py

Ensure inventory.xlsx is in the same directory.


Output:

A new Excel file with updated inventory values.

Printed summary of:

Products per supplier.

Total inventory value per supplier.

Low-stock products.

Future Improvements

Add error handling.

Optimize performance using pandas.

Implement logging for better tracking.


License:

MIT License.


