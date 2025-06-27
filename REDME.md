with open("README.md", "w", encoding="utf-8") as f:
    f.write("""\
# تحليل المشاعر من تعليقات باللغة العربية باستخدام AraBERT

🎯 **وصف المشروع:**
هذا المشروع يهدف إلى تحليل المشاعر في تعليقات مكتوبة باللغة العربية، وتحديد ما إذا كانت التعليقات إيجابية أو سلبية، باستخدام نموذج التعلم العميق AraBERT.

📦 **المكتبات والأدوات المستخدمة:**
- Python
- Google Colab
- Pandas, Numpy
- Transformers (HuggingFace)
- AraBERT model (aubmindlab/bert-base-arabertv02)
- Scikit-learn

📁 **محتوى المشروع:**
- `sentiment_analysis_project.ipynb`: كود المشروع الكامل للتدريب والتنبؤ.
- `arabic_sentiment_dataset.csv`: بيانات التدريب (تعليقات + مشاعرها).
- `arabic_sentiment_results.csv`: النتائج بعد التنبؤ.

📊 **خطوات العمل:**
1. تحميل البيانات.
2. تنظيف ومعالجة النصوص.
3. تحميل نموذج AraBERT.
4. تحويل النصوص إلى تمثيلات رقمية باستخدام tokenizer.
5. تدريب النموذج على البيانات.
6. اختبار النموذج وتوليد النتائج.
7. تحليل الأداء بدقة و Recall و F1 Score.

🚀 **النتائج:**
النموذج أظهر دقة جيدة في تصنيف المشاعر خاصة ضمن البيانات المتوازنة.

🧠 **أسباب اختيار AraBERT:**
- لأنه من أقوى نماذج اللغة العربية.
- مدرب على بيانات عربية منوعة (أخبار، تويتر، الخ...).
- مناسب تماماً لمهام تحليل النصوص والتصنيف.

📌 **ملاحظات إضافية:**
- المشروع تم تنفيذه بالكامل على Google Colab للاستفادة من موارد الحوسبة السحابية.
- لم يتم استخدام جهاز محلي لأن المواصفات محدودة.
- المشروع قابل للتطوير لاحقاً باستخدام بيانات حقيقية من منصات اجتماعية.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ibrahimqreet/sentiment-analysis/blob/main/sentiment_analysis_project.ipynb)

📫 **للتواصل / الدعم:**
يمكن مراسلتي عبر GitHub لأي استفسار أو اقتراح.

"ibrahim.qreet97@gmail.com"")
