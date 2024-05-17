# ch13
Public class Example5_10{
 Public static void main(String[] args); {

   String str ="hello ali";
   int width =15;
   String s= stringFormatter.leftAdjust(str,width);
   Systen.out.println("Left justify string is:" + s);
   s= stringFormatter.center(str,width);
   Systen.out.println("middle justify string is:" + s
  }
}

Public class stringFormatter{
  Public static String leftAdjust(string s, int widht){
    final int stringLength=s.Length();
    if(stringLength >= width)
    {
      return s;
    }
    else
       return spaces (width-stringLength).insert(0,s).toString();
  }

  Public static String righttAdjust(string s, int widht){
    final int stringLength=s.Length();
    if(stringLength >= width)
    {
      return s;
    }
    else
       return spaces (width-stringLength).append(s).toString();
      }
      //***********

       Public static String center(string s, int widht){
         final int stringLength=s.Length();
    if(stringLength >= width)
    {
      return s;
    }
    else
       {
         final int suSpaces= widht_stringLength;
         final int leftpaces= numSpaces / 2, rightspace= numSpaces _leftSpace;
         return spaces(leftSpace).append(s).append(spaces(rightSpace)).toString();
         }
    }

    private static stringBuffer spaces( int numSpaces){
      if(numSpaces <=0)
          return new String Buffer();
      else
      {
        StringBuffer spaces= new StringBuffer();
        for(int i=0; i,numSpaces; i++)
            spaces.append('');
       return spaces;
       }
    }
}




       
