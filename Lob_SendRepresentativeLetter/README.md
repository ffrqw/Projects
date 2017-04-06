# Haoming Zhang<br>
   Email: zanhoming@gmail.com      Phone:424-402-7028
<br>
<br>
## Structure
The project is written in Java and use Maven for management.<br>
#### There are two main files:<br>
   * SendRepresentativeLetter.java
   * pom.xml<br>

## How to input parameters
I choose to Build a `command line program` for the project.<br>
You can input the parameters following the instructions when running the program.<br>
![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/sample_input.png) 

## Outputs
I choose the level is `"administrativeArea1"` and the role is `"deputyHeadOfGovernment"` as the parameters to search the representative.<br> 
When the input is valid, the output of the program is a PDF as a URL.<br>

![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/URL.png)  

When the input is not valid(such as `empty input`, `meaningless input` and `an input indicated a place has no representative`), the output
is `"Failed in Sending Letter"`.<br>
I have tried several testcases, and here are the outputs:<br>

   >* The Output of Sample Input<br>
![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/sample.png) <br>   
[Sample Output PDF URL](https://s3-us-west-2.amazonaws.com/assets.lob.com/ltr_61d64ad5e1beef96.pdf?AWSAccessKeyId=AKIAIILJUBJGGIBQDPQQ&Expires=1494063479&Signature=S0094sjzOxcTIwQlD99%2BXU61m9Q%3D)<br>

   >* The Output of Empty Input<br>
![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/empty.png) <br> 
   
   >* The Output of meaningless input<br>
![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/nonsense.png) <br>

// 过程中的问题
## Correction for Your Website Tutorial
   // 1. data()
In the API Java tutorial, the part 
   [Letter API](https://lob.com/docs/java#letters_create)
may have missed a `.data(data)`. Otherwise the name, "Harry" may not pass into the builder. 
![](https://github.com/ffrqw/Projects/raw/master/Lob_SendRepresentativeLetter/datacrt.png)  
   // 2. part?
   
// 有信心让它的介绍变得更加易懂

// 编程思想<br>

