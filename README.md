# Portfolio-UiPath-Stock-excel-update
takes stock ticker from spreadsheet, looks up prices in web site and updates spreadsheet

Opens StockQuotes.xlsx
Loops through StockQuotes
  Gets stock ticker from column A
  Puts ticker in proper field in web site and presses enter key to search
  Gets values from the web site for the stock
  Updates the spreadsheet columns with the values
 End loop
 Close spreadsheet
  
