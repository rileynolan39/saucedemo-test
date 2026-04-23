| Test Case ID | Test Scenario        | Preconditions         | Steps                                                                 			| Expected Result                                      | Priority |
|--------------|--------------------- |---------------------- |-------------------------------------------------------------------------------- |----------------------------------------------------- |----------|
| TC_001       | Valid Login          | User is on login page | 1. Enter valid username  2. Enter valid password  3. Click Login      			| User is redirected to the products page              | High     |
| TC_002       | Invalid Login        | User is on login page | 1. Enter valid username  2. Enter invalid password  3. Click Login    			| Error message is displayed                           | High     |
| TC_003       | Empty Fields         | User is on login page | 1. Leave username blank  2. Leave password blank  3. Click Login      			| Validation error message is displayed                | Medium   |
| TC_004	   | Sort Items (Z to A)  | User is logged in 	  | 1. Click Sort dropdown  2. Select Name (Z to A)					  	  			| Products sorted in reverse alphabetical order		   | Low	  |
| TC_005	   | Sort Items (A to Z)  | User is logged in 	  | 1. Click Sort dropdown  2. Select Name (A to Z)					  	  			| Products sorted in alphabetical order				   | Low	  |
| TC_006	   | Sort Items Price Asc | User is logged in 	  | 1. Click Sort dropdown  2. Select Price (low to high)				  			| Products sorted in ascending price order		   	   | Low	  |
| TC_007	   | Sort Items Price Desc| User is logged in 	  | 1. Click Sort dropdown  2. Select Name (high to low)				  			| Products sorted in descending price order			   | Low	  |
| TC_008       | Add Item to Cart     | User is logged in     | 1. Click “Add to Cart” on a product                                   			| Product is added to cart                             | High     |
| TC_009	   | Navigate to Cart     | User is logged in 	  | 1. Click Cart icon in the top right of the page						  			| User is redirected to cart page					   | High	  |
| TC_010       | Remove Item from Cart| Item in cart          | 1. Click “Remove”                                                     			| Item is removed from cart                            | Medium   |
| TC_011	   | Return from Cart	  | User is on cart page  | 1. Click "Continue Shopping"										  			| User is redirected to the products page			   | Low  	  |
| TC_012	   | Navigate to Checkout | User is on cart page  | 1. Click "Checkout"													  			| User is redirected to Checkout: Your Information page| High	  |
| TC_013	   | Valid Info 		  | User is on info page  | 1. Enter text for all fields  2. Click "Checkout"					  			| User is redirected to final checkout page			   | High	  |
| TC_014	   | Empty First Name	  | User is on info page  | 1. Leave first name field blank  2. Fill in other fields  3. Click "Checkout"	| Error message for first name is displayed            | High     |
| TC_015	   | Empty Last Name 	  | User is on info page  | 1. Leave last name field blank  2. Fill in other fields  3. Click "Checkout"    | Error message for last name is displayed             | High     |
| TC_016	   | Empty Postal Code    | User is on info page  | 1. Leave postal code field blank  2. Fill in other fields  3. Click "Checkout"  | Error message for postal code is displayed           | High	  |
| TC_017	   | Cancel Checkout	  | User is on info page  | 1. Click "Cancel"																| User is redirected to cart page				       | Low      |
| TC_018	   | Finish Checkout	  | User is at checkout	  | 1. Click "Finish"																| User is redirected to Checkout: Complete page		   | High	  |
| TC_019	   | Cancel Checkout 2    | User is at checkout   | 1. Click "Cancel"																| User is redirected to cart page					   | Low      |
| TC_020 	   | Back Home			  | User is at complete	  | 1. Click "Back Home"															| User is redirected back to the products page		   | Medium   |