medicines = []
suppliers = []
sales = []
categories = []
orders = []

while True:
    print("\n========== MEDICAL STORE MANAGEMENT SYSTEM ==========")
    print("1. Medicines")
    print("2. Suppliers")
    print("3. Sales")
    print("4. Categories")
    print("5. Supplier Orders")
    print("6. Exit")

    choice = int(input("Enter your choice: "))

    if choice == 1:
        while True:
            print("\n========== MEDICINES ==========")
            print("1. View")
            print("2. Add")
            print("3. Back")

            option = int(input("Enter your choice: "))

            if option == 1:
                if len(medicines) == 0:
                    print("No medicines available.")
                else:
                    print("\nAVAILABLE MEDICINES")
                    for medicine in medicines:
                        print("Medicine ID:", medicine["id"])
                        print("Medicine Name:", medicine["name"])
                        print("Manufacturer:", medicine["manufacturer"])
                        print("Category:", medicine["category"])
                        print("Price:", medicine["price"])
                        print("Quantity:", medicine["quantity"])
                        print("Expiry Date:", medicine["expiry"])
                        print()

            elif option == 2:
                medicine_id = input("Enter medicine ID: ")
                name = input("Enter medicine name: ")
                manufacturer = input("Enter manufacturer: ")
                category = input("Enter category: ")
                price = float(input("Enter price: "))
                quantity = int(input("Enter quantity: "))
                expiry = input("Enter expiry date: ")

                medicine = {
                    "id": medicine_id,
                    "name": name,
                    "manufacturer": manufacturer,
                    "category": category,
                    "price": price,
                    "quantity": quantity,
                    "expiry": expiry
                }

                medicines.append(medicine)
                print("Medicine stored successfully.")

            elif option == 3:
                break

            else:
                print("Invalid choice.")

    elif choice == 2:
        while True:
            print("\n========== SUPPLIERS ==========")
            print("1. View")
            print("2. Add")
            print("3. Search")
            print("4. Update")
            print("5. Delete")
            print("6. Back")

            option = int(input("Enter your choice: "))

            if option == 1:
                if len(suppliers) == 0:
                    print("No suppliers available.")
                else:
                    for supplier in suppliers:
                        print("\nSupplier ID:", supplier["id"])
                        print("Name:", supplier["name"])
                        print("Phone:", supplier["phone"])
                        print("Email:", supplier["email"])

            elif option == 2:
                supplier_id = input("Enter supplier ID: ")
                name = input("Enter supplier name: ")
                phone = input("Enter phone number: ")
                email = input("Enter email: ")

                supplier = {
                    "id": supplier_id,
                    "name": name,
                    "phone": phone,
                    "email": email
                }

                suppliers.append(supplier)
                print("Supplier added successfully.")

            elif option == 3:
                supplier_id = input("Enter supplier ID to search: ")

                found = False

                for supplier in suppliers:
                    if supplier["id"] == supplier_id:
                        print("\nSupplier ID:", supplier["id"])
                        print("Name:", supplier["name"])
                        print("Phone:", supplier["phone"])
                        print("Email:", supplier["email"])
                        found = True

                if not found:
                    print("Supplier not found.")

            elif option == 4:
                supplier_id = input("Enter supplier ID to update: ")

                found = False

                for supplier in suppliers:
                    if supplier["id"] == supplier_id:
                        supplier["name"] = input("Enter new name: ")
                        supplier["phone"] = input("Enter new phone number: ")
                        supplier["email"] = input("Enter new email: ")
                        print("Supplier updated successfully.")
                        found = True

                if not found:
                    print("Supplier not found.")

            elif option == 5:
                supplier_id = input("Enter supplier ID to delete: ")

                found = False

                for supplier in suppliers:
                    if supplier["id"] == supplier_id:
                        suppliers.remove(supplier)
                        print("Supplier deleted successfully.")
                        found = True
                        break

                if not found:
                    print("Supplier not found.")

            elif option == 6:
                break

            else:
                print("Invalid choice.")

    elif choice == 3:
        while True:
            print("\n========== SALES ==========")
            print("1. View")
            print("2. Make Sale")
            print("3. Search")
            print("4. Back")

            option = int(input("Enter your choice: "))

            if option == 1:
                if len(sales) == 0:
                    print("No sales available.")
                else:
                    for sale in sales:
                        print("\nSale ID:", sale["id"])
                        print("Customer Name:", sale["customer"])
                        print("Medicine:", sale["medicine"])
                        print("Quantity:", sale["quantity"])
                        print("Total Price:", sale["total"])
                        print("Sale Date:", sale["date"])

            elif option == 2:
                sale_id = input("Enter sale ID: ")
                customer = input("Enter customer name: ")
                medicine = input("Enter medicine name: ")
                quantity = int(input("Enter quantity: "))
                total = float(input("Enter total price: "))
                date = input("Enter sale date: ")

                sale = {
                    "id": sale_id,
                    "customer": customer,
                    "medicine": medicine,
                    "quantity": quantity,
                    "total": total,
                    "date": date
                }

                sales.append(sale)
                print("Sale recorded successfully.")

            elif option == 3:
                sale_id = input("Enter sale ID to search: ")

                found = False

                for sale in sales:
                    if sale["id"] == sale_id:
                        print("\nSale ID:", sale["id"])
                        print("Customer Name:", sale["customer"])
                        print("Medicine:", sale["medicine"])
                        print("Quantity:", sale["quantity"])
                        print("Total Price:", sale["total"])
                        print("Sale Date:", sale["date"])
                        found = True

                if not found:
                    print("Sale not found.")

            elif option == 4:
                break

            else:
                print("Invalid choice.")

    elif choice == 4:
        while True:
            print("\n========== CATEGORIES ==========")
            print("1. View")
            print("2. Add")
            print("3. Delete")
            print("4. Back")

            option = int(input("Enter your choice: "))

            if option == 1:
                if len(categories) == 0:
                    print("No categories available.")
                else:
                    for category in categories:
                        print("Category ID:", category["id"])
                        print("Category Name:", category["name"])

            elif option == 2:
                category_id = input("Enter category ID: ")
                name = input("Enter category name: ")

                category = {
                    "id": category_id,
                    "name": name
                }

                categories.append(category)
                print("Category added successfully.")

            elif option == 3:
                category_id = input("Enter category ID to delete: ")

                found = False

                for category in categories:
                    if category["id"] == category_id:
                        categories.remove(category)
                        print("Category deleted successfully.")
                        found = True
                        break

                if not found:
                    print("Category not found.")

            elif option == 4:
                break

            else:
                print("Invalid choice.")

    elif choice == 5:
        while True:
            print("\n========== SUPPLIER ORDERS ==========")
            print("1. View")
            print("2. Create")
            print("3. Search")
            print("4. Back")

            option = int(input("Enter your choice: "))

            if option == 1:
                if len(orders) == 0:
                    print("No supplier orders available.")
                else:
                    for order in orders:
                        print("\nOrder ID:", order["id"])
                        print("Supplier ID:", order["supplier"])
                        print("Order Date:", order["date"])
                        print("Total Cost:", order["cost"])

            elif option == 2:
                order_id = input("Enter order ID: ")
                supplier_id = input("Enter supplier ID: ")
                date = input("Enter order date: ")
                cost = float(input("Enter total cost: "))

                order = {
                    "id": order_id,
                    "supplier": supplier_id,
                    "date": date,
                    "cost": cost
                }

                orders.append(order)
                print("Supplier order created successfully.")

            elif option == 3:
                order_id = input("Enter order ID to search: ")

                found = False

                for order in orders:
                    if order["id"] == order_id:
                        print("\nOrder ID:", order["id"])
                        print("Supplier ID:", order["supplier"])
                        print("Order Date:", order["date"])
                        print("Total Cost:", order["cost"])
                        found = True

                if not found:
                    print("Order not found.")
            elif option == 4:
                break
            else:
                print("Invalid choice.")
    elif choice == 6:
        print("Thank you for using the Medical Store Management System.")
        break
    else:
        print("Invalid choice.")
