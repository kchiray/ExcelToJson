# ExcelToJson
Class that allows user to convert A SINGLE .xlsx document to Json

# Steps:
1) Download Spire.Xls

# Functions
Excel To Csv
-Converts Excel (.xlsx) to Csv document

Csv To Json
-Converts CSV doc to Json

Delete Files
-Deletes file where excel is temporarily stored

Download
-Download a CSV version of the uploaded excel document

Example Usage
var excelPath = "home/desktop" -> directory where excel document is temporarily stored stored;
                ExcelToJson.SaveExcelSheet(fileBase, excelPath); -> saves excel sheet
                return ExcelToJson.ExcelToCsv(fileBase, excelPath); -> returns json
