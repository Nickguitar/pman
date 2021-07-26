# pman
Command line utilitary for the PHP manual

This is a simple script that helps you see quick information about PHP functions directly from command line.

It returns: 
1. The function's availability
2. The function's description
3. The function's definition
4. The function's parameters
5. The function's return value

### Usage

`$ ./pman function_name`

### Screenshots

![image](https://user-images.githubusercontent.com/3837916/126942931-3d9849d8-ff6a-4d12-8453-30c626bad2d3.png)

![image](https://user-images.githubusercontent.com/3837916/126942900-3a846ca2-4524-4861-8265-5a277b4bf203.png)




### Installation

1. Download the PHP documentation "many files" (https://www.php.net/distributions/manual/php_manual_en.tar.gz)
2. Unzip everything to some folder (e.g. `/opt/pman/`)
3. Change the path in `$manual_path` at line 4 to the path where you unzipped the files
4. Make pman executable with `chmod +x pman`

**Tip:** use `# mv pman /bin` to call it from anywhere

### Note
This is by far not the best code I could to, and I've made some quick fixes. I know the code isn't beaultiful.

I haven't tested with a lot of functions and the PHP manual has some inconsistences, so it's possible that there is some bug.

Oh, and since I made this to work with functions only, I deleted every html file that doesn't start with "function." on the folder at step 2
