java c
MODEL   BUILDING   IN   MATHEMATICAL   PROGRAMMING
12.24          Yield   managementAn   airline   is   selling   tickets   for   ﬂights   to   a   particular   destination.   The   ﬂight   will depart   in   three   weeks’   time.   It   can   use   up   to   six   planes   each   costing   £50   000   to hire.   Each   plane   has   the   following:
37   First   Class   seats
38   Business   Class   seats
47   Economy   Class   seats.
Up   to      10%   of   seats   in      any   one   category   can   be   transferred   to   an   adjacent category.It   wishes   to    decide      a   price   for   each      of   these      seats.    There      will   be   further opportunities      to      update      these      prices      after      one      week      and      two      weeks.    Once      a customer   has   purchased   a   ticket,   there   is   no   cancellation   option.For   administrative   simplicity,   three   price   level   options   are   possible   in   each class   (one   of   which   must   be   chosen).   The   same   option   need   not   be   chosen   for each   class.   These   are   given   in   Table   12.17   for   the   current   period   (period   1)   and   two   future   periods.
Table   12.17
   
Option   1
Option   2
Option   3
   
First
£1200
£1000
£950Period   1
Business
£900
£800
£600
   
Economy
£500
£300
£200
   
First
£1400
£1300
£1150Period   2
Business
£1100
£900
£750
   
Economy
£700
£400
£350
   
First
£1500
£900
£850Period   3
Business
£820
£800
£500
   
Economy
£480
£470
£450
   Demand   is uncertain but   will be   affected by   price.   Forecasts   have   been   made   of these   demands   according   to   a   probability   distribution   that   divides   the   demand   levels   into   three   scenarios   for   each   period. The   probabilities   of   the   three   scenarios in   each   period   are   as   follows:
Scenario   10.1
Scenario   20.7
Scenario   30.2
The   forecast   demands   are   shown   in   Table   12.18.
Table   12.18
Decide   price   levels   for   the   current   period,   how   many   seats   to   sell   in   each class      (depending      on      demand),    the   provisional      number      of   planes   to   book      and provisional   price   levels   and   seats   to   sell   in   future   periods   in   order   to   maximise expected   yield.   You   should   schedule   to   be   able   to   meet   commitments   under   all possible   combinations   of   scenari代 写282 MODEL BUILDING IN MATHEMATICAL PROGRAMMING 12.24 Yield managementR
代做程序编程语言os.With   hindsight      (i.e.   not   known   until   the   beginning      of   the   next   period),   it turned   out   that   demand   in   each   period   (depending   on   the   price   level   you   chose) was   as   shown   in   Table   12.19.
Table   12.19
   
Price   option   1
Price   option   2
Price   option   3
   
First
25
30
40Period   1
Business
50
40
45
   
Economy
50
53
65
   
First
22
45
50Period   2
Business
45
55
75
   
Economy
50
60
80
   
First
45
60
75Period   3
Business
20
40
50
   
Economy
55
60
75
   Use   the   actual   demands   that   resulted   from   the   prices   you   set   in   period   1   to rerun   the   model   at   the   beginning   of   period   2   to   set   price   levels   for   period   2   and provisional   price   levels   for   period   3.
Repeat   this   procedure   with   a   rerun   at   the   beginning   of   period   3.   Give   the   ﬁnal   operational   solution.
Contrast   this   solution   to   one   obtained   at   the   beginning   of   period   1 by   pricing to   maximise   yield   based   on   expected   demands.
12.25            Car   rental   1A   small   (‘cut   price’)   car   rental   company,   renting   one   type   of   car,   has   depots   in Glasgow, Manchester, Birmingham and Plymouth. There   is   an   estimated   demand   for   each   day   of   the   week   except   Sunday   when   the   company   is   closed.   These   estimates   are   given   in   Table   12.20.   It   is   not   necessary   to   meet   all   demand.
Table   12.20
   
Glasgow
Manchester
BirminghamPlymouth
Monday
100
250
95
160
Tuesday
150
143
195
99
Wednesday
135
80
242
55
Thursday
83
225
111
96
Friday
120
210
70
115
Saturday
230
98
124
80Cars    can   be   rented   for      one,   two      or   three      days      and   returned      to      either   the depot   from   which   rented   or   another   depot   at   the   start   of   the   next   morning.   For example,   a   2-day   rental   on   Thursday   means   that   the   car   has   to   be   returned   on Saturday   morning;   a   3-day   rental   on   Friday   means   that   the   car   has   to   be   returned on   Tuesday   morning.   A    1-day   rental   on   Saturday   means   that   the   car   has   to   be returned   on   Monday   morning   and   a   2-day   rental   on   Tuesday   morning.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
