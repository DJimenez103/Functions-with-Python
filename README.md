# Functions-with-Python
Create algorithm that uses Python code to check whether it contains any IP addresses identified on the remove list. Then remove the IP addresses from the file containing the allow list.
<h2>Description</h2>
Project consists of using different functions in Python that will help us to:
<br />
- Open the file that contains the allow list
<br />
- Read the file contents
<br />
- Convert the string into a list
<br />
- Iterate through the remove list
<br />
- Remove IP addresses that are on the remove list
<br />
- Using the "print" function to display results
<br />
- Update the file with the revised list of IP addresses 
<br />
<br />
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 


<p align="center">

<br/>
In order to open the file that contains the allow list, the allow list needs to be assigned  to the variable import_file. We now want to read the file contents while storing it in the variable "ip_addresses". Since we opened the import file as "file" we apply this to our ".read" function we then assign this output to the variable ip_address to further build out algorithm.

<br />
<img src="https://imgur.com/ySx9Lnd.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The string then needs to be in a list format in order to view the list and to be able to remove IP addresses that are on the "remove list". After using the read method to read our file, we then print the ip_addresses using the ".split" method to convert the string into a list.

<br/>
<img src="https://imgur.com/6orRGku.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In order to iterate through the remove list, the remove list must be defined just as the allow list also needed to be defined. We then use a for loop. To start the for loop, we used the loop variable "element" first followed by in remove_list to show which list we are iterating through.

<br />
<img src="https://imgur.com/yTzExzT.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
To remove the IP addresses that are on the remove list, the ".remove" method must be applied. Using the header of our for loop, we continued the code adding the "if" method which starts the conditional statement. We then enter the loop variable we created "element" and state that if it there is an IP address "in" the remove list, then the ".remove" method would remove "element" from the IP address list.

<br />
<img src="https://imgur.com/DAgYw9X.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To update the file, we must first convert "ip_addresses" back to a string using the ".join" method. First, we use the variable "ip_addresses" and use "\n" as the first argument to separate the elements by placing them on a new line. The join method comes after followed by "ip_addresses". We then use a "with" loop in order to open the import as a writable file. Last step is to write the file using the newly updated "ip_addresses".
<br />
<img src="https://imgur.com/xQPGHOO.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
