abbreviation.md
the most python modules used en arabic :
# ========== Standard Modules ==========

import math
# math: تقدم دوال رياضية مثل الجذر، الأس، الجيب، إلخ
print(math.sqrt(16))        # √16 = 4
print(math.pow(2, 3))       # 2^3 = 8
print(math.sin(math.pi/2)) # sin(π/2) = 1

import random
# random: لتوليد أرقام عشوائية أو اختيار عشوائي من قائمة
print(random.randint(1, 10))     # عدد عشوائي من 1 إلى 10
print(random.choice(['a', 'b', 'c']))  # اختيار عنصر عشوائي

import datetime
# datetime: للعمل مع التواريخ والأوقات
now = datetime.datetime.now()
print(now)
print(now.strftime("%Y-%m-%d %H:%M:%S"))  # تنسيق التاريخ والوقت

import os
# os: للتعامل مع نظام الملفات والمجلدات
print(os.getcwd())     # طباعة المسار الحالي
print(os.listdir())    # قائمة الملفات في المسار الحالي

import sys
# sys: للتعامل مع نظام التشغيل والمعاملات الخارجية
print(sys.platform)     # نوع النظام (مثلاً: win32 أو linux)

import time
# time: لتأخير التنفيذ أو التعامل مع الوقت
time.sleep(1)           # إيقاف البرنامج لمدة ثانية
print(time.time())      # الوقت الحالي
