# ClubSpeed Events Karting Enterprise API - Command Line Tool

USAGE:

```   csekent <OPTIONS> <COMMAND> <COMMAND OPTIONS>```


### OPTIONS

> Make sure to pass these options before the command  
 
```
   -c <csek-ent.json>,        ClubSpeed Configuration file - default: csek-ent.json       
   --config <csek-ent.json>                                                    

   -l                    Log file path                                    
   <command-name.log>,                                                    
   --log                                                                  
   <command-name.log>                                                     

   -e <dev|prod>, --env  Environment - dev or production                  
   <dev|prod>                                                             

   -s, --simulate        Simulate                                         

   -q, --quiet           Quiet Mode                                       

   -d, --skip-defaults   Skip Configuration Defaults                      

   -v, --version         Show Version                                     

   -h, --help            Display this help screen and exit immeadiately.  

   --no-colors           Do not use any colors in output. Useful when     
                         piping output to other tools or files.           

   --loglevel <level>    Minimum level of messages to display. Default is 
                         debug. Valid levels are: debug, info, notice,    
                         success, warning, error, critical, alert,        
                         emergency.                                       

```
### COMMANDS

   > Pass the command as first parameter after the above options. Options for 
   each command, as outlined below, need to be passed after the command      



   #### ` getVersion <OPTIONS>`
##### Get Club Speed version                                               
                                                                          

     -m, --man            Show help on this command                       


#### `  getApiVersion <OPTIONS>`

##### Get API version                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getOSVersion <OPTIONS>`

##### Get OS version                                                       
                                                                          

     -m, --man            Show help on this command                       


#### `  getSQLVersion <OPTIONS>`

##### Get SQL version                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getSettings <OPTIONS>`

##### Get all settings of a group                                          
                                                                          

     --group <group>                                                      

     -m, --man            Show help on this command                       


#### `  getSetting <OPTIONS>`

##### Get individual setting                                               
                                                                          

     --group <group>                                                      

     --setting <setting>                                                  

     -m, --man            Show help on this command                       


#### `  getKioskSettings <OPTIONS>`

##### Get Kiosk settings                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  getAppImages <OPTIONS>`

##### Retrieve images by app                                               
                                                                          

     --app <app>                                                          

     -m, --man            Show help on this command                       


#### `  getTracks <OPTIONS>`

##### Get SQL version                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getChannelConfig <OPTIONS>`

##### Get Club Speed channel configuration                                 
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  testUserLogin <OPTIONS>`

##### Attempt to login a user                                              
                                                                          

     --username                                                           
     <username>                                                           

     --password                                                           
     <password>                                                           

     -m, --man            Show help on this command                       


#### `  testAdminUserLogin <OPTIONS>`

##### Attempt to login an admin user                                       
                                                                          

     --username                                                           
     <username>                                                           

     --password                                                           
     <password>                                                           

     -m, --man            Show help on this command                       


#### `  getBooking <OPTIONS>`

##### Get Bookings                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createBooking <OPTIONS>`

##### Create Booking                                                       
                                                                          

     --heat <heat>                                                        

     --product <product>                                                  

     --public <public>                                                    

     --quantity                                                           
     <quantity>                                                           

     -m, --man            Show help on this command                       


#### `  updateBooking <OPTIONS>`

##### Update Booking                                                       
                                                                          

     --id <id>                                                            

     --heat <heat>                                                        

     --product <product>                                                  

     --public <public>                                                    

     --quantity                                                           
     <quantity>                                                           

     -m, --man            Show help on this command                       


#### `  deleteBooking <OPTIONS>`

##### Delete Bookings                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getBookingCount <OPTIONS>`

##### Get Bookings count                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  getBookingAvailability <OPTIONS>`

##### Get all Bookings                                                     
                                                                          

     -m, --man            Show help on this command                       


#### `  getCheckDetails <OPTIONS>`

##### Get CheckDetails                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createCheckDetails <OPTIONS>`

