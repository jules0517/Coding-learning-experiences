def check_ingredient_match(recipe, ingredients):
    numb_ingredients=0
    missing_ingredients=[]
    for item in range(0,len(recipe)):
        if recipe[item] not in ingredients:
            missing_ingredients.append(recipe[item])
        else:
            numb_ingredients+=1
    percentage=(numb_ingredients)/len(recipe)*100
    return percentage, missing_ingredients
