# STRING-BUFFERS
class HelloWorld {
    public static void main(String[] args) {
        StringBuffer s1=new StringBuffer("object oriented");
        StringBuffer s2=new StringBuffer(" programming language");
        s1.setCharAt(6,'-');
        System.out.println("setChar: "+s1);
        s1.insert(15,s2);
        System.out.println("Insert: "+s1);
        s1.append(" Example is java");
        System.out.println("append: "+s1);
        System.out.println("setChar: "+s1.reverse());
        
    }
}
