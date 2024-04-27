# Blockchain Transaction Viewer

This Python program implements a Blockchain Transaction Viewer using the Tkinter GUI toolkit. It reads transaction data from a CSV file, creates blocks for each transaction, and allows users to view all transactions or search for specific transaction details.

## Features

- **Show Transactions**: Display all transactions stored in the blockchain.
- **Find Transaction**: Search for a specific transaction by entering its transaction number.

## Requirements

- Python 3.x
- pandas
- hashlib
- time
- json
- tkinter

## Usage

1. **Install Dependencies**: Install the required Python dependencies using pip.

    ```bash
    pip install pandas
    pip install tk
    ```

2. **Run the Program**: Run the Python script `blockchain_transaction_viewer.py`.

    ```bash
    python blockchain_transaction_viewer.py
    ```

3. **Interact with the GUI**: Use the GUI to show all transactions or find specific transaction details by entering the transaction number.

## CSV Data Format

The CSV file should contain transaction data with the following columns:

- TransactionNo
- Date
- ProductNo
- ProductName
- Price
- Quantity
- CustomerNo
- Country

## Example

```python
# Sample code demonstrating how to use the Blockchain Transaction Viewer

# Run the Python script
# Follow the on-screen instructions to interact with the GUI
