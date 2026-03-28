🚢 Titanic Survival Insights Dashboard
📌 Project Overview
هذا المشروع يقدم تحليلًا شاملاً لبيانات ركاب سفينة تايتانيك باستخدام Power BI. الهدف هو فهم العوامل التي أثرت على فرص النجاة واستكشاف الخصائص الديموغرافية والاقتصادية للركاب من خلال لوحة بيانات تفاعلية (Interactive Dashboard).

🛠️ Tools & Technologies Used
Power BI Desktop: للتصميم والعرض البصري.

Power Query: لتنظيف وتحويل البيانات (Data Cleaning & Transformation).

DAX (Data Analysis Expressions): لإنشاء المقاييس (Measures) والمعادلات التحليلية.

Dataset: Titanic dataset (train.csv).

🚀 Key Features & Steps
1. Data Cleaning & Feature Engineering
التعامل مع القيم المفقودة (Nulls) في أعمدة العمر (Age) والكبينة (Cabin).

استخراج الألقاب (Title Extraction): استخراج اللقب (Mr, Mrs, Miss) من الأسماء لفهم الفئات الاجتماعية بشكل أدق.

تجميع الأعمار (Age Grouping): تقسيم الأعمار إلى فئات (Child, Teenager, Adult, Elderly).

حجم العائلة (Family Size): دمج أعمدة SibSp و Parch لمعرفة من سافر وحيداً ومن كان مع عائلة.

2. DAX Measures
حساب Survival Rate %: لمعرفة نسبة النجاة الكلية وتأثرها بالفلاتر.

حساب Total Passengers و Total Survived و Total Deceased.

3. Interactive Visuals
Survival Analysis Page: تركز على نسب النجاة حسب النوع (Sex) والدرجة (Pclass).

Demographics & Economics Page: تعرض توزيع الأعمار، ميناء الصعود (Embarked)، وعلاقة سعر التذكرة بالعمر (Fare vs Age).

Navigation: أزرار للتنقل السلس بين صفحات التقرير.

📊 Key Insights
النساء والأطفال أولاً: كانت نسبة نجاة الإناث أعلى بكثير من الذكور (حوالي 74% مقابل 18%).

تأثير الطبقة الاجتماعية: ركاب الدرجة الأولى (First Class) حصلوا على فرص نجاة أعلى مقارنة بالدرجة الثالثة.

ميناء الصعود: أغلب الركاب صعدوا من ميناء Southampton (S).

📂 Project Structure
Data/: يحتوي على ملف البيانات الخام (train.csv).

Dashboard/: يحتوي على ملف الـ .pbix الخاص ببرنامج Power BI.

Screenshots/: صور توضيحية لشكل لوحة البيانات النهائية.