##### Create CheckDetails                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  updateCheckDetails <OPTIONS>`

##### Update CheckDetails                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteCheckDetails <OPTIONS>`

##### Delete CheckDetails                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getCheckDetailsCount <OPTIONS>`

##### Get CheckDetails count                                               
                                                                          

     -m, --man            Show help on this command                       


#### `  getChecks <OPTIONS>`

##### Get Checks                                                           
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createChecks <OPTIONS>`

##### Create Checks                                                        
                                                                          

     -m, --man            Show help on this command                       


#### `  updateChecks <OPTIONS>`

##### Update Checks                                                        
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteCheck <OPTIONS>`

##### Void Check                                                           
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getChecksCount <OPTIONS>`

##### Get Checks count                                                     
                                                                          

     -m, --man            Show help on this command                       


#### `  finalizeCheck <OPTIONS>`

##### Finalize Check                                                       
                                                                          

     --id <id>                                                            

     --checkDetailId                                                      
     <check-detail-id>                                                    

     --heatId <heat-id>                                                   

     -m, --man            Show help on this command                       


#### `  getCheckTotals <OPTIONS>`

##### Get CheckTotals                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createCheckTotals <OPTIONS>`

##### Create CheckTotals                                                   
                                                                          

     --customerId                                                         
     <customer-id>                                                        

     --checkDiscountId                                                    
     <check-discount-id>                                                  

     --userId <user-id>                                                   

     -m, --man            Show help on this command                       


#### `  calculateCheckTotals <OPTIONS>`

##### Create CheckTotals                                                   
                                                                          

     --customerId                                                         
     <customer-id>                                                        

     --checkDiscountId                                                    
     <check-discount-id>                                                  

     --userId <user-id>                                                   

     -m, --man            Show help on this command                       


#### `  getCheckTotalsCount <OPTIONS>`

##### Get CheckTotals count                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  getCustomers <OPTIONS>`

##### Get Customers                                                        
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createCustomers <OPTIONS>`

##### Create Customers                                                     
                                                                          

     -m, --man            Show help on this command                       


#### `  updateCustomers <OPTIONS>`

##### Update Customers                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteCustomers <OPTIONS>`

##### Delete Customers                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getCustomersCount <OPTIONS>`

##### Get Customers count                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  getDiscountType <OPTIONS>`

##### Get DiscountType                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createDiscountType <OPTIONS>`

##### Create DiscountType                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  updateDiscountType <OPTIONS>`

##### Update DiscountType                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteDiscountType <OPTIONS>`

##### Delete DiscountType                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getDiscountTypeCount <OPTIONS>`

##### Get DiscountTypes count                                              
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventHeatDetails <OPTIONS>`

##### Get EventHeatDetails                                                 
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventHeatDetails <OPTIONS>`

##### Create EventHeatDetails                                              
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventHeatDetails <OPTIONS>`

##### Update EventHeatDetails                                              
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventHeatDetails <OPTIONS>`

##### Delete EventHeatDetails                                              
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventHeatDetailsCount <OPTIONS>`

##### Get EventHeatDetails count                                           
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventHeatTypes <OPTIONS>`

##### Get EventHeatTypes                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventHeatTypes <OPTIONS>`

##### Create EventHeatTypes                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventHeatTypes <OPTIONS>`

##### Update EventHeatTypes                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventHeatTypes <OPTIONS>`

##### Delete EventHeatTypes                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventHeatTypesCount <OPTIONS>`

##### Get EventHeatTypes count                                             
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventReservationLinks <OPTIONS>`

##### Get EventReservationLinks                                            
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventReservationLinks <OPTIONS>`

##### Create EventReservationLinks                                         
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventReservationLinks <OPTIONS>`

##### Update EventReservationLinks                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventReservationLinks <OPTIONS>`

##### Delete EventReservationLinks                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventReservationLinksCount <OPTIONS>`

##### Get EventReservationLinks count                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventReservations <OPTIONS>`

