# fraction2

          function fraction2(num){
              if(num === 99){
            
                  return 1/(num*(num+1));
            
              } else {
          
                     return fraction2(num + 1) + 1/(num * (num + 1));
                
              }
          }
          
          fraction2(2);
