# Learning-PySpark
A Beginner's Guide to learning PySpark - The Python API for Apache Spark for Stream Analytics

## Installation Guide

- Step 1: Go to the Apache Spark Downloads Page at [here](https://spark.apache.org/downloads.html) and download the Spark latest version in form of zip file

![alt-text](https://raw.githubusercontent.com/vgaurav3011/Learning-PySpark/master/images/Spark-Home.png)

- Step 2: Extract the spark zipped file in the home directory (or you may use the tar command using the terminal)

![alt-text](https://raw.githubusercontent.com/vgaurav3011/Learning-PySpark/master/images/extract.png)

- Step 3: Go to the home directory where you extracted the PySpark Folder and copy the path of your PySpark Destination Folder

![alt-text](https://raw.githubusercontent.com/vgaurav3011/Learning-PySpark/master/images/path.png)

- Step 4: Open the hidden file .bashrc using the following command:

```console
sudo gedit ~/.bashrc
```

![alt-text](https://raw.githubusercontent.com/vgaurav3011/Learning-PySpark/master/images/bashrc.png)

- Step 5: Setting the PATH variables
  - Add the path variables with 'export' keyword as shown in the figure
  - We are setting the default IDE as jupyter notebook, feel free to use your own favourite IDE
  - Make sure that the path given to the Spark Folder extracted is correct
  - In this example, I have used the home directory as the destination of the extracted folder
  
 ![alt-text](https://raw.githubusercontent.com/vgaurav3011/Learning-PySpark/master/images/edit_bashrc.png)
 
 - Step 6: Save the bashrc file after adding the path variables in the text editor and finally execute the following command in the terminal to activate the changes made
 
 ```console
 $ source ~/.bashrc
 ```
 
 Hurray! You have successfully installed and configured PySpark in your system. To check if the installation was correct you can execute:
 
 ```console
 $ pyspark
 ```
 
 This should open the default IDE (Jupyter Notebook in case of the example)
 
Alternatively, you can also use the pip installation directly for pyspark in Python Packages
```console
$ pip3 install pyspark
```

To check the installation was correctly executed or not run:

```console
$ python3 -c "import pyspark"
```

If this executes correctly, then the installation was successfull. Note that you may use Python 2 as well instead of version 3.6.7!
