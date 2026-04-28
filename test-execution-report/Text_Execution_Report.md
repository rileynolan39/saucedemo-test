| Test Case ID | Test Scenario        | Status (Pass/Fail)    | Comments                                                                 			                                       
|--------------|--------------------- |---------------------- |---------------------------------------------------------------------------------------------------------------------------- 
| TC_001       | Valid Login          | Pass             	  | User successfully logged in and brought to product page                                                                    
| TC_002       | Invalid Login        | Pass                  | Username/Password mismatch error correctly displays
| TC_003       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_004	   | Sort Items (Z to A)  | Pass                  | Items correctly sorted
| TC_005	   | Sort Items (A to Z)  | Pass                  | Items correctly sorted
| TC_006	   | Sort Items Price Asc | Pass                  | Items correctly sorted
| TC_007	   | Sort Items Price Desc| Pass	              | Items correctly sorted
| TC_008       | Add Item to Cart     | Pass                  | Items successfully added to cart
| TC_009	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_010       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_011	   | Return from Cart	  | Pass                  | Navigation from cart successful
| TC_012	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart
| TC_013	   | Valid Info 		  | Pass                  | Checkout process proceeds successfully, though the only check is that the fields are not empty, not that they are valid
| TC_014	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_015	   | Empty Last Name 	  | Pass                  | Empty last name field error correctly displays, though empty first name error has priority
| TC_016	   | Empty Postal Code    | Pass                  | Empty postal code field error correctly displays, though the previous error both have priority
| TC_017	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_018	   | Finish Checkout	  | Pass                  | Full checkout successful, though can be done with an empty cart
| TC_019	   | Cancel Checkout 2    | Pass                  | Navigation back to cart successful
| TC_020 	   | Back Home			  | Pass                  | Navigation back to product page successful