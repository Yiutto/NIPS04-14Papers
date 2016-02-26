1.Translation to text files: 
==========================
  - The following is a descrption of the preprocessing applied to NIPS2004-2014 papers. 
  - Text was extracted from pdf files using pdfbox-app-1.8.10.jar 
  (http://pdfbox.apache,org/download.html), and write code to achieve.
  - The file 2543-machine-learning-applied-to-perception-decision-images-for-gender-classification.pdf 
    translated to NIPS2004-2543.txt.
  - Fortunately,All pdf files in the NIPS2004-2014 database could be converted to text.
    
  - All text files 
    NIPS2004:	2543~2749 (total texts:207)
    NIPS2005:	2750~2956£¨total texts:207£©
    NIPS2006:	2957~3160£¨total texts:204£©
    NIPS2007:	3161~3377£¨total texts:217£©
    NIPS2008:	3378~3627£¨total texts:250£©
    NIPS2009:	3628~3889£¨total texts:262£©
    NIPS2010:	3890~4181£¨total texts:292£©
    NIPS2011:	4182~4487£¨total texts:306£©
    NIPS2012:	4488~4856£¨total texts:368£©No including text_id:4751
    NIPS2013:	4857~5216£¨total texts:360£©
    NIPS2014:	5222~5632£¨total texts:411£©
	In total texts:3084

    All texts in the package"text(first)"
	
2.Papers preprocessing: 
==========================
   In order to facilitate the document segmentation,
  -Firstly,I deleted the content between the beginning of document and 'Abstract'(included this word),
   and deleted the content after 'References'(included this word).
  -Secondly, I got the English words in the document by Regular Expressions (str='[a-zA-Z]+').
  -Finally, the English words of the second step is to refresh to the original document.
  
   All texts in the package"text(last)"


3.Calculating counts:
==========================
   -docs_authors¡¢docs_words¡¢authors_words counts were extracted using the Matlab code by myself.
   
   
   
   
   -The author's name is same as the original document,and I was not alone to rename.
   -The question that is some author's name in the process of transformation will appear garbled, because 
    of some author's name not the pure English name.Fortunately, only a small part, I can only be negligible.
   
   
If you want to learn more, or need to source code, can contact my QQ-mail:yiutto@qq.com
   
   
   
   
   

