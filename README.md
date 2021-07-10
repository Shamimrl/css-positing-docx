
# Css Positioning Properties

A brief description of the behavour of RELATIVE and ABSOLUTE property of css.


## Acknowledgements

 - [BY Tawhid](https://github.com/devtawhid)
 - [And Shamim](https://github.com/shamimrl)

 Css RELATIVE property works with 
 In Bangla 

 সিএসএস পসিশনিং প্রপার্টি relative কাজ করে এর এর বর্তমান অবস্থানের সাপেক্ষে ( এর immediate parent এর সাপেক্ষে নয়)
আমরা চাইলে এখানে বেশ কয়েক জেনারেশন ধরে রিলিটি প্রপার্টি ব্যাবহার করতে পারি। যেমন অনেক ক্ষেত্রে আমাদেরকে কোন এইচটিএমএল এলিমেন্ট এর চাইল্ড এর চাইল্ড কে পজিশনিং করা লাগতে পারে। 
https://codepen.io/shamim-the-sans/pen/QWvEPzQ?editors=1100
যেমন উদাহরণে আমরা 3 জেনারেশন ধরে relative প্রপার্টি ব্যাবহার করেছি ( grandpa> father> child)
সবাইকে RELATIVE করে সরানোর চেষ্টা করা হয়েছে।



অন্যদিকে absolute property কাজ করে এর parent এর সাপেক্ষে যার positioning করা আছে(relative or absolute দুই ক্ষেত্রেই)।
উদাহরণ:https://codepen.io/shamim-the-sans/pen/XWNGebZ
 
## Screenshots

![App Screenshot](https://prnt.sc/19qw6j7)

-------------------------------------------------------------------------------End--------------------------------------------------------------------------------------------
# Css Transition Properties

A brief description of the behavour of TRANSITION on hover.

Transition property এর কাজের ধরণ কিছু টা এরকম। 

উদাহরণ: https://codepen.io/shamim-the-sans/pen/abWmmqP?editors=1100

1. Only in element: যদি element এর ভিতর transition দেয়া‌ থাকে তাহলে সে on hover and after hover দুই সময় ই control করবে। 
উদাহরণ: উপরের উদাহরণের btn1

2.Only in hover: যদি শুধু hover এ দেয়া থাকে তাহলে শুধু আসার সময়ের অবস্থা নিয়ন্ত্রণ হবে। তবে ফিরে আসার সময় দ্রুত চলে আসবে একটু ও দাঁড়াবে না বা আস্তে আস্তে আসবে না।
উদাহরণ: উপরের উদাহরণের btn2

3.Both in element and hover: যদি element এবং hover দুই জায়গাতেই থাকে তাহলে hover করলে hover এর transition value follow করবে আর আগের অবস্থায় আসার সময় element এর transition value follow করবে ।
উদাহরণ: উপরের উদাহরণের btn3
