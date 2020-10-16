# Datatables with dynamic columns

A solution to add dynamic headers to datatables jQuery plugin.
This public repository will help to post solutions and code-snippets we find useful, please feel free to fork and add your own commentaries and examples.
Resume:

  - dynamic-headers.html  loads json from data/data.json 
    The idea is that in the JSON we define the columns, adding a **name** additional attribute that defines the Title of the table header
    Any other render or transformation applied to the column should be defined in the Javascript code (see example)

## Test notes:

datatables js and css is included for demo purposes. Please download latest version of datatables here:
[https://datatables.net/download](https://datatables.net/download)

## Exceptions

Using this dynamic generation of Columns won't play well with:

     "serverSide": true
     
 Since we are “fabricating” the table ourselves. Other than that so far everything else works just as a normal dataTable.
 
### Thanks to 

Allan from Datatables for creating such an awesome data visualization plugin. Using if for more than 3 years and counting!
Diego for his help on building a simple, yet effective logic.
[SkyGate GmbH](https://www.skygate.de) for giving me the time and support to do this and share it in an open repository

### Sponsoring

If you like this solution please consider becoming a sponsor where you can donate as little as 2 u$ per month. Just click on:
**❤ Sponsor**  on the top right

♢ For cryptocurrency users is also possible to help this project transferring Ethereum:

    0x65B7EF685E5B493603740310A84268c6D59f58B5

We are thankful for the support and contributions so far!
