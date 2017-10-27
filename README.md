# ROPE – Remembering Outlines in Plover more Easily

## Intro and TL;DR

ROPE is a guide to learning and recalling Plover outlines for common English words. It does this in two ways: first, it relies on Anki's spaced repetition system to help you solidify the outlines in your memory. Second, it includes mnemonic devices (in the form of stories) for a sizeable chunk of the outlines. These stories serve to connect the outlines to their corresponding word by including words that are similar to the components of the outlines. 

## History

ROPE was initiated by Kenneth Burchfiel and released to the public domain. His first version was based on the word frequency list Mark Davies containing 5000 English words. To allow easier collaboration, Martin Körner ported the list to a non-binary format and uploaded it to GitHub. To allow the publication of the whole list under a [CC0 license](LICENSE), we switched to the [NGSL word frequency list](http://www.newgeneralservicelist.org/). This list was extended to include interesting plurals, conjugations, and other extensions of the root words in the list. Most of this README file was written by Kenneth Burchfiel.

## Stories

### What do you mean by 'stories'?

The credit for the idea of using mnemonic stories to recall information goes to James Heisig, the author of the brilliant Remembering the Kanji and Remembering the Hanzi books. Heisig wrote those books to help people learn the characters that are found in written Japanese and Chinese. His premise was that in order to remember how to write characters, you need to look at the individual elements of those characters, and then craft a story that connects those elements to the meaning of the character.

The stories in ROPE use a similar concept. Generally, any given story uses one or more words inspired by the letters in the Plover outline to link those letters to the word that the outline produces. (There will be examples, don't worry!) The idea is that when you're faced with a word in English that you're trying to remember the outline for, you'll first remember the story for that word, as stories are easier to remember than strings of letters. Each story has one or more words that represent some or all of the letters in the outline. Once you remember those words, you'll be able to transition from the words to the letters in the outline, perhaps aided by characteristics in the original word and/or your understanding of steno theory. 

As a disclaimer, these stories do not solve all the work of remembering an outline. That's because this is not a precise system in which each letter always maps to the same word in a story. Depending on their context, any given letter or series of letters in an outline can mean different things story to story. Also, the words in the story can be based off just one letter in the outline, or they can be based off multiple (or all of) the letters in the outline. Finally, the stories generally focus on parts of an outline that will be hard to remember, and may not mention letters that you would know to include anyway. We mention all this because this mnemonic system is a little "fuzzier" than a system where the mnemonic device takes all the guesswork away. (The advantage of a 'fuzzy' system, in my view, is that it's much more flexible and allows you to create stories in many different ways. It also allows for much shorter and simpler stories with fewer elements in them to remember.)

A more precise mnemonic method to use with Plover can be found in the [Plover Wiki](https://github.com/openstenoproject/plover/wiki/Stenotype-Mnemonics-for-Beginners-(English)). 

### Examples

Here are 10 examples of the varying kinds of stories included in the [NGSL list]{lists/ngsl.tsv}. They're sorted from less complex to more complex.

1. A story for the outline STEUBGS (simplified: STEUKS) for the word "statistics": 

    A guy stares at his statistics textbook for hours, but try as he might, none of the content STEUBGS (sticks) to his brain.

    Explanation: STEUBGS and "statistics" don't sound too alike. But fortunately, STEUBGS does sound a lot like the word "sticks." Therefore, this story connects statistics to "sticks," and from there, you should be able to remember that 'sticks' corresponds to STEUBGS (at least once you've formed an understanding of how steno theory works, which I call a 'steno sense'.) 

    In other words, your memory's path from "statistics" to "STEUBGS" goes: statistics > story > "sticks" > 'steno sense' > STEUBGS.

2. A story for the outline KERT for the word "concert": 

    "I'll be KERT (curt) with you: I don't want to go to any more acoustic guitar concerts!" says your friend.

    Explanation: This story introduces a new word (curt) to connect KERT to "concert." True, KERT has an E and 'curt' has a U, but the word we're trying to write—concert—should help you remember the correct vowel keys. 'Curt' is meant to get you halfway from "concert" to KERT, and it shouldn't be too hard to remember KERT once you've made it that far. 

    In this case, your recall path goes: "concert" > "curt" > 'steno sense' and the "e" sound in concert > KERT. 

3. A story for the outline SAOUPL (simplified: SAOUM) for the word "assume": 

    "If you're a lawyer, you may assume that the best way to handle a conflict with someone else is to SAOUPL (sue 'em)."

    In this case, we turn the letters in the outline into two words, not one. 

4. A story for the outline TK-BG (simplified: D-K) for the word "background":

    D-K (Donkey Kong) games are so good that it's hard to find them at a discount. They have plenty of resale value.

    Explanation: In outlines without any vowel sounds, we often will have the letters serve as acronyms for something, or form words from individual letters. Thus, as long as you know that DK is Donkey Kong, one of Nintendo's most famous mascots, you should be able to use this story to connect "discount" and DK without too much trouble.

5. A story for the outline KR*EUL for the word "critical":

    "Your pet porcupine is very critical of the idea of eating KREUL (krill) for dinner, since it doesn't seem as tasty as the leftover Chinese food in your trash can."

    Explanation: This story, like many others, uses the word "porcupine" to represent an * (asterisk) within a brief. Porcupines are small and pointy, after all. In some other stories, we use the words "star" or "asterisk" instead, but we mention explicitly that we're doing so.

6. A story for the outline KOEUP for "copy":

    The copy machine at your office never breaks, as long as you pour a K(a)P (cap)-ful of OIL into it each month.

    Explanation: This is an example of one of the 'OIL stories.' Basically, Plover often uses the OEU sound in words that don't have an "oi" sound. This can make the vowel sound very hard to remember unless you have an explicit specifier in the story that the vowel diphthong used is OEU. That's where "OIL" (capitalized) comes in. Whenever that's present, you replace whatever vowels are suggested in the story with OEU. 

    So in this story, we have both K(a)P for "cap" and OIL. The OIL tells us that we need to overwrite the "a" sound in KAP with OEU, providing us with KOEUP.

    We know this seems like a lot of extra work. We'll just note that we didn't use this OIL convention at first, but then added it later on because outlines with OEU were just so difficult to remember otherwise.

    Special thanks to the author of [Stenotype Mnemonics for Beginners](https://github.com/openstenoproject/plover/wiki/Stenotype-Mnemonics-for-Beginners-(English)) (Joshua Pan?) for helping inspire this "OIL" convention.

7. A story for PAOERP for the word "pepper":

    "The Carolina Reaper is a pepper so spicy that just PAOER-ing (peering) at it will make your eyes burn. It is truly a pepper without PAOER (peer)."

    Explanation: We didn't include the final P in the story because it shouldn't be too hard to remember that on your own. This story thus focuses on the 'hard' part. Thus, to produce the right outline, you have to borrow not just from the story, but also from your 'steno sense' and another part of your memory as well.

8. A story for PRAEGS (simplified: PRAESHUN) for the word "pregnancy":

    A c-section is an o-PRAESHUN (operation) that is sometimes performed at the end of a pregnancy.

    Explanation: In this story, the entire outline only forms part of the word we're inserting into the story (operation). This isn't too common, but it can happen.

9. A story for SPEF for "specify":

    "PEF by itself is "perspective." Most people want candidates to specify their political perspectives on important issues before they choose to vote for them."

    Explanation: This story uses the actual word ("perspective") that part of the outline (PEF) maps to. The disadvantage to this is that if you've forgotten or haven't yet learned that other word, the story may not be of much use. The advantage to this strategy, though, is that it helps you reinforce your memory of two different outlines at the same time.

10. A story for SAO*UFRPZ for "supervisor":

    Two porcupines try to order PZ (pizza) at a restaurant, but the supervisor kicks them out, saying: "We only sell to humans." The porcupines SAOUFR (sue for) the right to eat PZ (pizza) at the restaurant, and hope that their case will allow porcupines to eat wherever they want.

    Explanation: This story is particularly complex because it introduces four words: pizza, sue for, and porcupines (to represent the asterisk). We think most of my stories only introduce one or two new words, but with a brief this tricky to remember, we had to bring in as many memory guides as possible.

### How can I remember what vowel to use for an outline that has many different potential vowel sounds?

One of the drawbacks of trying to use outlines with as few keypresses as possible (with some exceptions) is that it's hard to remember when you can use a shortened vowel combo, and when you need to use a longer one. Take "meet" and "need," for example. "need" can be written as TPHAED, but to write "meet," you need the full e sound: PHAOET. We often got these words wrong because we couldn't remember which outline required which vowel sound. 

Therefore, we've added some words to stories that, when written in capital letters, specify that the outline uses a particular vowel combo. That combo "overrides" any other vowels suggested by the story. Here are those words, and the vowel combos they're associated with: 

* A: APPLE 
* O: OCTOPUS
* E: ELEPHANT 
* U: URANIUM (U being its atomic symbol)
* EU: EUROPE (as the EU is an abbreviation for the European Union)
* AO: BOOT
* AE: ACCIDENT & EMERGENCY DEPARTMENT
* AU: GOLD (chemical symbol is AU)
* OE: DEBT (since a debt is something you OE (owe))
* OU: OKLAHOMA (since OU is a university in Oklahoma)
* AOE: MOSQUITO (mosquitos make an annoying eeee sound when they're flying by your ear)
* OEU: OIL (this one is especially common, as there are many outlines with OEU for words without an "oi" sound)
* AEU: CANADA (in honor of the word "eh")
* AOU: U-TURN
* AOEU: ICEBERG

These vowel specifiers are only used when we feel them to be necessary, but feel free to add them to stories when they would be helpful for you. When you keep entering the wrong vowel sound when quizzing, that's an indicator that you need to include one of the vowel specifiers into my story.

When these words are used in stories, they give us more freedom in choosing a word to help you remember the outline. Normally, the word we choose should have a pretty similar vowel sound as the outline, as otherwise you might enter the wrong vowel sound. However, when one of the above words is entered in a story, we know for certain what vowel a word will have. 

That means when choosing words that will connect the outline to its meaning, we can use words that have similar consonant sounds as the outline, but an entirely different main vowel. To make the connection between the outline and the word clearer, we sometimes replaced the vowels in the outline with lowercase vowels, enclosed in parentheses, that match the vowel in the story. 

This probably sounds pretty confusing without an example, so here's one.
The story for ROEUR for the word "error" reads: 
"If you ask to have your steak grilled R(ae)R (rare), but it comes to you well done and fried in OIL, then the chef has made two unfortunate errors.

What's going on here? Well, since OIL is present, we know that the final vowel must be OEU. That means that when writing the story, we didn't need to connect "ROEUR" to a word with an "oi" sound; we just needed to find a word that started with R and ended with R, like the outline does. "Rare" seemed like a good choice. 

However, ROEUR doesn't really sound like rare, and it might be hard to connect the two in your head. So instead of writing out ROEUR within the story, we wrote R(ae)R, which sounds a lot more like "rare." The "ae" is made lowercase and parenthesized so that you won't mistake it for actual letters in the outline.

The idea here is that when you're recalling the outline for error, you'll think of R…R from the word "rare," and then OEU from the word "OIL." Putting them together, we get ROEUR.

We probably went into more detail here than was necessary, but we didn't want you to get confused when you saw something like R(ae)R in a story.

One final note: when Kenneth Burchfiel first uploaded ROPE to the internet, the only vowel specifiers he used were OIL and "ACCIDENT & EMERGENCY DEPARTMENT." He included all the others afterwards when he recognized that more words like this would be helpful. That means that you may not see many of these other words in use—and some might never be used. But he wanted them to be available for you to insert in your own stories.

### These stories seem like a lot of extra effort and are kind of silly. Do they really work?

Based on our experience, we believe they do work. It's a lot easier to remember stories, even ones as dopey as the story of porcupines suing for the right to eat pizza (see example #10 above), than it is to remember non-intuitive strings of letters. That reflects a central truth about mnemonics—that to remember something, you want to convert it into a form that's easier to recall. 
However, we're quite sure that not all of our stories will work for you. Some of them reference things (like Nintendo games) that you may not know anything about. And in the process of studying these outlines, you'll probably think of some far better stories than the ones that I had. In this case, the solution is easy: overwrite my story with your story and consider contributing it to our shared list! 

### Why not a story for every word?

There are a number of reasons why a word may not have a story attached to it: 

1. In general, we only included stories when they would make a substantial contribution towards my recall of an outline. That's why there's no story for POP for the word "pop," or PORGS for the word "portion." They simply wouldn't be necessary! 
2. Quite a few of the words are just derivatives of other words. If we have a story for one of those words (ideally the root), then we normally didn't include a story for the derivative words. For example, since we have a story to help me remember FEF for the word "effective," we didn't see a need to write stories for FEFL and FEFNS for "effectively" and "effectiveness," respectively. 
3. We think the story method isn't as important for ultra-common words, since writing them over and over again will force them into your memory. The stories are more valuable for words that will only come up once in a while.
4. Sometimes an outline will demonstrate a pretty straightforward inversion (like PHAOEURPB for "minor"), and in cases like that we often wouldn't create a story.
Regardless, if you see a word that you think needs a story, go ahead and create one! We'll admit that creating a story yourself is probably more conductive towards remembering it than using one of ours.

### But won't pausing to remember a story take time? Wouldn't it just be faster to output words from muscle memory?

Yes! Absolutely. Steno is built for speed, and recalling stories takes longer than just writing a word.

These stories are meant to be like the giant Saturn V rockets that powered astronauts in the Apollo missions into orbit. The rockets served a useful purpose, but once they were no longer needed, the astronauts detached them and let them fall away. Likewise, these stories can help you go from consistently forgetting an outline to consistently remembering them. And once you're consistently remembering them, you may be able to let go of the story and just encode the outline into your muscle memory.

But not to worry—if you forget an outline, the stories can help you insert it back into your memory.

### Anything else I should know about the stories?

1. Don't assume anything we say in the stories to be true! There's a ton of made-up stuff and false information, but it's all there to help you learn the outlines.  
2. Don't assume that an apparent outline we inserted in a story actually maps to a word unless it's stated explicitly that it does. A huge chunk of the outlines that I included in these stories, probably the vast majority, are 'pseudo-outlines' that are just there to help you link the word you're studying to the outline you're studying. 
3. The stories shouldn't be assumed to be actual explanations of how these outlines were developed. 


## The Outlines and the Words

### How did you pick what outlines to use for each word?

It was pretty arbitrary sometimes, but we tried to follow a general pattern, which went as follows:

1. We stick to outlines that already work with Plover
2. In all or almost all cases, we chose an outline that required the fewest strokes possible. (By "stroke," we mean the process of depressing one or multiple keys, then releasing them. A `/` is used in the Plover dictionary window to separate strokes. One stroke can have multiple keypresses.) That's why we chose an outline like SAO*UFRPZ (9 keypresses) instead of SAOUP/O*R (8 keypresses) for the word "supervisor." Our very rough estimate is that 75% of the outlines in the dictionary require just one stroke.
3. When comparing outlines with the same amount of strokes, we tried to choose an outline with the lowest amount of keypresses, with some important exceptions. First, we often avoided an outline that was just a misstroke, but not always! 
Second, if a word had multiple strokes, we normally chose an outline that used an 'official' prefix or suffix instead of one that used an 'unofficial' one. As an example, you can write "concede" with the outline KOPB/SAED, but we chose KAUPB/SAOED, since KAUPB is the prefix listed for "con-" in Plover's dictionary. This was done because remembering which words 'required' the official suffix or prefix and which didn't is hard, so we just revised our outlines to use the official ones by default.
4. We sometimes took ergonomics into account. If one key combination was harder to type successfully than another, we would sometimes default to the easier one, even if it required additional keypresses.

### I'd rather use a different outline for some of these words.

No problem! Anki is super-customizable, so you can make substitutions for outlines that you'd like. The outlines we've listed are simply our preferences, just as the stories we've listed are simply the ones that we preferred to use. Feel free to make any changes you'd like. Even better, consider sending us your suggestions and changes via a pull request on GitHub! We would be happy to update our lists.

### Did you include any other words beyond the original frequency list?

The only words that were added to the original lists are extensions of the root word such as the plural of nouns or conjunction of verbs. This allows us to update our list in case there are changes to the original list. The best way to add additional words would be to start a separate file.

## Other useful stuff

### How long will this take?

Kenneth Burchfiel: All I know is how long it's taken me to get where I am now. I first started learning Plover in June 2017, and began this project after I already had some experience with the system. 

I needed about 50 days to test myself on all 4,383 cards at least once. I stuck pretty close to a schedule of learning 100 new outlines and reviewing 100 old outlines each day in Anki. It normally took me about an hour or a little longer to review the 100 old cards, but the 100 new cards could take 2 hours or longer—probably because I spent some of that time writing stories. 

This was a pretty grueling schedule, so if you don't want to devote 3 hours+ a day to learning these cards, it means you're probably more rational than I am! If you learned just 12 new cards a day, you could still get through the entire deck in a year. 

Now that I've gotten through all the cards, my plan is to keep reviewing 100 new cards a day, which is currently taking me about an hour. As my accuracy improves, I imagine I can eventually get through the cards much faster than that.

What I do believe, though, is that learning a word systematically will often be faster than going through a cycle of learning, forgetting, and re-learning it, which is what I might be doing without my Excel file and Anki deck.

### I just downloaded Plover for the first time tonight. Can I start using this immediately? 
We wouldn't recommend using this until you've gone through all the terrific [Learn Plover! exercises](https://sites.google.com/site/ploverdoc/) and understand them well. We normally didn't include any information about interpreting outlines if it was already listed there. For instance, the stories assume that you know which combinations of keys on the Plover keyboard (e.g. PH-, -BG) map to which keys (e.g. M, K.).
Once you've done the Learn Plover! exercises, we think you're ready to start ROPE if you'd like to. 

### I want to focus on learning the most common 500/1000/2000 words first. Is there a way to do this?

That's a nice approach! Since the list is sorted by frequency, an easy way to do this would be to open a `.tsv` list in some text editor or excel and delete the words that you don't want to use.

### How should I sort the Excel file?

In addition to sorting by frequency, we think sorting it in alphabetical order is especially useful, since you can then identify patterns among similar words. 

### I'd like to contribute! Can I send you stories and corrections? 

Corrections are welcome! We're still figuring out the best way to handle this but for now here are some guidelines for your pull requests:

* Only use strokes that exist in the plover `main.json` dictionary.
* Don't add or remove root words. We will use them to keep our list up to date in case our original frequency list changes.
* Avoid any offensive terms in your story, even if they help you remembering an outline. If you really must, give an indirect hint at which word you mean but keep it classy.

### What information is included in the lists?

* The word
* The preferred outline
* A simplified version of the preferred outline
* Whether the word is a brief or not
* The rank of the word based on the original frequency list. Derivations of a root word got assigned the same frequency
* The word type
* All alternative outlines in the official Plover dictionary
* A mnemonic story

### I don't like the formatting of the Anki cards! The text is far too large/small.

It's possible to change the formatting in Anki. This is done using HTML syntax.

### Am I the only person who has read this whole README?

Yes. 



