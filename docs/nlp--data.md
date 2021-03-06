# NLP Data (Corpora, Lexica)

Corpora are collections of documents like conversation transcripts, books, e-mails, tweets, etc. The most valuable corpora have labels for things like the syntax tree, parts of speech, sentiment, "in-reply-to" (for dialog), number of favorites (for tweets) etc

Lexica are collections of words like dictionaries, thesauruses, N-gram collections, or vocabularies (lists of words)


## Lists and Compilations

- [niderhoff list of NLP datasets](https://github.com/niderhoff/nlp-datasets)

## Dialog Corpora

- [Deep Mind Q&A Dialog Corpus](https://cs.nyu.edu/~kcho/DMQA/)
- [Twitter post dialog (1 GB/mo scraper)](https://github.com/Marsan-Ma/twitter_scraper)
- [Reddit comment dialog (.5 TB bz2)](http://files.pushshift.io/reddit/comments/)
- [Ubuntu IRC dialog (.5 GB tgz)](http://dataset.cs.mcgill.ca/ubuntu-corpus-1.0/)
- [Supreme Court law dialog (80 MB .zip)](http://scdb.wustl.edu/data.php)
- [Cornel-labeled movie dialog (300k utterances, 10 MB .gz)](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)

## Corpora

- [keyword extraction datasets](https://github.com/zelandiya/keyword-extraction-datasets)
- [Manually Annotated Sub-Corpus (MASC) for American English](http://www.anc.org/data/masc/downloads/data-download/)
- [PCAP packet logs](http://pen-testing.sans.org/holiday-challenge/2013)
- Twitter [Bullying Traces Data Set](http://research.cs.wisc.edu/bullying/data.html)
- [twitter corpora and lexica](http://saifmohammad.com/WebPages/lexicons.html)
- [Google NGrams (up to 5-Grams) for 15% of all books up to 2012](http://storage.googleapis.com/books/ngrams/books/datasetsv2.html)
- [Music Match Dataset](http://labrosa.ee.columbia.edu/millionsong/musixmatch#getting)
- [Kaggle news article summarization challenge](https://www.kaggle.com/sunnysai12345/news-summary/data)

## Lexica

Lexica are lists of words that can be used in:

- spell checkers
- regular expressions
- ML classifiers that recognize kinds of words
- lemmatizers, stemmers, and tokenizers
- machine learning systems that predict string labels like part of speech (POS)
- whether it's a URL, or whether it's a proper word spelling in a particular language or dialect.

- [All Top Level Domains (great for regexes that recognize URIs or URLs)](https://domainpunch.com/tlds/)
- [GNU `aspell` Dictionaries in various languages](ftp://ftp.gnu.org/gnu/aspell/dict/0index.html)
- [SCOWL word lists](http://wordlist.aspell.net/)
- [WordNet](http://wordnet.princeton.edu/)
- [dict.org gcide dictionary with definitions](ftp://ftp.gnu.org/gnu/gcide)

### Password Cracking Dictionaries

**!!BE CAREFUL!!**

Password cracking may be illegal in your jurisdiction and the websites that support are often run by people with hacking and cracking "skilz".
So they may try to exploit OS and browser bugs to "own" your machine if you visit these websites.
Some compression formats and implementations have vulnerabilities that allow hackers to run software on your machine when you decompress them.  I've downloaded these files without noticable adverse affects... but a good hack wouldn't be "noticeable" by me. 

- [word lists for password cracking](https://hashcat.net/forum/thread-1236.html)
- [Crack Station 15GB password list](https://crackstation.net/buy-crackstation-wordlist-password-cracking-dictionary.htm) <--donate at your own risk

## AIML (Patterns & Templates)

Open source Artificial Intelligence Markup Language (AIML) files are a great way to give your chatbot a [head start](https://eclkc.ohs.acf.hhs.gov/) in its education:
Though AIML files are referred to as "knowledge bases" by AIML's creators, it's really just a way to specify and share NLP grammars and response templates.
So you can use them anywhere you need grammars or templates.

- Loebner Prize-winning Mitsuku [AIML files](http://www.square-bear.co.uk/aiml) 
- The first AIML-based chatbot, [ALICE](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/aiml-en-us-foundation-alice/aiml-en-us-foundation-alice.v1-9.zip)
- [ALICE AIML files for other languages](http://www.alicebot.org/downloads/sets.html)

## Trained Models

[Official Google News Word2Vec Code & Data](https://code.google.com/archive/p/word2vec/)
[GitHub Mirror of Google News Word2Vec Code & Data](https://github.com/mmihaltz/word2vec-GoogleNews-vectors)
Download Google Drive 1.5GB Word2Vec Model[GoogleNews-vectors-negative300.bin.gz](https://drive.google.com/uc?export=download&id=0B7XkCwpI5KDYNlNUTTlSS21pQmM)