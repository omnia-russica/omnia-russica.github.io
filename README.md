


# Omnia Russica 



![](/assets/banner2.png)  { width: 600px; }

## About
Omnia Russica (_lat. all Russian_) is an open source corpus project, containing 33 billion words.

Omnia Russica is combining major Russian corpus sources within one pipeline


|                  | Format     | Morphology | Syntax | Size  |
|------------------|------------|------------|--------|-------|
| Wikipedia        | vertical   | TreeTagger | None   | 0.5 G |
| Taiga            | CoNLL-U    | UDpipe     | UDpipe | 4.5 G |
| Araneum Russicum | vertical   | TreeTagger | None   | 25 G  |
| Common Crawl     | Plain text | None       | None   | 3 G   |


### Download
[Download plain text data (97 Gb)](url)


### Web Interface
We have noSketch Engine search interface [here](http://unesco.uniba.sk/guest)


###  Contact and cite us

 - omnia.russica@yandex.ru

 - T.Shavrina and V.Benko (2019) Omnia Russica: Even larger Russian corpus. In Proc.Corpora. 
 
Check out our [documentation on github](https://github.com/omnia-russica/pipeline) 

### Pipeline

For merging the data, the following principles are applied:
 - metadata contained in the respective parts should be preserved;
 - the primary format will be (No)SkE-compatible vertical, CoNLL-U format can be obtained by conversion if necessary;
 - all data will be tagged both by UDPipe and TreeTagger at first, with possible more annotations added in the future;
 - both original and deduplicated version will be available;
 - for online search, the corpus will be processed by NoSketch Engine.
    
    
At the time of writing this paper (May 2019), all respective data has been collected and preprocessed, except Common Crawl part, which is still being scaled to the limit. Now, the Wikipedia and Araneum Russicum corpora need to be retagged by UDPipe, and Taiga by TreeTagger to get a uniform format suitable for subsequent merging and optional deduplication; Common Crawl part should be  also deduplicated and processed. 
