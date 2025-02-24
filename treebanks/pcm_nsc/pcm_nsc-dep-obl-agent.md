---
layout: base
title:  'Statistics of obl:agent in UD_Naija-NSC'
udver: '2'
---

## Treebank Statistics: UD_Naija-NSC: Relations: `obl:agent`

This relation is a language-specific subtype of .
There are also 2 other language-specific subtypes of `obl`: <tt><a href="pcm_nsc-dep-obl-arg.html">obl:arg</a></tt>, <tt><a href="pcm_nsc-dep-obl-mod.html">obl:mod</a></tt>.

18 nodes (0%) are attached to their parents as `obl:agent`.

18 instances of `obl:agent` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.94444444444444.

The following 3 pairs of parts of speech are connected with `obl:agent`: <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-NOUN.html">NOUN</a></tt> (16; 89% instances), <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-ADJ.html">ADJ</a></tt> (1; 6% instances), <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-X.html">X</a></tt> (1; 6% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 9 obl:agent	color:blue
1	di	di	DET	_	Definite=Def|PronType=Art	3	det	_	AlignBegin=85203|AlignEnd=85406|Gloss=DEF.ART|SyllableCount=1|WordContour=lm
2	English	English	ADJ	_	_	3	amod	_	AlignBegin=85406|AlignEnd=85780|Gloss=English|SyllableCount=2|WordContour=mm
3	man	man	NOUN	_	_	4	nsubj	_	AlignBegin=85780|AlignEnd=86020|Gloss=man|SyllableCount=1|WordContour=mlh1
4	dey	dey	VERB	_	VerbType=Cop	0	root	_	AlignBegin=86020|AlignEnd=86180|Gloss=be|SyllableCount=1|WordContour=lh
5	wanted	want	VERB	_	Mood=Ind|Tense=Past|VerbForm=Fin	4	ccomp	_	AlignBegin=86180|AlignEnd=86687|Gloss=want.IND.PST.FIN|SyllableCount=2|WordContour=hl
6	by	by	ADP	_	_	9	case	_	AlignBegin=86687|AlignEnd=86820|Gloss=by|SyllableCount=1|WordContour=lmm1
7	{	{	X	_	_	9	dep	_	AlignBegin=86687|AlignEnd=86820|Gloss=PUNCT
8	former	former	ADJ	_	_	9	amod	_	AlignBegin=86820|AlignEnd=87120|Gloss=former|SyllableCount=2|WordContour=mmh2
9	club	club	NOUN	_	_	5	obl:agent	_	AlignBegin=87120|AlignEnd=87370|Gloss=club|SyllableCount=1|WordContour=llm2
10	|a	|a	X	_	_	11	dep	_	AlignBegin=87370|AlignEnd=88010|Gloss=PUNCT
11	Southampton	Southampton	PROPN	_	_	9	appos	_	AlignBegin=87370|AlignEnd=88010|Gloss=Southampton|SyllableCount=3|WordContour=llh3
12	ah	ah	INTJ	_	_	11	discourse	_	AlignBegin=88010|AlignEnd=88110|Gloss=ah|SyllableCount=1|WordContour=lL
13	}	}	X	_	_	9	dep	_	AlignBegin=88010|AlignEnd=88110|Gloss=PUNCT
14	//	//	X	_	_	4	dep	_	AlignBegin=88010|AlignEnd=88110|Gloss=PUNCT

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 11 obl:agent	color:blue
1	#	#	X	_	_	4	dep	_	AlignBegin=31867|AlignEnd=32520|Gloss=PUNCT
2	dis	dis	DET	_	Number=Sing|PronType=Dem	3	det	_	AlignBegin=32520|AlignEnd=32832|Gloss=SG.DEM|SyllableCount=1|WordContour=lLh1
3	decision	decision	NOUN	_	_	4	nsubj	_	AlignBegin=32832|AlignEnd=33339|Gloss=decision|SyllableCount=3|WordContour=Lmh2
4	follow	follow	VERB	_	_	0	root	_	AlignBegin=33339|AlignEnd=33750|Gloss=follow|SyllableCount=2|WordContour=lmh3
5	one	one	DET	_	Definite=Spec|PronType=Art	6	det	_	AlignBegin=33750|AlignEnd=33955|Gloss=SPEC.ART|SyllableCount=1|WordContour=mh
6	motion	motion	NOUN	_	_	4	obj	_	AlignBegin=33955|AlignEnd=34390|Gloss=motion|SyllableCount=2|WordContour=hm
7	wey	wey	SCONJ	_	_	9	mark	_	AlignBegin=34390|AlignEnd=34510|Gloss=REL|SyllableCount=1|WordContour=mh
8	de	dem	PRON	_	Case=Nom|Number=Plur|Person=3|PronType=Prs	9	nsubj	_	AlignBegin=34510|AlignEnd=34643|Gloss=NOM.PL.3|SyllableCount=1|WordContour=mm
9	move	move	VERB	_	_	6	acl:relcl	_	AlignBegin=34643|AlignEnd=34890|Gloss=move|SyllableCount=1|WordContour=mm
10	by	by	ADP	_	_	11	case	_	AlignBegin=34890|AlignEnd=35170|Gloss=by|SyllableCount=1|WordContour=mm
11	Honourable	honourable	ADJ	_	_	9	obl:agent	_	AlignBegin=35170|AlignEnd=35610|Gloss=honourable|SyllableCount=4|WordContour=lm
12	Abubakar	Abubakar	PROPN	_	_	11	flat	_	AlignBegin=35610|AlignEnd=36250|Gloss=Abubakar|SyllableCount=4|WordContour=mLH1
13	Yunusa	Yunusa	PROPN	_	_	11	flat	_	AlignBegin=36250|AlignEnd=37170|Gloss=Yunusa|SyllableCount=3|WordContour=LHL1
14	as	as	ADP	_	_	16	mark	_	AlignBegin=37170|AlignEnd=37480|Gloss=as|SyllableCount=1|WordContour=mh
15	e	im	PRON	_	Case=Nom|Number=Sing|Person=3|PronType=Prs	16	nsubj	_	AlignBegin=37480|AlignEnd=37559|Gloss=NOM.SG.3|SyllableCount=1|WordContour=hm
16	come	come	VERB	_	_	4	advcl	_	AlignBegin=37559|AlignEnd=37760|Gloss=come|SyllableCount=1|WordContour=hh
17	outside	outside	ADP	_	_	16	compound:prt	_	AlignBegin=37760|AlignEnd=38180|Gloss=outside|SyllableCount=2|WordContour=hml3
18	shout	shout	VERB	_	_	16	compound:svc	_	AlignBegin=38180|AlignEnd=38629|Gloss=shout|SyllableCount=1|WordContour=mlh2
19	sey	sey	SCONJ	_	_	44	mark	_	AlignBegin=38629|AlignEnd=38812|Gloss=COMP|SyllableCount=1|WordContour=hm
20	[	[	X	_	_	44	dep	_	AlignBegin=38812|AlignEnd=38842|Gloss=PUNCT
21	dis	dis	DET	_	Number=Sing|PronType=Dem	23	det	_	AlignBegin=38842|AlignEnd=39121|Gloss=SG.DEM|SyllableCount=1|WordContour=mmh2
22	rising	rise	VERB	_	Tense=Pres|VerbForm=Part	23	acl	_	AlignBegin=39121|AlignEnd=39550|Gloss=rising.PRS.PTCP|SyllableCount=2|WordContour=mh
23	price	price	NOUN	_	_	44	dislocated	_	AlignBegin=39550|AlignEnd=39830|Gloss=price|SyllableCount=1|WordContour=hm
24	of	of	ADP	_	_	26	case	_	AlignBegin=39830|AlignEnd=40060|Gloss=of|SyllableCount=1|WordContour=ml
25	different	different	ADJ	_	_	26	amod	_	AlignBegin=40060|AlignEnd=40430|Gloss=different|SyllableCount=3|WordContour=lh
26	kinds	kind	NOUN	_	Number=Plur	23	nmod	_	AlignBegin=40430|AlignEnd=40710|Gloss=kind.PL|SyllableCount=1|WordContour=hm
27	of	of	ADP	_	_	28	case	_	AlignBegin=40710|AlignEnd=40950|Gloss=of|SyllableCount=1|WordContour=ml
28	cement	cement	NOUN	_	_	26	nmod	_	AlignBegin=40950|AlignEnd=41730|Gloss=cement|SyllableCount=2|WordContour=lLh2
29	inside	inside	ADP	_	_	31	case	_	AlignBegin=41730|AlignEnd=42298|Gloss=inside|SyllableCount=2|WordContour=Llh3
30	we	we	PRON	_	Number=Plur|Person=1|Poss=Yes	31	nmod:poss	_	AlignBegin=42298|AlignEnd=42443|Gloss=PL.1.POSS|SyllableCount=1|WordContour=ll
31	country	country	NOUN	_	_	23	nmod	_	AlignBegin=42443|AlignEnd=42840|Gloss=country|SyllableCount=2|WordContour=mlh1
32	without	without	ADP	_	_	33	case	_	AlignBegin=42840|AlignEnd=43239|Gloss=without|SyllableCount=2|WordContour=lmh2
33	considerate	considerate	NOUN	_	_	23	nmod	_	AlignBegin=43239|AlignEnd=44197|Gloss=consideration|SyllableCount=4|WordContour=lLh3
34	of	of	ADP	_	_	37	case	_	AlignBegin=44197|AlignEnd=44583|Gloss=of|SyllableCount=1|WordContour=lLl3
35	di	di	DET	_	Definite=Def|PronType=Art	37	det	_	AlignBegin=44583|AlignEnd=44660|Gloss=DEF.ART|SyllableCount=1|WordContour=Ll
36	negative	negative	ADJ	_	_	37	amod	_	AlignBegin=44660|AlignEnd=45149|Gloss=negative|SyllableCount=3|WordContour=LmH3
37	implicate	implicate	NOUN	_	_	33	nmod	_	AlignBegin=45149|AlignEnd=45926|Gloss=implication|SyllableCount=3|WordContour=lLh3
38	inside	inside	ADP	_	_	41	case	_	AlignBegin=45926|AlignEnd=46380|Gloss=inside|SyllableCount=2|WordContour=llH2
39	di	di	DET	_	Definite=Def|PronType=Art	41	det	_	AlignBegin=46380|AlignEnd=46500|Gloss=DEF.ART|SyllableCount=1|WordContour=lLl2
40	building	building	NOUN	_	_	41	compound	_	AlignBegin=46500|AlignEnd=46886|Gloss=building|SyllableCount=2|WordContour=LhH2
41	industry	industry	NOUN	_	_	37	nmod	_	AlignBegin=46886|AlignEnd=47450|Gloss=industry|SyllableCount=3|WordContour=mlh1
42	<	<	X	_	_	23	dep	_	AlignBegin=47450|AlignEnd=47480|Gloss=PUNCT
43	e	im	PRON	_	Case=Nom|Number=Sing|Person=3|PronType=Prs	44	nsubj	_	AlignBegin=47480|AlignEnd=47650|Gloss=NOM.SG.3|SyllableCount=1|WordContour=LL
44	get	get	VERB	_	_	18	ccomp	_	AlignBegin=47650|AlignEnd=47840|Gloss=get|SyllableCount=1|WordContour=lm
45	as	as	ADP	_	_	47	mark	_	AlignBegin=47840|AlignEnd=48040|Gloss=as|SyllableCount=1|WordContour=ml
46	e	im	PRON	_	Case=Nom|Number=Sing|Person=3|PronType=Prs	47	nsubj	_	AlignBegin=48040|AlignEnd=48100|Gloss=NOM.SG.3|SyllableCount=1|WordContour=ml
47	be	be	VERB	_	PartType=Cop	44	ccomp	_	AlignBegin=48100|AlignEnd=48290|Gloss=be|SyllableCount=1|WordContour=lhL1
48	o	o	PART	_	PartType=Disc	44	advmod	_	AlignBegin=48290|AlignEnd=48510|Gloss=EMPH|SyllableCount=1|WordContour=hm
49	]	]	X	_	_	44	dep	_	AlignBegin=48510|AlignEnd=48540|Gloss=PUNCT
50	//	//	X	_	_	4	dep	_	AlignBegin=48510|AlignEnd=48540|Gloss=PUNCT

