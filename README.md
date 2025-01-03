                                                      TO DO LIST APP
                                                      
সংক্ষিপ্ত বিবরণ
এই প্রকল্পটি একটি TO DO অ্যাপ্লিকেশন যা Swift ব্যবহার করে Xcode-এ তৈরি করা হয়েছে। অ্যাপটি ব্যবহারকারীদের দৈনন্দিন কাজগুলো সহজ এবং ব্যবহারবান্ধব ইন্টারফেসের মাধ্যমে তৈরি, পরিচালনা এবং ট্র্যাক করার সুযোগ দেয়। প্রকল্পটি ডেটা সংরক্ষণের জন্য Firebase Firestore এর সাথে একত্রিত এবং ব্যবহারকারী প্রমাণীকরণ, কাজ তৈরি, মুছে ফেলা এবং কাজ দেখার মতো প্রয়োজনীয় কার্যকারিতা সমর্থন করে।

                                                         ফিচারসমূহ
ব্যবহারকারী প্রমাণীকরণ:

লগইন এবং রেজিস্ট্রেশন সিস্টেম।
সুরক্ষিত ইমেইল এবং পাসওয়ার্ড ব্যবস্থাপনা।
কাজ ব্যবস্থাপনা:

কাজের বর্ণনা এবং সময়সীমা সহ নতুন কাজ যোগ করা।
তালিকা ফরম্যাটে কাজ দেখা।
কাজ মুছে ফেলার জন্য সুইপ অ্যাকশন।
কাজ সম্পন্ন হিসাবে চিহ্নিত করার সুযোগ।
প্রোফাইল ব্যবস্থাপনা:

ব্যবহারকারীর প্রোফাইল তথ্য যেমন নাম, ইমেইল এবং সদস্যপদ শুরুর তারিখ প্রদর্শন।
নিরাপদ লগআউটের বিকল্প।
দৈনিক কাজ:

নির্দিষ্ট দিনের জন্য কাজগুলোর জন্য একটি ডেডিকেটেড ভিউ।
কাজের সময় বিশ্লেষণ করে সংগঠিতভাবে প্রদর্শন।
Firestore ইন্টিগ্রেশন:

Firebase Firestore ব্যবহারকারীর তথ্য এবং কাজ সংরক্ষণের জন্য ব্যবহৃত।
রিয়েল-টাইম আপডেট ব্যবহারকারীদের মধ্যে সমন্বয় নিশ্চিত করে।
রেসপনসিভ UI:

লাইট এবং ডার্ক মোড সমর্থন।
ক্লিন এবং ব্যবহারবান্ধব নেভিগেশন একটি বটম ট্যাব বার ব্যবহার করে।
ব্যবহৃত প্রযুক্তি
Swift: iOS ডেভেলপমেন্টের জন্য প্রোগ্রামিং ল্যাংগুয়েজ।
Xcode: অ্যাপ তৈরির জন্য ব্যবহৃত ইন্টিগ্রেটেড ডেভেলপমেন্ট এনভায়রনমেন্ট।
Firebase Firestore: ডেটাবেস এবং প্রমাণীকরণের জন্য Backend as a Service (BaaS)।
স্ক্রিনশটসমূহ
প্রোফাইল ভিউ: ব্যবহারকারীর প্রোফাইল ডিটেইলস এবং লগআউট অপশন প্রদর্শন করে।
টুডু লিস্ট ভিউ: কাজের তালিকা দেখায় এবং কাজ যোগ ও মুছে ফেলার অপশন দেয়।
দৈনিক কাজ ভিউ: নির্দিষ্ট দিনের জন্য কাজ তালিকা দেখায়।
লগইন ভিউ: ইমেইল এবং পাসওয়ার্ড দিয়ে লগইন করার সুবিধা।
প্রকল্পের গঠন
ToDo_77_70_89

                                                             Models:
ToDoListItem.swift
অন্যান্য মডেল।
ViewModels:
DailyTasksViewModel.swift
LoginViewModel.swift
ProfileViewModel.swift
অন্যান্য ভিউমডেল।
Views:
ToDoListView.swift
ProfileView.swift
LoginView.swift
DailyTasksView.swift
অন্যান্য ভিউ।
Firebase Integration:
GoogleService-Info.plist
Assets:
অ্যাপ আইকন।
Extensions
Launch Screen
ইনস্টলেশন
রেপোজিটরি ক্লোন করুন:
bash
Copy code
git clone <repository-url>  
প্রজেক্টটি Xcode-এ ওপেন করুন।
সর্বশেষ Xcode ভার্সন নিশ্চিত করুন।
Firebase সেটআপ করুন:
GoogleService-Info.plist ফাইলটি প্রজেক্টে যোগ করুন।
Firebase Firestore এবং Authentication কনফিগার করুন।
অ্যাপটি সিমুলেটর বা ফিজিক্যাল ডিভাইসে রান করুন।

                                                    ব্যবহারবিধি
