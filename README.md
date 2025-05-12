# Advanced Python: Large-Scale Sales Data Analysis Project

## Project Overview
This project demonstrates advanced Python techniques for efficiently processing and analyzing a large sales dataset containing 1 million transactions. The goal is to handle data too large for memory using optimized approaches while extracting key business insights.

## Key Features
- 🏗️ **Data Sampling**: 1% random sampling with memory-optimized data types
- ⚡ **Efficient File Formats**: CSV vs. Feather vs. Parquet vs. HDF5 performance comparison
- 🧩 **Chunk Processing**: Memory-friendly handling of large files
- 🗃️ **SQL Integration**: SQLite database for complex queries
- 📈 **Sales Analytics**: Key metrics calculation and filtering

## Technical Stack
- Python 3.8+
- Core Libraries:
  - Pandas (data manipulation)
  - NumPy (numerical operations)
  - PyArrow (Feather/Parquet support)
  - H5Py (HDF5 handling)
  - SQLite3 (database operations)

## Dataset Structure
Generated dataset (`sales_data.csv`) contains:
- 1 million transactions
- Columns: transaction_id, customer_id, product_id, quantity, price, transaction_date, region
