# Sizes-of-Primitive-Datatypes-in-Java
A small program which brings the size of primitive data types in bits and bytes.


public class SizesOfPriDataTypes {

	public static void main(String[] args) {
				
		int a=0;
		short b;
		char c='i';
		byte byt;
		long l;
		float f;
		double d;
		String s="Pakistan";
		s.length();
		Boolean bl=true;
		
		
		
		System.out.println("SHOWS THE DATA TYPE VALUE IN BITS");
		System.out.println("================================");
		System.out.println(Byte.SIZE);
		System.out.println(Short.SIZE);
		System.out.println(Integer.SIZE);
		System.out.println(Character.SIZE);
		System.out.println(Long.SIZE);
		System.out.println(Float.SIZE);
		System.out.println(Double.SIZE);
		System.out.println(String.valueOf(s));
		System.out.println(Boolean.toString(bl));
		
		System.out.println("\nSHOWS THE DATA TYPE VALUE IN BYTES");
		System.out.println("===================================");
		System.out.println(Byte.SIZE/8);
		System.out.println(Short.SIZE/8);
		System.out.println(Integer.SIZE/8);
		System.out.println(Character.SIZE/8);
		System.out.println(Long.SIZE/8);
		System.out.println(Float.SIZE/8);
		System.out.println(Double.SIZE/8);
		int j;
		for(j=0; j<=s.length()-1; j+=1){}
		System.out.println(String.valueOf(s)+" Number of characters in a string: "+j);
		System.out.println(Boolean.toString(bl));
		
		
	}

}
