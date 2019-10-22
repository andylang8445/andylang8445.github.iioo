---
title:  "Arrays Documentation"
date:   2019-10-06 23:13:24
categories:
- Java
- School
- Programming
tags:
- Java
- Study
- Programing
- School
---
<h1>Class Arrays</h1>
<hr>

<h1>Method Summary</h1>
  <table>
   <tr> <th><b>Modifier and Type</b></th> <th>Method and Description</th></tr>
   <tr> <th><b>public static String[]</b></th> <th>createEmptyStringArray:<br><i>Creates the String array and return created array</i></th></tr>
  </table>
<hr>
<h1>Method Detail</h1>
<h4>makeArray</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] makeArray:</b><br><i>Creates the new integer array and return created array</i></th> <th><b>int array_size:</b><br><i>The size of the array the user want to create</i></th> <th><i>Created int type array with Parameters</i></th> </tr>
</table>

<h4>user_defined_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] user_defined_array:</b><br><i>Creates the new integer array with user defined values and return the array using makeArray method</i></th> <th><b>NA</b><br></th> <th><i>Created int type array with value that user entered</i></th> </tr>
</table>

<h4>random_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] random_array:</b><br><i>Creates the new integer array with random values and return the array using makeArray method</i></th> <th><b>NA</b><br></th> <th><i>Created int type array with random value</i></th> </tr>
</table>

<h4>print_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static void print_array:</b><br><i>Print the values of integer array from parameter</i></th> <th><b>int[] array:</b><br><i>The array the user wants to print to the screen and file</i></th> <th><i>Created int type array with value</i></th> </tr>
</table>

<h4>search_value</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int search_value:</b><br><i>Print the values of integer array from parameter</i></th> <th><b>int[] array:</b><i>The array looking for the value</i><b>int target:</b><i>The value that the program is looking for</i><b>boolean mode:</b><i>Select if the user wants to print out every log or not</i><br></th> <th><i>if the value exists in the array, return the location and if not, return -1</i></th> </tr>
</table>

<h4>element_count</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static void element_count:</b><br><i>return the number of the specific element provided by the parameter that appears in the array</i></th> <th><b>int[] array:</b><i>The array looking for the value</i><b>int target:</b><i>The value that the program is looking for</i><br></th> <th><i>return the number of the element appears in the array</i></th> </tr>
</table>

<h4>change_size_of_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] change_size_of_array:</b><br><i>return the new array with all the values from original array but with different size</i></th> <th><b>int[] original_array:</b><i>The original array that the program is resizing</i><b>int operation:</b><i>Decides if the program is expanding the size or making it smaller</i><b>int hole:</b><i>Set the location of the empty spot when the program is expanding the size of the array</i><br></th> <th><i>return the new array that is resized from the original array</i></th> </tr>
</table>

<h4>insert_element</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] insert_element:</b><br><i>return the new array with all the values from original array and additional value using change_size_of_array method</i></th> <th><b>int[] array:</b><i>The original array that the program is inserting the value to</i><b>int target:</b><i>the value that the program is inserting to the array</i><b>int index:</b><i>The location that the program is inserting the value into the array</i><br></th> <th><i>return the new array with the value inserted to the original array</i></th> </tr>
</table>

<h4>selection_sort_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] selection_sort_array:</b><br><i>return the sorted array of the original array</i></th> <th><b>int[] array_original:</b><i>The original array that the program is sorting using the values using selection sort algorithm</i><b>boolean respond_option:</b><i>select if the program is printing the log of the operation or not</i><br></th> <th><i>return the sorted array</i></th> </tr>
</table>

<h4>largest_element</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int largest_element:</b><br><i>return the largest number in array</i></th> <th><b>int[] array:</b><i>The array that the program is looking for the largest value</i><br></th> <th><i>return the maximum value in the array</i></th> </tr>
</table>

<h4>smallest_value</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int smallest_value:</b><br><i>return the smallest number in array</i></th> <th><b>int[] array:</b><i>The array that the program is looking for the smallest value</i><br></th> <th><i>return the minimum value in the array</i></th> </tr>
</table>

<h4>delete_element</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] delete_element:</b><br><i>return the new array with all the values from original array and the selected value deleted using change_size_of_array method and search_value method</i></th> <th><b>int[] array:</b><i>The original array that the program is deleting the value from</i><b>int target:</b><i>the value that the program is deleting from the array</i><br></th> <th><i>return the new array with the value inserted to the original array</i></th> </tr>
</table>

<h4>make_copied_array</h4>
<table>
<tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static int[] make_copied_array:</b><br><i>return the new array with all the values from original array</i></th> <th><b>int[] array:</b><i>The original array that the program is copying the value from</i><br></th> <th><i>return the new array with the identical value copied from the original array</i></th> </tr>
</table>




<!--String-->
 <h4>createEmptyStringArray</h4>
<table>
 <tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
<tr> <th><b>public static String[] createEmptyStringArray:</b><br><i>Creates the String array and return created array</i></th> <th><b>int array_size:</b><br><i>The size of the array the user want to create</i></th> <th><i>Created String type array with Parameters</i></th> </tr>
</table>

<h4>printArray</h4>
<table>
 <tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
 <tr> <th><b>public static void printArray:</b><br><i>Prints the String array from parameter</i></th> <th><b>String[] array:</b><br><i>The String array that is being required to print</i></th> <th><i>N/A</i></th> </tr>
</table>

<h4>array_contains</h4>
<table>
 <tr> <th><b>Method Summary</b></th> <th><b>Parameters</b></th> <th><b>Return</b></th> </tr>
 <tr> <th><b>public static void array_contains:</b><br><i>Prints if String array contains the String element</i></th> <th><b>String[] array:</b><br><i>The String array that is being searched from</i><br>String element:<br><i>The String element that the method is looking for in the array</i></th> <th><i>N/A</i></th> </tr>
</table>
