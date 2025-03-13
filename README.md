# Singly-Linkedlist operat
class Node{
    int data;
    Node next;
    
    // constructor 
    
    Node(int data){
        this.data=data;
        this.next=null;
    }
}

class SinglyLinkedList{
    Node head;
    
    // insertatbegin
    
    public void InsertAtBegin(int data){
        Node newNode = new Node(data);
        newNode.next = head;
        head=newNode;
    }
    
    
    // InsertAtEnd 
    
    public void InsertAtEnd(int data){
        Node newNode = new Node(data);
        if(head==null){
            head=newNode;
            return;
        }
        
        Node temp= head;
        while(temp.next!=null){
            temp=temp.next;
        }
        temp.next = newNode;
    }
    
 // delete at begining
 
   public void deleteatbegining(){
       if(head==null){
           System.out.println("No node delete");
           return;
       }
       
       head = head.next;
       
       
   }
  
 
 
    
    
        //display the elements 
    
    public void display(){
        Node temp = head;
       
        while(temp!=null){
            System.out.println(temp.data + " ");
            temp=temp.next;
        }
        System.out.println();
    }
}

public class Main{
    public static void main(String[] args){
     SinglyLinkedList list = new SinglyLinkedList(); 
     list.InsertAtBegin(10);
     list.InsertAtBegin(20);
     list.InsertAtBegin(30);
     list.InsertAtBegin(40);
    // list.InsertAtBegin(50);
    //  list.InsertAtBegin(60);
     list.InsertAtEnd(90);
     list.InsertAtEnd(200);
     list.InsertAtEnd(2000);
     list.deleteatbegining();
     list.display();
    }
}
output:
        class Node{
    int data;
    Node next;
    
    // constructor 
    
    Node(int data){
        this.data=data;
        this.next=null;
    }
}

class SinglyLinkedList{
    Node head;
    
    // insertatbegin
    
    public void InsertAtBegin(int data){
        Node newNode = new Node(data);
        newNode.next = head;
        head=newNode;
    }
    
    
    // InsertAtEnd 
    
    public void InsertAtEnd(int data){
        Node newNode = new Node(data);
        if(head==null){
            head=newNode;
            return;
        }
        
        Node temp= head;
        while(temp.next!=null){
            temp=temp.next;
        }
        temp.next = newNode;
    }
    
 // delete at begining
 
   public void deleteatbegining(){
       if(head==null){
           System.out.println("No node delete");
           return;
       }
       
       head = head.next;
       
       
   }
  
 
 
    
    
        //display the elements 
    
    public void display(){
        Node temp = head;
       
        while(temp!=null){
            System.out.println(temp.data + " ");
            temp=temp.next;
        }
        System.out.println();
    }
}

public class Main{
    public static void main(String[] args){
     SinglyLinkedList list = new SinglyLinkedList(); 
     list.InsertAtBegin(10);
     list.InsertAtBegin(20);
     list.InsertAtBegin(30);
     list.InsertAtBegin(40);
    // list.InsertAtBegin(50);
    //  list.InsertAtBegin(60);
     list.InsertAtEnd(90);
     list.InsertAtEnd(200);
     list.InsertAtEnd(2000);
     list.deleteatbegining();
     list.display();
    }
}
output:
class Node{
    int data;
    Node next;
    
    // constructor 
    
    Node(int data){
        this.data=data;
        this.next=null;
    }
}

class SinglyLinkedList{
    Node head;
    
    // insertatbegin
    
    public void InsertAtBegin(int data){
        Node newNode = new Node(data);
        newNode.next = head;
        head=newNode;
    }
    
    
    // InsertAtEnd 
    
    public void InsertAtEnd(int data){
        Node newNode = new Node(data);
        if(head==null){
            head=newNode;
            return;
        }
        
        Node temp= head;
        while(temp.next!=null){
            temp=temp.next;
        }
        temp.next = newNode;
    }
    
 // delete at begining
 
   public void deleteatbegining(){
       if(head==null){
           System.out.println("No node delete");
           return;
       }
       
       head = head.next;
       
       
   }
  
 
 
    
    
        //display the elements 
    
    public void display(){
        Node temp = head;
       
        while(temp!=null){
            System.out.println(temp.data + " ");
            temp=temp.next;
        }
        System.out.println();
    }
}

public class Main{
    public static void main(String[] args){
     SinglyLinkedList list = new SinglyLinkedList(); 
     list.InsertAtBegin(10);
     list.InsertAtBegin(20);
     list.InsertAtBegin(30);
     list.InsertAtBegin(40);
    // list.InsertAtBegin(50);
    //  list.InsertAtBegin(60);
     list.InsertAtEnd(90);
     list.InsertAtEnd(200);
     list.InsertAtEnd(2000);
     list.deleteatbegining();
     list.display();
    }
}






























































































































