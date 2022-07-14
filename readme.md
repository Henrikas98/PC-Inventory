# Inventory Integration into PC Dashboard

## Why its Needed?

Along with Present Connection management team and myself(IT administrator/developer) we felt that there should be a way to control equipment flow through employees, which should help to represent how inventory is handled within a company. 

## How it Going to Work?

This project will be implemented into already existing Present Connection dashboard as subsection. It will be represented in the sidebar by the name Inventory (may be changed during development process). After clicking this button user will be taken into separate page where he will be able to monitor table of existing equipment. In the same page user will see several subsections (Computers, Monitors, Keyboards and Mouse, Headphones, Additional Assets) - each one of them will act as separate page where table of existing equipment will be represent and user will have the ability to add, edit or delete equipment. When pressing item in the table pop-up window will apear and user will have the posibility to edit the record and choose a user which currently owns this piece of equipment. Besides that we will have to modify already existing user page where we have to display all the assets that user currently holds. Everything will done keeping with the already existing PC Dashboard design and the components. 

## Idea of Inventory Page

All the inventory subsection editing/creating tables will be represented by a separate page or pop-up window. It will be a simple table with input fields which will allow to place down these fields:
- Number of Inventory Unit (internal, shared within company)
- Model
- Purchase Date
- Price
- Comments
- Current Owner (this field selection will be mapped from existing "Employees" table)

## Technological Stack 

- React.js 	:heart:
- C# || .NET :vomiting_face:
- Database? :thinking:

## Database Mockup
![Database mockup](https://freeimage.host/i/wWhzV2)