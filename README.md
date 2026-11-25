# Madrasa Poster Maker

একটি বিনামূল্যের, browser-based বাংলা বিদায়ী ছাত্র পোস্টার জেনারেটর। GitHub Pages-এ প্রকাশ করা যায়।

## ফাইল
- `index.html`: সম্পূর্ণ ওয়েব অ্যাপ। আলাদা API বা backend প্রয়োজন নেই।

## লোকালি পরীক্ষা
1. `index.html` ফাইলে ডাবল ক্লিক করে ব্রাউজারে খুলুন।
2. ফরমের তথ্য পরিবর্তন করুন।
3. ছাত্রের ছবি আপলোড করুন।
4. `PNG পোস্টার ডাউনলোড` চাপুন।

ইন্টারনেট সংযোগ থাকলে Google Fonts থেকে Noto Sans Bengali লোড হবে। ইন্টারনেট না থাকলে ডিভাইসের fallback বাংলা ফন্ট ব্যবহার হবে।

## GitHub Pages-এ প্রকাশ
1. https://github.com এ সাইন আপ/লগইন করুন।
2. New repository তৈরি করুন। উদাহরণ: `madrasa-poster-maker`
3. Repository-টি Public রাখুন।
4. `Add file` → `Upload files` দিয়ে `index.html` আপলোড করে Commit changes করুন।
5. Repository-র `Settings` → `Pages` খুলুন।
6. `Build and deployment` অংশে `Deploy from a branch` নির্বাচন করুন।
7. Branch হিসেবে `main` এবং folder হিসেবে `/ (root)` নির্বাচন করে Save করুন।
8. কিছুক্ষণ পর `https://YOUR-USERNAME.github.io/madrasa-poster-maker/` ঠিকানায় সাইট চালু হবে।

## সীমাবদ্ধতা ও নিরাপত্তা
- এই সংস্করণে কোনো সার্ভার, API বা ডেটাবেস নেই।
- ছাত্রের ছবি ব্রাউজারেই প্রসেস হয়; স্বয়ংক্রিয়ভাবে সার্ভারে আপলোড হয় না।
- ফরমের তথ্য পেজ রিফ্রেশ করলে মুছে যাবে।
- সবার তৈরি পোস্টার কেন্দ্রীয়ভাবে সংরক্ষণ বা অ্যাডমিন থেকে দেখা যাবে না।
- Google Fonts লোড করতে ইন্টারনেট লাগে।
- GitHub Pages static hosting; এটি WordPress/PHP backend চালায় না।

## কাস্টমাইজেশন
`index.html`-এর ফরমের default value পরিবর্তন করে মাদ্রাসার নাম/ঠিকানা/ব্যাচের ডিফল্ট তথ্য সেট করা যাবে। ডিজাইনের রং ও মাপ CSS এবং JavaScript canvas drawing অংশে আছে।
