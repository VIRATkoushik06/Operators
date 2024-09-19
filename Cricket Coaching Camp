'''
2) Dhoni once wished to join a a reputed Cricket Coaching Camp to be held at a place "X" kms away from his house. He told about this to his father and got his consent to use his friend's bike for the Camp. The Camp was to be held on all days of the month. His friend's bike provides a mileage of Y km/litre and the cost of petrol was Rs. Z. Dhoni's father now wanted to know the total amount that was needed by Dhoni to spend on his travel to the Camp. Help him find the same and assume number of days in a month as 30 days.
Input Format:
First line of the input is an integer "X" in kms that specifies the distance of the Camp from Dhoni's house.
Second line is an integer "Y" in km/litre that specifies the mileage of his friend's bike.
Third line is a float "Z" that specifies the cost of petrol in rupees.
Output Format:
Output should display a float that gives the total amount that is needed by Dhoni to spend on his travel in rupees. The float value is displayed correct to 2 decimal places.
Sample Input and Output 1:
75
55
63
2577.27
Sample Input and Output 2:
35
78
65.0
875.00
Note: Bold highlighted is the output
x=float(input())
y=float(input())
z=float(input())
a=(x*z*30)/y
print("%.2f"%a)
Ans:
'''
def calculate_travel_cost(distance, mileage, petrol_cost):
    # Total distance for 30 days
    total_distance = distance * 30
    # Total amount needed for travel
    total_cost = (total_distance * petrol_cost) / mileage
    return total_cost

# Main program
# Input values
distance = float(input("Enter distance to the camp (in kms): "))
mileage = float(input("Enter mileage of the bike (in km/litre): "))
petrol_cost = float(input("Enter cost of petrol (in Rs.): "))

# Calculate total travel cost
travel_cost = calculate_travel_cost(distance, mileage, petrol_cost)

# Output the result formatted to 2 decimal places
print(f"{travel_cost:.2f}")
