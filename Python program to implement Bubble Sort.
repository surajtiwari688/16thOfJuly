import sys

def bubble_sort(arr):
    # This function will sort the array in non-decreasing order. 
    n = len(arr)
    #Traverse through all the array elements
    for i in range(n):
        # The inner loop will run for n-i-1 times as the
        # last i elements are already in place.
        for j in range(0, n-i-1):
        # Swap if the present element is greater than the
        # next element.
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp 
    return arr

# main code
if __name__=='__main__':

    arr = [2, 1, 9, 3, 7, 5, 6, 4, 8, 0]
    print("Sorted array: ")
    print(bubble_sort(arr))