~~~


~~~ conllu
# visual-style 28	bgColor:blue
# visual-style 28	fgColor:white
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 22 28 obl:agent	color:blue
1	#	#	X	_	_	3	dep	_	AlignBegin=213860|AlignEnd=214160|Gloss=PUNCT
2	dem	dem	PRON	_	Case=Nom|Number=Plur|Person=3|PronType=Prs	3	nsubj	_	AlignBegin=214160|AlignEnd=214373|Gloss=NOM.PL.3|SyllableCount=1|WordContour=lLm1
3	say	say	VERB	_	_	0	root	_	AlignBegin=214373|AlignEnd=214511|Gloss=say|SyllableCount=1|WordContour=mh
4	[	[	X	_	_	22	dep	_	AlignBegin=214511|AlignEnd=214541|Gloss=PUNCT
5	one	one	DET	_	Definite=Spec|PronType=Art	7	det	_	AlignBegin=214541|AlignEnd=214800|Gloss=SPEC.ART|SyllableCount=1|WordContour=hh
6	sales	sale	NOUN	_	Number=Plur	7	compound	_	AlignBegin=214800|AlignEnd=215082|Gloss=sale.PL|SyllableCount=1|WordContour=hmh2
7	man	man	NOUN	_	_	22	dislocated	_	AlignBegin=215082|AlignEnd=215607|Gloss=man|SyllableCount=1|WordContour=mLh2
8	for	for	ADP	_	_	10	case	_	AlignBegin=215607|AlignEnd=215752|Gloss=for|SyllableCount=1|WordContour=ll
9	one	one	DET	_	Definite=Spec|PronType=Art	10	det	_	AlignBegin=215752|AlignEnd=215981|Gloss=SPEC.ART|SyllableCount=1|WordContour=lh
10	restaurant	restaurant	NOUN	_	_	7	nmod	_	AlignBegin=215981|AlignEnd=216549|Gloss=restaurant|SyllableCount=3|WordContour=hL
11	for	for	ADP	_	_	12	case	_	AlignBegin=216549|AlignEnd=216750|Gloss=for|SyllableCount=1|WordContour=ll
12	Awoyaya	Awoyaya	PROPN	_	_	10	nmod	_	AlignBegin=216750|AlignEnd=217520|Gloss=Awoyaya|SyllableCount=2|WordContour=lmh2
13	Ibeju	Ibeju	PROPN	_	_	12	flat	_	AlignBegin=217520|AlignEnd=218000|Gloss=Ibeju|SyllableCount=3|WordContour=mL
14	Lekki	Lekki	PROPN	_	_	12	flat	_	AlignBegin=218000|AlignEnd=218293|Gloss=Lekki|SyllableCount=2|WordContour=Lmh3
15	for	for	ADP	_	_	16	case	_	AlignBegin=218293|AlignEnd=218460|Gloss=for|SyllableCount=1|WordContour=ml
16	Lagos	Lagos	PROPN	_	_	14	nmod	_	AlignBegin=218460|AlignEnd=218836|ExtPos=PROPN|Gloss=Lagos|SyllableCount=2|Title=Yes|WordContour=Lmh3
17	State	state	NOUN	_	_	16	flat	_	AlignBegin=218836|AlignEnd=219210|Gloss=state|InTitle=Yes|SyllableCount=1|WordContour=ml
18	<	<	X	_	_	7	dep	_	AlignBegin=219210|AlignEnd=219240|Gloss=PUNCT
19	#	#	X	_	_	7	dep	_	AlignBegin=219240|AlignEnd=219540|Gloss=PUNCT
20	dem	dem	PRON	_	Case=Nom|Number=Plur|Person=3|PronType=Prs	22	nsubj	_	AlignBegin=219540|AlignEnd=219661|Gloss=NOM.PL.3|SyllableCount=1|WordContour=mh
21	don	don	AUX	_	Aspect=Perf	22	aux	_	AlignBegin=219661|AlignEnd=219870|Gloss=PRF|SyllableCount=1|WordContour=hhH2
22	catch	catch	VERB	_	_	3	parataxis	_	AlignBegin=219870|AlignEnd=220110|Gloss=catch|SyllableCount=1|WordContour=hm
23	am	am	PRON	_	Case=Acc|Number=Sing|Person=3|PronType=Prs	22	obj	_	AlignBegin=220110|AlignEnd=220340|Gloss=ACC.SG.3|SyllableCount=1|WordContour=hl
24	o	o	PART	_	PartType=Disc	22	advmod	_	AlignBegin=220340|AlignEnd=220480|Gloss=EMPH|SyllableCount=1|WordContour=ll
25	#	#	X	_	_	28	dep	_	AlignBegin=220480|AlignEnd=220656|Gloss=PUNCT
26	by	by	ADP	_	_	28	case	_	AlignBegin=220656|AlignEnd=220946|Gloss=by|SyllableCount=1|WordContour=ll
27	{	{	X	_	_	28	dep	_	AlignBegin=220946|AlignEnd=220976|Gloss=PUNCT
28	oro~	X	X	_	_	22	obl:agent	_	AlignBegin=220976|AlignEnd=221206|Gloss=X|SyllableCount=2|WordContour=hm
29	||	||	X	_	_	30	dep	_	AlignBegin=221206|AlignEnd=221236|Gloss=PUNCT
30	operatives	operative	NOUN	_	Number=Plur	28	reparandum	_	AlignBegin=221236|AlignEnd=221942|Gloss=operative.PL|SyllableCount=4|WordContour=mlh2
31	}	}	X	_	_	28	dep	_	AlignBegin=221942|AlignEnd=221972|Gloss=PUNCT
32	of	of	ADP	_	_	34	case	_	AlignBegin=221972|AlignEnd=222136|Gloss=of|SyllableCount=1|WordContour=lL
33	di	di	DET	_	Definite=Def|PronType=Art	34	det	_	AlignBegin=222136|AlignEnd=222237|Gloss=DEF.ART|SyllableCount=1|WordContour=LL
34	Lagos	Lagos	PROPN	_	_	30	nmod	_	AlignBegin=222237|AlignEnd=222600|ExtPos=PROPN|Gloss=Lagos|SyllableCount=2|Title=Yes|WordContour=Lmh3
35	State	state	NOUN	_	_	34	flat	_	AlignBegin=222600|AlignEnd=222786|Gloss=state|InTitle=Yes|SyllableCount=1|WordContour=hm
36	Command	command	NOUN	_	_	34	flat	_	AlignBegin=222786|AlignEnd=223350|ExtPos=PROPN|Gloss=command|InTitle=Yes|SyllableCount=2|WordContour=mLh2
37	#	#	X	_	_	44	dep	_	AlignBegin=223350|AlignEnd=223541|Gloss=PUNCT
38	on	on	ADP	_	_	44	mark	_	AlignBegin=223541|AlignEnd=223731|ExtPos=ADP|Gloss=on|Idiom=Yes|SyllableCount=1|WordContour=lL
39	top	top	NOUN	_	_	38	fixed	_	AlignBegin=223731|AlignEnd=223973|Gloss=top|InIdiom=Yes|SyllableCount=1|WordContour=hl
40	sey	sey	SCONJ	_	_	38	fixed	_	AlignBegin=223973|AlignEnd=224241|Gloss=COMP|InIdiom=Yes|SyllableCount=1|WordContour=lmh2
41	[	[	X	_	_	44	dep	_	AlignBegin=224241|AlignEnd=224271|Gloss=PUNCT
42	di	di	DET	_	Definite=Def|PronType=Art	43	det	_	AlignBegin=224271|AlignEnd=224421|Gloss=DEF.ART|SyllableCount=1|WordContour=lL
43	guy	guy	NOUN	_	_	44	nsubj	_	AlignBegin=224421|AlignEnd=224741|Gloss=guy|SyllableCount=1|WordContour=Llh2
44	rob	rob	VERB	_	_	22	ccomp	_	AlignBegin=224741|AlignEnd=225081|Gloss=rob|SyllableCount=1|WordContour=lmh3
45	{	{	X	_	_	47	dep	_	AlignBegin=225081|AlignEnd=225111|Gloss=PUNCT
46	im	im	PRON	_	Case=Nom|Number=Sing|Person=3|PronType=Prs	47	nmod:poss	_	AlignBegin=225111|AlignEnd=225390|Gloss=NOM.SG.3|SyllableCount=1|WordContour=lL
47	oga	oga	NOUN	_	_	44	obj	_	AlignBegin=225390|AlignEnd=225842|Gloss=boss|SyllableCount=2|WordContour=LmL2
48	|a	|a	X	_	_	50	dep	_	AlignBegin=225842|AlignEnd=225872|Gloss=PUNCT
49	one	one	DET	_	Definite=Spec|PronType=Art	50	det	_	AlignBegin=225872|AlignEnd=226130|Gloss=SPEC.ART|SyllableCount=1|WordContour=mmh2
50	Paulina	Paulina	PROPN	_	_	47	appos	_	AlignBegin=226130|AlignEnd=226773|Gloss=Paulina|SyllableCount=3|WordContour=mLh2
51	Paul	Paul	PROPN	_	_	50	flat	_	AlignBegin=226773|AlignEnd=227385|Gloss=Paul|SyllableCount=1|WordContour=mLh1
52	}	}	X	_	_	47	dep	_	AlignBegin=227385|AlignEnd=227415|Gloss=PUNCT
53	]	]	X	_	_	44	dep	_	AlignBegin=227385|AlignEnd=227415|Gloss=PUNCT
54	]	]	X	_	_	22	dep	_	AlignBegin=227385|AlignEnd=227415|Gloss=PUNCT
55	//	//	X	_	_	3	dep	_	AlignBegin=227385|AlignEnd=227415|Gloss=PUNCT

~~~


