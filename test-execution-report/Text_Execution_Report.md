| Test Case ID | Test Scenario        | Status (Pass/Fail)    | Comments                                                                 			                                       
|--------------|--------------------- |---------------------- |---------------------------------------------------------------------------------------------------------------------------- 
| TC_001       | Valid Login          | Pass             	  | User successfully logged in and brought to product page                                                                    
| TC_002       | Invalid Login        | Pass                  | Invalid Username/Password error correctly displays
| TC_003       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_004	   | Sort Items (Z to A)  | Pass                  | Items correctly sorted
| TC_005	   | Sort Items (A to Z)  | Pass                  | Items correctly sorted
| TC_006	   | Sort Items Price Asc | Pass                  | Items correctly sorted
| TC_007	   | Sort Items Price Desc| Pass	              | Items correctly sorted
| TC_008       | Add Item to Cart     | Pass                  | Items successfully added to cart
| TC_009       | Remove Item          | Pass                  | Items successfully removed from cart
| TC_010	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_011       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_012	   | Return from Cart	  | Pass                  | Navigation from cart successful
| TC_013	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart
| TC_014	   | Valid Info 		  | Pass                  | Checkout process proceeds successfully, though the only check is that the fields are not empty, not that they are valid
| TC_015	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_016	   | Empty Last Name 	  | Pass                  | Empty last name field error correctly displays, though empty first name error has priority
| TC_017	   | Empty Postal Code    | Pass                  | Empty postal code field error correctly displays, though the previous error both have priority
| TC_018	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_019	   | Finish Checkout	  | Pass                  | Full checkout successful, though can be done with an empty cart
| TC_020	   | Cancel Checkout 2    | Pass                  | Navigation back to product page successful
| TC_021 	   | Back Home			  | Pass                  | Navigation back to product page successful
| TC_022       | Navigate to Item     | Pass                  | Navigation to correct item page is successful
| TC_023       | Back to Products     | Pass                  | Navigation back to product page successful
| TC_024       | Item Information     | Pass                  | All information is correct

| TC_101       | Valid Login(Lock out)| Pass             	  | Error message for locked out user successfully displays                                                                    
| TC_102       | Invalid Login        | Pass                  | Invalid Username/Password error correctly displays
| TC_103       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty

| TC_201       | Valid Login          | Pass             	  | User successfully logged in and brought to product page                                                                    
| TC_202       | Invalid Login        | Pass                  | Invalid Username/Password error correctly displays
| TC_203       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_204	   | Sort Items (Z to A)  | Fail                  | Item order does not change
| TC_205	   | Sort Items (A to Z)  | Fail                  | Item order is A-Z by default, failure because item order cannot be changed to something else then back
| TC_206	   | Sort Items Price Asc | Fail                  | Item order does not change
| TC_207	   | Sort Items Price Desc| Fail	              | Item order does not change
| TC_208       | Add Item to Cart     | Fail                  | T-shirt items and Jacket item cannot be added to cart, both from products page and item pages
| TC_209       | Remove Item          | Fail                  | No items can be removed from cart, both from the products page and the item pages
| TC_210	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_211       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_212	   | Return from Cart	  | Pass                  | Navigation from cart successful
| TC_213	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart
| TC_214	   | Valid Info 		  | Fail                  | Last name text box cannot be filled out, proceeding further in checkout process not possible
| TC_215	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_216	   | Empty Last Name 	  | Pass                  | Empty last name field error correctly displays, though empty first name error has priority
| TC_217	   | Empty Postal Code    | Fail                  | Cannot be tested because last name field cannot be filled
| TC_218	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_219	   | Finish Checkout	  | Fail                  | Cannot proceed to final checkout page
| TC_220	   | Cancel Checkout 2    | Fail                  | Cannot proceed to final checkout page
| TC_221 	   | Back Home			  | Fail                  | Cannot successfully checkout
| TC_222       | Navigate to Item     | Fail                  | Item images on products page are incorrect, no item link navigates to the correct page, Fleece link navigates to an item not found page
| TC_223       | Back to Products     | Pass                  | Navigation back to product page successful
| TC_224       | Item Information     | Fail                  | All item images on product page incorrect, all prices are correct

| TC_301       | Valid Login          | Pass             	  | User successfully logged in and brought to product page, long load time after clicking "Login"                                                
| TC_302       | Invalid Login        | Pass                  | Username/Password mismatch error correctly displays
| TC_303       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_304	   | Sort Items (Z to A)  | Pass                  | Items correctly sorted, long load time after clicking the sorting option
| TC_305	   | Sort Items (A to Z)  | Pass                  | Items correctly sorted, long load time after clicking the sorting option
| TC_306	   | Sort Items Price Asc | Pass                  | Items correctly sorted, long load time after clicking the sorting option
| TC_307	   | Sort Items Price Desc| Pass	              | Items correctly sorted, long load time after clicking the sorting option
| TC_308       | Add Item to Cart     | Pass                  | Items successfully added to cart
| TC_309       | Remove Item          | Pass                  | Items successfully removed from cart
| TC_310	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_311       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_312	   | Return from Cart	  | Pass                  | Navigation from cart successful, long load time after clicking "Continue Shopping"
| TC_313	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart
| TC_314	   | Valid Info 		  | Pass                  | Checkout process proceeds successfully, though the only check is that the fields are not empty, not that they are valid
| TC_315	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_316	   | Empty Last Name 	  | Pass                  | Empty last name field error correctly displays, though empty first name error has priority
| TC_317	   | Empty Postal Code    | Pass                  | Empty postal code field error correctly displays, though the previous error both have priority
| TC_318	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_319	   | Finish Checkout	  | Pass                  | Full checkout successful, though can be done with an empty cart
| TC_320	   | Cancel Checkout 2    | Pass                  | Navigation back to product page successful
| TC_321 	   | Back Home			  | Pass                  | Navigation back to product page successful, long load time after clicking "Back Home"
| TC_322       | Navigate to Item     | Pass                  | Navigation to correct item page is successful
| TC_323       | Back to Products     | Pass                  | Navigation back to product page successful, long load time after clicking "Back to Prodcuts"
| TC_324       | Item Information     | Pass                  | All information is correct

