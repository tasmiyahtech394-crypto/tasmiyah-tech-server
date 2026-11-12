# Tasmiyah Tech Server — Android App Project

এই Android Studio project-এ একই অ্যাপ থেকে চারটি ওয়েব প্যানেল খোলা যাবে:

1. Invoice: https://tasmiyah-tech-invoice.netlify.app
2. VSOL OLT: https://103.199.108.200:8082/action/login.html
3. Bijoy CRM: https://crm.bijoy.net/login
4. Carnival CRM: https://reportpanel.carnival.com.bd/areacrm/index.php

## APK বানানোর নিয়ম
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. Android Studio থেকে এই ফোল্ডারটি Open করুন।
3. Gradle Sync শেষ হলে **Build > Build Bundle(s) / APK(s) > Build APK(s)** নির্বাচন করুন।
4. APK পাওয়া যাবে: `app/build/outputs/apk/debug/app-debug.apk`

প্রয়োজন: Android Studio, JDK 17, Android SDK Platform 35।

নোট: এই পরিবেশে Android SDK/Gradle build tool নেই, তাই এখানে APK binary compile করা সম্ভব হয়নি। এটি APK তৈরির জন্য প্রস্তুত Android Studio project। VSOL প্যানেলের IP certificate error-এর জন্য কেবল ওই নির্দিষ্ট host-এর SSL warning-ই allow করা হয়েছে।
