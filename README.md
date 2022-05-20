# Practicing_association_rules
Exploring association rule mining using a Python library mlxtend


dataset = [
['Potatoes', 'Eggs', 'Bread', 'Beer', 'Milk', 'Cheese'],
['Eggs', 'Bread', 'Milk', 'Beans', 'Mustard', 'Cheese', 'Peanut Butter', 'Turkey'],
['Beans', 'Turkey', 'Eggs', 'Cheese'],
['Bread', 'Romaine', 'Apples', 'Ice Cream', 'Peanut Butter', 'Soup'],
['Potatoes', 'Bread', 'Romaine', 'Beer', 'Milk', 'Apples', 'Cheese', 'Peanut Butter', 'Soup'],
['Bread', 'Beer', 'Beans', 'Milk', 'Cheese', 'Ice Cream', 'Mustard', 'Turkey'],
['Eggs', 'Strawberries', 'Bread', 'Romaine', 'Beer', 'Milk', 'Carrots', 'Almonds', 'Turkey', 'Jelly'],
['Milk', 'Apples', 'Turkey', 'Beer'],
['Potatoes', 'Candy', 'Beer', 'Carrots', 'Almonds', 'Cheese', 'Peanut Butter'],
['Eggs', 'Bread', 'Milk', 'Soup', 'Ice Cream', 'Strawberries'],
['Potatoes', 'Eggs', 'Bread', 'Beer', 'Milk', 'Peanut Butter', 'Soup', 'Jelly'],
['Eggs', 'Potatoes', 'Bread', 'Romaine', 'Beer', 'Milk', 'Beans', 'Cheese', 'Ice Cream'],
['Eggs', 'Potatoes', 'Bread', 'Beans', 'Apples', 'Cheese', 'Candy'],
['Potatoes', 'Eggs', 'Strawberries', 'Bread', 'Milk', 'Cheese', 'Candy', 'Soup'],
['Eggs', 'Potatoes', 'Bread', 'Beer', 'Milk', 'Carrots', 'Cheese', 'Turkey'],
['Eggs', 'Beer', 'Beans', 'Carrots', 'Apples', 'Candy', 'Soup'],
['Potatoes', 'Eggs', 'Soup', 'Milk', 'Cheese', 'Candy', 'Turkey'],
['Eggs', 'Bread', 'Milk', 'Carrots', 'Candy'],
['Eggs', 'Bread', 'Beer', 'Milk', 'Carrots', 'Cheese', 'Candy', 'Turkey', 'Peanut Butter'],
['Potatoes', 'Beer', 'Beans', 'Cheese', 'Strawberries'],
['Eggs', 'Bread', 'Romaine', 'Beer', 'Milk', 'Noodles', 'Apples', 'Almonds', 'Turkey'],
['Potatoes', 'Bread', 'Milk', 'Mustard', 'Cheese', 'Peanut Butter', 'Soup', 'Turkey', 'Jelly'],
['Potatoes', 'Bread', 'Romaine', 'Beer', 'Soup', 'Milk', 'Peanut Butter', 'Turkey'],
['Strawberries', 'Carrots', 'Apples', 'Cheese', 'Ice Cream', 'Soup', 'Turkey'],
['Eggs', 'Bread', 'Milk', 'Carrots', 'Cheese', 'Peanut Butter', 'Jelly'],
['Eggs', 'Bread', 'Beer', 'Milk', 'Cheese', 'Candy', 'Soup', 'Peanut Butter', 'Turkey'],
['Romaine', 'Beer', 'Soup', 'Cheese', 'Peanut Butter', 'Turkey'],
['Bread', 'Romaine', 'Milk', 'Cheese', 'Candy', 'Strawberries', 'Turkey'],
['Bread', 'Beer', 'Milk', 'Cheese', 'Ice Cream', 'Soup', 'Jelly'],
['Eggs', 'Bread', 'Beer', 'Milk', 'Carrots', 'Cheese', 'Candy', 'Turkey']
]
