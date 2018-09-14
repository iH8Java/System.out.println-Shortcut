# System.out.println-Shortcut
p.p() prints out foo in a new line.
p.p() takes multiple arguments and prints them out each in a new line in the order they appear in the method.
p.i() prints out in the same line.


Code for copy and paste below:

//i've decided that typing sout tab takes too much time
//p.p() is sout tab
//it can take multiple arguments and prints them each in a new line
//p.i() is System.out.print()



    public class p {
        public static void i (String a){
            System.out.print(a);
    }    
    
        public static void p (Object ... b){
            for (Object c: b)
                System.out.println(c);
        }
    }

