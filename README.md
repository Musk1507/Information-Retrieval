# Information-Retrieval
Information Retrieval- obtains information system resources that are relevant to an information need from a collection of those resources.

In this repository, I have solved
1.Text preprocessing,
2.Inverted Index,
3.Vector Space model,
4.Probability matrix.
 
With the help of the provided 10 text documents namely T1,T2,...T10 for relevant information retrieval.

*PROJECT*:
AUTOMATED ESSAY 
SUMMARIZATION AND GRADING 

Why summarize?
With our busy schedule, we usually prefer to read the 
summary of articles before we decide to hop in for reading 
the entire article. Reading a summary help us to identify the 
interest area, gives a brief context of the story.
Who mainly need it
-
1.Teacher who have to correct 
papers of multiple students.

2.Students and Researchers 
who have to read multiple 
research papers.

3.Foreign University 
Admissions who have to 
read essays of multiple 
applicants.

How can we help?
For teachers, they can simply 
enter the essay into our system 
and the essay will be 
automatically graded. 
Furthermore the teacher will 
receive a summary of the 
grading along with list of reason 
for the current grade. This way 
a time taking and mundane task 
can be automated.
Similarly for scientific 
researchers, a short summary 
will help them in deciding 
weather the paper is of interest 
to them.


IR-Concepts used:
-
We have implemented various IR-
Algorithms in building this project. 

Document pre-processing 
-
has been used 
to convert the user essay to tokens and 
remove the stop words.

Building a similarity matrix 
-
We compute 
the similarity between each sentence in 
an essay with every other essay.

Cosine similarity 
-
will have represented 
our sentences as the bunch of vectors. We 
can use it to find the similarity among 
sentences. Its measures cosine of the 
angle between vectors.

TextRank 
-
does not rely on any previous 
training data and can work with any 
arbitrary piece of text. TextRank is a 
general purpose graph-based ranking.


Grading Approach Used
-
The SAT is a standardized exam for 
applying to universities in the 
America. The SAT also includes an 
essay section which is graded 
using a set of 262 words for a good 
vocabulary. We have included this 
dataset in our software to provide 
an accurate correction of words 
used in the essay. The scores of the 
students are tallied using the 
number of good vocabulary terms 
they have used, that are also 
present in SAT’s dataset. Also the 
spelling mistakes, length of the 
essay are all considered as factors while calculating the grade.
