# 2023-Pycon-Polars

You should be able to run this directly from github.

Type period (.) to get into Codespaces

Open a terminal and install Polars:

    pip install polars pandas matplotlib

Launch the notebook:

    jupyter notebook

Open the notebook file and run a cell (cntrl-enter)    


Polars 

Uses Rust language with arrow 

- Arrow specifies which datatypes are being processed also allocates memeory based ont he datatype.

- There are no index in the pandas 
- Polars cannot scale ypto multiple machines like DASK and Pyspark. But it can handle the dataframes which are beyond the size of the Memory.
- There are 3 layers and upper layer is python and middle layer is rust and lower layer is pyarrow. 
- We used expressions when we are writing the rust code in the pythonn.
- Polars doesn't allow duplicate columns.
- It is also recommended to use the expressions.
- While perfroming the lazy operations one should use the pipe operations. WE define the sequence of the operations we are performing. 
