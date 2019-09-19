# Answers Summary

## Questions to Answer
Please answer the following 4 questions for each unit test:
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
2. Why the test failed at first?
3. Why you corrected the test that way?
4. Do you have further questions on this knowledge point?

## BooleanOperatorsTest
#### should_perform_logical_boolean_operations
1. This is for me to learn the differences of different logical operators that are commonly encountered and used in Java.
https://www.geeksforgeeks.org/bitwise-operators-in-java/
https://www.tutorialspoint.com/Java-Bitwise-Operators
2. The expected result is blank.
3. Corrected the test by putting/supplementing the correct answer.
4. None.

#### should_do_bitwise_and_boolean_operation
1. For me to familiarize more in other number systems since the commonly used is Decimal, This test introduced me to Binary and Hexadecimal
https://www.mathsisfun.com/binary-decimal-hexadecimal-converter.html
https://www.baeldung.com/java-bitwise-operators
2. It failed because the value and mask values will not result to 0.
3. Have it corrected by converting the value and mask values to binary and do the boolean operation then convert the answer back to Hexadecimal
4. None.

#### should_do_bitwise_or_boolean_operation
1. For me to familiarize more in other number systems since the commonly used is Decimal, This test introduced me to Binary and Hexadecimal
https://www.mathsisfun.com/binary-decimal-hexadecimal-converter.html
https://www.baeldung.com/java-bitwise-operators
2. It failed because the value and mask values will not result to 0.
3. Have it corrected by converting the value or mask values to binary and do the boolean operation then convert the answer back to Hexadecimal
4. None.


#### should_do_bitwise_not_operation
1. For me to familiarize more in other number systems since the commonly used is Decimal, This test introduced us to Binary and Hexadecimal
https://www.mathsisfun.com/binary-decimal-hexadecimal-converter.html
https://www.baeldung.com/java-bitwise-operators
2. It failed because the value and mask values will not result to 0.
3. Have it corrected by converting the value variable to binary and do the boolean operation then convert the answer back to Hexadecimal
4. None.

## CharTypeTest
#### should_describe_escaped_chars
1. This is for me to familiarize more with the escaped characters being used in Java since most are using only the \n when we are studying at school.
https://en.wikipedia.org/wiki/Escape_character
2. It failed because the intial value of variables are just space.
3. Corrected it by supplementing the correct value of those variables with slash(\) and the character.
4. None.

## FloatingTypeTest
#### should_not_get_rounded_result_if_convert_floating_number_to_integer
1. This test is for me to understand and how to use typecasting.
https://www.baeldung.com/java-type-casting
2. It failed because the real expected value is not reaching the Max Value of Integer.
3. Corrected it by evaluating the floatingPointNumber variable and get the whole number part or integer part only. 
4. None.

#### should_not_round_number_when_convert_to_integer
1. This test is for me to understand and how to use typecasting. (same as above)
https://www.baeldung.com/java-type-casting
2. It failed because the real expected value is not reaching the Max Value of Integer.
3. Corrected it by evaluating the floatingPointNumber variable and get the whole number part or integer part only. 
4. None.

#### should_round_number
1. This is for me to further utilize methods such as Math
https://www.geeksforgeeks.org/java-math-round-method-example/
2. It failed at first because the variable has long max value.
3. Corrected it by using Math.Round the floatingPointNumber variable.
4. None.

####should_judge_special_double_cases
1. This is for me to be familiarized with the Double and other methods that is being used together with it. 
https://www.javatpoint.com/java-double-isinfinite-method
2. It failed because the in isNan and isInfinite method are only throwing a not implemented exception.
3. Corrected it that way by using isInfinite and isNan methods.  
4. None.

## IntegerTypeTest
#### should_get_range_of_primitive_int_type
http://www.java2s.com/Tutorial/Java/0040__Data-Type/IntegerMAXMINVALUE.htm
1. This is for me to familiarize and utilize more on Integer and its methods.
2. It failed because the value in maximumSymbol and minimumSymbol is not correct.
3. Corrected it by evaluating this whole method and used Integer methods max and min values.
4. None.

#### should_get_range_of_primitive_short_type
1. This is for me to familiarize and utilize more on Short and its methods.
http://www.java2s.com/Tutorials/Java/Data_Types/Find_out_the_min_value_max_value_and_size_of_Java_Short_types.htm
2.  It failed because the value in maximumSymbol and minimumSymbol is not correct.
3. Corrected it by evaluating this whole method and used Short methods max and min values.
4. None.

#### should_get_range_of_primitive_long_type
1. This is for me to familiarize and utilize more on Long and its methods.
2.  It failed because the value in maximumSymbol and minimumSymbol is not correct.
3. Corrected it by evaluating this whole method and used Long methods max and min values.
4. None.

#### should_get_range_of_primitive_byte_type
1. This is for me to familiarize and utilize more on Byte and its methods.
2.  It failed because the value in maximumSymbol and minimumSymbol is not correct.
3. Corrected it by evaluating this whole method and used Byte methods max and min values.
4. None.

#### should_overflow_silently
1. This is for me to deepen my knowledge regarding the flowing and overflowing of data
https://dzone.com/articles/overflow-and-underflow-data
2. It failed because the expected value is not correct.
3. Corrected it by using Integer Min Value because if it overflow, it will go back to the minimum integer value. 
4. None.

#### should_underflow_silently
1. This is for me to deepen my knowledge regarding the flowing and overflowing of data
https://dzone.com/articles/overflow-and-underflow-data
2. It failed because the expected value is not correct.
3. Same as above case as above. While here, I used of Integer Max Value.
4. None.


#### should_take_care_of_number_type_when_doing_calculation
1. This is for me to familiarize rerding with Order of Precedence and usage of Delta.
https://introcs.cs.princeton.edu/java/11precedence/
https://stackoverflow.com/questions/5686755/meaning-of-epsilon-argument-of-assertequals-for-double-values
2. It failed because the value in expected results are not correct. It is above in the limit set in delta in this method.
3. Corrected it by using the evaluating the result values guided by the order of precedence. 
4. None.

#### should_truncate_number_when_casting
1. This is for me to familiarize more on typecasting between integer to short.
2. It failed because the value in expected is not correct.
3. Corrected it by evaluating the integer values to decimal then typecast to short then have the expected value.
4. None.

#### should_increment
1. This knowledge point is for the usage of increment and postfix.
http://cs-fundamentals.com/java-programming/java-increment-decrement-operators.php
2. It failed because expected results are not correct.
3. Evaluated the values then add it to one as following the definition of incrementation and postfix.
4. None.

#### should_increment_2
1. This knowledge point is for the usage of increment and prefix.
http://cs-fundamentals.com/java-programming/java-increment-decrement-operators.php
2. It failed because expected results are not correct.
3. Evaluated the values then already add it to one as following the definition of incrementation and prefix.
4. None.

#### should_throw_exception_when_overflow
1. This is for familiarization of throwing exceptions 
2. It failed because add method is not properly defined and implemented.
3. Corrected it by using OR for min and max values of sum then it will be catched by an Arithmethic exception when it either overflow or underflow.
4. None.

#### just_prevent_lazy_implementation
1. More utilization of method calling.
2. t failed because add method is not properly defined and implemented.
3. Corrected it by using OR for min and max values of sum then it will be catched by an Arithmethic exception when it either overflow or underflow. If no issue with values, then it will just get the sum.
4. None.