# map_IP_address_to_range
Map a list of IP addresses to a subnet/IP range.
Input expected - List of IPs or ranges separated by commas in a text file. E.g. 10.0.0.1, 10.0.0.0/24, 10.0.0.0-10.0.0.255

Steps to run the 'Map_IP-Address_To_Range.xlsm' -->
1. Copy the input text i.e. IPs or ranges separated by commas to column 'Z' of the excel file.
2. The IPs needed to be mapped to IPs/ranges are to be entered in column 'E'.
3. Now, use 'Text to Columns' ('Data' -> 'Text to Columns') feature of excel and apply on the IPs/ranges in column 'Z'.
4. Click on 'Run' button.
5. Output will be in column 'F'.
6. To clear the programmatic data, use 'Clear' button.

Note - Ensure the following settings are in place before running the macro:
1.  Select the radio button for
File -> More -> Options -> Trust Center -> Trust Center Settings -> Macro Settings  Enable VBA macros (not recommended; potentially dangerous code can run)
2.	Check the box for ‘Trust access to the VBA project object model’
3.	Enable ‘Developer’ option
File -> More -> Options -> Customize Ribbon -> (Customize the Ribbon) Main Tabs  Check the box for ‘Developer’
4.	Press ‘ALT+F11’ -> Tools -> References -> Check the box for ‘Microsoft Scripting Runtime’ 
