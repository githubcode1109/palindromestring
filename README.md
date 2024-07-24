# palindromestring
class Stringpalindrome {
    public static void main(String[] args) {
        String s="Hello world!";
        String rev=" ";
        int last=s.length()-1;
        for(int i=0;i<s.length();i++){
            rev=rev+s.charAt(last);
            last--;
        }
          if(rev.equals(s)){
              System.out.println("given string is palindrome");
          }
          else{
              System.out.println("given string is not palindrome");
          }
       
    }
}
