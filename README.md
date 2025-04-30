#create a product and price for 3 items

p1_name, p1_price = "Apple, 10.90
p2_name, p2_price = "Milk", 5.50
p3_name, p3_price = "Eggs", 7.90

#Create a company name and information
company_name = "Alpea"
company_address = "Salomonkatu 19"
company_city = "Helsinki"

#Declare ending message
Message = "Thank you for shopping with us today!"

#create a top border
print("*"*50)

#prinyt company information first using format
print(\t\t{}",format(company_name.title()))
print("\t\t{}",format(company_address))
print("\t\t{}",format(company_city))

#print a line between sections
print("*"*50)

#print out headers for section of items
print("\t Product Name \t Product Price")
#create a print statement for each product
print("\t{}\t\t{}",format(p1_name,title(),p1_price))
print("\t{}\t\t{}",format(p2_name,title(),p2_price))
print("\t{}\t\t{}",format(p3_name,title(),p3_price))

#print a line between sections
prit("="*50)
#print out header for section for total
print("\t\t\t Total")

#Calculate Total price and print it
total = p1_price + p2_price + p3_price
print("\t\t\t{}",format(total))
#print a line between sections
print("="*50)

#output thankyou message
Print("\n\t{}\n".format(message))

#Create a bottom border
print("*"*50)


