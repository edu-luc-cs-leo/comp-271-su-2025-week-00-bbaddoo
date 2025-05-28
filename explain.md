Part 1: The first two lines(40-41) take elements from the beginning of the array and put them into a temporary array. This also does not include the smallest_index. Then. there is a second loop that is startinf right after the smallest_index in the array and goes until it is done. It then is out into a temporary array that is one less than the original position. 

This shifts it over to the left by one.

Part 2:

public class Realistic {

    /** Set up our test array. */
    static int[] arr = { 10, -5, 11, 2 };
    //new array with an extra space
    int[] hwArr = new int[arr.length + 1];

    public static void add(int value)
    //put all elements into a new array
    for (int 1 = 0; i < arr.length; i++) {
        hwArr[i] = arr[i];
    }
    //add the new value to the last position
    hwArr[hwArr.length - 1] = value;
     
     //update to show the new array
    arr = hwArr;

}