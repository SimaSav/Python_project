import time
import random
import string

def mystring(lenth):
        all_symbols=string.ascii_uppercase+string.ascii_lowercase
        result=''.join(random.choice(all_symbols) for _ in range (len>
        #print(result)
        return result

n=10000

my_list=[mystring(5) for result  in range(n)]
print(my_list)

def swap(my_list, a, b):
    temp = my_list[a]
    my_list[a] = my_list[b]
    my_list[b] = temp

#tets=[5,4,3,2,1]
#print(f"{tets} origin")
#n=5
def bubble_sort(my_list):
        for i in range(0,n-1):
                swapped=False
#               print(f"{i} - i now")
                for j in range(0, n-1-i):
                        if my_list[j]>my_list[j+1]:
                                swap(my_list, j, j+1)
                                swapped=True
                if not swapped:
                        break
        print(my_list)
start = time.time()
bubble_sort(my_list)
print(end-start)
