![](https://shonharsh.github.io/curriculum-vitae/Images/Banner-UiPath-01.png)

# S06P01 Get & Sort Data

This project is my solution in **Windows Legacy (Deprecated), C#** to the **Get & Sort Data** practice found in section 06 practice 01 of the UiPath - RPA Developer Foundation course.

### Getting Started

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output panel.

### Practice Requirements

###### **Practice 1 - Get and Sort Data**

Create a workflow that generates 10 fake names along with their details and then sorts them in an excel file that will be organized in 5 columns namely: Name, Phone, Birth-date, Email-Address and City, State, Zip. After sorting all the details, the workflow should continue to save the excel file in a specified folder.

**Notes:**

- Use the [www.fakepersongenerator.com](https://www.fakepersongenerator.com/) site to generate the 10 fake names along with their details.
- All selectors must not contain idx attributes.
- All of the activities starting with the first record generation to the last activity which is saving the excel file in a specific folder should be processed in one workflow execution.

### Details

**Course:** UiPath - RPA Developer Foundation

**Section:** 06 Selectors

**Practice:** 01 Get & Sort Data

**Project Format:** Windows Legacy (Deprecated), C#

**GitHub:** https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-WindowsLegacy

### Sample Output

```sh
05/07/2024 14:55:43 => [Debug] Debug started for file: Main
05/07/2024 14:55:44 => [Info] RPADev-S06P01-GetAndSortData-WindowsLegacy execution started
05/07/2024 14:55:54 => [Debug] Audit: Using Web App. Browser: Chrome URL: https://www.fakepersongenerator.com/
05/07/2024 14:58:04 => [Debug] The file has been written: N:\Cloud\Dropbox\Code\Robotic Process Automation\UiPath\UiPath - Projects\RPADev-S05P05-DataScraping-WindowsLegacy\Data\Output\RPADev-S05P05-DataScraping.csv
05/07/2024 14:58:04 => [Info] RPADev-S06P01-GetAndSortData-WindowsLegacy execution ended in: 00:02:20
```

### Architecture Requirements

A standard UiPath, Studio to Orchestrator cloud setup is the base of operation.  It is easy to setup and free.
1. An Orchestrator connection - Visit https://cloud.uipath.com/ and authenticate or sign up.
2. [UiPath Studio](https://www.uipath.com/product/studio) is used to run the robot.  Note that Studio Web can be used directly in Orchestrator but I recommend installing the Studio IDE application.

[![UiPath Setup Guide](https://shonharsh.github.io/curriculum-vitae/Images/Title-UiPath-Setup-Guide.png)](https://github.com/ShonHarsh/UiPath-SetupGuide)

### Git Notes

Clone the project to develop or change it.

```sh
git clone https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-WindowsLegacy
```

### Links
- [UiPath Automation Platform](https://www.uipath.com/)
- [UiPath Studio](https://www.uipath.com/product/studio)- [Pulsar](https://pulsar-edit.dev/) (Atom Successor) - Used for all my README.md files
- [Shon Harsh Website 127.0.0.1](https://shonharsh.github.io/curriculum-vitae/index.html)
- [This.GitHub](https://github.com/shonharsh)
- [LinkedIn](https://www.linkedin.com/in/shonharsh/)

### RPS Developer Foundation Sections

1. Get Started With RPA Development

2. Variables, Data Types And Control Flow In Studio

   P01 RPADev-S02P01-ForEachIfStatement [[C#](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement)] [[VB](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement-WindowsLegacy)]

   P02 RPADev-S02P02-GenericValue [[C#](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue)] [[VB](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue-WindowsLegacy)]

   P03 RPADev-S02P03-Switch [[C#](https://github.com/ShonHarsh/RPADev-S02P03-Switch)] [[VB](https://github.com/ShonHarsh/RPADev-S02P03-Switch-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P03-Switch-WindowsLegacy)]

3. Data Manipulation In Studio

   P01 RPADev-S03P01-Lists [[C#](https://github.com/ShonHarsh/RPADev-S03P01-Lists)] [[VB](https://github.com/ShonHarsh/RPADev-S03P01-Lists-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P01-Lists-WindowsLegacy)]

   P02 RPADev-S03P03-Dictionaries-Integers [[C#](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers)] [[VB](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers-WindowsLegacy)]

   P03 RPADev-S03P04-Dictionaries-Doubles [[C#](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles)] [[VB](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles-WindowsLegacy)]

   P04 RPADev-S03P05-InputValidation [[C#](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation)] [[VB](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation-WindowsLegacy)]

   P05 RPADev-S03P06-ReplacingPlaceholders [[C#](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders)] [[VB](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders-WindowsLegacy)]

   P06 RPADev-S03P07-ExtractEmailAddress [[C#](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress)] [[VB](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress-WindowsLegacy)]

   P07 RPADev-S03P08-ExtractEmailAddressRegEx [[C#](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx)] [[VB](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx-WindowsLegacy)]

4. Excel And Data Tables With Studio

   P01 RPADev-S04P01-CalculatingSums [[C#](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums)] [[VB](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums-WindowsLegacy)]

   P02 RPADev-S04P02-CalculatingLossInvoices [[C#](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices)] [[VB](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices-WindowsLegacy)]

   P03 RPADev-S04P03-CalculatingPercentagesOfExpenses [[C#](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses)] [[VB](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses-WindowsLegacy)]

5. UI Automation With Studio

   P01 RPADev-S05P01-PasswordGenerator [[C#](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator)] [[VB](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator-WindowsLegacy)]

   P02 RPADev-S05P02-TheRPAChallenge [[C#](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge)] [[VB](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge-WindowsLegacy)]

   P03 RPADev-S05P03-InputActions [[C#](https://github.com/ShonHarsh/RPADev-S05P03-InputActions)] [[VB](https://github.com/ShonHarsh/RPADev-S05P03-InputActions-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P03-InputActions-WindowsLegacy)]

   P04 RPADev-S05P04-OutputActions [[C#](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions)] [[VB](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions-WindowsLegacy)]

   P05 RPADev-S05P05-DataScraping [[C#](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping)] [[VB](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping-WindowsLegacy)]

6. Selectors In Studio

   P01 RPADev-S06P01-GetAndSortData [[C#](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData)] [[VB](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-WindowsLegacy)]

   P02 RPADev-S06P02-SetData [[C#](https://github.com/ShonHarsh/RPADev-S06P02-SetData)] [[VB](https://github.com/ShonHarsh/RPADev-S06P02-SetData-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P02-SetData-WindowsLegacy)]

   P03 RPADev-S06P03-Highlight-TypeItems [[C#](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems)] [[VB](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems-WindowsLegacy)]

7. Project Organization In Studio

   P02 RPADev-S07P02-StateMachines [[C#](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines)] [[VB](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-WindowsLegacy)]

   P03 RPADev-S07P03-FixMyWorkflow [[C#](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow)] [[VB](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow-WindowsLegacy)]

   P04 RPADev-S07P04-Libraries [[C#](https://github.com/ShonHarsh/RPADev-S07P04-Libraries)] [[VB](https://github.com/ShonHarsh/RPADev-S07P04-Libraries-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S07P04-Libraries-WindowsLegacy)]

8. Error And Exception Handling In Studio

9. Debugging In Studio

10. PDF Automation In Studio

11. Email Automation With Studio

12. Orchestrator For RPA Developers

13. Robotic Enterprise Framework Overview
