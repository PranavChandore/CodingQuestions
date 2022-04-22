# CodingQuestions
Dsa and Algorithm  in c++
.......................<LINKED LIST>.................
141.Linked List Cycle<https://leetcode.com/problems/linked-list-cycle/>

19.Remove Nth Node From End of List <https://leetcode.com/problems/remove-nth-node-from-end-of-list/>
two pointer algo same
  //you can create dummy node heare
  1>for(int i=1;i<=n(is postion which is given);i++){f=f->next;}
  then follw to two star but hrere 
  2>while(f!=NULL && f->next!=NULL){
  slow and fast pointer both move one step same
  3> then just condtion false then s->next = s->next->next;
  return head;

237.Delete Node in a Linked List<https://leetcode.com/problems/delete-node-in-a-linked-list/>
  
203.Remove Linked List Elements <https://leetcode.com/problems/remove-linked-list-elements/>
  

876. Middle of linked List <https://leetcode.com/problems/middle-of-the-linked-list/>
  ------two pointer algo and return slow
  
 206.Reverse Linked List <https://leetcode.com/problems/reverse-linked-list/>
  create three pointer

  1097.Delete the Middle Node of a Linked List <https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/>
so here same apporach just like we find to middle element then creat prev null  node to store prev slow poitner value and after my slow pointer reaches to middle
  then prev =s;
  s= s->next;
  
  142.Linked List Cycle II  <https://leetcode.com/problems/linked-list-cycle-ii/>
  -----try creat entry pointer points to head and entry and slow both now travel 
                //from its starting position and when they are equal thats begingig point of 
                //loop node
234.Palindrome linked list <https://leetcode.com/problems/palindrome-linked-list/>
  .....1)finde mid if even stop at before mid
      2)then reverse from mid next ;
    3)mid->next =revers(temp) where temp store temp->next;
  4)compare data of given two halfs