##### Get EventReservations                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventReservations <OPTIONS>`

##### Create EventReservations                                             
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventReservations <OPTIONS>`

##### Update EventReservations                                             
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  updateEventReservationStatus <OPTIONS>`

##### Update EventReservation status                                       
                                                                          

     --id <id>                                                            

     --statusId                                                           
     <status-id>                                                          

     -m, --man            Show help on this command                       


#### `  deleteEventReservations <OPTIONS>`

##### Delete EventReservations                                             
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventReservationsCount <OPTIONS>`

##### Get EventReservations count                                          
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventReservationTypes <OPTIONS>`

##### Get EventReservationTypes                                            
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventReservationTypes <OPTIONS>`

##### Create EventReservationTypes                                         
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventReservationTypes <OPTIONS>`

##### Update EventReservationTypes                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventReservationTypes <OPTIONS>`

##### Delete EventReservationTypes                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventReservationTypesCount <OPTIONS>`

##### Get EventReservationTypes count                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventRounds <OPTIONS>`

##### Get EventRounds                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventRounds <OPTIONS>`

##### Create EventRounds                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventRounds <OPTIONS>`

##### Update EventRounds                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventRounds <OPTIONS>`

##### Delete EventRounds                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventRoundsCount <OPTIONS>`

##### Get EventRounds count                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  getEvents <OPTIONS>`

##### Get Events                                                           
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEvents <OPTIONS>`

##### Create Events                                                        
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEvents <OPTIONS>`

##### Update Events                                                        
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEvents <OPTIONS>`

##### Delete Events                                                        
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventsCount <OPTIONS>`

##### Get Events count                                                     
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventStatuses <OPTIONS>`

##### Get EventStatuses                                                    
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventStatuses <OPTIONS>`

##### Create EventStatuses                                                 
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventStatuses <OPTIONS>`

##### Update EventStatuses                                                 
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventStatuses <OPTIONS>`

##### Delete EventStatuses                                                 
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventStatusesCount <OPTIONS>`

##### Get EventStatuses count                                              
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventTasks <OPTIONS>`

##### Get EventTasks                                                       
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventTasks <OPTIONS>`

##### Create EventTasks                                                    
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventTasks <OPTIONS>`

##### Update EventTasks                                                    
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventTasks <OPTIONS>`

##### Delete EventTasks                                                    
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventTasksCount <OPTIONS>`

##### Get EventTasks count                                                 
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventTaskTypes <OPTIONS>`

##### Get EventTaskTypes                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventTaskTypes <OPTIONS>`

##### Create EventTaskTypes                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventTaskTypes <OPTIONS>`

##### Update EventTaskTypes                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventTaskTypes <OPTIONS>`

##### Delete EventTaskTypes                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventTaskTypesCount <OPTIONS>`

##### Get EventTaskTypes count                                             
                                                                          

     -m, --man            Show help on this command                       


#### `  getEventTypes <OPTIONS>`

##### Get EventTypes                                                       
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createEventTypes <OPTIONS>`

##### Create EventTypes                                                    
                                                                          

     -m, --man            Show help on this command                       


#### `  updateEventTypes <OPTIONS>`

##### Update EventTypes                                                    
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteEventTypes <OPTIONS>`

##### Delete EventTypes                                                    
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getEventTypesCount <OPTIONS>`

##### Get EventTypes count                                                 
                                                                          

     -m, --man            Show help on this command                       


#### `  getGiftCardHistory <OPTIONS>`

##### Get GiftCardHistory                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createGiftCardHistory <OPTIONS>`

##### Create GiftCardHistory                                               
                                                                          

     -m, --man            Show help on this command                       


#### `  updateGiftCardHistory <OPTIONS>`

##### Update GiftCardHistory                                               
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteGiftCardHistory <OPTIONS>`

##### Delete GiftCardHistory                                               
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getGiftCardHistoryCount <OPTIONS>`

