//Given n array find count number of elements having at least 1 item greater than itself

//psuedocode
//1) iterate and get the max element of array
//2) iterate and count no of element that are not equal to max

public class technical_skill {
    public static void main(String[] args) {
        int[] array = {-3,2,5,4,7,8,6};
        int count = 0;
        int largest = array[0];
//        for(int i = 0;i<array.length;i++){
//            for(int j = 1;j<array.length;j++){
//                if(array[j]>array[i]){
//                    count++;
//                    break;
//                }
//            }
//        }
//        System.out.println(count);

        for(int i = 0;i<array.length;i++){
            if(array[i]>largest){
                largest = array[i];
            }
        }
        for(int i =0;i<array.length;i++){
            if(array[i]!=largest){
                count++;
            }
        }
        System.out.println(count);
    }
}
