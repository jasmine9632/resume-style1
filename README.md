# resume-style1

.cleafix::after{
content:'''
display:block;
clear:both;
}



float:left;

width:200px;


margin-left:200px;

//用伪元素画线

.user h1::after{

        content: '';
        
        display: block;
        
        margin:16px auto;
        
        border-top:1px solid #ccc;
        
        width:60px;
        
      }
      
      
      //用伪元素画三角形
      
      .aside .user::after{
        content:'';
        display: block;
        margin-top: 20px;
        border-right: 140px solid #d6d6d6;
        border-left: 140px solid transparent;
        border-top: 20px solid #d6d6d6;
        border-bottom: 20px solid transparent;
      }
