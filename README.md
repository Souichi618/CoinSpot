# CoinSpot
1. Description

During Angela's IOS13 & Swift5 course , the code of ByteCoin-IOS13 is modified to monitor CoinSPOT market status.

2. Brief Description of Function

    2.1 Access Crypt currency CoinSpot API instead of CoinAPI
  
   2.2 Update and display "last price", "bidding price", "asking price" and changes of price from previous update cycle of 
      crypt coin selected by PickerView
      
   2.3 Save amount of crypt coin to local storage
  
   2.4 Calculate current total price of crypt coin selected
  
3. On screen, there are 3 labels and 1 text editor with 2 buttons and 1 Pickerviewer
  
   From Top 1st Label prefixed by "P" : Last price and changes percentage from the previous update cycle,
            blue background color means up, red means down 
            
            2nd prefixed by "BID" : Bidding price
            
            3rd prefixed by "ASK" : Asking price
            
   Text editor input : quantity of coin
   
        In case of add button is clicked  
      
            display calculate last price times quantity of coin 
         
        In case of total button is clicked
      
            display total amount of coins which quantity of coin is placed
         
    PickerView contains 2 commands, Update and Save, and Coin,  BTC,LTC,DOGE,ETH,POWR,ANS,XRP,TRX,EOS,STR,GAS
       
        Update command : Get the latest market price
        Save command : Save quantity of coin to local storage
    
      
         
               





 
