---
layout: base
title:  'Statistics of PronType in UD_Norwegian-Nynorsk'
udver: '2'
---

## Treebank Statistics: UD_Norwegian-Nynorsk: Features: `PronType`

This feature is universal.
It occurs with 9 different values: `Art`, `Dem`, `Ind`, `Int`, `Neg`, `Prs`, `Rcp`, `Rel`, `Tot`.
Some words have combined values of the feature; 4 combinations have been observed: `Art|Prs`, `Ind|Prs`, `Neg|Prs`, `Prs|Tot`.

37798 tokens (13%) have a non-empty value of `PronType`.
172 types (1%) occur at least once with a non-empty value of `PronType`.
74 lemmas (0%) occur at least once with a non-empty value of `PronType`.
The feature is used with 3 part-of-speech tags: <tt><a href="no_nynorsk-pos-PRON.html">PRON</a></tt> (21241; 7% instances), <tt><a href="no_nynorsk-pos-DET.html">DET</a></tt> (16556; 5% instances), <tt><a href="no_nynorsk-pos-NUM.html">NUM</a></tt> (1; 0% instances).

### `PRON`

21241 <tt><a href="no_nynorsk-pos-PRON.html">PRON</a></tt> tokens (100% of all `PRON` tokens) have a non-empty value of `PronType`.

The most frequent other feature values with which `PRON` and `PronType` co-occurred: <tt><a href="no_nynorsk-feat-Animacy.html">Animacy</a></tt><tt>=EMPTY</tt> (14467; 68%), <tt><a href="no_nynorsk-feat-Number.html">Number</a></tt><tt>=Sing</tt> (13228; 62%), <tt><a href="no_nynorsk-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (12019; 57%), <tt><a href="no_nynorsk-feat-Case.html">Case</a></tt><tt>=EMPTY</tt> (11940; 56%), <tt><a href="no_nynorsk-feat-Person.html">Person</a></tt><tt>=3</tt> (11204; 53%).

`PRON` tokens may have the following values of `PronType`:

* `Art,Prs` (824; 4% of non-empty `PronType`): <em>ein, ei</em>
* `Ind,Prs` (357; 2% of non-empty `PronType`): <em>noko, nokon</em>
* `Int` (356; 2% of non-empty `PronType`): <em>kva, kven</em>
* `Neg` (28; 0% of non-empty `PronType`): <em>ingenting</em>
* `Neg,Prs` (62; 0% of non-empty `PronType`): <em>ingen</em>
* `Prs` (15989; 75% of non-empty `PronType`): <em>det, dei, han, eg, vi, seg, dette, ho, me, du</em>
* `Prs,Tot` (145; 1% of non-empty `PronType`): <em>alle, begge</em>
* `Rcp` (46; 0% of non-empty `PronType`): <em>kvarandre</em>
* `Rel` (3434; 16% of non-empty `PronType`): <em>som</em>

`PronType` seems to be **lexical feature** of `PRON`. 100% lemmas (34) occur only with one value of `PronType`.

### `DET`

16556 <tt><a href="no_nynorsk-pos-DET.html">DET</a></tt> tokens (100% of all `DET` tokens) have a non-empty value of `PronType`.

The most frequent other feature values with which `DET` and `PronType` co-occurred: <tt><a href="no_nynorsk-feat-Number.html">Number</a></tt><tt>=Sing</tt> (12482; 75%).

`DET` tokens may have the following values of `PronType`:

* `Art` (5926; 36% of non-empty `PronType`): <em>ein, eit, ei, eitt, en, eir</em>
* `Dem` (7036; 42% of non-empty `PronType`): <em>den, dei, det, andre, denne, anna, same, dette, desse, slike</em>
* `Ind` (454; 3% of non-empty `PronType`): <em>noko, nokre, nokon, noka, nokor</em>
* `Int` (106; 1% of non-empty `PronType`): <em>kva</em>
* `Neg` (138; 1% of non-empty `PronType`): <em>ingen, inga</em>
* `Prs` (2066; 12% of non-empty `PronType`): <em>sjølv, sin, sine, sitt, si, hans, vår, sjølve, eigen, våre</em>
* `Tot` (830; 5% of non-empty `PronType`): <em>alle, kvar, kvart, all, alt, begge, einkvar</em>

<table>
  <tr><th>Paradigm <i>det</i></th><th><tt>Prs</tt></th><th><tt>Dem</tt></th></tr>
  <tr><td><tt><tt><a href="no_nynorsk-feat-Case.html">Case</a></tt><tt>=Gen</tt></tt></td><td></td><td><em>dets</em></td></tr>
  <tr><td><tt></tt></td><td><em>det</em></td><td><em>det, dét</em></td></tr>
</table>

`PronType` seems to be **lexical feature** of `DET`. 98% lemmas (52) occur only with one value of `PronType`.

### `NUM`

1 <tt><a href="no_nynorsk-pos-NUM.html">NUM</a></tt> tokens (0% of all `NUM` tokens) have a non-empty value of `PronType`.

The most frequent other feature values with which `NUM` and `PronType` co-occurred: <tt><a href="no_nynorsk-feat-NumType.html">NumType</a></tt><tt>=Card</tt> (1; 100%), <tt><a href="no_nynorsk-feat-Number.html">Number</a></tt><tt>=EMPTY</tt> (1; 100%).

`NUM` tokens may have the following values of `PronType`:

* `Dem` (1; 100% of non-empty `PronType`): <em>fem-seks</em>
* `EMPTY` (4031): <em>to, tre, fire, ti, fem, 20, 1, seks, 2005, 2006</em>

## Relations with Agreement in `PronType`

The 10 most frequent relations where parent and child node agree in `PronType`:
<tt>PRON --[<tt><a href="no_nynorsk-dep-det.html">det</a></tt>]--> DET</tt> (122; 67%),
<tt>DET --[<tt><a href="no_nynorsk-dep-det.html">det</a></tt>]--> DET</tt> (90; 60%),
<tt>PRON --[<tt><a href="no_nynorsk-dep-expl.html">expl</a></tt>]--> PRON</tt> (50; 70%),
<tt>PRON --[<tt><a href="no_nynorsk-dep-appos.html">appos</a></tt>]--> PRON</tt> (23; 96%),
<tt>PRON --[<tt><a href="no_nynorsk-dep-conj.html">conj</a></tt>]--> PRON</tt> (22; 96%),
<tt>PRON --[<tt><a href="no_nynorsk-dep-nmod.html">nmod</a></tt>]--> PRON</tt> (12; 67%),
<tt>DET --[<tt><a href="no_nynorsk-dep-nmod.html">nmod</a></tt>]--> DET</tt> (8; 89%),
<tt>DET --[<tt><a href="no_nynorsk-dep-flat-name.html">flat:name</a></tt>]--> DET</tt> (1; 100%).

