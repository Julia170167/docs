---
layout: base
title:  'Statistics of acl:relcl in UD_English-GUMReddit'
udver: '2'
---

## Treebank Statistics: UD_English-GUMReddit: Relations: `acl:relcl`

This relation is a language-specific subtype of <tt><a href="en_gumreddit-dep-acl.html">acl</a></tt>.

249 nodes (2%) are attached to their parents as `acl:relcl`.

249 instances of `acl:relcl` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.85542168674699.

The following 18 pairs of parts of speech are connected with `acl:relcl`: <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (160; 64% instances), <tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (35; 14% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (13; 5% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (10; 4% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (8; 3% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (6; 2% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt> (3; 1% instances), <tt><a href="en_gumreddit-pos-DET.html">DET</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 23	bgColor:blue
# visual-style 23	fgColor:white
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 21 23 acl:relcl	color:blue
1	_	_	PRON	DT	Number=Sing|PronType=Dem	3	nsubj	3:nsubj	Discourse=evaluation-comment:24->16:3|Entity=(22-event-giv:act-cf1*-1-coref)|Lem=*LOWER*|Len=4
2	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	cop	3:cop	Lem=be|Len=2
3	_	_	ADJ	JJ	Degree=Pos	0	root	0:root	Lem=_|Len=7
4	_	_	SCONJ	IN	_	6	mark	6:mark	Discourse=causal-cause:25->24:0|Lem=_|Len=7
5	_	_	NOUN	NNS	Number=Plur	6	nsubj	6:nsubj	Entity=(28-event-new-cf9-2-disc(29-person-new-cf7-1-sgl)|Lem=person|Len=6
6	_	_	VERB	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	3	advcl	3:advcl:because	Lem=_|Len=3
7	_	_	NOUN	NN	Number=Sing	6	obj	6:obj	Entity=(12-abstract-giv:inact-cf4-1-coref)|Lem=_|Len=5
8	_	_	PART	TO	_	9	mark	9:mark	Discourse=purpose-goal:26->25:0|Lem=_|Len=2
9	_	_	VERB	VB	VerbForm=Inf	6	advcl	6:advcl:to	Lem=_|Len=3
10	_	_	PROPN	NNP	Abbr=Yes|Number=Sing	11	compound	11:compound	Entity=(30-abstract-new-cf8-2-sgl(31-place-new-cf3-1-coref-United_States)|Lem=_|Len=2
11	_	_	NOUN	NN	Number=Sing	9	obj	9:obj	Entity=30)|Lem=_|Len=4
12	_	_	PUNCT	:	_	15	punct	15:punct	Discourse=elaboration-additional:27->25:1|Lem=-|Len=2
13	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	15	nsubj	15:nsubj	Entity=(32-person-acc:com-cf5-1-ana)|Lem=_|Len=2|SpaceAfter=No
14	_	_	AUX	VBP	Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	15	aux	15:aux	Lem=be|Len=3
15	_	_	VERB	VBG	Tense=Pres|VerbForm=Part	6	parataxis	6:parataxis	Lem=loan|Len=7
16	_	_	DET	DT	Definite=Def|PronType=Art	18	det	18:det	Entity=(23-organization-giv:act-cf2-3-coref|Lem=_|Len=3
17	_	_	PROPN	NNP	Abbr=Yes|Number=Sing	18	compound	18:compound	Entity=(31-place-giv:act-cf3-1-coref-United_States)|Lem=_|Len=2
18	_	_	NOUN	NN	Number=Sing	15	iobj	15:iobj	CorrectForm=government|Entity=23)|Lem=government|Len=4|XML=<sic ana:::"government"></sic>
19	_	_	DET	DT	Definite=Def|PronType=Art	21	det	21:det	Bridge=12<33|Entity=(33-abstract-acc:inf-cf6-3-sgl|Lem=_|Len=3
20	_	_	ADJ	JJ	Degree=Pos	21	amod	21:amod	Lem=_|Len=4
21	_	_	NOUN	NN	Number=Sing	15	obj	15:obj	Lem=_|Len=5
22	_	_	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	23	nsubj	23:nsubj	Discourse=elaboration-attribute:28->27:0|Entity=(23-organization-giv:act-cf2-1-ana)|Lem=_|Len=2
23	_	_	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	21	acl:relcl	21:acl:relcl	Entity=33)28)|Lem=print|Len=6|SpaceAfter=No
24	_	_	PUNCT	.	_	3	punct	3:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 acl:relcl	color:blue
1	_	_	PRON	DT	Number=Sing|PronType=Dem	3	nsubj	3:nsubj	Discourse=explanation-evidence:54->51:2|Entity=(58-time-giv:act-cf1*-1-ana)|Lem=*LOWER*|Len=4
2	_	_	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	cop	3:cop	Lem=be|Len=2
3	_	_	PRON	WP	PronType=Rel	0	root	0:root	Lem=_|Len=4
4	_	_	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	3	acl:relcl	3:acl:relcl	Lem=happen|Len=8
5	_	_	ADP	IN	_	6	case	6:case	Lem=_|Len=2
6	_	_	PROPN	NNP	Number=Sing	4	obl	4:obl:in	Entity=(60-place-new-cf3-1-coref-Zimbabwe)|Lem=_|Len=8
7	_	_	SCONJ	WRB	PronType=Rel	13	mark	13:mark	Discourse=elaboration-attribute:55->54:0|Lem=_|Len=5
8	_	_	DET	DT	Definite=Ind|PronType=Art	11	det	11:det	Entity=(61-event-new-cf2-4-sgl|Lem=_|Len=1
9	_	_	NUM	CD	NumForm=Word|NumType=Card	10	nummod	10:nummod	Lem=_|Len=7
10	_	_	NOUN	NN	Number=Sing	11	compound	11:compound	Lem=_|Len=6
11	_	_	NOUN	NN	Number=Sing	13	nsubj	13:nsubj	Entity=61)|Lem=_|Len=11
12	_	_	AUX	MD	Number=Sing|Person=3|VerbForm=Fin	13	aux	13:aux	Lem=_|Len=5
13	_	_	VERB	VB	VerbForm=Inf	6	acl:relcl	6:acl:relcl	Lem=_|Len=6
14	_	_	ADP	IN	_	16	case	16:case	Lem=_|Len=3
15	_	_	DET	DT	Definite=Ind|PronType=Art	16	det	16:det	Entity=(62-object-new-cf4-2-sgl|Lem=_|Len=1
16	_	_	NOUN	NN	Number=Sing	13	obl	13:obl:for	Lem=_|Len=4
17	_	_	ADP	IN	_	18	case	18:case	Lem=_|Len=2
18	_	_	NOUN	NN	Number=Sing	16	nmod	16:nmod:of	Entity=62)|Lem=_|Len=5|SpaceAfter=No
19	_	_	PUNCT	.	_	3	punct	3:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 acl:relcl	color:blue
1	_	_	VERB	VB	Person=2|VerbForm=Inf	0	root	0:root	Discourse=context-background:8->16:2|Lem=*LOWER*|Len=8
2	_	_	ADV	WRB	PronType=Rel	1	obj	1:obj	Lem=_|Len=4
3	_	_	PROPN	NNP	Number=Sing	5	nsubj	5:nsubj|13:nsubj	Entity=(13-person-new-cf2-1,2-coref-Anne_Burrell|Lem=_|Len=4
4	_	_	PROPN	NNP	Number=Sing	3	flat	3:flat	Entity=13)|Lem=_|Len=7
5	_	_	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	2	acl:relcl	2:acl:relcl	Entity=(14-event-new-cf4-1-disc|Lem=challenge|Len=10
6	_	_	PROPN	NNP	Number=Sing	5	obj	5:obj	Entity=(2-person-giv:inact-cf1-1-coref-Bobby_Flay)|Lem=_|Len=5
7	_	_	ADP	IN	_	10	case	10:case	Lem=_|Len=2
8	_	_	DET	DT	Definite=Ind|PronType=Art	10	det	10:det	Entity=(15-event-new-cf3-3-sgl|Lem=_|Len=1
9	_	_	NOUN	NN	Number=Sing	10	compound	10:compound	Entity=(16-object-new-cf5-1-coref)|Lem=_|Len=10
10	_	_	NOUN	NN	Number=Sing	5	obl	5:obl:to	Entity=15)14)|Lem=_|Len=6|SpaceAfter=No
11	_	_	PUNCT	,	_	13	punct	13:punct	Lem=_|Len=1
12	_	_	CCONJ	CC	_	13	cc	13:cc	Discourse=joint-sequence_m:9->8:0|Lem=_|Len=3
13	_	_	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	5	conj	2:acl:relcl|5:conj:and	Lem=win|Len=3|SpaceAfter=No
14	_	_	PUNCT	.	_	1	punct	1:punct	Lem=_|Len=1

~~~


