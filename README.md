import java.lang.reflect.Array;
import java.util.ArrayList;
import java.util.HashMap;
import java.util.HashSet;
import java.util.List;
import java.util.Map;
import java.util.Scanner;
import java.util.Set;

public class MainDemo {
	public static  Map<Character,Integer> count(String s) {
		  char[] c=s.toCharArray();
	      HashMap<Character,Integer>hm=new HashMap<Character,Integer>();
	      
	      
	     for(Character x:c) {
	    	 if(hm.get(x)==null) {
	    		 hm.put(x, 1);
	    		 
	    	 }else {
	    		
	    		 hm.put(x, hm.get(x)+1);
	    	 }
	     }
	     return hm;
		
	}
	public static void main(String args[]) {
		 Map<Character,Integer>x=count("sreedhar");
       
     System.out.println(x);
        }}
    
	 

	
	

