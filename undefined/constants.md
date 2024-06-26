# কন্সট্যান্টস

কন্সট্যান্ট মানে ফিক্সড ভ্যালু । সহজ ভাবে বলা যায়, যার ভ্যালু প্রোগ্রাম এক্সিকিউসনের সময় চেঞ্জ হয় নাহ। কন্সট্যান্ট যে কোন ব্যাসিক ডাটা টাইপের হতে পারে। সাধারণত সি প্রোগ্রামিং এ চার ধরনের কন্সট্যান্ট দেখা যায়।

| Constant | Type of value stored |
| :--- | :--- |
| Integer Constant | যে সকল কন্সট্যান্ট ইন্টিজার ভ্যালু স্টোর করে। |
| Floating Constant | যে সকল কন্সট্যান্ট ফোল্টিং ভ্যালু স্টোর করে। |
| Character Constant | যে সকল কন্সট্যান্ট ক্যারেক্টার ভ্যালু স্টোর করে। |
| String Constant | যে সকল কন্সট্যান্ট স্ট্রিং ভ্যালু স্টোর করে। |

এছাড়া ইনুমেরশন\(enumeration or enum\) নামে এক ধরনের কন্সটেন্ট রয়েছে। প্রতি টাইপের কন্সট্যান্টস নিয়ে পরবর্তিতে আমরা বিস্তারিত আলোচনা করব উদাহরনসহ। এখন আমরা দেখবো কিভাবে কন্সট্যান্স ডিক্লেয়ার করা হয়।

## ডিক্লেয়ারিং কন্সট্যান্টস

সি প্রগ্রামিং এ সাধারনত দুই ভাবে কন্সট্যান্টস ডিক্লেয়ার করা যায় -

1. \#define প্রিপ্রসেসর ব্যবহার করে। 
2. const কিওয়ার্ড ব্যবহার করে। 

## _\#define প্রিপ্রসেসর_

কিভাবে \#define প্রিপ্রসেসর ব্যবহার করে কন্সট্যান্ট ডিক্লেয়ার করা যায় তার সিন্টেক্স নিচে দেয়া হল -

```text
#define identifier value
```

উদাহরন:

```text
#define PI 3.1416
```

এখানে PI হচ্ছে কন্সট্যান্টের নাম এবং 3.1416 হচ্ছে ভ্যালু।

## _const কিওয়ার্ড_

কিভাবে const কিওয়ার্ড ব্যবহার করে কন্সট্যান্ট ডিক্লেয়ার করা যায় তার সিন্টেক্স নিচে দেয়া হল -

```text
const type variable = value;
```

উদাহরন:

```text
const float PI = 3.1416;
```

উল্লেখ্য যে কন্সট্যান্টকে সাধারনত ক্যাপিটাল লেটার বা বড় হাতের অক্ষরে লিখা হয়। এটা আব্যশিক কোন নিয়ম নাহ, তবে এইভাবে লেখাকে 'Good Practice' হিসেবে ধরা হয়।

নোট: ফিক্সট ভ্যালু হওয়ার কারণে কন্সট্যান্টস লিটারালস নামেও পরিচিত।