##### Get GiftCardHistorys count                                           
                                                                          

     -m, --man            Show help on this command                       


#### `  getHeatDetails <OPTIONS>`

##### Get HeatDetails                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createHeatDetails <OPTIONS>`

##### Create HeatDetails                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  updateHeatDetails <OPTIONS>`

##### Update HeatDetails                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteHeatDetails <OPTIONS>`

##### Delete HeatDetails                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getHeatDetailsCount <OPTIONS>`

##### Get HeatDetails count                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  getHeatMain <OPTIONS>`

##### Get HeatMain                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createHeatMain <OPTIONS>`

##### Create HeatMain                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  updateHeatMain <OPTIONS>`

##### Update HeatMain                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteHeatMain <OPTIONS>`

##### Delete HeatMain                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getHeatMainCount <OPTIONS>`

##### Get HeatMains count                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  getHeatTypes <OPTIONS>`

##### Get HeatTypes                                                        
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createHeatTypes <OPTIONS>`

##### Create HeatTypes                                                     
                                                                          

     -m, --man            Show help on this command                       


#### `  updateHeatTypes <OPTIONS>`

##### Update HeatTypes                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteHeatTypes <OPTIONS>`

##### Delete HeatTypes                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getHeatTypesCount <OPTIONS>`

##### Get HeatTypes count                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  getMemberships <OPTIONS>`

##### Get Memberships                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createMemberships <OPTIONS>`

##### Create Memberships                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  updateMemberships <OPTIONS>`

##### Update Memberships                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteMemberships <OPTIONS>`

##### Delete Memberships                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getMembershipsCount <OPTIONS>`

##### Get Memberships count                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  getMembershipTypes <OPTIONS>`

##### Get MembershipTypes                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createMembershipTypes <OPTIONS>`

##### Create MembershipTypes                                               
                                                                          

     -m, --man            Show help on this command                       


#### `  updateMembershipTypes <OPTIONS>`

##### Update MembershipTypes                                               
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteMembershipTypes <OPTIONS>`

##### Delete MembershipTypes                                               
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getMembershipTypesCount <OPTIONS>`

##### Get MembershipTypes count                                            
                                                                          

     -m, --man            Show help on this command                       


#### `  getOmnipayVendors <OPTIONS>`

##### List Vendors                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  acceptOmnipayPayment <OPTIONS>`

##### Accept Payment (omnipay)                                             
                                                                          

     --name <name>                                                        

     --amount <amount>                                                    

     --transactionId                                                      
     <transaction-id>                                                     

     --currency                                                           
     <currency>                                                           

     --returnUrl                                                          
     <return-url>                                                         

#### `    --options <options>`                                                  

     --card <card>                                                        

     -m, --man            Show help on this command                       


#### `  completeOmnipayPayment <OPTIONS>`

##### Complete Payment (omnipay)                                           
                                                                          

     -m, --man            Show help on this command                       


#### `  generateResetToken <OPTIONS>`

##### Generate Reset Token                                                 
                                                                          

     --email <email>                                                      

     --url <url>                                                          

     -m, --man            Show help on this command                       


#### `  consumeResetToken <OPTIONS>`

##### Consume Reset Token                                                  
                                                                          

     --token <token>                                                      

     --password                                                           
     <password>                                                           

     -m, --man            Show help on this command                       


#### `  getPayments <OPTIONS>`

##### Get Payments                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createPayments <OPTIONS>`

##### Create Payments                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  updatePayments <OPTIONS>`

##### Update Payments                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deletePayments <OPTIONS>`

##### Delete Payments                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getPaymentsCount <OPTIONS>`

##### Get Payments count                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  processPayment <OPTIONS>`

##### Process Payment                                                      
                                                                          

     --name <name>                                                        

#### `    --options <options>`                                                  

     --checkId <check-id>                                                 

     --checkDetailId                                                      
     <check-detail-id>                                                    

     --heatId <heat-id>                                                   

     --card <card>                                                        

     -m, --man            Show help on this command                       


