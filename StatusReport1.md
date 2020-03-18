# Status Report 1
Team 1 - Brant, Sarah, Ryan C, Stephen, Parker, Matt M

### Data Description BLUF
_Describe the data that you have received -- provide a 1-slide BLUF perspective of what you have received_



### Network Data
1. How many months/weeks/days/hours/minutes worth of network data do you have? **4 days, 7 hours, 45 minutes and 55 seconds**
2. How many packets? **12,315,047** _Note: "killed" exception was thrown on 02-27-2020_1.4_
  ```
  def countpack():
      counter = 0
      for name in filenames:
          os.system("sudo tshark -r " + name + " > tempfile.txt")
          with open("tempfile.txt") as file:
              for line in file:
                  counter = counter + 1
      print(str(counter))
  ```
3. What times - beginning and ending?
  - Begins on Feb 28, 2020 05:16:18.989733000 EST
  - Ends on Mar 3, 2020 13:02:13.407194000 EST

### Forensic Image Analysis
1. How many different systems do you have forensic images for? **8**
2. Verify the hashes provided, or provide a hash of the image you received **See table**
3. What are those systems used for? **See table**
4. What user accounts exist on each system? **See table**
5. What other stuff were you provided? **A .zip of ShareDrive?**

System        | Purpose                         | User Accounts                                    | SHA256 Hash
------------- | ------------------------------- | ------------------------------------------------ | -------------
IT_2          | Network Analysis and Topologies | admin, Administrator, DouglasAdams, RoyTremmeman | AE7F452E833FE73CBF47FE02004AAEC2FE31D9EE1958D3774B557DC565E3D809
Mayor2_2      |                                 |                                                  | A2DF12A14DA8CC43736145FAEDAA56C91461F93BE2231BCE9DFB1AD9CD9196A7  
Mayor2_4      |                                 |                                                  |
Police1_1     |                                 |                                                  |
ShareDrive_1  | Means of sharing office data    |                                                  |
TaxOffice_1   |                                 |                                                  |
TaxOffice_2   |                                 |                                                  |
TaxOffice_4   |                                 |                                                  |

### Memory Forensics
1. Which systems do you have a memory capture for?
2. What operating systems are each system?
3. What times/days were the captures completed?

### Log Files
1. How many log entries do you have?
2. What are the date/time ranges of the logs?
3. Describe the types of log entries you have -- what systems generated the log entries?
4. Describe the log file aggregator, if you can
5. Identify any initial findings
6. Identify any preliminary Indicators of Compromise

### Questions and Concerns
1. Identify any questions you have for the client
2. Identify any concerns or issues that your team has