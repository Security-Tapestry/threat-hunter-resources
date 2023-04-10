---
title: CyberChef QuickStart Guide
categories: [Tutorials,CyberChef]
tags: [tutorial,guide,cyberchef,ossec,quickstart,tool,webapp]
render_with_liquid: false
---

## Introduction
CyberChef is a powerful and versatile tool for data analysis and manipulation, particularly in the field of cybersecurity. It was developed by GCHQ (the UK's Government Communications Headquarters) and released as open source software in 2016. The tool has a user-friendly interface and supports a wide range of data formats and operations, making it a popular choice for analysts and developers.

In this guide, we will provide an in-depth overview of CyberChef's features and capabilities, as well as some practical examples of how it can be used.

### Getting started with CyberChef
CyberChef can be accessed through a web browser, and no installation is required. To get started, simply navigate to the CyberChef App at [https://security-tapestry.github.io/CyberChef/](https://security-tapestry.github.io/CyberChef/) and you'll be greeted with a blank canvas to work with.

#### The CyberChef interface
The CyberChef interface is divided into several sections:

1. **Input area**: This is where you can paste or type in the data you want to work with. CyberChef supports a wide range of data formats, including text, hex, binary, and base64.
2. **Recipe area**: This is where you build your recipe, which is a series of operations that CyberChef will perform on your input data. Each operation is represented as a block that you can drag and drop onto the canvas.
3. **Output area**: This is where you can view the results of your recipe.

#### Building a recipe
To build a recipe, simply drag and drop operations from the "operations" panel on the right-hand side of the interface onto the canvas. Operations are grouped into categories, such as "encoding", "hashing", and "compression".

Each operation block has one or more input and output sockets. To connect two blocks, simply drag a line from an output socket to an input socket. You can also connect multiple blocks to a single input socket, or split the output of a block into multiple input sockets.

#### Running a recipe
Once you have built your recipe, you can run it by clicking the "bake" button at the bottom of the interface. CyberChef will perform each operation in turn, passing the output of one block as the input to the next. The results will be displayed in the output area.

### Common use cases for CyberChef
CyberChef is a highly versatile tool that can be used for a wide range of data analysis and manipulation tasks. Here are some common use cases:

#### Data format conversion
One of the most common use cases for CyberChef is to convert data between different formats. For example, you might have a file that is encoded in base64, but you need to convert it to ASCII text. To do this, you could use the "From Base64" and "To Text" operations in CyberChef.

#### Data decoding
Another common use case for CyberChef is to decode encoded data. For example, you might have a string of text that has been encoded in URL format, and you need to decode it to its original form. CyberChef supports a wide range of encoding formats, including URL encoding, HTML encoding, and Unicode.

#### Cryptographic operations
CyberChef also supports a wide range of cryptographic operations, such as hashing, encryption, and decryption. For example, you might have a file that has been encrypted with a symmetric encryption algorithm, and you need to decrypt it using a key. CyberChef supports a wide range of encryption algorithms, including AES, DES, and RSA.

#### File analysis
CyberChef can also be used for file analysis tasks, such as searching for specific patterns in a file or extracting specific data from a file. For example, you might have a large log file that contains a lot of irrelevant information, and you need to extract only the relevant data. You could use CyberChef to search for specific patterns in the file, such as IP addresses or error codes, and extract only the relevant data.

#### Forensic analysis
CyberChef can also be used for forensic analysis tasks, such as examining network traffic or examining system logs. For example, you might have captured network traffic that contains encrypted data, and you need to decrypt it to see what information is being transmitted. CyberChef can be used to decrypt the data and extract the relevant information.

### Advanced features of CyberChef
CyberChef has a number of advanced features that can be used to customize its behavior and extend its capabilities.

#### Custom operations
One of the most powerful features of CyberChef is the ability to create custom operations. If you need to perform a specific data manipulation task that is not supported by the built-in operations, you can create your own custom operation using JavaScript.

To create a custom operation, click the "options" button at the top of the operations panel and select "Custom operations". From there, you can create a new custom operation and define its input and output sockets and its behavior.

#### Regular expressions
CyberChef also supports regular expressions, which can be used to search for patterns in text data. Regular expressions are a powerful tool for text manipulation and can be used to extract specific data from a larger block of text.

To use regular expressions in CyberChef, you can use the "Regex" operation block. Simply enter your regular expression pattern and CyberChef will search for all matches in the input data.

#### Batch processing
CyberChef also supports batch processing, which can be used to perform the same operation on multiple files or blocks of data. To use batch processing, simply upload a list of files or blocks of data and build your recipe as usual. CyberChef will apply the recipe to each file or block of data in turn and generate separate output files.

## Functions

### Encoding and Decoding
CyberChef supports a wide range of encoding and decoding functions, including Base64, URL, HTML, and Unicode. Encoding and decoding functions are used to convert data between different formats, which is a common task in data analysis and manipulation.

For example, you might have a text file that is encoded in Base64 format, but you need to decode it to read the original text. In CyberChef, you can use the "From Base64" operation to decode the text and convert it back to its original format. Similarly, if you need to encode data in a specific format, you can use the "To Base64" or "To URL" operations.

### Hashing
Hashing is a cryptographic operation that is used to generate a fixed-length, unique representation of data. Hashing is commonly used in data security and integrity applications, such as verifying file integrity or password storage.

CyberChef supports a wide range of hashing functions, including MD5, SHA-1, SHA-256, and SHA-512. To use the hashing function in CyberChef, you can drag and drop the relevant operation block onto the canvas and connect it to the input data. The output of the hashing function is a fixed-length string of characters that represents the original input data.

### Encryption and Decryption
Encryption and decryption are cryptographic operations that are used to protect data from unauthorized access. Encryption transforms data into an unreadable format, while decryption transforms it back into its original format.

CyberChef supports a wide range of encryption and decryption functions, including AES, DES, and RSA. To use encryption or decryption in CyberChef, you need to provide a key or passphrase that is used to transform the data. CyberChef also supports asymmetric encryption, where different keys are used for encryption and decryption.

### Regular Expressions
Regular expressions are a powerful tool for text manipulation and searching. Regular expressions are used to search for patterns in text data and can be used to extract specific data from a larger block of text.

CyberChef supports regular expressions and provides a dedicated operation block for regular expressions. To use regular expressions in CyberChef, you can drag and drop the "Regex" operation block onto the canvas and provide the regular expression pattern. CyberChef will search for all matches in the input data and highlight them in the output.

### Compression and Decompression
Compression and decompression functions are used to reduce the size of data files by removing redundant or unnecessary data. This is useful when transferring or storing large files, as it reduces the amount of storage space required.

CyberChef supports a wide range of compression and decompression functions, including gzip, bzip2, and zip. To use compression or decompression in CyberChef, you can drag and drop the relevant operation block onto the canvas and connect it to the input data. The output of the compression function is a smaller, compressed file, while the output of the decompression function is a larger, uncompressed file.

### Batch Processing
Batch processing is a powerful feature in CyberChef that allows you to apply the same operation to multiple files or blocks of data. This is useful when processing large datasets or when automating data processing tasks.

To use batch processing in CyberChef, you need to upload a list of files or blocks of data and build your recipe as usual. CyberChef will apply the recipe to each file or block of data in turn and generate separate output files.

### Custom Operations
Custom operations are a powerful feature in CyberChef that allows you to create your own custom functions using JavaScript. This is useful when you need to perform a specific data manipulation task that is not supported by the built-in operations.

To create a custom operation in CyberChef, you can click the "options" button at the top of the operations panel and select "Custom operations". From there, you can create a new custom operation and define its input and output sockets and its behavior using JavaScript.

Custom operations in CyberChef can be used to extend its capabilities and make it more suitable for your specific use case. You can also share your custom operations with others, which can help to foster a community of users and contributors.

## Conclusion
In this guide, we have covered the basics of using CyberChef for data analysis and manipulation. CyberChef is a powerful and versatile tool that supports a wide range of data formats and operations, and it has a user-friendly interface that makes it easy to use.

Some of the most commonly used functions in CyberChef include encoding and decoding, hashing, encryption and decryption, regular expressions, compression and decompression, batch processing, and custom operations. By understanding these functions and how to use them, you can make the most of CyberChef and use it to solve a wide range of data manipulation tasks.

Whether you are a cybersecurity analyst, developer, or data scientist, CyberChef is a tool that can help you work more efficiently and effectively. By exploring its features and experimenting with different functions, you can unlock its full potential and make it a valuable part of your data analysis toolkit.