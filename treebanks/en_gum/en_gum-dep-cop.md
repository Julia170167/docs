---
layout: base
title:  'Statistics of cop in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `cop`

This relation is universal.

3036 nodes (2%) are attached to their parents as `cop`.

2968 instances of `cop` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.34387351778656.

The following 14 pairs of parts of speech are connected with `cop`: <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (1267; 42% instances), <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (1197; 39% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (146; 5% instances), <tt><a href="en_gum-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (119; 4% instances), <tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (113; 4% instances), <tt><a href="en_gum-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (97; 3% instances), <tt><a href="en_gum-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (62; 2% instances), <tt><a href="en_gum-pos-DET.html">DET</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (13; 0% instances), <tt><a href="en_gum-pos-ADP.html">ADP</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (7; 0% instances), <tt><a href="en_gum-pos-X.html">X</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (5; 0% instances), <tt><a href="en_gum-pos-PART.html">PART</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (4; 0% instances), <tt><a href="en_gum-pos-INTJ.html">INTJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-SYM.html">SYM</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (2; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 cop	color:blue
1	You	you	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	4	nsubj	4:nsubj	Discourse=evaluation-comment:11->13:1|Entity=(12-person-new-cf3-1-ana)|SpaceAfter=No
2	're	be	AUX	VBP	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	4	cop	4:cop	_
3	so	so	ADV	RB	_	4	advmod	4:advmod	_
4	stupid	stupid	ADJ	JJ	Degree=Pos	0	root	0:root	_
5	thinking	think	VERB	VBG	VerbForm=Ger	4	advcl	4:advcl	Discourse=attribution-positive:12->13:0
6	I	I	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	7	nsubj	7:nsubj	Discourse=adversative-antithesis:13->14:1|Entity=(4-person-giv:act-cf1*-1-ana)
7	spent	spend	VERB	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	5	ccomp	5:ccomp	_
8	the	the	DET	DT	Definite=Def|PronType=Art	9	det	9:det	Entity=(7-time-giv:inact-cf2-2-coref
9	night	night	NOUN	NN	Number=Sing	7	obj	7:obj	Entity=7)|SpaceAfter=No
10	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 cop	color:blue
1	It	it	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	4	nsubj	4:nsubj	Discourse=evaluation-comment:5->3:1|Entity=(3-event-giv:act-cf1*-1-coref)
2	was	be	AUX	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	4	cop	4:cop	_
3	an	a	DET	DT	Definite=Ind|PronType=Art	4	det	4:det	Entity=(3-event-giv:act-cf1*-2-pred
4	accident	accident	NOUN	NN	Number=Sing	0	root	0:root	Entity=3)|SpaceAfter=No
5	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 2 cop	color:blue
1	That	that	PRON	DT	Number=Sing|PronType=Dem	10	nsubj	10:nsubj	Discourse=adversative-concession:10->6:1
2	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	10:cop	SpaceAfter=No
3	,	,	PUNCT	,	_	2	punct	2:punct	_
4	of	of	ADV	IN	_	10	advmod	10:advmod	_
5	course	course	NOUN	NN	Number=Sing	4	fixed	4:fixed	SpaceAfter=No
6	,	,	PUNCT	,	_	4	punct	4:punct	_
7	if	if	SCONJ	IN	_	10	mark	10:mark	Discourse=contingency-condition:11->10:0
8	you	you	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	10	nsubj	10:nsubj	Entity=(9-person-giv:inact-cf1-1-ana)
9	can	can	AUX	MD	VerbForm=Fin	10	aux	10:aux	_
10	get	get	VERB	VB	VerbForm=Inf	0	root	0:root	_
11	a	a	DET	DT	Definite=Ind|PronType=Art	12	det	12:det	Entity=(18-event-new-cf2-2-sgl
12	laugh	laugh	NOUN	NN	Number=Sing	10	obj	10:obj	Entity=18)|SpaceAfter=No
13	.	.	PUNCT	.	_	10	punct	10:punct	_

~~~


