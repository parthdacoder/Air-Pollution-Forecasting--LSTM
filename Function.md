# Series_to_supervised (data, n_in=1, n_out=1, dropna = True)

## Flow of function:

- Import Libraries
- Define Function to Convert Series to Supervised Learning Format:
  - Function definition and parameters
  - Determine number of variables
  - Convert data into DataFrame
  - Initialize lists for columns and column names
  - Create input sequence (t-n, ..., t-1)
  - Create output sequence (t, t+1, ..., t+n)
  - Concatenate all columns
  - Drop rows with NaN Values
- Load Dataset
- Encode Categorical Data
- Ensure all data is Float
- Normalize Features
- Frame as supervised learning
- Drop unwanted columns
