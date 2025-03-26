# Relational_model

Relational Schema:
-
Hotel (**Hotel_id**, Hotel_name)
Type (**Type_id**, Type_name, **#Hotel_id**)
Category (**Category_id**, Category_name, Price, Beds_numbers)
Room (**Room_id**, Floor, **#Category_id**)
Employee (**Employee_id**, Employee_name, Employee_speciality, **#Hotel_id**)
Employee_Room (**#Employee_id**, **#Room_id**)
