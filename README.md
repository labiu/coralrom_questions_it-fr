# coralrom_questions_it-fr

**Source**

The data set collects all utterances classified as *genuine questions*
in samples of spontaneous speech interactions derived from the Italian
and French corpora collected in the C-ORAL-ROM multilingual resource.
C-ORAL-ROM is available through ELDA and through Cresti & Moneglia (eds)
(2005) C-ORAL-ROM. Integrated Reference Corpora of Spoken Romance
Languages. Amsterdam: Benjamins. Italian and French C-ORAL-ROM corpora
are also freely available from: http://corpus.lablita.it/?locale=en and
https://orfeo.ortolang.fr/?locale=fr

**Samples**

The Italian collection of samples gathers ten files comprising 4162
utterances, from which 366 questions have been retrieved. It represents
the language variety mostly spoken in Tuscany and collects data from 22
speakers (7 males, 15 females).

The French corpus collects 14 files recording 4179 utterances and 264
questions. It mainly represents the language variety spoken in South
France and collects data from 27 speakers (13 males and 14 females).

Corpus files are listed below using the original C-ORAL-ROM file name in
the ELDA and Benjamins editions. The filename defines the type of
interaction according to the following file name conventions.

-   Corpus: f (French); i (Italian);
-   Social context: fam (family / private): pub (public;) natbu
    (business); natte (teaching)
-   Interaction type: dial (dialogue); cv (multi dialogue)

ifamdl12 - two young women trying to cook a Tiramisù
Ifamdl02 – a souvenir of a family
ifamdl20 - gossips of two women about a friend’s love story
ifamcv14 – poker game among friends
ifamdl15 - chat with the beautician during the depilation
ifamcv01 - showing the family Photo album to the daughter-in-low
ifamdl09 - chat after a rock concert experience
ifamdl19 - driving school
ipubcv03 - setting the agenda for young children’s assistance
ifamdl17-developing photographs in a dark room

fnatte02 - explaining linguistic concepts in a class
fpubcv02 - students dealing with the University administration
ffamdl01 - chat among friends after the weekend
fnatbu01 - the sale of a car
famdl08 - criticism of the odd behavior of a family
ffamdl23 - visiting the grandmother
ffamdl02 - how the market of goods is organized
fpubdl01- discussion with workers on strike
fpubdl02- door-to-door sale
ffamcv03 - talking about skinheads in France
ffamcv05 - two women talk of the home décor
ffamdl04 - the life of a student who wants to become a singer
ffamdl10- a journey to Cuba
ffamdl17 - life and Memories of a Miner

**Data set**

The selection of questions among the utterances provided in the corpus
selection undergoes the following annotation criteria:

-   Recognition of the utterance as a question in the language context
    by at least 2 out of 3 mother tongue annotators.
-   Contextual adequacy.
-   Reaction by the addressee (answer).
-   Syntactic form (if applicable).

The Data set excludes *rhetorical questions*, *self-questions*, *echo
questions*, questions used as *dialogic moves*, and *surprise
questions*), identified as questions by mother-tongue speakers. However,
the criterion regarding the addressee’s answer is not satisfied. For
this reason, the above types of utterances are not considered “genuine”.
They are not in the data set which aims at identifying questions as
those directive utterances “aimed at the addressee linguistic behavior.”

Questions are classified according to the annotation schema in the following table:

