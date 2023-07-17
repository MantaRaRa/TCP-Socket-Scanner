# TCP-Socket-Scanner
Using Python to create a Socket Connection.
Running these two scripts will help you determine if the Hosts and Ports are open and unprotected, I will be showing how you can use Windows Command line to run the Python scripts:

If your Successful the Result will return a 0, 
If not it will retun an error Socket code. 

You'll have to look up the Error Socket code to see what's Blocking you:

'https://www.ibm.com/docs/en/db2/11.1?topic=message-tcpip-errors'

## How to use these scripts on a Windows Machine with CMD

1: Download Python if you havent yet, these files were created with the current released --v 3.11

1: Clone Repo

2: Windows key + R, Type CMD in the pop up window

3: Change the working directory to the folder you Cloned to:

'cd C:\Users\...\...\...\...\TCP-Socket-Scanner'

4: Once there type:

'python create_connection.py'

### You will have to play around with the host and port on lines 5 and 6 of the file till you are able to Break Through,

### Experiment at YOUR OWN RISK:
I will not be liable to you for any loss or damage, whether in contract, tort (including negligence), breach of statutory duty, or otherwise, even if foreseeable (including, without limitation, damage for loss of business or loss of profits) arising under or in connection with your use of or inability to use, my repos or your use of or reliance on any content displayed on them.
