//Question
//create an integer array a with n elements in 1 second you can increase the value of 1 element by 1. find the minimum time in seconds to make all elements of the array equal

//Observation :
//To minimize time may all elements equal to the maximum element in the array

//Approach :
//find the maximum element in the array
//for every element how much it needs to be increaces to reach the maximum
//sum all those differences


public class seconds {
    public static void main(String[] args) {

//        array input
        int[] array = {3,4,5,0,2};
        int largest = array[0];
        for(int i=0;i<array.length;i++){
            if(array[i]>largest){
                largest=array[i];
            }
        }
        int sum = 0;
        for(int i=0;i<array.length;i++){
            sum += largest-array[i];
        }
        System.out.println(sum);
    }
}