#### `  updateProcessPayment <OPTIONS>`

##### Update ProcessPayment                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteProcessPayment <OPTIONS>`

##### Delete ProcessPayment                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getProcessPaymentCount <OPTIONS>`

##### Get ProcessPayments count                                            
                                                                          

     -m, --man            Show help on this command                       


#### `  getProductClasses <OPTIONS>`

##### Get ProductClasses                                                   
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createProductClasses <OPTIONS>`

##### Create ProductClasses                                                
                                                                          

     -m, --man            Show help on this command                       


#### `  updateProductClasses <OPTIONS>`

##### Update ProductClasses                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteProductClasses <OPTIONS>`

##### Delete ProductClasses                                                
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getProductClassesCount <OPTIONS>`

##### Get ProductClasses count                                             
                                                                          

     -m, --man            Show help on this command                       


#### `  getProducts <OPTIONS>`

##### Get Products                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createProducts <OPTIONS>`

##### Create Products                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  updateProducts <OPTIONS>`

##### Update Products                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteProducts <OPTIONS>`

##### Delete Products                                                      
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getProductsCount <OPTIONS>`

##### Get Products count                                                   
                                                                          

     -m, --man            Show help on this command                       


#### `  getReservations <OPTIONS>`

##### Get Reservations                                                     
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createReservations <OPTIONS>`

##### Create Reservations                                                  
                                                                          

     -m, --man            Show help on this command                       


#### `  updateReservations <OPTIONS>`

##### Update Reservations                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteReservations <OPTIONS>`

##### Delete Reservations                                                  
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getReservationsCount <OPTIONS>`

##### Get Reservations count                                               
                                                                          

     -m, --man            Show help on this command                       


#### `  getSources <OPTIONS>`

##### Get Sources                                                          
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createSources <OPTIONS>`

##### Create Sources                                                       
                                                                          

     -m, --man            Show help on this command                       


#### `  updateSources <OPTIONS>`

##### Update Sources                                                       
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteSources <OPTIONS>`

##### Delete Sources                                                       
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getSourcesCount <OPTIONS>`

##### Get Sources count                                                    
                                                                          

     -m, --man            Show help on this command                       


#### `  getTaxes <OPTIONS>`

##### Get Taxes                                                            
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createTaxes <OPTIONS>`

##### Create Taxes                                                         
                                                                          

     -m, --man            Show help on this command                       


#### `  updateTaxes <OPTIONS>`

##### Update Taxes                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteTaxes <OPTIONS>`

##### Delete Taxes                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getTaxesCount <OPTIONS>`

##### Get Taxes count                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  getUsers <OPTIONS>`

##### Get Users                                                            
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  createUsers <OPTIONS>`

##### Create Users                                                         
                                                                          

     -m, --man            Show help on this command                       


#### `  updateUsers <OPTIONS>`

##### Update Users                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  deleteUsers <OPTIONS>`

##### Delete Users                                                         
                                                                          

     --id <id>                                                            

     -m, --man            Show help on this command                       


#### `  getUsersCount <OPTIONS>`

##### Get Users count                                                      
                                                                          

     -m, --man            Show help on this command                       


#### `  createRacer <OPTIONS>`

##### Create as racer                                                      
                                                                          

     --racername                                                          
     <racername>                                                          

     --email <email>                                                      

     --password                                                           
     <password>                                                           

     --donotemail                                                         
     <donotemail>                                                         

     --firstname                                                          
     <firstname>                                                          

     --lastname                                                           
     <lastname>                                                           

     --birthdate                                                          
     <birthdate>                                                          

     --gender <gender>                                                    

     --mobilephone                                                        
     <mobilephone>                                                        

     --address <address>                                                  

     --address2                                                           
     <address2>                                                           

     --city <city>                                                        

     --country <country>                                                  

     --howdidyouhearabout                                                 
     us                                                                   
     <howdidyouhearaboutu                                                 
     s>                                                                   

     --state <state>                                                      

     --zip <zip>                                                          

     -m, --man            Show help on this command                       