| TC_401       | Valid Login          | Pass             	  | User successfully logged in and brought to product page                                                                    
| TC_402       | Invalid Login        | Pass                  | Username/Password mismatch error correctly displays
| TC_403       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_404	   | Sort Items (Z to A)  | Fail                  | Error popup when attempting to sort
| TC_405	   | Sort Items (A to Z)  | Fail                  | Item order is A-Z by default, failure because item order cannot be changed to something else then back
| TC_406	   | Sort Items Price Asc | Fail                  | Error popup when attempting to sort
| TC_407	   | Sort Items Price Desc| Fail	              | Error popup when attempting to sort
| TC_408       | Add Item to Cart     | Fail                  | T-shirt items and Jacket item cannot be added to cart, both from products page and item pages
| TC_409       | Remove Item          | Fail                  | No items can be removed from cart, both from the products page and the item pages
| TC_410	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_411       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_412	   | Return from Cart	  | Pass                  | Navigation from cart successful
| TC_413	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart
| TC_414	   | Valid Info 		  | Fail                  | Last name text box cannot be filled, though proceeding to final checkout page still possible
| TC_415	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_416	   | Empty Last Name 	  | Fail                  | Empty last name field does not display and an empty field does not prevent the user from progressing
| TC_417	   | Empty Postal Code    | Pass                  | Empty postal code field error correctly displays, though the previous error both have priority
| TC_418	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_419	   | Finish Checkout	  | Fail                  | "Finish" button not functioning, finishing checkout impossible
| TC_420	   | Cancel Checkout 2    | Pass                  | Navigation back to product page successful
| TC_421 	   | Back Home			  | Fail                  | Cannot successfully checkout
| TC_422       | Navigate to Item     | Pass                  | Navigation to correct item page is successful
| TC_423       | Back to Products     | Pass                  | Navigation back to product page successful
| TC_424       | Item Information     | Pass                  | All information is correct

| TC_501       | Valid Login          | Pass             	  | User successfully logged in and brought to product page                                                                    
| TC_502       | Invalid Login        | Pass                  | Username/Password mismatch error correctly displays
| TC_503       | Empty Fields         | Pass                  | Empty field error correctly displays, though defaults to empty username when both are empty
| TC_504	   | Sort Items (Z to A)  | Pass                  | Items correctly sorted
| TC_505	   | Sort Items (A to Z)  | Pass                  | Items correctly sorted
| TC_506	   | Sort Items Price Asc | Pass                  | Items correctly sorted, even though the displayed item prices are incorrect
| TC_507	   | Sort Items Price Desc| Pass	              | Items correctly sorted, even though the displayed item prices are incorrect
| TC_508       | Add Item to Cart     | Pass                  | Items successfully added to cart
| TC_509       | Remove Item          | Pass                  | Items successfully removed from cart
| TC_510	   | Navigate to Cart     | Pass                  | Navigation to cart successful
| TC_511       | Remove Item from Cart| Pass                  | Items successfully removed from cart
| TC_512	   | Return from Cart	  | Pass                  | Navigation from cart successful
| TC_513	   | Navigate to Checkout | Pass                  | Navigation to checkout successful, though it can be done with an empty cart, "Checkout" button position incorrect
| TC_514	   | Valid Info 		  | Pass                  | Checkout process proceeds successfully, though the only check is that the fields are not empty, not that they are valid
| TC_515	   | Empty First Name	  | Pass                  | Empty first name field error correctly displays
| TC_516	   | Empty Last Name 	  | Pass                  | Empty last name field error correctly displays, though empty first name error has priority
| TC_517	   | Empty Postal Code    | Pass                  | Empty postal code field error correctly displays, though the previous error both have priority
| TC_518	   | Cancel Checkout	  | Pass                  | Navigation back to cart successful
| TC_519	   | Finish Checkout	  | Pass                  | Full checkout successful, though can be done with an empty cart
| TC_520	   | Cancel Checkout 2    | Pass                  | Navigation back to product page successful
| TC_521 	   | Back Home			  | Pass                  | Navigation back to product page successful
| TC_522       | Navigate to Item     | Pass                  | Navigation to correct item page is successful
| TC_523       | Back to Products     | Pass                  | Navigation back to product page successful
| TC_524       | Item Information     | Fail                  | First item image incorrect, all prices on product page incorrect
