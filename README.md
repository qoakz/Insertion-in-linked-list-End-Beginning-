### Insertion-in-linked-list-(End/Beginning)-

class Linkedlist{
    Node head;
}
class Node{
    int data;
    Node next;   //pointer
    Node(int d){
        data=d;
        next=null;
    }
}

//Implementation of insertion of a node at the end
public void insertAtEnd(int new data){
    Node newNode=new Node(new data);
    
    // To check whether linked list is empty or not
    if(head==null){
        head=new Node(new data);
        return;
    }
    //When the linked list is not empty
    newNode.next=null;
    Node temp=head;
    while(temp.next !=null){
        temp=temp.next;
    }
    temp.next=newNode;
    return;
}

//Implememtation of insertion of node at the beginning
public void insertAtBeginng(int new data ){
    Node newNode=new NOde(newData);
    newNode.next=head;
    head=newNode;
}






//Implementatin of displaying the linked list
public void display(){
    Node current=head;
    while(current!=null){
        System.out.println(temp.data+"");
        temp=temp.next;
        
    }
}
public class Main
{
	public static void main(String[] args) {
	    Linkedlist list=insertAtEnd(int new data);
	    Linkedlist list=insertAtBeginning(int new data);
	    list.insertAtEnd(14);
	    list.insertAtBeginning(14);
	
	}
}