#### `  login <OPTIONS>`

##### Login as racer                                                       
                                                                          

     --username                                                           
     <username>                                                           

     --password                                                           
     <password>                                                           

     -m, --man            Show help on this command                       


#### `  loginFb <OPTIONS>`

##### Login as racer using Facebook                                        
                                                                          

     --email <email>                                                      

     --facebookId <facebook-id>                                                        

     --facebookToken                                                      
     <facebook-token>                                                     

     --facebookAllowEmail                                                 
     <facebook-allow-emai                                                 
     l>                                                                   

     --facebookAllowPost                                                  
     <facebook-allow-post                                                 
     >                                                                    

     --facebookEnabled                                                    
     <facebook-enabled>                                                   

     --facebookExpiresIn                                                  
     <facebook-expires-in                                                 
     >                                                                    

     --racername                                                          
     <racername>                                                          

     --password                                                           
     <password>                                                           

     --donotemail                                                         
     <donotemail>                                                         

     --firstname                                                          
     <firstname>                                                          

     --lastname                                                           
     <lastname>                                                           

     --birthdate                                                          
     <birthdate>                                                          

     --gender <gender>                                                    

     --mobilephone                                                        
     <mobilephone>                                                        

     --address <address>                                                  

     --address2                                                           
     <address2>                                                           

     --city <city>                                                        

     --country <country>                                                  

     --howdidyouhearabout                                                 
     us                                                                   
     <howdidyouhearaboutu                                                 
     s>                                                                   

     --state <state>                                                      

     --zip <zip>                                                          

     -m, --man            Show help on this command                       


----

## SKIPPED API

#### Racers
Use these methods to find a racer's "racer_id" which can be used to get information on both the racer and the races they have participated in. Without a field parameter this is a wildcard match across First Name, Last Name, Racer Name and Email. It is possible to specify a specific field. "field=email" is currently supported. See email example below for usage.

* Find racer_id by Nickname: /racers/search?query=Wes Ratcliff (JSON, JSONP, XML)

* Find racer_id by Email: /racers/search?field=email&query=wes@nolamotor.com (JSON, JSONP, XML)

* Find Racer by racer_id: /racers/1000002 (JSON, JSONP, XML)

* Find Racer's Races: /racers/1000002/races (JSON, JSONP, XML)

* Top RPM Ranking

	* Limit: /racers/toprpm?limit=5 (JSON, JSONP, XML)
	
	* Gender (m: Male, f: Female): /racers/toprpm?gender=m (JSON, JSONP, XML)
	
	* Most Improved RPM (range: (month or year); month; year): /racers/most_improved_rpm?range=month&month=6&year=2014&limit=5 (JSON, JSONP, XML)
	
	* Most Improved RPM (start; end): /racers/most_improved_rpm?start=2016-09-09&end=2016-10-02 (JSON, JSONP, XML)

* Find by last updated: /racers/last_updated?start=2012-09-01+00:00:00&limit=1000&end=2019-11-01+00:00:00&startCustId=1000000&endCustId=1999999 (JSON, JSONP, XML)
 
 
 #### Races - Race Results
  
Get information on races and laps. Can use "next" or "current" in place of the race_id to pull information from the next or currently running race.

`heat_status_id`: 0 = Not Started; 1 = Currently Running; 2 = Auto Stopped; 3 = Manually Stopped; 4 = Closed

There are two ways to win, stored as `win_by` in the race -- by "position" or by fastest "laptime". 
Races by position's timing is started when the first person crosses the start/finish line. 
This is the lowest `amb_time` in the laps returned. Gaps to the leader and position in the 
race may be calculated by taking the racer's time and subtracting out the lowest `amb_time`.

* Today's Races: /races/races (JSON, JSONP, XML)

* Today's Upcoming Races: /races/upcoming (JSON, JSONP, XML)

