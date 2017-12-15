<nav class="open">
	Navigation
</nav>

[toc]

# Speaking Thai

### Weekly Questions

* 

---

## Basics & Etiquette

Append ***ka/krap*** to sentences or responses for formality.

### Affirmative & Negative

English Word | Thai Translation
:--|:--
yes | *chai*
no | *mai [chai]*

### Greetings
English Phrase | Thai Translation
:--|:--
hello | *sa-wat dii*
how's it going? | *bpen-ngai?*
how are you? | *sa-baai dii mai?*
I'm fine | *[pom/chan] sa-baii dii*

### Introductions
English Phrase | Thai Translation
:--|:--
what is your name? | *kun chue a-rai?*
my name is... | *chan/pom chue...*
and you? | *kun la?*
nice to meet you | *yin dii tii dai ruu-jak*
me too | *chen-gan*

### Manners
English Phrase | Thai Translation
:--|:--
thank you | *khccp kun*
excuse me | *khcc-tot*
never mind | *mai bpen rai*

### Misunderstandings
English Phrase | Thai Translation
:--|:--
I [don't] understand | *[mai] khao-jai*
do you understand? | *khao-jai mai?*
what did you say? | *a-rai na*
speak again | *puud ek-krang*
wait a moment | *ro sak kruu*

## Sentence Structure

### Pronouns, Verbs, Q&A

**"Like" (*chob*)** may act as a modifier that preceeds other verbs.

Subject | Verb | Interrogative
:--|:--|:--
**you**: *kun* | **like**: *chob* | **what?**: *a-rai?*
**I**: *phom* (m); *[di-]chan* (f) | **go**: *bpai* | **where?**: *tii-nai?*
**he/she**: *khao (m); ter (f)* | **come from**: *maa jaak* | **[declaration], no?**: *mai?*
**we**: *rao* | **eat**: *gin* | —
**they**: *puak khao* | **drink**: *duem* | —
— | **be**: *bpen* | —
— | **do**: *tam* | —
— | **buy**: *sue* | —
— | **have**: *mii* | —
— | **speak**: *puud* | —
— | **study**: *rian* | —
— | **stop**: *yut* | —

### Adjectives/Adverbs & Nouns

Adjective/Adverb | Noun
:--|:--
**hungry**: *hiu* | **water**: *naam*
**much**: *maak* | **teacher**: *kru*
**little**: *nit-noi* | **language**: *passa*
**spicy**: *phet* | —
**quickly**: *rao*| —
**slowly**: *cha*| —
**delicious**: *a-roi* | —
**drunk**: *mao* | —
**good**: *dii* | —

### Tenses

Tense | Thai Translation
:--|:--
future (will) | *ja*

## Numbers

### Digits

Numeral | Thai Translation
:--|:--
0   | *soon*             
1   | *nung*             
2   | *sccng*             
3   | *saam*             
4   | *sii*            
5   | *haa*             
6   | *hok*             
7   | *jet*             
8   | *bpeet*             
9   | *gaao*

For **ordinals**, prepend *tii* (e.g. *tii nung*—"the first").             

### Decimal System

All applicable as suffixes or literals except for *et* (literal).

Ten Thousands | Thousands | Hundreds | Tens     | Ones
:--|:--|:--|:--|:--
*muen* | *pan* | *roy* | *sip* | *et*

Numbers in the **twenties are exceptions** to the decimal system above.

Numeral | Thai Translation
:--|:--
20       | *yii-sip*

## Time

### Days of the Week
Day | Thai Translation
:--|:--
Monday | *wan-jan*
Tuesday| *wan eng-kaan*
Wednesday | *wan put*
Thursday | *wan pa-rue-hat*
Friday | *wan suk*
Saturday | *wan sao*
Sunday | *wan aa-tit*

### Time Intervals
Unit | Thai Translation
:--|:--
day | *wan*
week | *aa-tit*
weekend | *sao aa-tit*
month | *duen*
year | *bpii*

### Past, Present, Future
English Word | Thai Translation
:--|:--
today | *wan-nii*
yesterday | *muea-wan-nii*
tomorrow | *prung-nii*
this | *nii*
last | *gon*
next | *naa*

## Miscellaneous Vocabulary

English Word | Thai Translation
:--|:--
— | —

<!-- STYLES & SCRIPTS -->
<style>
	body {
		margin: 0;
		padding-top: 40px;
	}
	
	nav {		
		display: flex;
		align-items: center;
		position: fixed;
		left: 0;
		top: 0;
		right: 0;
		z-index: 2;
		height: 40px;
		padding-left: 30px;
		font-size: 16px;
		font-weight: bold;
		background: #333;
		color: white;
		cursor: pointer;
	}
	
	nav::before {
		content: "–";
		margin-right: .5em;
		position: relative;
		top: -1px;
	}
	
	nav.closed::before {
		content: "+";
	}
	
	.toc {
		position: fixed;
	    top: 0;
	    left:0;
	    right: 0;
	    z-index: 1;
	    box-sizing: border-box;
	    height: 100%;
	    margin: 0;
	    padding: 40px 30px 10px;
	    background: #eaeaea;
	    overflow: scroll;
	    transition: all .3s;
	}
	
	.toc.closed {
		transform: translateY(-100%);
	}
	
	.toc::before {
	    content: "Table of Contents";
	    display: block;
	    font-size: 18px;
	    font-weight: bold;
	    margin: 20px 0 10px;
	}
	
	.toc ul {
		margin: 0 0 10px;
	}
	
	.toc li a {
		background: #4183C4;
		border-radius: 5px;
		padding: .5em;
		line-height: 3em;
		color: white;	
		text-decoration: none;	
	}
	
	h1::before, h2::before, h3::before {
	    display: block;
	    content: "";
	    height: 60px;
	    margin-top: -60px;
	}
	
	@media screen and (min-width: 914px) {
		
		nav {
			display: none;
		}
		
		body {
			padding-top: 0;
		}
		
		.toc {
			left: inherit;
			padding-top: 0px;
		}
		
		.toc.closed {
			transform: translateY(0);
		}
		
		h1::before, h2::before, h3::before {
		    height: 20px;
		    margin-top: -20px;
		}
	}
	
	@media print {
		nav, .toc {
			display: none;
		}
	}
</style>
<script>
	var nav = document.querySelector("nav");
	var toc = document.querySelector(".toc");
	var links = document.querySelectorAll(".toc a");
	
	function toggleNav(){
		if(nav.className === "closed") {
				nav.className = "";
				toc.className = "toc";
			}
		else {
			nav.className = "closed";
			toc.className = "toc closed";
		}
	}
	
	nav.addEventListener("click", toggleNav);
	for(var i=0; i<links.length; i++)
		links[i].addEventListener("click", toggleNav);
</script>