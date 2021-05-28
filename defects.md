__ID:__  
1  
__Summary:__  
No validation for empty fields in «Контактные данные»  
__Description:__  
Empty input fields on the page «Контактные данные» are not processed.  
__Steps to Reproduce:__  
1. Click button «Продолжить» with empty fields.  

__Expected result:__  
An error message appears.  
__Actual result:__  
No error message and empty fields are not processed.  
__Severity:__  
Medium  
__Priority:__  
Normal


__ID:__  
2  
__Summary:__  
No validation for invalid characters in the field «Полных лет» in «Контактные данные»  
__Description:__  
In the field «Полных лет» on the page «Контактные данные» you can enter any characters other than numbers.  
__Steps to Reproduce:__  
1. Enter the value «д5 !» in the field «Полных лет».
2. Click button «Продолжить».

__Expected result:__  
An error message appears.  
__Actual result:__  
No error message and invalid data is not processed.  
__Severity:__  
Medium  
__Priority:__  
Normal  


__ID:__  
3  
__Summary:__  
«OutMemoryError» in the list of engines in the car «GLC 250D 4MATIC»  
__Description:__  
When selecting the car «GLC 250D 4MATIC», there is an «OutMemoryError» element in the list of engines.  
__Steps to Reproduce:__  
1. Select the car «GLC 250D 4MATIC».
2. Click on the drop-down list of engines.

__Expected result:__  
Engine type in list item.  
__Actual result:__  
«OutMemoryError» in list item.  
__Severity:__  
Major  
__Priority:__  
High  
__Attachments:__  
 <img width="366" alt="image" src="https://user-images.githubusercontent.com/33639319/120005979-1a04c880-bfe1-11eb-8a85-b891873ac173.png">


__ID:__  
4  
__Summary:__  
The car image appears under the main on double-click on the arrow  
__Description:__  
If you double-click on the arrow when selecting a car, the image of the missed car appears under the main one for one second.  
__Steps to Reproduce:__  
1. Double-click on any arrow.

__Expected result:__  
The missed car image does not appear under the main.  
__Actual result:__  
The missed car image appears under the main.  
__Severity:__  
Minor  
__Priority:__  
Low  
__Attachments:__  
 <img width="348" alt="image" src="https://user-images.githubusercontent.com/33639319/120005999-1f621300-bfe1-11eb-846f-dc6f7d19ab3a.png">


__ID:__  
5  
__Summary:__  
No hyphen in the word «тест-драйв» in the header  
__Description:__  
There is no hyphen in the word «тест-драйв» in the header.  
__Steps to Reproduce:__  
1. Pay attention to the header.

__Expected result:__  
Hyphen in the word «тест-драйв».  
__Actual result:__  
No hyphen: «тест драйв».  
__Severity:__  
Minor  
__Priority:__  
Low  
__Attachments:__  
 <img width="355" alt="image" src="https://user-images.githubusercontent.com/33639319/120006033-2721b780-bfe1-11eb-9a1c-b5e40783e68a.png">


__ID:__  
6  
__Summary:__  
Products are not sorted on the page «Для кошек»  
__Description:__  
On the page «Для кошек» products are not sorted by name, price, rating and model.  
__Steps to Reproduce:__  
1. Sort products by name, price, rating and model on the page «Для кошек».

__Expected result:__  
Products are sorted based on the selected sorting.  
__Actual result:__  
Products are not sorted.  
__Severity:__  
Medium  
__Priority:__  
Normal  
__Attachments:__  
<img width="248" alt="image" src="https://user-images.githubusercontent.com/33639319/120006063-2e48c580-bfe1-11eb-9be8-4c8c31fa1faf.png">