* Races on Date: /races/races.json?start=2014-01-01&end=2014-01-01 (JSON, JSONP, XML)

* Get next race: (defaults to track 1, offset 0) /races/next (JSON, JSONP, XML)

* Get previous race: (defaults to track 1, offset 0) /races/previous (JSON, JSONP, XML)

* Get current race_id: (defaults to track 1) /races/current_race_id (JSON, JSONP, XML)

* Details on race: /races/9829 (JSON, JSONP, XML)

* Laps completed: /races/9829/number_of_laps (JSON, JSONP, XML)

* Details on race (limiting by racer and only laps after a certain lap_id): /races/9829/laps.json?racer_id=1000002&lap_id=584079 (JSON, JSONP, XML)

* Upcoming Heat Types (for Web): /races/upcoming_heat_types (JSON, JSONP, XML)


#### Races - Scoreboard

Get the scoreboard for a specific heat or track

* By track_id: /races/scoreboard (JSON, JSONP, XML)

* By heat_id: /races/scoreboard (JSON, JSONP, XML)


#### Races - Stats

Find out some interesting info about the laps run during races

* Total Laps Completed: /races/total_laps (JSON, JSONP, XML)

* Who Did Lap #: /races/lap_number/500000 (JSON, JSONP, XML)


#### Races - After specific time

Get a list of completed heats after a specific date and time

* Races after specific time: /races/since?&date=2014-04-01 09:00:00&limit=200
(JSON, JSONP, XML)
 (Limit is an optional parameter. Defaults to 100 rows, maxes out at 500 rows.)


#### Races - Final positions

Find out the final positions for each racer in a finished heat

* Final positions of heat: /races/final_positions?&race_id=1000 (JSON,JSONP,XML)


#### Races - Fastest Laps


Find the fastest laps. Results have many options for filtering and sorting. Supports a maximum of 100 per query.

* By Time Period

	* Day: /races/fastest?range=day (JSON, JSONP, XML)
	
	* Week: /races/fastest?range=week
	
	* Month: /races/fastest?range=month
	
	* Year: /races/fastest?range=year
	
	* In a Date Range: /races/fastest?start=2012-01-01&end=2012-01-01
	
* Filter Results By

	* Tracks (1: Rental, 2: Oval, 3: Race): /races/fastest?track=1
	
	* Speed Level (1: Adult Rental CCW; 2: Junior Rental CCW; 3-4 Not Used; 5: Event Track: 6; Adult Rental CW; 7: Junior Rental CW): /races/fastest?speed_level=1
	
	* Limt: /races/fastest?limit=5
	
	* Gender (m: Male, f: Female): /races/fastest?gender=m
	
	* Exclude Employees: /races/fastest?exclude_employees=1
	
	* Only Employees: /races/fastest?only_employees=1
	
	* Employees and Customers: /races/fastest?exclude_employees=0
	
	* Weight (light: 0-155lb, medium: 156-190lb, heavy: 191-220lb, sumo: 221+lb): /races/fastest?weight=light
	
	* Birth Date in Range: /races/fastest?start_birthdate=1982-01-01&end_birthdate=1982-12-31
	

#### Translations

Tie into Club Speed's translation database. Translations are grouped by "namespaces".

* Retrieve by namespace: `translations/getNamespace` (JSON, JSONP, XML)
		http://vm-119.clubspeedtiming.com/api/index.php/translations/getNamespace.json?namespace=Interfaces.Common&key=YOUR_KEY_HERE
		
* Retrieve by language: `translations/getTranslations` (JSON, JSONP, XML)
http://vm-119.clubspeedtiming.com/api/index.php/translations/getTranslations.json?language=en-US&key=YOUR_KEY_HERE

* Translate by key(s). Keys may be String or Array: `translations/translate` (JSON, JSONP, XML)
http://vm-119.clubspeedtiming.com/api/index.php/translations/translate.json?keys=strPoints&language=en-US&namespace=Interfaces.Common&key=YOUR_KEY_HERE

