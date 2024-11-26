The tokenizer accepts Urdu text as input.

=======================================================================
- use of start-of-sentence & end-of-sentence words
- Tokenization Logic:
1. The main function uses regular expressions or other linguistic rules specific to Urdu to identify sentence boundaries.
2. This involves looking for punctuation marks typical for ending sentences, such as periods, question marks, or exclamation points, and considering Urdu-specific cases like ending postpositions.

- Once the text is segmented into sentences, the tokenizer returns these as a list or another structured format suitable for downstream processing.
- it also implement Byte-pair-encoding
=======================================================================
This tokenizer be used in applications like sentiment analysis, translation, or other text analysis tasks that require sentence-level processing.
=======================================================================

"""گزشتہ کئی سالوں سے مختلف بحران آتے جاتے رہے لیکن حالیہ آٹا ، چینی سمیت دیگر بحران اچانک پیدا ہوئے اور ان پر جے آئی ٹی تشکیل دے دیں گئیں تاکہ عوام کو ریلیف دیا جاسکے دوسری جانب بجلی ، گیس ، پانی سمیت دیگر بلوں میں کئی سو گنا اضافہ کردیا گیا ، صوبائی و وفاقی وزراء نے اپنے اپنے ایوانوں بحران کے ذمہ دار عناصر کو بے نقاب کرنے کے بجائے سب اچھا ہے کی رپورٹ پیش کیں ساتھ ہی اورنگزیب کی طرح جواب دیا ، حقائق کی قبر ذرا گہری کھودنا ! تاریخی گواہ ہے بقول ماہرین ، مبصرین اور صحافیوں کا کہنا اور لکھنا ہے کہ پگڑی بدل بھائی کی رسم کی آڑ میں نادر شاہ نے محمد شاہ رنگیلا سے کوہِ نور ہیرا حاصل کیا تھا 12 مئی 1739 کی شام دہلی میں زبردست چہل پہل ہے"""

the above text is segmented into:
گزشتہ کئی سالوں سے مختلف بحران آتے جاتے رہے لیکن حالیہ آٹا، چینی سمیت دیگر بحران اچانک پیدا ہوئے۔
ان پر جے آئی ٹی تشکیل دی گئیں تاکہ عوام کو ریلیف دیا جاسکے۔
دوسری جانب بجلی، گیس، پانی سمیت دیگر بلوں میں کئی سو گنا اضافہ کردیا گیا۔
صوبائی و وفاقی وزراء نے اپنے اپنے ایوانوں بحران کے ذمہ دار عناصر کو بے نقاب کرنے کے بجائے سب اچھاہے کی رپورٹ پیش کیں۔
ساتھ ہی اورنگزیب کی طرح جواب دیا، حقائق کی قبر ذرا گہری کھودنا!
تاریخی گواہ ہے بقول ماہرین، مبصرین اور صحافیوں کا کہنا اور لکھنا ہے کہ پگڑی بدل بھائی کی رسم کی آڑ میں نادر شاہ نے محمد شاہ رنگیلا سے کوہِ نور ہیرا حاصل کیا تھا۔
12 مئی 1739 کی شام دہلی میں زبردست چہل پہل ہے۔
