# Data-Analysis-learn# أول تجربة كود بايثون في مشروعي الجديد
print("Hello World! This is Ruba Ashi.")
# استدعاء مكتبة تحليل البيانات الشهيرة بايثون
import pandas as pd

# إنشاء جدول بيانات صغير يحتوي على اسم مشروعكِ الجديد وهدفكِ
data = {
    'Project Name': ['Data-Analysis-learn', 'Lavender Website'],
    'Status': ['Learning Python', 'Published on GitHub Pages'],
    'Goal': ['Future Data Analyst 📊', 'Web Developer 💻']
}

# تحويل البيانات إلى جدول منظم (DataFrame) وعرضه
df = pd.DataFrame(data)
print(df)
