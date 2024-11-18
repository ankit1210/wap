# wap

 Array Sorting :
int[] arr = {5, 6, 1, 8, 2, 9, 3};

        for(int i = 0; i < arr.length-1; i++) {
            if(arr[i] > arr[i+1]) {
            // Swap if i is greater than i+1
                int temp = arr[i];
                arr[i] = arr[i+1];
                arr[i+1] = temp;
            // Change pointer again to initial, -1    
                i = -1;
            }
        }
