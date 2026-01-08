# device-promo-abuse-detection
SQL, Power BI and Python based fraud detection project to identify promo abuse using user behavior analysis.

## 🔴 Problem Statement 
Online platforms that offer new-user promotions (such as discounts, cashback, or free deliveries) often face significant revenue leakage due to promo abuse. A common abuse pattern occurs when users create multiple accounts to repeatedly claim benefits intended for first-time users.

#### Traditional fraud-prevention checks typically rely on phone numbers, email IDs, to identify unique users. However, these methods are easily bypassed because:
<br> Phone numbers can be changed or obtained easily
<br> Email addresses can be created in seconds
<br> Users can log out and re-register with minimal effort

As a result, the same individual can appear as multiple “new users” in the system.

#### This creates a challenge for platforms because:
<br> Promo costs increase without genuine customer acquisition
<br> Marketing metrics become inaccurate
<br> Legitimate users are indirectly affected due to stricter promo policies

Therefore, the key challenge is to identify and link accounts that appear different at the user level but originate from similar behavioral or device-level patterns, enabling the platform to detect and prevent promo abuse at scale.
