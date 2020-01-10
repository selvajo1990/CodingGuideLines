# AL Coding Guidelines - Followed in ATG

## Standard Code Modification - Multiline
**Syntax**: // Start TaskID - Date - Last 3 digit of employee id

**Example 1**: // Start #15 - 20/12/2019 - 005

**Example 2**: // Stop #15 - 20/12/2019 - 005

---

## Standard Code Modification - Singleline
**Syntax**: // TaskID - Date - Last 3 digit of employee id

**Example**: // #15 - 20/12/2019 - 005

---

## Variable Declaration
**Example**: 

**Global** 'Sales Header' --> SalesHeaderG, (declaration of same variable again should follow) SalesHeader2G

**Local**  'Sales Invoice Header' --> SalesInvoiceHeaderL

**Parameter** 'G/L Account' --> GLAccountP

**Return** 'Amount' --> AmountR

---

## Field Creation

Primary key field must be - 1 to 20 field no. for new table, other field should start from field no. 21

For Extension - field id must start with app.json object range 

All the table fields mush have caption property.

---

## Object Creation
Any new object creation should have the following file name format

**Example**:

Table           --> Tab.50102.VisaType.al

Table Extension --> Ext54106-Tab17.GLEntry.al

Page            --> Pag.54101.Levels.al

Page Extension  --> Ext54107-Pag101.GenJnlTemplate.al

Report          --> Rep.54101.SalaryComputation.al

Codeunit        --> Cod.54101.HumanResourceEvents.al

Query           --> Que.54101.SalaryComputationList.al

Xmlport         --> Xml.54101.EmployeeList.al

Note: no special character on naming

---
