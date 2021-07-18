# hashset
class MyHashSet 
{ 
    HashSet<Integer> myHashSet; 
    /** Initialize your data structure here. */ 
    public MyHashSet() 
    { 
        // HashSet<Integer>        myHashSet=new HashSet<Integer>(); 
        myHashSet = new HashSet<Integer>(); 
    } 
    public void add(int key) { 
        myHashSet.add(key); 
    } 
    public void remove(int key) { 
        myHashSet.remove(key); 
    }
    public boolean contains(int key){
        return myHashSet.contains(key);
    }
 }
