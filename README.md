# Exercise-12
Bookshelf

/*
*Jonathan Saldivar
*ITSE 1302-011
*Exercise 12
*Creating a book with all the information
*/

import java.util.Scanner;

public class BookShelf {

   public static void main(String [] strArgs){

      public class Book {
      private String strTitle = "";
      private String strAuthor = "";
      private String strPublisher = "";
      private int intCopyrightDate = "";

      Scanner objInput = new Scanner(System.in);
    
      public Book(){
      inputTitle();
      inputAuthor();
      inputPublisher();
      inputCopyrightDate();
 }
    
    public String getStrTitle() {
    return strTitle;
 }
    
    public void setStrTitle(String pstrTitle){
    strTitle =  pstrTitle;
    }
    
    public String getStrAuthor(){
    return strAuthor;
    }
    
    public void setStrAuthor(String pstrAuthor){
    strAuthor = pstrAuthor;
    }
    
    public String getStrPublisher(){
    return strPublisher;
    }
    
    public void setStrPublisher(String pstrPublisher){
    strPublisher = pstrPublisher;
    }
    
    public int getIntCopyrightDate(){
    return intCopyrightDate;
    }
    
    public void setIntCopyrightDate(int pintCopyrightDate){
    intCopyrightDate = pintCopyrightDate;
    }
    
    public void inputTitle(){
    System.out.println("Title: ");
    setStrTitle(objInput.next().toUpperCase());
    }
    
    public void inputAuthor(){
    System.out.print("Author: ");
    setStrAuthor(objInput.next().toUpperCase());
    }
    
    public void inputPublisher(){
    System.out.print("Publisher: ");
    setStrPublisher(objInput.next().toUpperCase());
    }
    
    public void inputCopyrightDate() {
    System.out.print("Copyright Date: ");
    setIntCopyrightDate(objInput.nextInt());
    }
    
    public String toString(){
    return
    "         Title: " + this.getStrTitle();
    "        Author: " + this.getStrAuthor();
    "     Publisher: " + this.getStrPublisher();
    "Copyright Date: " + this.getIntCopyrightDate();
    
    }
}
    
   public String getBookStats(){
   return
   "         Title: " + this.getStrTitle();
   "        Author: " + this.getStrAuthor();
   "     Publisher: " + this.getStrPublisher();
   "Copyright Date: " + this.getIntCopyrightDate();
}
    
   public void setBookStats(String pstrTitle, String pstrAuthor, String pstrPublisher, int pintCopyrightDate){
   this.setStrTitle(pstrTitle);
   this.setStrAuthor(pstrAuthor);
   this.setStrPublisher(pstrPublisher);
   this.setIntCopyrightDate(pintCopyrightDate);
    
}
        
   }
}
