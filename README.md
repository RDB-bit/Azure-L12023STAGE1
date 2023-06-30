## Azure-L12023STAGE1---azure-blob-SDK-for-python

This repository contains examples of working with Azure Blob Storage using Python. The examples demonstrate various operations such as creating containers, uploading and downloading files, listing blobs, and more.

## Prerequisites

1. An Azure account with an active subscription. 
2. A Batch account with a linked Azure Storage account.
3. A Data Factory instance. 
4. Batch Explorer downloaded and installed.
5. Storage Explorer downloaded and installed
    **not necessary 
6. Python 3.7 or above, with the azure-storage-blob package installed by using pip.
    **When using Batch EXplorer gives option to set up Batch pool fro 'Data Science' projects that come with python and packages for data science
    **I did not see that option using Azure portal alone
7. Prepare requirements.txt file (most packages are not required with Data Science batch pool but I did it as an exercise)
    1. pip install azure-mgmt-storage
    2. pip install azure-storage-blob
8. Prepare json file with parameters to use in python script like connection string etc
    **You can also use ADF pipeline Parameter list OR Batch Process Extended Properties


## Getting Started

1. Clone the repository:

   git clone https://github.com/RDB-bit/Azure-L12023STAGE1---azure-blob-SDK-for-python.git

2. Install the required dependencies:

    vs code or jupyter notebook
    cd "to/your/environment/"
    pip install -r requirements.txt

3. Configure the parameters:

    Create a JSON file named config.json in the root directory.
    Add your Azure Blob Storage connection string and other required parameters in the JSON file. Example:

    {
        "connection_string": "your-connection-string",
        "storage_account_name": "your-storage-account-name",
        ...
    }

4. Run the examples using the jupyter notebook


## Examples 

The repository provides the following examples:

1. make container: creates a new container in Azure Blob Storage
2. list containers: list containers in the resource
3. copy containers : copy blobs from a container to another
4. rename containers : rename a container to a new name
5. delete container : deletes a specified container
6. upload_blobs: uploads a blob to a specified container
7. delete blob : deletes blob in a container

Feel free to explore each example for detailed usage and functionality.


## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

