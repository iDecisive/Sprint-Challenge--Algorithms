#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - If I input 3 it will take three steps and if I input 6 it will take six steps. The result is a linear time.


b) ?????????????


c) O(n) - if I input 3 it'll run three times because of recursion and if I input 50 it'll run 50 times 

## Exercise II

assumes dropEgg function exists and returns if the egg breaks or not

def findFirstDangerouFloor(floors):
    dangerousFloors = []
    for floor in floors: #itterates through input once
        if dropEgg(floor) == 'Break':
            dangerousFloors.append(floor)
    if danerousFoors[0] == None:
        return None
    else:
        return min(dangerousFloors) #itterates through part of input
        
O(n*2) runtime complexity - Worse case senario; if all the floors are dangerous
O(n) - Simplified
