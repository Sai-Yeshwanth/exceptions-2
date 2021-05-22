class Do{
	public void findException(){
       int i=2;
       int j=0;
       try{
    	   int k=i/j;
       }
       catch(ArithmeticException ae)
       {
    	   System.out.println("Number can't be divided by zero " + ae);
       }
    }
}
class Jala {
	public static void main(String[] args){
		Do example = new Do();
        example.findException();
	}
}
