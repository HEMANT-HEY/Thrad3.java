# Thrad3.java
 //Threading....................
import java.lang.Thread;
class Ttread extends Thread{
    public void run(){
        try{
            for(int i=0; i<5; i++){
                System.out.println(i);
                sleep(1000);
            }
        }
            catch(Exception e){
                System.out.println("Somthing wrong");
            }
        
    }
}
public class Thread1 {
    public static void main(String[] args) {
        Ttread T1=new Ttread();
        T1.start();
        for(int i=0; i<5; i++){
            System.out.println("Hemant");
        }
    }
}