অ্যাপে রেজিস্টার বা লগইন করুন।
ট্যাবগুলোর মধ্যে নেভিগেট করুন:
আপনার প্রোফাইল দেখুন।
আপনার কাজগুলো পরিচালনা করুন।
দৈনিক কাজ চেক করুন।
প্রয়োজনে কাজ যোগ, মুছে ফেলা বা সম্পন্ন করুন।
ভবিষ্যৎ উন্নতি পরিকল্পনা
কাজের রিমাইন্ডারের জন্য নোটিফিকেশন যুক্ত করা।
কাজের অগ্রাধিকার ব্যবস্থা যোগ করা।
অন্যান্য ব্যবহারকারীদের সাথে কাজ শেয়ারের সুবিধা।
ব্যবহারকারীর আচরণ ট্র্যাক করার জন্য অ্যানালিটিক্স ইন্টিগ্রেশন।
উপলব্ধি
এই প্রকল্পটি একটি দলগত প্রচেষ্টায় তৈরি হয়েছে। বিশেষ ধন্যবাদ সমস্ত সহযোগীদের যাঁরা অ্যাপটি তৈরি ও পরীক্ষা করার জন্য কঠোর পরিশ্রম করেছেন।

<img width="1379" alt="Screenshot 2024-12-30 at 11 55 38ΓÇ»PM" src="https://github.com/user-attachments/assets/33fcd8a9-b986-49c5-858f-c5cde3447879" />
<img width="1121" alt="Screenshot 2024-12-30 at 4 08 31ΓÇ»PM" src="https://github.com/user-attachments/assets/95adad51-3ed1-492c-83c4-9935a35a2f5d" />
<img width="1099" alt="Screenshot 2024-12-30 at 3 58 29ΓÇ»PM" src="https://github.com/user-attachments/assets/82fc8590-3349-4b26-a803-7031de4d064f" />
<img width="406" alt="Screenshot 2024-12-29 at 4 53 15ΓÇ»PM" src="https://github.com/user-attachments/assets/cbb72a4c-93de-4b1a-8546-fadc1b076066" />
<img width="490" alt="Screenshot 2024-12-29 at 1 27 55ΓÇ»PM" src="https://github.com/user-attachments/assets/04af68b3-6b68-40f3-9a24-81e3e6aac5a7" />
<img width="523" alt="Screenshot 2024-12-29 at 1 25 00ΓÇ»PM" src="https://github.com/user-attachments/assets/0fa1005f-32b0-4c2c-984a-609dd7baa8b7" />
<img width="1397" alt="Screenshot 2024-12-29 at 1 14 24ΓÇ»PM" src="https://github.com/user-attachments/assets/246a2ff4-36df-4618-9d33-7c859d800fbf" />
![Screenshot 2024-12-29 at 1 10 16ΓÇ»PM](https://github.com/user-attachments/assets/95e5fa71-cb28-4761-8ee5-2ccfbc1d6bcf)
<img width="1318" alt="Screenshot 2024-12-31 at 12 22 43ΓÇ»AM" src="https://github.com/user-attachments/assets/dc523884-ea6f-4f2a-b2e4-327ffdc3d48f" />
<img width="1372" alt="Screenshot 2024-12-31 at 12 07 32ΓÇ»AM" src="https://github.com/user-attachments/assets/ff349bc9-a0a5-4f81-ad86-5e26bbdae90c" />
<img width="1680" alt="Screenshot 2024-12-31 at 11 52 14ΓÇ»PM" src="https://github.com/user-attachments/assets/12870ae9-6ac7-4bbb-8f2f-a98baa15bebf" />
<img width="1680" alt="Screenshot 2024-12-31 at 11 52 06ΓÇ»PM" src="https://github.com/user-attachments/assets/d45f589f-5cba-4bba-a090-52fe132efc58" />
<img width="401" alt="Screenshot 2024-12-31 at 11 51 43ΓÇ»PM" src="https://github.com/user-attachments/assets/1b120847-7ecb-42cf-8829-2edd27bd85a6" />
<img width="403" alt="Screenshot 2024-12-31 at 11 50 16ΓÇ»PM" src="https://github.com/user-attachments/assets/ff38d4c3-6046-439b-9118-b194673bb03e" />
<img width="394" alt="Screenshot 2024-12-31 at 1 02 13ΓÇ»AM" src="https://github.com/user-attachments/assets/3386aa94-bc57-41a5-ad1c-ffa8d6a1bfdb" />
<img width="1680" alt="Screenshot 2024-12-31 at 1 01 01ΓÇ»AM" src="https://github.com/user-attachments/assets/fe411c4a-4c82-4eae-bb56-146496df867c" />