<table>
<tbody>
<tr class="odd">
<td><strong>Question Type </strong></td>
<td><strong>Tag(s)</strong></td>
<td><strong>Working definition</strong></td>
<td><strong>Italian example</strong></td>
<td><strong>French example</strong></td>
</tr>
<tr class="even">
<td><em>Total </em></td>
<td>rc</td>
<td>the scope of the question is the whole proposition and must be answered by Y/N.</td>
<td><p>vieni a cena stasera?</p>
<p>[are you coming for dinner tonight]</p></td>
<td><p>tu viens dîner ce soir?</p>
<p>[are you coming for dinner tonight]</p></td>
</tr>
<tr class="odd">
<td>rf</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td><em>Partial</em></td>
<td>wh</td>
<td>the scope is an interrogative variable to be saturated in the answer.</td>
<td><p>dove vai ?</p>
<p>[where are you going ?]</p></td>
<td><p>où tu vas ?</p>
<p>[where are you going ?]</p></td>
</tr>
<tr class="odd">
<td><em>Open </em></td>
<td>op</td>
<td>the scope is a verb-less phrase that must be freely explained in the answer.</td>
<td><p>(bella macchina) e il prezzo ?</p>
<p>[(lovely car) and the price?]</p></td>
<td><p>(belle voiture) et le prix?</p>
<p>[(lovely car) and the price?]</p></td>
</tr>
<tr class="even">
<td><em>Alternative</em></td>
<td>ap</td>
<td>composed of two questions whose scope is the choice between them to be given in the answer.</td>
<td><p>Vieni la mattina / o il pomeriggio?</p>
<p>[are you coming in the morning or the afternoon?]</p>
<p>Vieni domani / o no ?</p>
<p>[Are you coming tomorrow or not]</p></td>
<td><p>Tu viens le matin ? ou l'après-midi ?</p>
<p>[are you coming in the morning or the afternoon?]</p>
<p>Tu viens demain / ou pas ?</p>
<p>[Are you coming tomorrow or not]</p></td>
</tr>
<tr class="odd">
<td>an</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td><em>Double</em></td>
<td>db</td>
<td>composed of two question units hierarchically structured, the second of which specifies the question, determining the type of answer.</td>
<td><p>quando parti/ domani?</p>
<p>[when do you leave? tomorrow?]</p></td>
<td><p>Tu pars quand / demain ?</p>
<p>[when do you leave? tomorrow?]</p></td>
</tr>
<tr class="odd">
<td><em>Tag</em></td>
<td>tag</td>
<td>composed of an assertive proposition and the request for its confirmation, whose scope is the proposition to be confirmed in the answer</td>
<td><p>oggi è il tuo compleanno, no?</p>
<p>[today is your birthday, isn't it?]</p></td>
<td><p>aujourd'hui c'est ton anniversaire, n'est-ce pas ?</p>
<p>[today is your birthday, isn't it?]</p></td>
</tr>
</tbody>
</table>


Total Questions and Alternative Questions are tagged according to
further specifications:[^1]

Total questions receive a tag according to the prosodic performance of
the nuclear part of the utterance:

-   “rc” (*rising* contour on the last tonic syllable in Italian;
    *rising* contour on the final vowel in French);
-   “rf” (rising-falling contour).

Alternative questions receive a tag according to the positive or
negative nature of the alternative:

-   Alternative positive (“ap”)
-   Alternative negative (“an”)

**File system**

*Acoustic source*

Utterances are delivered in wav or mp3 files. The filename comprises two
fields:

1.  the filename of the C-ORAL-ROM sample
2.  the time stamp of the utterance in the C-ORAL-ROM acoustic file

*Question classification*

The file Q-French and the file Q-Italian list each question in a record
identified by the following fields, where (A) and (B) constitute the
unique ID of the utterance in the file system:

1.  The filename of the C-ORAL-ROM source
2.  The time stamp of the utterance in the C-ORAL-ROM acoustic file
3.  The tag received according to the annotation schema
4.  The gender of the speaker
5.  The nickname of the speaker in the original C-ORAL-ROM collection
6.  The orthographic transcription of the utterance with the following
    punctuation

|       |                                                      |
|-------|------------------------------------------------------|
| tag   | definition                                           |
| //    | Terminal prosodic break                              |
| ?     | Terminal prosodic break marking a question value.    |
| /     | Non-terminal prosodic break                          |
| \[/\] | Fragmentation event in the speech flow (retracing)   |
| \<    | Beginning of an overlapped word sequence[^2]         |
| \>    | End of an overlapped word sequence                   |
| &     | Mark was given to a word fragment or to time taking. |



**Warning**

The data set derives from spontaneous speech interactions recorded in a
real environment and diverse recording situations. For this reason, the
acoustic signal may not allow full computability, particularly in
overlapped sequences.

[^1]:  Details are in Cresti E and Moneglia M (2023). The role of
    prosody for the expression of illocutionary types. The prosodic
    system of questions in spoken Italian and French according to
    Language into Act Theory. *Front. Commun. *8:1124513. doi
    10.3389/fcomm.2023.1124513
 
