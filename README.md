class HelloWorld {
    public static void main(String[] args) {
        int [] aN;
        aN = new int []{5,7,6,2,10};
        
        int s;
        int l;
        for(int i = 0; i<aN.length; i++){
            for (int j = 0; j<aN.length; j++){
        
                s = aN[i];
                l = aN[j];
                if(s>l){
                int temp = aN[i];
                aN[i] = aN[j];
                aN[j] = temp;
            }
        }
    }
    System.out.println(java.util.Arrays.toString(aN));
}
}
