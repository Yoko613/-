# -伪类css
      
      
      
       &:after {
            display: block;
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 200%;
            height: 1rem;
            border-bottom: 1px solid #d9d9d9;
            transform-origin: left bottom;
            -webkit-transform-origin: left bottom;
            transform: scale(0.5);
            -webkit-transform: scale(0.5);
        }
        &:last-child::after {
            content: "";
            background: initial;
            border-bottom: none;
        }
       
       
        
# 渐变：

       {
            background-image: -webkit-linear-gradient(rgba(255, 255, 255, 0), rgba(255, 255, 255, 0.85));
             background-image: linear-gradient(rgba(255, 255, 255, 0), rgba(255, 255, 255, 0.85)); 
          
       }

