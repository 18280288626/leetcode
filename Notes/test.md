a
-
# a
## a
`aaaa`
`kdsjfklsdjfk
fsdkfjdslkf
fjlsdkfj`
1. sfasf
2. dsfdsf
3. sdfsf
---
  
  
    function getXML(servlet,args){    
        return loadXMLDoc("/post/"+servlet, "get",null,args);
    }  
    function postXML(servlet,inp,args){  
        var pinp = inp;
        //if(pinp=="")pinp="[empty]";
      return loadXMLDoc("/post/"+servlet, "post",pinp,args);
    }  
