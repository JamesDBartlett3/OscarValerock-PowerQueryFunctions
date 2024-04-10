# Power Query Functions
## Introduction
This repository contains a collection of Power Query functions, the intention is to give the Power Query community the possibility of using tested and proved functions without having to write them from scratch. 

## History
### This M functions library stands on the shoulders of giants:
This repository was inspired by [Injae Park's YouTube video](https://www.youtube.com/watch?v=GXFxiEVAmfI) and [repository](https://github.com/PowerBIPark/PowerBI_MQueryTest) on how to version control M Code, his research and code is a corner stone of this project; also, specially useful were the references he included: 

- Imke Feldman's [post on expression evaluate](https://www.thebiccountant.com/2018/05/17/automatically-create-function-record-for-expression-evaluate-in-power-bi-and-power-query/) came particularly handy when dealing with documentation. 
- Kim Burgess' [repository, m-tools](https://github.com/acaprojects/m-tools/blob/master/M.pq) was very useful when defining the usage of the functions and the readme file.

## Usage
### Library installation and usage

This library is "imported" into Power Query by following this steps:

1. Open the file [M.pq](M.pq) and copy the code.
2. Open an advanced editor in Power Query and paste the code, rename the query to "M".
3. Use the functions as records on M. For example, PictureBinary, which is located in the General Folder, has as arguments one table and two numbers, can be invoked like: 

`M[General.PictureBinary](table, number, number)`

## Contributing
Contributions are welcome! If you have any new functions or improvements to existing ones, feel free to submit a pull request.

Please contribute in the folder category that best suits. If the folder does not exist, create it. 

The functions you create will only work if the all the Power Query native functions used are declared in the [M.pq](M.pq) file. You can run the  [M_Creator.py](M_Creator.py) Python script and it will locate all the functions via regex and rewrite a M.pq file. 

### Contributing guidelines
1. Make sure to add the corresponding credits on the code you use. Plagiarism will not be tolerated.
2. **Document your functions,** for this you can use the file  [M_FxDocTemplate.pq](https://github.com/OscarValerock/PowerQueryFunctions/blob/main/M_FxDocTemplate.pq "M_FxDocTemplate.pq")
3. Comment your code.
4. Have fun! 🎉

## License
This project is licensed under the [MIT License](LICENSE).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjY3OTEwNzAsMTMxNTgxODU0NiwxMTgyOT
gyOTg2LC01MzIwNjA0MywtMTY3NTQzNzY4OF19
-->