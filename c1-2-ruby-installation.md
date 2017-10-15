## ১.২ রুবির ইন্সটলেশন

ম্যাক ও এস \(Mac OSX\) এ রুবি বাই ডিফল্ট পোর্ট হয়। তবে লিনাক্স বেজ্ড এনভাইরনমেন্টে আপনাকে রুবি ইন্সটল করে নিতে হবে। ডিফল্ট আসে না। রুবি অনেক ভাবে ইন্সটল করা যায়। তবে আমি সাপোর্ট করি ভার্সন মেনেজারগুলো ব্যাবহার কের রুবি ইন্সটল করাটা বুদ্ধিমানের কাজ হবে। ভার্সন ম্যানেজারগুলোর কারনে আপনি প্রয়োজন অনেক ভার্সন কনফিগার করতে পারবেন আপনার প্রজেক্টগুলোর সাথে।

একটি সতর্কতা- কোন ভার্সন ম্যানেজার ব্যাবহারকালে _sudo _ব্যাবহার করলে আপনার ভার্সন ম্যানেজারের এনভাইরনমেন্ট মেলফর্মড হতে পারে। পারমিশনগুলো এলোমেলো হয়ে যেতে পারে ফলে অনেক অপ্রত্যাশিত ঘটনাও ঘটতে পারে। তাই কোন ভার্সন ম্যানেজার ব্যাবহার কালে _sudo_ ব্যাবহার করা যাবে না।

রুবিতে সর্বাধিক পরিচিত ভার্সন ম্যানেজরগুলো হলো-

১। আর ভি এম \(RVM- [http://rvm.io\](http://rvm.io\)\)

২। আর বি এন বি \(Rbenv- [https://github.com/rbenv/rbenv/wiki\](https://github.com/rbenv/rbenv/wiki\)\)

RVM ইনস্টলেশন:

আর ভি এম ইন্সটলেশনের আগে আপনাকে নিশ্চিত হতে হবে আপনার এনভারনমেন্টে কার্ল \(Curl\) টুল এবং গিট ইন্সটল আছে কী না। লিনাক্সে আপনি নিচের কমান্ডটি দিয়ে Curl টুল ইন্সটল করতে পারবেন-

> _**sudo apt-get install curl**_

এবং গিট ইনস্টলেশনে জ

> **sudo apt-get install git-all**

গিট এবং কার্ল টুলটি ইন্সটল হয়ে গেলে এইবার আমরা rvm ইন্সটলেশনের দিকে যাবো।

> **gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB**

এবার-

> **\curl -sSL **[https://get.rvm.io](https://get.rvm.io)** \| bash**

উপরের কমান্ডটি ঠিকভাবে একজিকিউট হলে আপনি রুবি ইন্সটলে খুব সহজে করতে পারবেন। নিচের কমান্ডটি দিয়ে আসুন আমরা প্রথম রুবি ইন্সটল করি।

> **rvm install 2.4.2**

এইবার rvm রুবির 2.4.2 বার্সনটি ইন্সটলেশন শুরু করবে। একটু অপেক্ষা করতে হবে পুরোপুরি ইন্সটলেশনের জন্য। যদি সিস্টেমের কোন কিছু লাইব্রেরি মিসিং থাকে যা রুবির বিল্ডের জন্য প্রয়োজন তা rvm নিজে থেকে ইন্সটল করে নিবে।

ইন্সটলেশনটি হয়ে গেলে আপনি এইবার প্রস্তুত রুবি প্রোগ্রামিং ল্যাংগোয়েজটি ব্যাবহারের জন্য। প্রথমে আপনাকে যে কাজটি করতে হবে, তা হলো রুবির ভার্সনটি আগে সিলেক্ট করে নিতে হবে। আপনি চাইলে যেকোন ভার্সন সিলেক্ট করতে পারেন এবং সেটিকে ডিফল্ট হিসেবে আপনার ও এস \(Operating System\) এ সেট করতে পারেন।

ভার্সন সিলেকশনের জন্য-

> **rvm use 2.4.2**

এবং কোন ভার্সনকে ডিফল্ট হিসেবে সেট করার জন্য-

> **$ rvm --default use 2.1.1**

এই বার আসুন যাচাই করে নেই ভার্সনটি পরিবর্তন হয়েছে কী না।

> **$ ruby -v**

একটা জিনিষ মনে রাখতে RVM ব্যাবহার করে আপনি আপনার সিস্টেমের ডিফল্ট রুবিতেও সুইচ করতে পারবেন। যেমন আপনি যদি নিচের কমান্ডটি চালান-

> **$ rvm use system**
>
> **$ ruby -v **






