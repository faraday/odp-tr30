==========================================================

-------------------- ODP TR30  Dataset --------------------
  
      http://github.com/faraday/odp-tr30

==========================================================



SUMMARY
==========================================================
ODP TR30 is a dataset designed for evaluating subtopic information retrieval.

It consists of 30 topics, each with a set of about 10 subtopics
and a set of about 100 documents associated with single subtopics.

The topics, subtopics, and their associated documents were selected
from the Open Directory Project (www.dmoz.org), Turkish directories.

The ODP TR30 dataset consists of four files where each row is terminated
by Linefeed (ASCII 10) and fields are separated by Tab (ASCII 9).
The four files are described below.




==================== topics.txt ========================

It contains topic ID and description.

ID	description
1	Bilgisayar > İnternet
2	Bilgisayar > Programlama
3	Bilgisayar > Yazılım
.........
==========================================================



==================== subTopics.txt ========================

It contains subtopic ID (formed by topic ID and subtopic number) and description. 

ID	description
1.1	Bilgisayar > İnternet > Web_Tasarımı_ve_Geliştirme
1.2	Bilgisayar > İnternet > Web
1.3	Bilgisayar > İnternet > Alan_Adları
.........
==========================================================



==================== results.txt ========================

It contains doc ID (formed by topic ID and doc number), url,  title, and snippet.

ID	url	title	snippet
1.1	http://www.goksel.com/bilgiislem/	Göksel Bilgi İşlem	Ücretsiz sayaç, ziyaretçi defteri ve öneri sistemi sunuyor.
1.2	http://www.gezginler.net/	Gezginler	Program indirme,webmaster kaynakları ve anket,ziyaretçi defteri gibi ücretsiz hizmetler sunmaktadır.
1.3	http://www.defter.us/	Defter.us	Ücretsiz ziyaretçi defteri barındırma hizmeti veriyor.
.........
==========================================================



==================== STRel.txt ========================
It contains subtopic ID (formed by topic ID and subtopic number) 
and doc ID (formed by topic ID and doc number).

subTopicID	docID
1.2	1.25
1.2	1.44
1.2	1.55
.........
==========================================================




A FEW STATISTICS ABOUT THE COLLECTION
==========================================================
Number of topics: 30
Number of subtopics: 264
Number of (labeled) documents: 2957
Number of subtopics per topic: 8.8 (min 6, max 10)
Number of docs per topic: 98.566 (min 41, max 121)
Number of docs per subtopic: 11.2 (min 4, max 84)
Words per title: 2.36 (min 1, max 13)
Words per snippet: 11.54 (min 1, max 37)
Characters per title: 16.54 (min 2, max 94)
Characters per snippet: 91.31 (min 6, max 279)
==========================================================




USAGE LICENSE
==========================================================

CC-BY-SA 2010 - Expect where otherwise noted, this work is licensed under:
http://creativecommons.org/licenses/by-sa/3.0/

Author: Çağatay Çallı

The copyright holder and authors can not guarantee the correctness of the data,
its suitability for any particular purpose, or the validity of results based
on the use of the data set, and they assume no responsibility for the content,
legality, reliability, and accuracy of the data.
The data set may be used for any research purposes.

Please acknowledge the use of the data set in publications
resulting from the use of the data set:
Calli C. (2010). ODP TR-30 dataset, http://github.com/faraday/odp-tr30




DOWNLOAD
==========================================================
http://github.com/faraday/odp-tr30


MORE INFO
==========================================================
If you have any further questions or comments, please contact Çağatay Çallı
<cagatay@ceng.metu.edu.tr>

