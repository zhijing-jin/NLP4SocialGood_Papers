# Must-Read Papers (and Various Resources) on NLP for Social Good

This is a reading list of papers on NLP for Social Good.

**Contributor:** [Zhijing Jin](http://zhijing-jin.com). If you want to contribute to this reading list, feel free to make pull requests, or issues telling me if you'd like to be a contributor of this GitHub Repo.

### Contents (Actively Updating)

(Hyperlinks only works in Chrome/Firefox/etc, not Safari.)

- [1. Meta-Info](#1-meta-info)
  - [1.1 Events/News](#11-eventsnews)
- [2. Overview Papers](#2-overview-papers)
  - [Proactive NLP](#proactive-nlp)
  - [Self-Defensive NLP](#self-defensive-NLP)
- [3. Equality for all demographics](#4-more-resources)
  - [3.1 (Self-Defensive) Gender/Demographical bias in models and data](#41-causality-papers-from-schoelkopfs-lab-mpi)
    - [Background](#background)
    - [Some recurring author names](#some-recurring-author-names)
    - [Survey/Overview](#surveyoverview)
    - [Gender vs. Embeddings](#gender-vs-embeddings)
    - [Demographics vs. NLP Model Performance](#demographics-vs-nlp-model-performance)
- [4. (Proactive) NLP for studying misinformation](#4-proactive-nlp-for-studying-misinformation)
  - [4.1 Propaganda](#41-propaganda)
  - [4.2 Misinformation](#42-misinformation)
  - [4.3 Fake news](#43-fake-news)
  - [4.4 Bias](#44-bias)
  - [4.5 Fact-checking](#45-fact-checking)
- [5. (Self-Defensive) Mitigating Issues with Dataset Collection](#5-mitigating-issues-with-dataset-collection)
  - [5.1 Promoting data ethic norms for the community](#51-promoting-data-ethic-norms-for-the-community)
  - [5.2 User surveys about their data being used](#52-user-surveys-about-their-data-being-used)
  - [5.3 Improving data quality for ML models](#53-improving-data-quality-for-ML)
- [6. (Proactive + Self-Defensive) NLP for all languages](#6. (Proactive + Self-Defensive) NLP for all languages)
  - [Motivation](#Motivation)
- [7. (Proactive) NLP for mental health](#7.-Proactive-NLP-for mental-health)
  - [Events and Resources](#Events-and-Resources)
- [8. More reading (for Systematic learning)](#8.-More-reading-(for-Systematic-learning))
  - [Courses](#Courses)
- [9. Engagement from Non-Academic Areas](#9.-Engagement-from Non-Academic-Areas)
  - [Non-Profit Movements](#Non-Profit-Movements)
- [10. Resources of (general) AI for social good](#10.-Resources-of-(general)-AI-for-social-good)
- [Acknowledgements](#acknowledgements)



## 1. Meta-Info

### 1.1 Events/News

1. [Workshop] **NLP for Positive Impact**@ACL 2021 [[Call for papers](https://sites.google.com/view/nlp4positiveimpact2021#h.66kopatg0kca) (April 26, 2021)]
   Organized by _Anjalie Field, Shrimai Prabhumoye, Maarten Sap, Zhijing Jin, Jieyu Zhao, Chris Brockett_.
1. ACL 2021 has the new theme track "NLP for Social Good." Accepted papers will be discussed at ACL 2021.

## 2. Overview Papers

1. (ACL 2020) **Give Me Convenience and Give Her Death: Who Should Decide What Uses of NLP are Appropriate, and on What Basis?.** *Kobi Leins, Jey Han Lau, Timothy Baldwin.* 

1. ⭐️ (Cited by 4K+; Daedalus 1980) **Do artifacts have politics?.** Landon Winner. [[pdf](https://web.media.mit.edu/~ascii/papers/winner_1980.pdf)]

   [Summary] Provocative claim that technology be be accurate judged by (1) contributions of efficiency, (2) environmental side effects, and (3) political qualities (i.e., the way they embody specific power and authority). E.g., nuclear power leads to authoritarianism. CORE: tech matters by the social and economic system in which it is embedded.

#### Proactive NLP

Applying NLP to help promote social good tasks, e.g., NLP for poverty, NLP for education, NLP for healthcare, etc.

1. (Linguistics should make contributions in return to society; Language in Society, 1997) **Unequal partnership: Sociolinguistics and the African American speech community.** *John Russell Rickford.* [[pdf](https://scholar.google.com/scholar_url?url=http://johnrickford.com/portals/45/documents/papers/Rickford-1997b-Unequal-Partnership-Sociolinguistics-and-the-African-American-Speech-Community.pdf&hl=en&sa=T&oi=gsb-gga&ct=res&cd=0&d=11235621755930150174&ei=ZJ08YL7LEsbPmAGYsb6gDA&scisig=AAGBfm0s05ZM_0O0Rjm11_dA0eoJ31FB4g)]

#### Self-Defensive NLP

Defending/fixing issues that is within (or closely co-occur with/caused by) NLP technologies, e.g., data privacy, mediating bias of NLP models, green NLP, etc.

1. (ACL 2016) **The Social Impact of Natural Language Processing.** *Dirk Hovy and Shannon L. Spruit.* [[pdf](https://www.aclweb.org/anthology/P16-2096.pdf)]

   [Summary] Introduced issues including (1) exclusion, (2) overgeneralization, (3) exposure inducing bias, topic overexposure, availability heuristic, underexposure. Introduced the concept "dual-use" of NLP models.

1. (Ethical issues with *shared tasks*; NLP Ethics workshop, 2017) **Ethical Considerations in NLP Shared Tasks**. *Carla Parra Escartín, Wessel Reijers, Teresa Lynn, Joss Moorkens, Andy Way, Chao-Hong Liu.* [[pdf](https://www.aclweb.org/anthology/W17-1608.pdf)]

1. (NLP Ethics workshop, 2017) **Gender as a variable in natural-language processing: Ethical considerations.** *Brian N. Larson*. 

   [Summary] Four guidelines:  (1) formulate research questions making explicit theories of what “gender” is; (2) avoid modeling gender unless very relevant; (3) make explicit methods for assigning gender categories; and (4) respect the difficulties gender classification

1. (Women researchers' glass ceiling; EMNLP 2018) **The glass ceiling in NLP.** *Natalie Schluter.* [[pdf](https://www.aclweb.org/anthology/D18-1301.pdf)]

## 3. Equality for all demographics

### 3.1 (Self-Defensive) Gender/Demographical bias in models and data

##### Background

1. (Science 2017) **Semantics derived automatically from language corpora necessarily contain human biases.** *Aylin Caliskan, Joanna J. Bryson, and Arvind Narayanan.* [[pdf](https://arxiv.org/pdf/1608.07187.pdf)]

   [Summary] Not only for machines, but psychology finds that humans also learns to be biased after some language inputs. Reason: Langauage contains recoverable and accurate imprints of our historic biases. Effect: We have various biases, including these are morally neutral as towards insects or flowers, problematic as towards race or gender, or even simply veridical, reflecting the status quo for the distribution of gender with respect to careers or first names.

1. (Book 1999) **Sorting Things Out.** *Geoffrey C. Bowker, Susan Leigh Star.* [[intro](https://ar264sweeney.files.wordpress.com/2015/09/9780262269070_introduction.pdf)]

##### Some recurring author names

- Kai-Wei Chang (UCLA)
- Yoav Goldberg (Bar-Ilan University & Allen AI)
- Dan Jurafsky (Stanford)
- Brendan O'Connor (UMass Amherst)
- Yulia Tsvetkov (CMU)

##### Survey/Overview

1. (arXiv 2020) **Language (Technology) is Power: A Critical Survey of "Bias" in NLP** *Su Lin Blodgett, Solon Barocas, Hal Daumé III, Hanna Wallach.* [[pdf](https://arxiv.org/pdf/2005.14050.pdf)]

   [Summary] Surveyed 147 papers. NLP researchers should articulate (1) what "bias" they mean—i.e., what kinds of system behaviors are harmful, in what ways, to whom, and why, and (2) normative reasoning behind.

1. (Book 2018) **Algorithms of Oppression.** *Safiya Noble.* [[Amazon](https://www.amazon.de/Algorithms-Oppression-Search-Engines-Reinforce/dp/1479837245)]

1. (NIPS Keynote 2017) **The trouble with bias.** *Kate Crawford.*

##### Gender vs. Embeddings

1. (Gender in word embeddings; NIPS 2016) **Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings.** *Tolga Bolukbasi, Kai-Wei Chang, James Zou, Venkatesh Saligrama, Adam Kalai.*

1. (Gender in word embeddings; NAACL 2019) **Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them.** *Hila Gonen, Yoav Goldberg*. [[pdf](https://www.aclweb.org/anthology/N19-1061.pdf)]

   [Summary] Existing methods mostly hiding the bias, not removing it.

1. (Gender in sentence embeddings; NAACL 2019) **On Measuring Social Biases in Sentence Encoders.** *Chandler May, Alex Wang, Shikha Bordia, Samuel R. Bowman, Rachel Rudinger.* [[pdf](https://www.aclweb.org/anthology/N19-1063.pdf)]

1. (Gender in sentence embeddings; NeurIPS 2019) **Assessing Social and Intersectional Biases in Contextualized Word Representations.** *Yi Chern Tan, L. Elisa Celis.* [[pdf](https://arxiv.org/pdf/1911.01485.pdf)]

1. (Gender in word embeddings; ACL 2019 Workshop) **Measuring bias in contextualized word representations. / Quantifying Social Biases in Contextual Word Representations.** *Keita Kurita, Nidhi Vyas, Ayush Pareek, Alan W Black, and Yulia Tsvetkov.* [[pdf](https://arxiv.org/pdf/1906.07337.pdf)]

1. (Gender in coreference resolution; NAACL 2018) **Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods.** *Jieyu Zhao, Tianlu Wang, Mark Yatskar, Vicente Ordonez, Kai-Wei Chang.* [[pdf](https://www.aclweb.org/anthology/N18-2003.pdf)]

1. (Gender in coreference resolution; NAACL 2018) **Gender Bias in Coreference Resolution.** *Rudinger, Jason Naradowsky, Brian Leonard, Benjamin Van Durme.*

1. (Gender and race in sentiment analysis; \*SEM 2018) **Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems.** *Svetlana Kiritchenko, Saif Mohammad.* [[pdf](https://www.aclweb.org/anthology/S18-2005.pdf)]

1. (Gender in POS tagging and parsing; ACL 2019) **Women’s Syntactic Resilience and Men’s Grammatical Luck: Gender-Bias in Part-of-Speech Tagging and Dependency Parsing.** *Aparna Garimella, Carmen Banea, Dirk Hovy, Rada Mihalcea.* [[pdf](https://www.aclweb.org/anthology/P19-1339.pdf)]

1. (Gender in relation extraction; ACL 2020) **Towards Understanding Gender Bias in Relation Extraction.** *Andrew Gaut, Tony Sun, Shirlyn Tang, Yuxin Huang, Jing Qian, Mai ElSherief, Jieyu Zhao, Diba Mirza, Elizabeth Belding, Kai-Wei Chang, William Yang Wang.* [[pdf](https://www.aclweb.org/anthology/2020.acl-main.265.pdf)] [[video](https://slideslive.com/38929244/towards-understanding-gender-bias-in-neural-relation-extraction)] [[data](https://www.aclweb.org/anthology/attachments/2020.acl-main.265.Dataset.zip)]

1. (Gender in MT; Neural Computing and Applications 2019) **Assessing Gender Bias in Machine Translation – A Case Study with Google Translate.** *Marcelo O. R. Prates, Pedro H. C. Avelar, Luis Lamb.* [[pdf](https://arxiv.org/pdf/1809.02208)]

1. (Gender in MT; ACL 2020) **Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem.** *Danielle Saunders, Bill Byrne.* [[pdf](https://arxiv.org/pdf/2004.04498.pdf)]

1. (Gender in MT; EMNLP Findings 2020) **Automatically Identifying Gender Issues in Machine Translation using Perturbations.** *Hila Gonen, Kellie Webster.* [[pdf](https://arxiv.org/pdf/2004.14065.pdf)]

1. (Gender in coreference resolution; ACL 2020) **Toward Gender-Inclusive Coreference Resolution.** *Yang Trista Cao, Hal Daumé III.* [[pdf](https://arxiv.org/pdf/1910.13913.pdf)]

1. (Gender in NER; ACM 2019) **Man is to Person as Woman is to Location: Measuring Gender Bias in Named Entity Recognition.** *Ninareh Mehrabi, Thamme Gowda, Fred Morstatter, Nanyun Peng, Aram Galstyan.* [[pdf](https://arxiv.org/pdf/1910.10872.pdf)]

1. (TACL 2018) **Mind the GAP: A Balanced Corpus of Gendered Ambiguous Pronouns.** *Kellie Webster, Marta Recasens, Vera Axelrod, Jason Baldridge* [[pdf](https://arxiv.org/pdf/1810.05201.pdf)]

1. (EMNLP 2017) **Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints.** *Jieyu Zhao, Tianlu Wang, Mark Yatskar, Vicente Ordonez, Kai-Wei Chang.* [[pdf](https://arxiv.org/pdf/1707.09457.pdf)]

1. (ACL 2020) **Mitigating Gender Bias Amplification in Distribution by Posterior Regularization.** *Shengyu Jia, Tao Meng, Jieyu Zhao, Kai-Wei Chang.* [[pdf](https://arxiv.org/pdf/2005.06251.pdf)]

##### Demographics vs. NLP Model Performance

1. (African American English; EMNLP 2016) **Demographic Dialectal Variation in Social Media: A Case Study of African-American English.** *Su Lin Blodgett, Lisa Green, Brendan O'Connor.* [[pdf](https://arxiv.org/pdf/1608.08868.pdf)]
1. (African American English; PNAS 2020) **Racial Disparity in Automated Speech Recognition.** *Allison Koenecke, Andrew Nam, Emily Lake, Joe Nudell, Minnie Quartey, Zion Mengesha, Connor Toups, John Rickford, Dan Jurafsky, and Sharad Goel.*
1. (ACL 2017 Workshop) **Social Bias in Elicited Natural Language Inferences.** *Rachel Rudinger, Chandler May, Benjamin Van Durme.* [[pdf](https://www.aclweb.org/anthology/W17-1609.pdf)]

1. (Interspeech 2017) **Effects of talker dialect, gender and race on accuracy of Bing speech and YouTube automatic captions.** *Rachael Tatman, Conner Kasten.* [[pdf](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1746.PDF)]
1. (Annual Review of Political Science 2016) **Race as a Bundle of Sticks: Designs that Estimate Effects of Seemingly Immutable Characteristics.** *Maya Sen, Omar Wasow.* [[pdf](https://scholar.harvard.edu/files/msen/files/race_causality.pdf)]
1. (KDD 2017 Workshop) **Racial Disparity in Natural Language Processing: A Case Study of Social Media African-American English.** *Su Lin Blodgett, Brendan O'Connor.* [[pdf](https://arxiv.org/pdf/1707.00061.pdf)]

## 4. (Proactive) NLP for studying misinformation

##### 4.1 Propaganda

1. (EMNLP 2018) **Framing and Agenda-setting in Russian News: a Computational Analysis of Intricate Political Strategies.** *Anjalie Field, Doron Kliger, Shuly Wintner, Jennifer Pan, Dan Jurafsky, and Yulia Tsvetkov.* [[pdf](https://www.aclweb.org/anthology/D18-1393.pdf)](EMNLP 2019) **Fine-Grained Analysis of Propaganda in News Articles.** *Giovanni Da San Martino, Seunghak Yu, Alberto Barrón-Cedeño, Rostislav Petrov, Preslav Nakov.* [[pdf](https://www.aclweb.org/anthology/D19-1565.pdf)]
1. (arXiv 2020) **Pro-Russian Biases in Anti-Chinese Tweets about the Novel Coronavirus.** *Autumn Toney, Akshat Pandey, Wei Guo, David Broniatowski, Aylin Caliskan.* [pdf]
1. (Internet Policy Review 2019) **Technology, autonomy, and manipulation.** *Daniel Susser, Beate Roessler, Helen Nissenbaum.* [[pdf](https://nissenbaum.tech.cornell.edu/papers/Technology,%20Autonomy,%20and%20Manipulation.pdf)]

##### 4.2 Misinformation

1. (arXiv 2020) **You are right. I am ALARMED -- But by Climate Change Counter Movement.** *Shraey Bhatia, Jey Han Lau, Timothy Baldwin.* [[pdf](https://arxiv.org/pdf/2004.14907.pdf)]
1. (iConference 2014) **Rumors, False Flags, and Digital Vigilantes: Misinformation on Twitter after the 2013 Boston Marathon Bombing.**  *Kate Starbird, Jim Maddock, Mania Orand, Peg Achterman, Robert M. Mason.* [[pdf](https://www.ideals.illinois.edu/bitstream/handle/2142/47257/308_ready.pdf?sequence=2&isAllowed=y)]
1. (Nature 2020) **The online competition between pro- and anti-vaccination views.** *Neil F. Johnson, Nicolas Velásquez, Nicholas Johnson Restrepo, Rhys Leahy, Nicholas Gabriel, Sara El Oud, Minzhang Zheng, Pedro Manrique, Stefan Wuchty, Yonatan Lupu.* [[pdf](https://www.nature.com/articles/s41586-020-2281-1.pdf)]
1. (ICWSM 2014) **Rumor Cascades.** *Adrien Friggeri, Lada A. Adamic, Dean Eckles, Justin Cheng.* [[pdf](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM14/paper/viewFile/8122/8110)]
1. (AJPH 2018) **Weaponized Health Communication: Twitter Bots and Russian Trolls Amplify the Vaccine Debate.** *David A Broniatowski, Amelia M Jamison, SiHua Qi, Lulwah AlKulaib, Tao Chen, Adrian Benton, Sandra C Quinn, Mark Dredze.* [[pdf](https://ajph.aphapublications.org/doi/pdf/10.2105/AJPH.2018.304567)]
1. (Wired article 2020) **The Professors Who Call ‘Bullshit’ on Covid-19 Misinformation.** *Jevin West, Carl Bergstrom.* [[website](https://www.wired.com/story/professors-call-bullshit-covid-19-misinformation/)]

##### 4.3 Fake news

1. (Journal of economic perspectives 2017) **Social Media and Fake News in the 2016 Election.** *Hunt Allcott, Matthew Gentzkow.* [[pdf](https://web.stanford.edu/~gentzkow/research/fakenews.pdf)]
1. (Science 2018) **The spread of true and false news online.** *Vosoughi, Soroush, Deb Roy, and Sinan Aral*. [[pdf](https://ide.mit.edu/sites/default/files/publications/2017%20IDE%20Research%20Brief%20False%20News.pdf)]

##### 4.4 Bias

1. (arXiv 2020) **Automatically Characterizing Targeted Information Operations Through Biases Present in Discourse on Twitter.** *Autumn Toney, Akshat Pandey, Wei Guo, David Broniatowski, Aylin Caliskan.* [[pdf](https://arxiv.org/pdf/2004.08726)]

##### 4.5 Fact-checking

1. (EMNLP 2019) **MultiFC: A Real-World Multi-Domain Dataset for Evidence-Based Fact Checking of Claims.** *Augenstein, Isabelle, Christina Lioma, Dongsheng Wang, Lucas Chaves Lima, Casper Hansen, Christian Hansen, and Jakob Grue Simonsen.* [[pdf](https://www.aclweb.org/anthology/D19-1475.pdf)]
1. (CL 2020) **The Limitations of Stylometry for Detecting Machine-Generated Fake News.** *Tal Schuster, Roei Schuster, Darsh J Shah, Regina Barzilay.* [[pdf](https://arxiv.org/pdf/1908.09805.pdf)]
1. (NeurIPS 2019) **Defending Against Neural Fake News.** *Rowan Zellers, Ari Holtzman, Hannah Rashkin, Yonatan Bisk, Ali Farhadi, Franziska Roesner, Yejin Choi.* [[pdf](https://proceedings.neurips.cc/paper/2019/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf)]
1. (NAACL 2018) **FEVER: a large-scale dataset for Fact Extraction and VERification.** *James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal.* [[pdf](https://www.aclweb.org/anthology/N18-1074.pdf)]

## 5. (Self-Defensive) Mitigating Issues with Dataset Collection

**Motivation:** Public social media data can invade user privacy.

- **The Common Rule: The Federal Policy for the Protection of Human Subjects.** [[45 CFR part 46](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/45-cfr-46/index.html)]

- (Human Rights: On Nuremberg Code; New England Journal of Medicine 1997) **Fifty years later: the significance of the Nuremberg Code.** *Evelyne Shuster.* [[paper](https://www.nejm.org/doi/full/10.1056/NEJM199711133372006)]

- **ACM Code of Ethics.**

  [Summary] Papers should 1.2 Avoid harm; 1.4 Be fair and take action not to discriminate; 1.6 Respect privacy; 2.6 Perform work only in areas of competence; and 3.1 Ensure that the public good is the central concern during all professional computing work.

#### 5.1 Promoting data ethic norms for the community

1. (TACL 2018) **Data statements for NLP: Toward mitigating system bias and enabling better science.** *Emily Bender and Batya Friedman*. [[pdf](https://www.mitpressjournals.org/doi/pdf/10.1162/tacl_a_00041)]

1. (arXiv 2020) **Datasheets for Datasets.** *Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna Wallach, Hal Daumé III, Kate Crawford.* [[pdf](https://arxiv.org/pdf/1803.09010.pdf)]

1. (CSCW 2016) **Beyond the Belmont Principles: Ethical Challenges, Practices, and Beliefs in the Online Data Research Community.** *Jessica Vitak, Katie Shilton, Zahra Ashktorab.* [[pdf](https://terpconnect.umd.edu/~kshilton/pdf/VitaketalCSCWpreprint.pdf)]

   [Summary] A survey of 200+ researchers' current practice

1. (Nature Digital Medicine 2018) **Don't quote me: reverse identification of research participants in social media studies.** *John W Ayers, Theodore L Caputi, Camille Nebeker, Mark Dredze.* [[pdf](https://www.nature.com/articles/s41746-018-0036-2.pdf)]

   [Summary] Do not quote users. 72% articles quoted tweets, and the tweeter can be identified 84% of the time.

#### 5.2 User surveys about their data being used

1. (Social Media + Society 2018) **"Participant" Perception of Twitter research ethics.** *Casey Fiesler and Nicholas Proferes.* [[pdf](https://journals.sagepub.com/doi/pdf/10.1177/2056305118763366)]

   [Summary] (1) Few users knew their public tweets could be used by researchers; (2) The majority thought their consent is important

1. (Sociology 2017) **Towards an Ethical Framework for Publishing Twitter Data in Social Research: Taking into Account Users’ Views, Online Context and Algorithmic Estimation.** *Matthew L Williams, Pete Burnap, Luke Sloan.* [[pdf](https://journals.sagepub.com/doi/pdf/10.1177/0038038517708140?source=post_page---------------------------)]

#### 5.3 Improving data quality for ML models

1. (ACM FAT* 2020) **Garbage In, Garbage Out? Do Machine Learning Application Papers in Social Computing Report Where Human-Labeled Training Data Comes From?** *Stuart Geiger, Kevin Yu, Yanlai Yang, Mindy Dai, Jie Qiu, Rebekah Tang, Jenny Huang.* [[pdf](https://arxiv.org/pdf/1912.08320.pdf)]

   [Summary] Inspecting papers to see whether the data collection process is reasonable.

1. (SIGdial 2007) **Comparing Spoken Dialog Corpora Collected with Recruited Subjects versus Real Users.** *Hua Ai, Antoine Raux, Dan Bohus, Maxine Eskenazi, Diane Litman.* [[pdf](https://www.aclweb.org/anthology/2007.sigdial-1.23.pdf)]

   [Summary] Recruited subjects talk more and faster, while real users ask for more help and more frequently interrupt the system.

## 6. (Proactive + Self-Defensive) NLP for all languages

**[Main focus]** Spreading the benefit of NLP to low-resource languages; equal gender ratio.

#### Motivation

1. (ACL 2020) **The State and Fate of Linguistic Diversity and Inclusion in the NLP World.** *Pratik Joshi, Sebastin Santy, Amar Budhiraja, Kalika Bali, and Monojit Choudhury.* [[pdf](https://arxiv.org/pdf/2004.09095.pdf)]

   [Summary] Only very few out of >7000 languages are represented in NLP.

## 7. (Proactive) NLP for mental health

1. **Large-scale Analysis of Counseling Conversations: An Application of Natural Language Processing to Mental Health.** _Tim Althoff, Kevin Clark, Jure Leskovec_. [[pdf](https://www.aclweb.org/anthology/Q16-1033.pdf)][[slides@Stanford](https://web.stanford.edu/class/cs124/lec/counseling_slides.pdf)] [[video](https://vimeo.com/239248873)]

#### Events and Resources

1. (Every year) CLPsych: Computational Linguistics and Clinical Psychology Workshop [[website](https://clpsych.org/)]

1. Research Fellowship Program (3-6 months) [[FAQ](https://docs.google.com/document/d/1_uQrOapzwy1JA8j38PX9unXDC_dzMyO7HT9jnhjxLEY/edit)]

## 8. (Proactive) NLP for education

1. (AIED 2015) **Educational Question Answering Motivated by Question-Specific Concept Maps.** _Thushari Atapattu, Katrina Falkner, Nickolas Falkner_. [[pdf](https://scholar.google.com/scholar_url?url=https://www.researchgate.net/profile/Thushari_Atapattu/publication/273460094_Educational_Question_Answering_Motivated_by_Question-Specific_Concept_Maps/links/55a5007008aef604aa0415a7.pdf&hl=en&sa=T&oi=gsb-gga&ct=res&cd=0&d=16059197396106165671&ei=g4c-YOaXJo-Ny9YPk6ib2Ac&scisig=AAGBfm2C12qBDEbcS4AiXLBYJ_OTuoVnmQ)]

## 9. More reading (for Systematic learning)

### 9.1 Courses

1. **Stanford CS 384: Ethical and Social Issues in NLP.** _Dan Jurafsky_. [[lectures](https://web.stanford.edu/class/cs384/)]
1. **Computational Ethics for NLP.** [Yulia Tsvetkov](http://www.cs.cmu.edu/~ytsvetko/) and [Alan Black](http://www.cs.cmu.edu/~awb/). [[lectures](http://demo.clab.cs.cmu.edu/ethical_nlp2020/)]
1. **Ethics in NLP.** [Emily Bender](http://faculty.washington.edu/ebender/). [[lectures](https://faculty.washington.edu/ebender/2017_575/)]

## 10. Engagement from Non-Academic Areas

### Non-Profit Movements

- (EA Movement) 80,000 Hours -> Career advice to design your career time (80,000 hours) in the rational way to optimize social good.

## 11. Resources of (general) AI for social good

1. **Introduction to Key Concepts in AI and Machine Learning for Good.** _James Weis, Geeticka Chauhan_. [[slides](https://drive.google.com/file/d/1Bgls-veTF0vMlEm-0xerbMsQm7MGccxw/view)]

## Acknowledgements

Lots of credits to the [reading list](https://web.stanford.edu/class/cs384/) of Stanford CS384.
