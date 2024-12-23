java c
MAST10010: Data Analysis 
Assignment 1
Due Date: Friday   August   23rd,      11.59pm.
Instructions 
Software: 
You must use Minitab to   produce   any   graphs,   tables   and   descriptive   statistics.
Graphs: 
● must include your name/student number, which   can   be   added   by   Editing   the   graph,   right-clicking   and   selecting   Add   →   Footnote   or   Add   →   Subtitle.
● must be relevant.    You   may   look   at   many   graphs,   but   you   should   only   include   the most   relevant   graph   for   each   question.
● should be clear:    ensure   that   labels   and   titles   are   correct   and   appropriate;   you   can   add      gridlines/change symbols/colour as appropriate to make the graph clearer.
There   are   some   marks   awarded   for   improving   upon   the   default   from   Minitab.
● Mac Users: you will need to use myUniApps or the computer labs on campus in   order   to edit the   graphs as required    above.
Statistics: 
Must be relevant:   you   will   be   penalised   for   including   statistics   which   are   not   relevant   to   the   questions   asked.
Comments: 
● must be in the context of the data.
●   should   be supported by relevant statistics where   possible.
● should be concise and informative.    Word   limits,   where   given, must   be   strictly   ad-   hered   to   (all   word   limits   are   a   maximum,   you   will   be   penalised   for   going   over   this limit!).   There   is   no   minimum,   use   the   marks   available   as   a   guide.
Question 1: Study Design  [0 + 2 + (2+2+2) = 8 marks] In   the   week   2   Tute/Lab   class   you   designed   studies   to   investigate   research   questions.    For   this   question   you   may   use   ideas   from   the   class   discussion,   but must write and submit your own work.   While   it   is   recommended   to   use   the   same   question   you   discussed   in   the tutorial,   you   may   also   choose   another   question   that   was   not   discussed   in   your   class.You   are   allowed   to   simplify   or   adjust   the   question   to   make   it   more   practical,   and   may   also make reasonable assumptions about what is possible/feasible   (you should clearly   state   these   assumptions).   For   example,   in   a   study   to   determine   “How   many   sheep   do   you   need   to   count   before   falling   asleep?”:    it   is   reasonable   to   assume   that   people   would   be   able   to   remember   (approximately) the   number   they   got   to   before   falling   asleep; it   is   not   reasonable   to   assume   that   you   can   measure   their   brainwaves   to   determine   this   number.
Select   ONE   of the   following   13   research   questions:
1       Monitoring   the   effect   upon   river   health   of   an   outbreak   of   an   algal   bloom.
2       Determining   the   effect   upon   AFL   anterior-cruciate   ligament   longitude   of   a   new   boot design.
3       Is   chiropractic   manual   therapy   an   effective   treatment   for   infant   colic   (unexplained   persistent   crying)?
4       Is   a   new   chemotherapy   drug   effective   in   treating   cancer?
5       Is   yoga   an   effective   treatment   for   back   pain?
6       Does   organically   grown   food   contain   more   nutrients   than   non-organic   food?
7       Is   starch   consumption   good   for   the   obese?
8       Can   a   diet   high   in   heart-healthy   foods   and   antioxidants   reduce   the   risk   of   developing Alzheimer’s   disease?
9       Is   the   population   of   minke   whales   in   Antarctica   decreasing   significantly?
10       Mobile   phone   usage   and   brain   function   -   should   we   be   worried?
11       Does   playing   action   video   games   improve   your   surgery   skills?
12       Do   genetically   modified   soybeans   have   different   (better) nutrient   value   than   standard   varieties?
13       Cows      at   Melbourne   University’s   robotic   dairy   (Dookie)   can   decide   when   they   are milked.   Are   they   Australia’s   happiest   dairy   cows?
For your selected research question: 
(a)    Clearly   state   the   research   question   you   are   investigating   (this   should   be   the   simpli-   fied/clarified   question,   if you   have   altered   it).
(b)   What are the Response Variable and primary Explanatory Variable?    Clearly   state   the   specific   data   type   (eg   “discrete   numerical”,   “nominal   categorical”,...)    of each.
(c)    For   each   of   the   following   aspects   of   experimental   design,   explain   how   you   would   implement   them代 写MAST10010: Data Analysis Assignment 1Prolog
代做程序编程语言   for   your   study,   or   why   it   is   not   possible/desirable   to   do   so. You   will   be   assessed   on   both   the   content   and   the   clarity   of   your   explanations.
i.    Comparison
ii.      Control
iii.    Replication
The Sudoku Data 
For   questions   2,   3 and   4 you   will   need   to   access   the   data   file 2024Asst1-sudoku.csv (file can   be   downloaded   from   the   LMS   as   a   .CSV   file).This   file   contains   some   of   the   data   collected   in   the   Sudoku   Activity   conducted   in   the   Tute/Lab   sessions   in week   2 of this   semester. The purpose of the   study was   to   investigate   factors   that   may   affect   time   to   complete   a   Sudoku   puzzle. In   this   assignment   we   will   con-   cern   ourselves   with   a   subset   of   this   data,   those   who   successfully   completed   their   assigned   Sudoku   puzzle   within   the   10   minute   time   limit.Data cleaning exercise: To   begin   this   assignment you will first need to clean the data.   In   particular,   you   will   need   to   recode   the   “Hours   of sleep”   column   to   only   contain   numbers. Note   that   any   person   who   entered “more   than”   or   “less   than”   or   similar,   you should just   replace   with   the   number   in   their   answer,   since   there   is   no   sensible   way   to   get   more   information.      Many   values   should   be   missing,   because   although   this   was   the   most   common   additional   question   it   was   not   answered   by   a   majority   of   students.    Missing   values should be entered   as   an   asterisk   *. You will know you have   done   this   correctly   if you   have   the   summary   statistics:
Question 2: Exploring time taken to complete a Sudoku puzzle [2 + 4 + 2 = 8 marks] 
Calculate   a   new   variable   ‘Time   (seconds)’ to   complete   the   puzzle.(a)      Produce   a   dotplot   and   relevant   summary   statistics   for   Time   (seconds),   time   to   suc-cessfully   complete   a   Sudoku   puzzle.
(b)      Describe   the   distribution   of   Time   (seconds).
(c)    Comment on whether the higher times   (over 400 seconds)   have   anything   in   common.   Restrict   your   comments   to   no   more   than   two   sentences.
[Hint:    use    the   brush    command.]
Question 3: Investigating the effect of Type of Puzzle [2 + 3 + 5 = 10 marks] 
(a)    Consider   the   different   puzzles.    Do   you   think   differences   in   the   times   to   complete   the puzzle   can   be   attributed   to   the   different   symbols?   Explain.
(b)      Produce   a   comparative   boxplot   and   summary   statistics,   comparing   the   time   taken   for   the   four   (4)   different   puzzle   types.
(c)    Comment on the effect   of Type   of Puzzle   on   time   to   successfully   complete   a   Sudoku   puzzle.
Your comments must be less than 150 words. 
Question 4: Investigating the effect of other variables [3 + 2 = 5 marks] 
(a)    Produce   a   table   comparing   previous   experience   with    Sudoku   puzzles   and   Puzzle   number. Include    a   short   comment   describing   any   association   apparent   from   the table.   Do   you   think   the   randomisation   was   adequate?
(b)    Consider   Hours of sleep the   night before   and   Time   (seconds). Comment on   whether   there   is   a   linear   relationship   between these variables   (you   should   support your   com-   ment   with   appropriate   evidence).
Question 5: Good statistical graphics [3 + 3 = 6 marks] 
The   graph   on   the   following   page   was   posted   with   the   caption   “no.    of   golf   courses   in   the contiguous   united   states   bylines   of   latitude” (Credit:    Jay   Cuda   (@JayCuda   on   Twitter/X)
The data from the table in the   image are available to you on the LMS as the file   “2024Asst1-   golf.csv”   .
(a)   Identify   one   strength   and   two   problems   with   this   graph.
(b)    Produce   a   graph   which   better   displays   these   data.
Relevance, Formatting  Submission [2 marks] 
You   can   gain   an   additional   2   marks   by:
●   only   including   relevant   material;
●   submitting   a   clearly   legible   assignment   (eg   all   pages   correct   orientation);
●   selecting   correct   page(s)   for   each   part   of   each   question   (when   you   upload   your   as-   signment to Gradescope, it will ask you to select pages:   you can   select   multiple   pages for   a   question   part,   you   can   also   select   the   same   page   for   multiple   parts).









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
