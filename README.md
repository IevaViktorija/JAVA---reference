# JAVA---reference

```
public class Main {
    public static void main(String[] args) { //Main method
        int[] array = {1, 2, 3, 4, 5}; // 1. declare an array
        array = changeArray(array); // 2. change the content of the array
        printOutArray(array); // 3. print out the values of the array
    }

    public static int[] changeArray(int[] array){ // 2
        for(int i = 0; i < array.length; i++){ // 2.1. 
            array[i] = 0; // 2.2
        }// 2.3
        return array; //2.4
    }

    public static void printOutArray(int[] array){ // 3
        for(int i = 0; i < array.length; i++){ //3.1
            System.out.println(array[i]);// 3.2
        } //3.3
    }
}

// Reference type
```
