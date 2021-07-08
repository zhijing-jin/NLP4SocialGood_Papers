# Must-Read Papers (and Various Resources) on NLP for Social Good

This is a reading list of papers on NLP for Social Good.

**Contributor:** [Zhijing Jin](http://zhijing-jin.com). If you want to contribute to this reading list, feel free to make pull requests, or issues telling me if you'd like to be a contributor of this GitHub Repo.

### Contents (Actively Updating)

(Hyperlinks only works in Chrome/Firefox/etc, not Safari.)

- [Meta-Info](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#meta-info)
  - [Events and News](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#events-and-news)
  - [Overview Papers](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#overview-papers)
    - [Proactive NLP](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#overview-of-proactive-nlp-to-help-social-good), [Patching NLP's intrinsic problems](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#overview-of-methods-to-patch-intrinsic-problems-with-nlp-research-side-effects)
- [Q1: Can we use NLP to **save** lifes?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#q1-can-we-use-nlp-to-save-lifes)
  - [1.1 NLP for healthcare (with EHRs)](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#11-nlp-for-healthcare-with-ehrs)
    - [Reviews](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#reviews), [NLP on clinical notes](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#nlp-on-clinical-notes), [NLP to facilitate biomedical research](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#nlp-to-facilitate-biomedical-research), [NLP to help reduce bias in Healthcare](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#nlp-to-help-reduce-bias-in-healthcare)
  - [1.2 NLP for disaster response](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#12-nlp-for-disaster-response)
  - [1.3. NLP to detect armed conflicts](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#13-nlp-to-detect-armed-conflicts)
- [Q2: Can we use NLP to **improve** lives?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#q2-can-we-use-nlp-to-improve-lives) 
  - [2.1 Knowledge is power - NLP for education](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#21-nlp-for-education)
  - [2.2 How to make people happier? - NLP for mental health](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#22-nlp-for-mental-health)
    - [Psychotherapy and counseling](#psychotherapy-and-counseling), [NLP for happiness](#nlp-for-happiness), [Mental health on social media (e.g., hate speech, hope speech)](#mental-health-on-social-media-eg-hate-speech-hope-speech), [Mental health through other text forms](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#mental-health-through-other-text-forms), [Workshops and Resources](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#workshops-and-resources)
- [Q3: Can we use NLP to **help the common future** of all humans?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#q3-can-we-use-nlp-to-help-the-common-future-of-all-humans)
  - [3.1 NLP for climate change](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#31-nlp-for-climate-change)
  - [3.2 NLP for Human Rights](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#32-nlp-for-human-rights)
    - [Detecting Human Right Violation](#detecting-human-right-violation), [Caveat: NLP for Privacy Invasion/Surveilance](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#please-dont-use-nlp-in-this-way-nlp-for-privacy-invasionsurveilance)
  - [3.2 Fight against the manipulation of thoughts](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#33-fight-against-the-manipulation-of-thoughts)
    - [Studying the existing trend](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#studying-the-existing-trend), [Studying media manipulation for political reasons](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#studying-media-manipulation-for-political-reasons), [Fake news and misinformation](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#fake-news-and-misinformation).
- [Q4: Can we use NLP to help make all people **equal**?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#q4-can-we-use-nlp-to-help-make-all-people-equal)
  - [4.1 NLP for all languages](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#41-nlp-for-all-languages)
  - [4.2 NLP for gender/demographical equality](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#42-nlp-for-genderdemographical-equality)
    - [NLP to detect bias](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#nlp-to-detect-bias), [NLP to detect bias specifically on social media](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#nlp-to-detect-bias-specifically-on-social-media)
- [Q5: Are there concerns over the practice of NLP? Can we mitigate this?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#q5-are-there-concerns-over-the-practice-of-nlp-can-we-mitigate-this)
  - [5.1 Prevent future scandals of conversational bots - How dialog systems should handle verbal abuse](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#51-prevent-future-scandals-of-conversational-bots---how-dialog-systems-should-handle-verbal-abuse)
  - [5.2 Who protects my privacy? - Privacy Issues with Dataset Collection](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#52-who-protects-my-privacy---privacy-issues-with-dataset-collection)
    - [Promoting data ethic norms for the community](#promoting-data-ethic-norms-for-the-community), [User surveys about their data being used](#user-surveys-about-their-data-being-used), [Building models that preserves privacy](#building-models-that-preserves-privacy), [Improving data quality for ML models](#improving-data-quality-for-ML-models)
  - [5.3 Can we prevent our model from being a sexist/racist/etc?](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#53-can-we-prevent-our-model-from-being-a-sexistracistetc)
    - [Gender/Demographical bias in models and data - Background](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#genderdemographical-bias-in-models-and-data---background), [Survey/Overview](Survey/Overview), [Gender vs. Embeddings](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#gender-vs-embeddings), [Demographics vs. NLP Model Performance](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#demographics-vs-nlp-model-performance), [Algorithmic fairness](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#algorithmic-fairness), [Caveats of Large Language Models](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#caveats-of-large-language-models).
  - [5.4 Can we save energy when training NLP models? - GreenNLP](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#54-can-we-save-energy-when-training-nlp-models---greennlp)
  - [5.5 Be alert of recommendation systems](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#55-be-alert-of-recommendation-systems)
  - [5.6 Equip AI with the same morals as humans](#56-equip-ai-with-the-same-morals-as-humans)
- [More reading (for Systematic learning)](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#more-reading-for-systematic-learning)
  - [Courses](#courses)
- [Engagement from Non-Academic Areas](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#engagement-from-non-academic-areas)
  - [Non-Profit Movements](#non-profit-movements)
- [Resources of (general) AI for social good](https://github.com/zhijing-jin/NLP4SocialGood_Papers/blob/main/README.md#resources-of-general-ai-for-social-good)
- [Acknowledgements](#acknowledgements)




## Meta-Info

### Events and News

1. [Workshop] **NLP for Positive Impact**@ACL 2021 [[Website](https://sites.google.com/view/nlp4positiveimpact2021)]
   Organized by _Anjalie Field, Shrimai Prabhumoye, Maarten Sap, Zhijing Jin, Jieyu Zhao, Chris Brockett_.
2. ACL 2021 has the new theme track "NLP for Social Good." Accepted papers will be discussed at ACL 2021.

3. Ethics in NLP - ACL Wiki. [[Website](https://aclweb.org/aclwiki/Ethics_in_NLP)]

### Overview Papers

1. (2021 ACL Findings) **How Good Is NLP? A Sober Look at NLP Tasks through the Lens of Social Impact.**
   _Zhijing Jin, Geeticka Chauhan, Brian Tse, Mrinmaya Sachan, Rada Mihalcea_.
   [[pdf](https://arxiv.org/pdf/2106.02359.pdf)]

2. (2020 ACL) **Give Me Convenience and Give Her Death: Who Should Decide What Uses of NLP are Appropriate, and on What Basis?.** *Kobi Leins, Jey Han Lau, Timothy Baldwin.* [[pdf](https://www.aclweb.org/anthology/2020.acl-main.261.pdf)]

#### Overview of proactive NLP to help social good

Applying NLP to help promote social good tasks, e.g., NLP for poverty, NLP for education, NLP for healthcare, etc.

1. (1997, Language in Society; Linguistics should make contributions in return to society) **Unequal partnership: Sociolinguistics and the African American speech community.** *John Russell Rickford.* [[pdf](https://scholar.google.com/scholar_url?url=http://johnrickford.com/portals/45/documents/papers/Rickford-1997b-Unequal-Partnership-Sociolinguistics-and-the-African-American-Speech-Community.pdf&hl=en&sa=T&oi=gsb-gga&ct=res&cd=0&d=11235621755930150174&ei=ZJ08YL7LEsbPmAGYsb6gDA&scisig=AAGBfm0s05ZM_0O0Rjm11_dA0eoJ31FB4g)]

2. (1980 Daedalus; High-level discussion of the function of technology) **Do artifacts have politics?.** Landon Winner. [[pdf](https://web.media.mit.edu/~ascii/papers/winner_1980.pdf)]

   [Summary] Provocative claim that technology be be accurate judged by (1) contributions of efficiency, (2) environmental side effects, and (3) political qualities (i.e., the way they embody specific power and authority). E.g., nuclear power leads to authoritarianism. CORE: tech matters by the social and economic system in which it is embedded.

#### Overview of methods to patch intrinsic problems with NLP research (side effects)

Defending/fixing issues that is within (or closely co-occur with/caused by) NLP technologies, e.g., data privacy, mediating bias of NLP models, green NLP, etc.

1. (2016 ACL) **The Social Impact of Natural Language Processing.** *Dirk Hovy and Shannon L. Spruit.* [[pdf](https://www.aclweb.org/anthology/P16-2096.pdf)]

   [Summary] Introduced issues including (1) exclusion, (2) overgeneralization, (3) exposure inducing bias, topic overexposure, availability heuristic, underexposure. Introduced the concept "dual-use" of NLP models.

2. (2017, NLP Ethics workshop; Ethical issues with *shared tasks*) **Ethical Considerations in NLP Shared Tasks**. *Carla Parra Escartín, Wessel Reijers, Teresa Lynn, Joss Moorkens, Andy Way, Chao-Hong Liu.* [[pdf](https://www.aclweb.org/anthology/W17-1608.pdf)]

3. (2017 NLP Ethics workshop) **Gender as a variable in natural-language processing: Ethical considerations.** *Brian N. Larson*. 

   [Summary] Four guidelines:  (1) formulate research questions making explicit theories of what “gender” is; (2) avoid modeling gender unless very relevant; (3) make explicit methods for assigning gender categories; and (4) respect the difficulties gender classification

4. (2018 EMNLP; Women researchers' glass ceiling) **The glass ceiling in NLP.** *Natalie Schluter.* [[pdf](https://www.aclweb.org/anthology/D18-1301.pdf)]

## Q1: Can we use NLP to **save** lifes?

### 1.1 NLP for healthcare (with EHRs)

#### Reviews

1. (2020 AMIA) **A Review of Challenges and Opportunities in Machine Learning for Health.** _Marzyeh Ghassemi, Tristan Naumann, Peter Schulam, Andrew Beam, Irene Chen, Rajesh Ranganath_. [[pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7233077/)]

   [Summary] E.g., Understanding causality is key

2. (2020 arXiv) **Ethical Machine Learning in Health Care.** _Irene Chen, Emma Pierson, Sherri Rose, Shalmali Joshi, Kadija Ferryman, Marzyeh Ghassemi_. [[pdf](https://arxiv.org/pdf/2009.10576.pdf)]


#### NLP on clinical notes

1. (2017 JAMIA) **De-identification of patient notes with recurrent neural networks**. _Franck Dernoncourt, Ji Young Lee, Ozlem Uzuner, Peter Szolovits_.
   [[pdf](https://arxiv.org/pdf/1606.03475)]
2. (2018 JAMIA) **Segment convolutional neural networks (Seg-CNNs) for classifying relations in clinical notes.** _Yuan Luo, Yu Cheng, Özlem Uzuner, Peter Szolovits, Justin Starren_. [[pdf](http://groups.csail.mit.edu/medg/ftp/psz-papers/J%20Am%20Med%20Inform%20Assoc%202017%20Luo.pdf)]
3. (2020, Machine Learning for Healthcare) **Fast, Structured Clinical Documentation via Contextual Autocomplete.** _Divya Gopinath, Monica Agrawal, Luke Murray, Steven Horng, David Karger, David Sontag_. [[pdf](https://arxiv.org/pdf/2007.15153)]
4. (2020 AAHPM; NER for heart disease patients) **An Artificial Intelligence Algorithm to Identify Documented Symptoms in Patients with Heart Failure who Received Cardiac Resynchronization Therapy** _Richard Leiter, Enrico Santus, Zhijing Jin, Katherine Lee, Miryam Yusufov, Isabel Chien, Ashwin Ramaswamy, Edward Moseley, Yujie Qian, Deborah Schrag, Charlotta Lindvall_. [[abstract](https://www.sciencedirect.com/science/article/pii/S0885392420305248?casa_token=8RfqMdn4AC0AAAAA:qDJ7TTlb1r8YItKnwp5bzPQiiY7OIKZhZFnkb9HgM2irMNWSN1TPIl15vjRjG7ZgN9nLZ7gf)] [[paper](http://zhijing-jin.com/files/papers/NLP_for_CRT.pdf)]
5. (2021 PSB Oral, Intimate Partner Violence prediction) **Intimate Partner Violence and Injury Prediction From Radiology Reports.** _Irene Y. Chen, Emily Alsentzer, Hyesun Park, Richard Thomas, Babina Gosangi, Rahul Gujrathi, Bharti Khurana_. [[pdf](https://arxiv.org/pdf/2009.09084.pdf)]
6. (2020 MLH) **UPSTAGE: Unsupervised Context Augmentation for Utterance Classification in Patient-Provider Communication.** *Do June Min, Veronica Perez-Rosas, Shihchen Kuo, William H. Herman, Rada Mihalcea*. [[pdf](http://proceedings.mlr.press/v126/min20a/min20a.pdf)]

#### NLP to facilitate biomedical research

1. **CORD-19: The COVID-19 Open Research Dataset.**
   _Lucy Lu Wang, Kyle Lo, Yoganand Chandrasekhar, Russell Reas, Jiangjiang Yang, Doug Burdick, Darrin Eide, Kathryn Funk, Yannis Katsis, Rodney Kinney, Yunyao Li, Ziyang Liu, William Merrill, Paul Mooney, Dewey Murdick, Devvret Rishi, Jerry Sheehan, Zhihong Shen, Brandon Stilson, Alex Wade, Kuansan Wang, Nancy Xin Ru Wang, Chris Wilhelm, Boya Xie, Douglas Raymond, Daniel S. Weld, Oren Etzioni, Sebastian Kohlmeier_.
   [[pdf](https://arxiv.org/pdf/2004.10706.pdf)]

#### NLP to help reduce bias in Healthcare

1. (2019, AMA Journal of Ethics) **Can AI Help Reduce Disparities in General Medical and Mental Health Care?.** _Irene Y. Chen, Peter Szolovits, and Marzyeh Ghassemi_.
   [[pdf](https://journalofethics.ama-assn.org/sites/journalofethics.ama-assn.org/files/2019-01/org1-1902_0.pdf)]

    [Summary] There is bias w.r.t. gender, insurance type, etc.


### 1.2 NLP for disaster response

1. (2020 IEEE) **The Ivory Tower Lost: How College Students Respond Differently than the General Public to the COVID-19 Pandemic.**
   _Viet Duong, Phu Pham, Tongyu Yang, Yu Wang, Jiebo Luo_. [[pdf](https://arxiv.org/pdf/2004.09968.pdf)]

### 1.3 NLP to detect armed conflicts

#### Resources and Datasets

1. **The Armed Conflict Location & Event Data Project.** [[link](https://acleddata.com/#/dashboard)]
2. (2016 ACL) **IBC-C: A Dataset for Armed Conflict Event Analysis.** _Andrej Žukov-Gregorič, Zhiyuan Luo, Bartal Veyhe_. [[pdf](https://aclanthology.org/P16-2061.pdf)]

#### Models

1. (2019 CSS Book Chapter) **Text as Data for Conflict Research: A Literature Survey.** _Seraphine F. MaerzCornelius Puschmann_. [[pdf](https://link.springer.com/chapter/10.1007/978-3-030-29333-8_3)]
2. (Talk@Google) **Towards an NLP Pipeline for Conflict Narrative Detection.** _Stephen Anning, George Konstantinidis, Craig Webber_. [[link](https://sorse.github.io/programme/talks/event-006/)]
3. (2019 ACL Workshop) **One-to-X Analogical Reasoning on Word Embeddings: a Case for Diachronic Armed Conflict Prediction from News Texts.**
   _Andrey Kutuzov, Erik Velldal, Lilja Øvrelid_. [[pdf](https://aclanthology.org/W19-4724.pdf)]
4. (2017 ACL Workshop) **Tracing armed conflicts with diachronic word embedding models.** _Andrey Kutuzov, Erik Velldal, Lilja Øvrelid_. [[pdf](https://aclanthology.org/W17-2705.pdf)]
5. (2012, International Interactions) **Event Data on Armed Conflict and Security: New Perspectives, Old Challenges, and Some Solutions.** _Sven Chojnacki, Christian Ickler, Michael Spies, John Wiesel_. [[pdf](https://www.conflict-data.org/publications/EDACS/EDACS__Naked/Chojnacki_etal_IntIA_2012_forthcoming.pdf)]



## Q2: Can we use NLP to **improve** lives?

### 2.1 NLP for Education

1. (2021 EACL Workshop) 16th Workshop on Innovative Use of NLP for Building Educational Applications [[website](https://sig-edu.org/bea/current)]

#### Improving textbooks

1. (2010 ACM Symposium) **Enriching Textbooks Through Data Mining.** _Rakesh Agrawal, Sreenivas Gollapudi, Krishnaram Kenthapadi, Nitish Srivastava, Raja Velu_. [[pdf](http://theory.stanford.edu/~kngk/papers/enrichingTextbooksThroughDataMining-DEV2010.pdf)]

#### Automatic grading

1. (2016 EMNLP) **A Neural Approach to Automated Essay Scoring.** _Kaveh Taghipour, Hwee Tou Ng_. [[pdf](https://www.aclweb.org/anthology/D16-1193.pdf)]
2. (2018 ICCL) **Automated Scoring: Beyond Natural Language Processing.** _Nitin Madnani, Aoife Cahill_. [[pdf](https://www.aclweb.org/anthology/C18-1094.pdf)]

#### Plagiarism detection

1. (2010 IPC) **Using Natural Language Processing for Automatic Detection of Plagiarism.** _Miranda Chong, Lucia Specia, Rusian Mitkov_. [[pdf](https://d1wqtxts1xzle7.cloudfront.net/40077408/Using_Natural_Language_Processing_for_Au20151116-27205-18j9w7z.pdf?1447706034=&response-content-disposition=inline%3B+filename%3DUsing_Natural_Language_Processing_for_Au.pdf&Expires=1614716474&Signature=HWqblSJY74yWBo0jzE4c82-dqyAk2ckBxGi1H09FReus2fdP4Y7v13Eupfdds5nA5zBGrgMs6WHqkTgESGaXetdUkzRHHXF6tmFn2618XGLkfoX5Xkl4kyHpmjl5Haq2lGC0rxXtQoSlVnm8K0kJbGVYn3g2ubXscwRTXS7LvzUWYrAokLXEfgqYAcoPoxbVTbdxlKEdbHvqjnUNiTOjnmTQMIAynoyY9QWC-E6N7uskMz69IS4MNwD11pLNi4KFOQnNip5SFZaGwhncmLzJj6KUYaJCH1odj~imz~t99KqwYZ0HQuPj3ZeeQQCSw0n~~GllGpPixB6c6-lC4x3S9w__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)] [[poster](http://clg.wlv.ac.uk/news/ChongM_regionalposter2010.pdf)]

#### Educational Question Answering

1. (2015 AIED) **Educational Question Answering Motivated by Question-Specific Concept Maps.** _Thushari Atapattu, Katrina Falkner, Nickolas Falkner_. [[pdf](https://scholar.google.com/scholar_url?url=https://www.researchgate.net/profile/Thushari_Atapattu/publication/273460094_Educational_Question_Answering_Motivated_by_Question-Specific_Concept_Maps/links/55a5007008aef604aa0415a7.pdf&hl=en&sa=T&oi=gsb-gga&ct=res&cd=0&d=16059197396106165671&ei=g4c-YOaXJo-Ny9YPk6ib2Ac&scisig=AAGBfm2C12qBDEbcS4AiXLBYJ_OTuoVnmQ)]
2. (2016 IEEE) **Question answering system on education acts using NLP techniques.** _Sweta P Lende and MM Raghuwanshi_. [[paper](https://ieeexplore.ieee.org/document/7583963)]

#### Reading/writing assistants

(e.g. writing assistants for Microsoft Word or Google Docs)

1. (2019 EMNLP) **Modeling the Relationship between User Comments and Edits in Document Revision.**
   _Xuchao Zhang, Dheeraj Rajagopal, Michael Gamon, Sujay Kumar Jauhar, ChangTien Lu_.
   [[pdf](https://www.aclweb.org/anthology/D19-1505.pdf)]
2. (2020 CSCW) **Characterizing Stage-Aware Writing Assistance in Collaborative Document Authoring.**
   _Bahareh Sarrafzadeh, Sujay Kumar Jauhar, Michael Gamon, Edward Lank, Ryen White_.
   [[pdf](https://arxiv.org/pdf/2008.08165.pdf)]

#### First, second (and subsequent) language learning

1. (2012, The encyclopedia of applied linguistics) **Natural Language Processing and Language Learning.** _Detmar Meurers_. [[pdf](http://tjure.sfs.uni-tuebingen.de/~dm/papers/meurers-11.pdf)]

#### Educational data mining from student data logs

1. (2010 ICEE) **Data Mining and Student e-Learning Profiles.** _Mingming  Zhou._ [[pdf](https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel5/5589107/5590383/05592904.pdf%3Fcasa_token%3DQanxy6EpahAAAAAA:buomiAvCVRQ8z2iBtWeS-aKYOHrnJyYYZinSpw67943TK1SAQU_ICN3XXYqzhGKEOsUTcLhG&hl=en&sa=T&oi=gsb-gga&ct=res&cd=0&d=17473948150158469748&ei=xZE-YMTKKIi8ywTr17_gDg&scisig=AAGBfm21cr6Y-CdflmrZLTQdfnG_FD9ysg)]

#### Multimodal student-computer interaction

1. (2020 ICBL) **A Multimodal Human-Computer Interaction System and Its Application in Smart Learning Environments.** _Jiyou Jia, Yunfan He, Huixiao Le_. [[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-51968-1_1)]

#### Potential new directions to pursue

1. NLP for career path counseling
2. Tools for learners with disabilities
3. NLP for compiling Google searched articles to youth-friendly teaching materials
4. Student personalization and engagement: assessment of learners’ language and cognitive skill levels and systems that detect and adapt to learners’ cognitive or emotional states

### 2.2 NLP for mental health

#### Psychotherapy and counseling

1. (2020 ACL) **What Makes a Good Counselor? Learning to Distinguish between High-quality and Low-quality Counseling Conversations.**
   _Verónica Pérez-Rosas, Xinyi Wu, Kenneth Resnicow, Rada Mihalcea_. [[pdf](https://www.aclweb.org/anthology/P19-1088.pdf)]
2. (2020 LREC) **Inferring Social Media Users’ Mental Health Status from Multimodal Information.** _Zhentao Xu, Veronica Pérez-Rosas, Rada Mihalcea_.
   [[pdf](https://www.aclweb.org/anthology/2020.lrec-1.772.pdf)]
3. (2020 EMNLP Workshop) **Quantifying the Effects of COVID-19 on Mental Health Support Forums.** _Laura Biester, Katie Matton, Janarthanan Rajendran, Emily Mower Provost, Rada Mihalcea_. [[pdf](https://www.aclweb.org/anthology/2020.nlpcovid19-2.8.pdf)]
4. (2020 arXiv) **Expressive Interviewing: A Conversational System for Coping with COVID-19.** *Charles Welch, Allison Lahnala, Verónica Pérez-Rosas, Siqi Shen, Sarah Seraj, Larry An, Kenneth Resnicow, James Pennebaker, Rada Mihalcea*. [[pdf](https://arxiv.org/pdf/2007.03819.pdf)]
5. (2017 ACL) **Understanding and Predicting Empathic Behavior in Counseling Therapy.** *Verónica Pérez-Rosas, Rada Mihalcea, Kenneth Resnicow, Satinder Singh, Lawrence An*. [[pdf](https://aclanthology.org/P17-1131.pdf)]
6. (2017 EACL) **Predicting Counselor Behaviors in Motivational Interviewing Encounters.** *Verónica Pérez-Rosas, Rada Mihalcea, Kenneth Resnicow, Satinder Singh, Lawrence An, Kathy J. Goggin, Delwyn Catley*. [[pdf](https://aclanthology.org/E17-1106.pdf)]
7. (2016 TACL) **Large-scale Analysis of Counseling Conversations: An Application of Natural Language Processing to Mental Health.** _Tim Althoff, Kevin Clark, Jure Leskovec_. [[pdf](https://www.aclweb.org/anthology/Q16-1033.pdf)] [[slides@Stanford](https://web.stanford.edu/class/cs124/lec/counseling_slides.pdf)] [[video](https://vimeo.com/239248873)]
8. (2016 ACL Workshop) **Building a Motivational Interviewing Dataset.** *Verónica Pérez-Rosas, Rada Mihalcea, Kenneth Resnicow, Satinder Singh, Lawrence An*. [[pdf](https://aclanthology.org/W16-0305.pdf)]

#### NLP for happiness

1. (2019 ACII) **Happiness Entailment: Automating Suggestions for Well-Being.** _Sara Evensen, Yoshihiko Suhara, Alon Halevy, Vivian Li, Wang-Chiew Tan, Saran Mumick_. [[pdf](https://arxiv.org/pdf/1907.10036.pdf)]
2. (2018 LREC) **HappyDB: A Corpus of 100,000 Crowdsourced Happy Moments.**
   _Akari Asai, Sara Evensen, Behzad Golshan, Alon Halevy, Vivian Li, Andrei Lopatenko, Daniela Stepanov, Yoshihiko Suhara, Wang-Chiew Tan, Yinzhan Xu_.
   [[pdf](https://arxiv.org/pdf/1801.07746.pdf)]
3. (2019, AffCon@AAAI) **Ingredients for Happiness: Modeling constructs via semi-supervised content driven inductive transfer.** *Bakhtiyar Syed, Vijayasaradhi Indurthi, Kulin Shah, Manish Gupta, Vasudeva Varma*. [[pdf](http://ceur-ws.org/Vol-2328/4_paper_19.pdf)]


#### Mental health on social media (e.g., hate speech, hope speech)

1. (2020 COLING Workshop) **HopeEDI: A Multilingual Hope Speech Detection Dataset for Equality, Diversity, and Inclusion.** _Bharathi Raja Chakravarthi_. [[pdf](https://www.aclweb.org/anthology/2020.peoples-1.5.pdf)]

  [Summary] "Hope speech" is text that is encouraging, positive and supportive, as opposed to hate speech.

1. **Fermi at SemEval-2019 Task 5: Using Sentence Embeddings to identify Hate Speech against Immigrants and Women on Twitter.**. *Vijayasaradhi Indurthi, Bakhtiyar Syed, Manish Shrivastava, Nikhil Chakravartula, Manish Gupta, Vasudeva Varma*. [[pdf](https://www.aclweb.org/anthology/S19-2009.pdf)]

2. **Fermi at SemEval-2019 Task 6: Identifying and Categorizing Offensive Language in Social Media using Sentence Embeddings.** *Vijayasaradhi Indurthi, Bakhtiyar Syed, Manish Shrivastava, Manish Gupta, Vasudeva Varma*. [[pdf](https://www.aclweb.org/anthology/S19-2109.pdf)]

#### Mental health through other text forms

1. (2020 SocInfo) **Women worry about family, men about the economy: Gender differences in emotional responses to COVID-19.**
   _Isabelle van der Vegt, Bennett Kleinberg_. [[pdf](https://arxiv.org/pdf/2004.08202.pdf)]

#### Workshops and Resources

1. (Every year) CLPsych: Computational Linguistics and Clinical Psychology Workshop [[website](https://clpsych.org/)]

2. Research Fellowship Program (3-6 months) [[FAQ](https://docs.google.com/document/d/1_uQrOapzwy1JA8j38PX9unXDC_dzMyO7HT9jnhjxLEY/edit)]

## Q3: Can we use NLP to **help the common future** of all humans?

### 3.1 NLP for climate change

1. (2021NeurIPS Workshop) **CLIMATE-FEVER: A Dataset for Verification of Real-World Climate Claims.** *Thomas Diggelmann, Jordan Boyd-Graber, Jannis Bulian, Massimiliano Ciaramita, Markus Leippold*. [[pdf](https://arxiv.org/pdf/2012.00614.pdf)]
2. (2020 EMNLP Findings) **Detecting Stance in Media on Global Warming.** _Yiwei Luo, Dallas Card, Dan Jurafsky_. [[pdf](https://arxiv.org/pdf/2010.15149.pdf)]
3. (2020 arXiv) **You are right. I am ALARMED -- But by Climate Change Counter Movement.** *Shraey Bhatia, Jey Han Lau, Timothy Baldwin.* [[pdf](https://arxiv.org/pdf/2004.14907.pdf)]
4. (2017 EMNLP Workshop) **Comparing Attitudes to Climate Change in the Media using sentiment analysis based on Latent Dirichlet Allocation.**
   _Ye Jiang, Xingyi Song, Jackie Harrison, Shaun Quegan, Diana Maynard_. [[pdf](https://www.aclweb.org/anthology/W17-4205.pdf)]
5. (2020 ICWSM Workshop) **Learning Twitter User Sentiments on Climate Change with Limited Labeled Data** _Allison Koenecke, Jordi Feliu-Fabà_. [[pdf](https://arxiv.org/pdf/1904.07342.pdf)]

### 3.2 NLP for Human Rights

#### Detecting Human Right Violation

1. **Paragraph-level Rationale Extraction through Regularization: A case study on European Court of Human Rights Cases.** *Ilias Chalkidis, Manos Fergadiotis, Dimitrios Tsarapatsanis, Nikolaos Aletras, Ion Androutsopoulos, Prodromos Malakasiotis*. [[pdf](https://arxiv.org/pdf/2103.13084.pdf)]

#### [Please don't use NLP in this way] NLP for Privacy Invasion/Surveilance

#### Background

1. (Inmate medical surveilance; Intercept 2020) **Prisons launch "absurd" attempt to detect coronavirus in inmate phone calls.** _Akela Lacy, Alice Speri, Jordan Smith, Sam Biddle._

   [Summary] Automatically downloads, analyzes, and transcribes inmate calls, to identify sick inmates, help allocate personnel in understaffed prisons, and even prevent “COVID-19 related murder.

2. (Teenagers want privacy; Symposium discussion 2011) **Social Privacy in Networked Publics: Teens’ Attitudes, Practices, and Strategies.** _Danah  Boyd, Alice Marwick_. [[pdf](https://www.danah.org/papers/2011/SocialPrivacyPLSC-Draft.pdf)]

#### Surveilance from companies

1. (Book 2019) **The age of surveillance capitalism.** _Shoshana Zuboff._ [[Amazon](https://www.amazon.com/Age-Surveillance-Capitalism-Future-Frontier/dp/1610395697)] [[pdf](http://125.22.40.134:8080/jspui/bitstream/123456789/4220/1/Shoshana%20Zuboff%20-%20The%20Age%20of%20Surveillance%20Capitalism.pdf)]

### 3.3 Fight against the manipulation of thoughts

#### Studying the existing trend

1. (2019 NAACL) **Analyzing Polarization in Social Media: Method and Application to Tweets on 21 Mass Shootings.**
   _Dorottya Demszky, Nikhil Garg, Rob Voigt, James Zou, Jesse Shapiro, Matthew Gentzkow, Dan Jurafsky_. [[pdf](https://aclanthology.org/N19-1304.pdf)]


#### Studying Media Manipulation for Political Reasons

Keywords: Framing, persuation, manipulation.

1. (EMNLP 2018) **Framing and Agenda-setting in Russian News: a Computational Analysis of Intricate Political Strategies.** *Anjalie Field, Doron Kliger, Shuly Wintner, Jennifer Pan, Dan Jurafsky, and Yulia Tsvetkov.* [[pdf](https://www.aclweb.org/anthology/D18-1393.pdf)]
2. (EMNLP 2019) **Fine-Grained Analysis of Propaganda in News Articles.** *Giovanni Da San Martino, Seunghak Yu, Alberto Barrón-Cedeño, Rostislav Petrov, Preslav Nakov.* [[pdf](https://www.aclweb.org/anthology/D19-1565.pdf)]
3. (2019 CoNLL) **Predicting the Role of Political Trolls in Social Media.** _Atanas Atanasov, Gianmarco De Francisci Morales, Preslav Nakov_. [[pdf](https://aclanthology.org/K19-1096.pdf)]
4. (2020 Harvard Review) **Cross-platform disinformation campaigns: Lessons learned and next steps.** _Tom Wilson, Kate Starbird_. [[pdf](https://misinforeview.hks.harvard.edu/article/cross-platform-disinformation-campaigns/)]
5. (2018 ACL) **Classification of Moral Foundations in Microblog Political Discourse.** _Kristen Johnson and Dan Goldwasser_. [[pdf](https://aclanthology.org/P18-1067.pdf)]
6. (arXiv 2020) **Automatically Characterizing Targeted Information Operations Through Biases Present in Discourse on Twitter.** _Autumn Toney, Akshat Pandey, Wei Guo, David Broniatowski, Aylin Caliskan_. [[pdf](https://arxiv.org/pdf/2004.08726.pdf)]
7. (Internet Policy Review 2019) **Technology, autonomy, and manipulation.** *Daniel Susser, Beate Roessler, Helen Nissenbaum.* [[pdf](https://nissenbaum.tech.cornell.edu/papers/Technology,%20Autonomy,%20and%20Manipulation.pdf)]
8. (2020 Personality and Social Psychology Bulletin) **Historical Change in the Moral Foundations of Political Persuasion.** _Nicholas Buttrick, Robert Moulder and Shigehiro Oishi_. [[pdf](https://journals.sagepub.com/doi/abs/10.1177/0146167220907467)]
9. (2019) **Measuring Proximity Between Newspapers and Political Parties: The Sentiment Political Compass.** _Fabian Falck, Julian Marstaller, Niklas Stoehr, Sören Maucher, Jeana Ren, Andreas Thalhammer, Achim Rettinger, Rudi Studer_. [[pdf](https://onlinelibrary.wiley.com/doi/pdf/10.1002/poi3.222?casa_token=u1R0goBcvHQAAAAA:QmIC9b2v5YNDgcKdArx7zSGLoSI1cUniCFglcV5p828X-COhZmWnxrsuGGtxIRZvMeJBQYd6QWDOTg)]
10. (2019 arXiv) **Red Bots Do It Better: Comparative Analysis of Social Bot Partisan Behavior.**
       _Luca Luceri, Ashok Deb, Adam Badawy, Emilio Ferrara_.
       [[pdf](https://arxiv.org/pdf/1902.02765.pdf)]
11. (CSCW 2018) **Acting the Part: Examining Information Operations within #BlackLivesMatter Discourse.** _Ahmer Arif, Leo G. Stewart, Kate Starbird_. [[pdf](http://faculty.washington.edu/kstarbi/BLM-IRA-Camera-Ready.pdf)]
12. (CSCW 2018) **Assembling Strategic Narratives: Information Operations as Collaborative Work within an Online Community.** _Tom Wilson, Kaitlyn Zhou, and Kate Starbird_. [[pdf](https://faculty.washington.edu/kstarbi/cscw-Wilson-Starbird-InfoOps-Omran-FINAL.pdf)]
13. (2020) **Potemkin Pages and Personas: Assessing GRU Online Operations, 2014-2019.** _Renee DiResta, Shelby Grossman_. [[pdf](https://fsi-live.s3.us-west-1.amazonaws.com/s3fs-public/potemkin-pages-personas-sio-wp.pdf)]
14. (2020 Book) **Blame it on Iran, Qatar, and Turkey: An analysis of a Twitter and Facebook operation linked to Egypt, the UAE, and Saudi Arabia.** _Shelby Grossman, Khadija H., Renée DiResta, Tara Kheradpir, and Carly Miller_. [[pdf](https://fsi-live.s3.us-west-1.amazonaws.com/s3fs-public/20200402_blame_it_on_iran_qatar_and_turkey_v2_0.pdf)]
15. (2018 Book) **Network propaganda: Manipulation, disinformation, and radicalization in American politics.** _Benkler, Yochai, Robert Faris, and Hal Roberts_.
16. (1928) **Propaganda.** _Edward Bernays._ 


1. (2019 NAACL) **Issue Framing in Online Discussion Fora.** _Mareike Hartmann, Tallulah Jansen, Isabelle Augenstein, Anders Søgaard_.
   [[pdf](https://aclanthology.org/N19-1142.pdf)]
2. (2019 EMNLP) **Modeling Frames in Argumentation.**
   _Yamen Ajjour, Milad Alshomary, Henning Wachsmuth, Benno Stein_. [[pdf](https://aclanthology.org/D19-1290.pdf)]
3. (2020 AAAI) **Automatically Neutralizing Subjective Bias in Text.**
   _Reid Pryzant, Richard Diehl Martinez, Nathan Dass, Sadao Kurohashi, Dan Jurafsky, Diyi Yang_. [[pdf](https://arxiv.org/pdf/1911.09709.pdf)]
4. (2020 WebSci) **A Systematic Media Frame Analysis of 1.5 Million New York Times Articles from 2000 to 2017.**
   _Haewoon Kwak, Jisun An, Yong-Yeol Ahn_ [[pdf](https://arxiv.org/pdf/2005.01803.pdf)]
5. (2020 arXiv) **FrameAxis: Characterizing Framing Bias and Intensity with Word Embedding.**
   _Haewoon Kwak, Jisun An, Elise Jing, Yong-Yeol Ahn_. [[pdf](https://arxiv.org/pdf/2002.08608.pdf)]
6. (2017 EMNLP) **Connotation Frames of Power and Agency in Modern Films.** _Maarten Sap, Marcella Cindy Prasettio, Ari Holtzman, Hannah Rashkin, Yejin Choi_. [[pdf](https://aclanthology.org/D17-1247.pdf)]
7. (2016 EMNLP) **Analyzing Framing through the Casts of Characters in the News.**
   _Dallas Card, Justin Gross, Amber Boydstun, Noah A. Smith_. [[pdf](https://aclanthology.org/D16-1148.pdf)]
8. (2015 ACL) **The Media Frames Corpus: Annotations of Frames Across Issues**
   _Dallas Card, Amber E. Boydstun, Justin H. Gross, Philip Resnik, Noah A. Smith_. [[pdf](https://aclanthology.org/P15-2072.pdf)]
9. (2013 ACL) **Linguistic Models for Analyzing and Detecting Biased Language.** _Marta Recasens, Cristian Danescu-Niculescu-Mizil, Dan Jurafsky_. [[pdf](https://aclanthology.org/P13-1162.pdf)]


1. (WWW 2019) **Who falls for online political manipulation?** _Adam Badawy, Kristina Lerman, and Emilio Ferrara_. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3308560.3316494)]

#### Fake news and misinformation

1. (2021 arXiv) **Misinfo Belief Frames: A Case Study on Covid & Climate News.** *Saadia Gabriel, Skyler Hallinan, Maarten Sap, Pemi Nguyen, Franziska Roesner, Eunsol Choi, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2104.08790.pdf)]
2. (2020 Nature) **The online competition between pro- and anti-vaccination views.** *Neil F. Johnson, Nicolas Velásquez, Nicholas Johnson Restrepo, Rhys Leahy, Nicholas Gabriel, Sara El Oud, Minzhang Zheng, Pedro Manrique, Stefan Wuchty, Yonatan Lupu.* [[pdf](https://www.nature.com/articles/s41586-020-2281-1.pdf)]
3. (2020 LREC) **r/Fakeddit: A New Multimodal Benchmark Dataset for Fine-grained Fake News Detection.** _Kai Nakamura, Sharon Levy, William Yang Wang_. [[pdf](https://arxiv.org/pdf/1911.03854.pdf)]
4. (2020 arXiv) **You are right. I am ALARMED -- But by Climate Change Counter Movement.** *Shraey Bhatia, Jey Han Lau, Timothy Baldwin.* [[pdf](https://arxiv.org/pdf/2004.14907.pdf)]
5. (2020 European Urology Focus) **Fake News: Spread of Misinformation about Urological Conditions on Social Media.** *Stacy Loeb, Jacob Taylor, James F. Borina, Rada Mihalcea, Veronica Perez-Rosas, Nataliya Byrne, Austin L. Chiang, Aisha Langford* [[pdf](https://pdf.sciencedirectassets.com/313345/1-s2.0-S2405456920X00046/1-s2.0-S2405456919303529/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCKsEjjPNjlJsfMt3e23FtEeEnJDG5l6L29fc8ik53lxwIhAOIMxiLuNAvE1c0PoQm4YE4dMfQ%2Bdfdpy0mc4LWDG0TJKvoDCHoQBBoMMDU5MDAzNTQ2ODY1Igx33MysHIfw3mhbXvwq1wO3NwEf%2FDWNFJzsmZIDU1TfpmbXt8k4Iu22UBJUYq4kSAR%2BVXwqd%2B4tIZk4XD119PC%2BleSlXAw5N2LAq2P4q7sr%2FECOTm8KH9FRbh8nTPcR4SXE%2FSpCs74HN0KG3e6Yf9UsCOyaCcbiGwLa%2BriHo%2B7tgq67BLLMu%2BoLMrW60je%2BLiKRS%2FwwsHJmyGZeLAtxCcqzOlbtCBP4Qgc3jln%2FmE0S%2F7c1gNoo8RoLFLXxY2N1lXZlgxTTh%2BmO2pfZe6avn2QmHlDmknoWPnjmXrh9IqeNcaFNI%2Be%2BYR26tT0Oa1ZBkOVKbE1624i2bR49xFJt73bpqLYVLN4z8EAhfqUaYGFxkqA0B11aH2OKE5ni3AWwPYqezieMnLkRp4kDRzqqyt%2BS%2F%2FnzMyACH9Y5Zk%2BX%2Fm6YGQRHi3OimWH6MscYG8%2F8jxYnh8KZcASdIhmVc0M6oMO2eq6iJpo7UZ2yLgjen9x79YzWPhHUdev8rHdlez3yehgWEcu1kC9yf86%2FMN%2BqY%2FvftDz6ZhnIxWKsAUbfPjViXZrmJZKN9x%2BmXdyBRb%2FNj3rkHRC23MdFGlC8dBohaIRMZe7VBEsXWzeblm2A8iuIfvcStEJ1RwAmWd6Cbquk%2FqueRDD4A5cwmNOchwY6pAGAKdSnEh1tpbF4e52R6uNCBc63fxTW%2FFDRW8u4qPSb3996gsbc3YB9RatsXqK6YPm%2FwCWau19rzXQw8cVq5hgYA5ZSq2k%2FMe%2FnN7RwOkW3BcfM262S9ZFkcyo30kL1KQzzR2lsn%2BXvErc5pKcIxzVYoenBXM2gRUo0E19y1nGRadweFW23HWBYbAslx9NDoWU1K2IkEftJugM8CwrI0ZKtYdQeAQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210708T172916Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYQIW74AH5%2F20210708%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d8fab83822c84077bca42a27c8551e963b54adc5389579d39967863fc4365eae&hash=0e4c4222bd2f474056055491f9783c0aece2ee229a6a481e87cc438b840e5ace&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2405456919303529&tid=spdf-82cd8286-7d6a-4111-a142-eefa00a83d02&sid=09bc6380973146447e7b4c99d7360cd2983bgxrqb&type=client)]
6. (2020 arXiv) **Coronavirus on social media: Analyzing misinformation in Twitter conversations.** _Sharma, Karishma, Sungyong Seo, Chuizheng Meng, Sirisha Rambhatla, Aastha Dua, and Yan Liu_.
   [[pdf](https://arxiv.org/pdf/2003.12309.pdf)]
7. (2020, Reuters Institute) **Types, Sources, and Claims of COVID-19 Misinformation.**
   _J. Scott Brennen, Felix M. Simon, Philip N. Howard, and Rasmus Kleis Nielsen_. [[pdf](http://www.primaonline.it/wp-content/uploads/2020/04/COVID-19_reuters.pdf)]
8. (2020 Wired article) **The Professors Who Call ‘Bullshit’ on Covid-19 Misinformation.** *Jevin West, Carl Bergstrom.* [[website](https://www.wired.com/story/professors-call-bullshit-covid-19-misinformation/)]
9. (2019 ACM) **Combating Fake News: A Survey on Identification and Mitigation Techniques.**
   _Karishma Sharma, Feng Qian, He Jiang, Natali Ruchansky, Ming Zhang, Yan Liu_. [[pdf](https://arxiv.org/pdf/1901.06437.pdf)]
10. (2018 COLING) **Automatic Detection of Fake News.** *Verónica Pérez-Rosas, Bennett Kleinberg, Alexandra Lefevre, Rada Mihalcea*. [[pdf](https://aclanthology.org/C18-1287.pdf)]
11. (2018 Science) **The spread of true and false news online.** *Vosoughi, Soroush, Deb Roy, and Sinan Aral*. [[pdf](https://ide.mit.edu/sites/default/files/publications/2017%20IDE%20Research%20Brief%20False%20News.pdf)]
12. (2018 ACM) **A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities.**
    _Xinyi Zhou, Reza Zafarani_. [[pdf](https://arxiv.org/pdf/1812.00315.pdf)]
13. (2018 AJPH) **Weaponized Health Communication: Twitter Bots and Russian Trolls Amplify the Vaccine Debate.** *David A Broniatowski, Amelia M Jamison, SiHua Qi, Lulwah AlKulaib, Tao Chen, Adrian Benton, Sandra C Quinn, Mark Dredze.* [[pdf](https://ajph.aphapublications.org/doi/pdf/10.2105/AJPH.2018.304567)]
14. (2017 ACL) **Liar, Liar Pants on Fire”: A New Benchmark Dataset for Fake News Detection.**
    _William Yang Wang_. [[pdf](https://aclanthology.org/P17-2067.pdf)]
15. (2017 EMNLP) **Truth of Varying Shades: Analyzing Language in Fake News and Political Fact-Checking.**
    _Hannah Rashkin, Eunsol Choi, Jin Yea Jang, Svitlana Volkova, Yejin Choi_. [[pdf](https://aclanthology.org/D17-1317.pdf)]
16. (2017, Journal of economic perspectives) **Social Media and Fake News in the 2016 Election.** *Hunt Allcott, Matthew Gentzkow.* [[pdf](https://web.stanford.edu/~gentzkow/research/fakenews.pdf)]
17. (2014 ICWSM) **Rumor Cascades.** *Adrien Friggeri, Lada A. Adamic, Dean Eckles, Justin Cheng.* [[pdf](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM14/paper/viewFile/8122/8110)]
18. (2014 iConference) **Rumors, False Flags, and Digital Vigilantes: Misinformation on Twitter after the 2013 Boston Marathon Bombing.**  *Kate Starbird, Jim Maddock, Mania Orand, Peg Achterman, Robert M. Mason.* [[pdf](https://www.ideals.illinois.edu/bitstream/handle/2142/47257/308_ready.pdf?sequence=2&isAllowed=y)]
19. (1986, Raritan Quarterly Review) **On Bullshit.** _Harry Frankfurt._ [[pdf](http://www2.csudh.edu/ccauthen/576f12/frankfurt__harry_-_on_bullshit.pdf)]


##### Fact-checking

1. (2021 arXiv) **Extractive and Abstractive Explanations for Fact-Checking and Evaluation of News.** *Ashkan Kazemi, Zehua Li, Verónica Pérez-Rosas, Rada Mihalcea*. [[pdf](https://arxiv.org/pdf/2104.12918.pdf)]

2. (2020 ACL) **That is a Known Lie: Detecting Previously Fact-Checked Claims.** _Shaden Shaar, Giovanni Da San Martino, Nikolay Babulkov, Preslav Nakov_.
   [[pdf](https://arxiv.org/pdf/2005.06058.pdf)]

3. (2020 CL) **The Limitations of Stylometry for Detecting Machine-Generated Fake News.** *Tal Schuster, Roei Schuster, Darsh J Shah, Regina Barzilay.* [[pdf](https://arxiv.org/pdf/1908.09805.pdf)]

4. (2020 EMNLP) **Fact or Fiction: Verifying Scientific Claims.**
   _David Wadden, Shanchuan Lin, Kyle Lo, Lucy Lu Wang, Madeleine van Zuylen, Arman Cohan, Hannaneh Hajishirzi_. [[pdf](https://arxiv.org/pdf/2004.14974.pdf)]

5. (2020 ICWSM) **A Benchmark Dataset of Check-worthy Factual Claims.**
   _Fatma Arslan, Naeemul Hassan, Chengkai Li, Mark Tremayne_. [[pdf](https://arxiv.org/pdf/2004.14425.pdf)]

6. (2020 ACL) **Generating Fact Checking Explanations.** _Pepa Atanasova, Jakob Grue Simonsen, Christina Lioma, Isabelle Augenstein_. [[pdf](https://arxiv.org/pdf/2004.05773.pdf)]

7. (2019 EMNLP) **MultiFC: A Real-World Multi-Domain Dataset for Evidence-Based Fact Checking of Claims.** *Augenstein, Isabelle, Christina Lioma, Dongsheng Wang, Lucas Chaves Lima, Casper Hansen, Christian Hansen, and Jakob Grue Simonsen.* [[pdf](https://www.aclweb.org/anthology/D19-1475.pdf)]

8. (2019 NeurIPS) **Defending Against Neural Fake News.** *Rowan Zellers, Ari Holtzman, Hannah Rashkin, Yonatan Bisk, Ali Farhadi, Franziska Roesner, Yejin Choi.* [[pdf](https://proceedings.neurips.cc/paper/2019/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf)]

   [Summary] Fake news generated by a large neural network, _Grover_, can appear more trustworthy than those written by human. Since the most accurate discriminator against _Grover_ in the trial is _Grover_ itself, the authors decided to release the model to researchers to facilitate misinformation detection, despite the potential damage it could cause as a fake news generator.

9. (2019 EMNLP) **Evaluating adversarial attacks against multiple fact verification systems.** _James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal_. [[pdf](https://aclanthology.org/D19-1292.pdf)]

10. (2019 EMNLP) **Towards Debiasing Fact Verification Models.** _Tal Schuster, Darsh Shah, Yun Jie Serene Yeo, Daniel Roberto Filizzola Ortiz, Enrico Santus, Regina Barzilay_. [[pdf](https://aclanthology.org/D19-1341.pdf)]

11. (2018 NAACL) **FEVER: a large-scale dataset for Fact Extraction and VERification.** *James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal.* [[pdf](https://www.aclweb.org/anthology/N18-1074.pdf)]

## Q4: Can we use NLP to help make all people **equal**?

### 4.1 NLP for all languages

**[Main focus]** Spreading the benefit of NLP to low-resource languages; equal gender ratio.

#### Motivation

1. (ACL 2020) **The State and Fate of Linguistic Diversity and Inclusion in the NLP World.** *Pratik Joshi, Sebastin Santy, Amar Budhiraja, Kalika Bali, and Monojit Choudhury.* [[pdf](https://arxiv.org/pdf/2004.09095.pdf)]

   [Summary] Only very few out of >7000 languages are represented in NLP.

### 4.2 NLP for gender/demographical equality

#### NLP to detect bias

1. (2021 ICWSM) **Measuring Societal Biases from Text Corpora with Smoothed First-Order Co-occurrence.** *Navid Rekabsaz, Robert West, James Henderson, Allan Hanbury*. (2020 ACL) [[pdf](https://arxiv.org/pdf/1812.10424.pdf)]
2. (2020 ACL) **When do Word Embeddings Accurately Reflect Surveys on our Beliefs About People?** *Kenneth Joseph, Jonathan H. Morgan*. [[pdf](https://arxiv.org/pdf/2004.12043.pdf)]
3. (2020 NBER Manuscript) **Stereotypes in High-Stakes Decisions: Evidence from U.S. Circuit Courts.** *Elliott Ash, Daniel L. Chen, Arianna Ornaghi.* [[pdf](http://elliottash.com/wp-content/uploads/2019/11/200205_Ash-Chen-Ornaghi.pdf)]
4. (2019 ACL) **Entity-Centric Contextual Affective Analysis.** *Anjalie Field, Yulia Tsvetkov.* [[pdf](https://www.aclweb.org/anthology/P19-1243.pdf)]
5. (2019 ACL) **Unsupervised Discovery of Gendered Language through Latent-Variable Modeling.** *Alexander Miserlis Hoyle, Lawrence Wolf-Sonkin, Hanna Wallach, Isabelle Augenstein, Ryan Cotterell*. [[pdf](https://aclanthology.org/P19-1167.pdf)]
6. (2019 EMNLP) **Automatically Inferring Gender Associations from Language.** *Serina Chang, Kathy McKeown.* [[pdf](https://www.aclweb.org/anthology/D19-1579.pdf)]
7. (2019 ICWSM) **Contextual Affective Analysis: A Case Study of People Portrayals in Online #MeToo Stories.** *Anjalie Field, Gayatri Bhat, Yulia Tsvetkov*. [[pdf](https://arxiv.org/pdf/1904.04164.pdf)]
8. (2019 BRiMS) **Relating Linguistic Gender Bias, Gender Values, and Gender Gaps: An International Analysis.** *Scott Friedman, Sonja Schmer-Galunder, Jeffrey Rye, Robert Goldman, and Anthony Chen*. [[pdf](http://sbp-brims.org/2019/proceedings/papers/working_papers/Friedman.pdf)]
9. (2018 PNAS) **Word embeddings quantify 100 years of gender and ethnic stereotypes.** *Nikhil Garg, Londa Schiebinger, Dan Jurafsky, James Zou.* [[pdf](http://www.pnas.org/content/pnas/early/2018/03/30/1720347115.full.pdf)]
10. (2017 PNAS) **Language from police body camera footage shows racial disparities in officer respect.** *Rob Voigt, Nicholas P. Camp, Vinodkumar Prabhakaran, William L. Hamilton, Rebecca C. Hetey, Camilla M. Griffiths, David Jurgens, Dan Jurafsky, and Jennifer L. Eberhardt.* [[pdf](http://www.pnas.org/content/early/2017/05/30/1702413114)]
11. (2016 IJCAI Workshop) **Tie-breaker: Using language models to quantify gender bias in sports journalism.** *Liye Fu, Cristian Danescu-Niculescu-Mizil, and Lillian Lee.* [[pdf](http://www.cs.cornell.edu/~cristian/papers/gender-tennis.pdf)]
12. (2016 CWSM) **Shirtless and Dangerous: Quantifying Linguistic Signals of Gender Bias in an Online Fiction Writing Community.** *Ethan Fast, Tina Vachovsky, Michael S. Bernstein.* [[pdf](https://arxiv.org/pdf/1603.08832.pdf)]

#### NLP to detect bias specifically on social media

1. (2020 ACL) **Social Bias Frames: Reasoning about Social and Power Implications of Language.** *Maarten Sap, Saadia Gabriel, Lianhui Qin, Dan Jurafsky, Noah A. Smith, Yejin Choi*. [[pdf](https://arxiv.org/pdf/1911.03891.pdf)]
2. (2020 arXiv) **Racism is a Virus: Anti-Asian Hate and Counterhate in Social Media during the COVID-19 Crisis.** _Caleb Ziems, Bing He, Sandeep Soni, Srijan Kumar_. [[pdf](https://arxiv.org/pdf/2005.12423.pdf)]


3. (2020 EMNLP Workshop) **Detecting East Asian Prejudice on Social Media.**
   _Bertie Vidgen, Austin Botelho, David Broniatowski, Ella Guest, Matthew Hall, Helen Margetts, Rebekah Tromble, Zeerak Waseem, Scott Hale_. [[pdf](https://arxiv.org/pdf/2005.03909.pdf)]
4. (2017 CSCW) **Girls rule, boys drool: Extracting semantic and affective stereotypes from Twitter.** *Kenneth Joseph, Wei Wei, and Kathleen M. Carley.* [[pdf](https://dl.acm.org/doi/pdf/10.1145/2998181.2998187)]

## Q5: Are there concerns over the practice of NLP? Can we mitigate this?

### 5.1 Prevent future scandals of conversational bots - How dialog systems should handle verbal abuse

1. (2016, International Journal of Communication) **Talking to Bots: Symbiotic Agency and the Case of Tay.**
   _Gina Neff, Peter Nagy_. [[pdf](http://csi.asu.edu/wp-content/uploads/2018/01/6277-22501-1-PB.pdf)]
2. (2020 CHI) **Empathy Is All You Need: How a Conversational Agent Should Respond to Verbal Abuse.** _Hyojin Chin, Lebogang Wame Molefi, Mun Yong Yi_. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3313831.3376461?casa_token=0HtnPh4QXLUAAAAA:clbj3rPckx29q8EOX5zXvolv1k3gBA3PX-3d__mABU0jbJ_eFpqtZoWBBWo_4-zV3YQJCSVJ6xg)]
3. (2019 UNESCO Report) **I'd Blush if I Could: Closing Gender Divides in Digital Skills Through Education** [[pdf](https://unesdoc.unesco.org/ark:/48223/pf0000367416.page=1)]
4. (2018 CHI) **Let's Talk About Race: Identity, Chatbots, and AI.** _Ari Schlesinger, Kenton P. O'Hara, Alex S. Taylor_. [[pdf](https://static1.squarespace.com/static/5a8b405a18b27d5478196dca/t/5a8b690d24a694d7072d25a1/1519085853799/chi18-schlesinger-LetsTalkAboutRace.pdf)]
5. (2018 ACL workshop) **#MeToo: How Conversational Systems Respond to Sexual Harassment.** _Amanda Cercas Curry, Verena Rieser_. [[pdf](https://aclanthology.org/W18-0802v2.pdf)]
6. (2016 EMNLP) **How NOT To Evaluate Your Dialogue System: An Empirical Study of Unsupervised Evaluation Metrics for Dialogue Response Generation.**
   _Chia-Wei Liu, Ryan Lowe, Iulian Serban, Mike Noseworthy, Laurent Charlin, Joelle Pineau_. [[pdf](https://aclanthology.org/D16-1230.pdf)]

### 5.2 Who protects my privacy? - Privacy Issues with Dataset Collection

**Motivation:** Public social media data can invade user privacy.

- **The Common Rule: The Federal Policy for the Protection of Human Subjects.** [[45 CFR part 46](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/45-cfr-46/index.html)]

- (Human Rights: On Nuremberg Code; New England Journal of Medicine 1997) **Fifty years later: the significance of the Nuremberg Code.** *Evelyne Shuster.* [[paper](https://www.nejm.org/doi/full/10.1056/NEJM199711133372006)]

- **ACM Code of Ethics.**

  [Summary] Papers should 1.2 Avoid harm; 1.4 Be fair and take action not to discriminate; 1.6 Respect privacy; 2.6 Perform work only in areas of competence; and 3.1 Ensure that the public good is the central concern during all professional computing work.

#### Promoting data ethic norms for the community

1. (TACL 2018) **Data statements for NLP: Toward mitigating system bias and enabling better science.** *Emily Bender and Batya Friedman*. [[pdf](https://www.mitpressjournals.org/doi/pdf/10.1162/tacl_a_00041)]

2. (arXiv 2020) **Datasheets for Datasets.** *Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna Wallach, Hal Daumé III, Kate Crawford.* [[pdf](https://arxiv.org/pdf/1803.09010.pdf)]

3. (CSCW 2016) **Beyond the Belmont Principles: Ethical Challenges, Practices, and Beliefs in the Online Data Research Community.** *Jessica Vitak, Katie Shilton, Zahra Ashktorab.* [[pdf](https://terpconnect.umd.edu/~kshilton/pdf/VitaketalCSCWpreprint.pdf)]

   [Summary] A survey of 200+ researchers' current practice

4. (Nature Digital Medicine 2018) **Don't quote me: reverse identification of research participants in social media studies.** *John W Ayers, Theodore L Caputi, Camille Nebeker, Mark Dredze.* [[pdf](https://www.nature.com/articles/s41746-018-0036-2.pdf)]

   [Summary] Do not quote users. 72% articles quoted tweets, and the tweeter can be identified 84% of the time.

#### User surveys about their data being used

1. (Social Media + Society 2018) **"Participant" Perception of Twitter research ethics.** *Casey Fiesler and Nicholas Proferes.* [[pdf](https://journals.sagepub.com/doi/pdf/10.1177/2056305118763366)]

   [Summary] (1) Few users knew their public tweets could be used by researchers; (2) The majority thought their consent is important

2. (Sociology 2017) **Towards an Ethical Framework for Publishing Twitter Data in Social Research: Taking into Account Users’ Views, Online Context and Algorithmic Estimation.** *Matthew L Williams, Pete Burnap, Luke Sloan.* [[pdf](https://journals.sagepub.com/doi/pdf/10.1177/0038038517708140?source=post_page---------------------------)]

#### Building models that preserves privacy

1. **Writer Profiling Without the Writer’s Text.** _David Jurgens, Yulia Tsvetkov, Dan Jurafsky_. [[pdf](https://jurgens.people.si.umich.edu/docs/jurgens-tsvetkov-jurafsky.socinfo2017.pdf)]

   [Summary] Linguistic cues are predictive of user gender, age, religion, diet, and personality traits.

2. (Dialog; AIES 2017) **Ethical Challenges in Data-Driven Dialogue Systems.** _Peter Henderson, Koustuv Sinha, Nicolas Angelard-Gontier, Nan Rosemary Ke, Genevieve Fried, Ryan Lowe, Joelle Pineau_.
   [[pdf](https://arxiv.org/pdf/1711.09050.pdf)]

3. **Privacy-preserving Neural Representations of Text.**
   _Maximin Coavoux, Shashi Narayan, Shay B. Cohen_. [[pdf](https://arxiv.org/pdf/1808.09408.pdf)]

   [Summary] Build representations with a tradeoff between privacy and utility of neural representations.

4. (USENIX Symposium 2019) **The Secret Sharer: Evaluating and Testing
   Unintended Memorization in Neural Networks.** _Nicholas Carlini, Chang Liu, Úlfar Erlingsson, Jernej Kos, Dawn Song_. [[pdf](https://arxiv.org/pdf/1802.08232.pdf)] [[4-gram experiment by Prof Yoav Goldberg](https://gist.github.com/yoavg/40d01b5df1014d9237157902926d20c6)]

#### Improving data quality for ML models

1. (ACM FAT* 2020) **Garbage In, Garbage Out? Do Machine Learning Application Papers in Social Computing Report Where Human-Labeled Training Data Comes From?** *Stuart Geiger, Kevin Yu, Yanlai Yang, Mindy Dai, Jie Qiu, Rebekah Tang, Jenny Huang.* [[pdf](https://arxiv.org/pdf/1912.08320.pdf)]

   [Summary] Inspecting papers to see whether the data collection process is reasonable.

2. (SIGdial 2007) **Comparing Spoken Dialog Corpora Collected with Recruited Subjects versus Real Users.** *Hua Ai, Antoine Raux, Dan Bohus, Maxine Eskenazi, Diane Litman.* [[pdf](https://www.aclweb.org/anthology/2007.sigdial-1.23.pdf)]

   [Summary] Recruited subjects talk more and faster, while real users ask for more help and more frequently interrupt the system.

### 5.3 Can we prevent our model from being a sexist/racist/etc?

#### Gender/Demographical bias in models and data - Background

1. (Science 2017) **Semantics derived automatically from language corpora necessarily contain human biases.** *Aylin Caliskan, Joanna J. Bryson, and Arvind Narayanan.* [[pdf](https://arxiv.org/pdf/1608.07187.pdf)]

   [Summary] Not only for machines, but psychology finds that humans also learns to be biased after some language inputs. Reason: Langauage contains recoverable and accurate imprints of our historic biases. Effect: We have various biases, including these are morally neutral as towards insects or flowers, problematic as towards race or gender, or even simply veridical, reflecting the status quo for the distribution of gender with respect to careers or first names.

2. (Book 1999) **Sorting Things Out.** *Geoffrey C. Bowker, Susan Leigh Star.* [[intro](https://ar264sweeney.files.wordpress.com/2015/09/9780262269070_introduction.pdf)]

#### Survey/Overview

1. (2020 arXiv) **Language (Technology) is Power: A Critical Survey of "Bias" in NLP.** *Su Lin Blodgett, Solon Barocas, Hal Daumé III, Hanna Wallach.* [[pdf](https://arxiv.org/pdf/2005.14050.pdf)]

   [Summary] Surveyed 147 papers. NLP researchers should articulate (1) what "bias" they mean—i.e., what kinds of system behaviors are harmful, in what ways, to whom, and why, and (2) normative reasoning behind.

2. (2019 ACL) **Mitigating Gender Bias in Natural Language Processing: Literature Review.** *Tony Sun, Andrew Gaut, Shirlyn Tang, Yuxin Huang, Mai ElSherief, Jieyu Zhao, Diba Mirza, Elizabeth Belding, Kai-Wei Chang, William Yang Wang*. [[pdf](https://aclanthology.org/P19-1159.pdf)]

3. (2018 Book) **Algorithms of Oppression.** *Safiya Noble.* [[Amazon](https://www.amazon.de/Algorithms-Oppression-Search-Engines-Reinforce/dp/1479837245)]

4. (2017 NIPS Keynote) **The trouble with bias.** *Kate Crawford.*

#### Gender vs. Embeddings

1. (Gender in word embeddings; NIPS 2016) **Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings.** *Tolga Bolukbasi, Kai-Wei Chang, James Zou, Venkatesh Saligrama, Adam Kalai.*

2. (Gender in word embeddings; NAACL 2019) **Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them.** *Hila Gonen, Yoav Goldberg*. [[pdf](https://www.aclweb.org/anthology/N19-1061.pdf)]

   [Summary] Existing methods mostly hiding the bias, not removing it.

3. (Gender in sentence embeddings; NAACL 2019) **On Measuring Social Biases in Sentence Encoders.** *Chandler May, Alex Wang, Shikha Bordia, Samuel R. Bowman, Rachel Rudinger.* [[pdf](https://www.aclweb.org/anthology/N19-1063.pdf)]

4. (Gender in sentence embeddings; NeurIPS 2019) **Assessing Social and Intersectional Biases in Contextualized Word Representations.** *Yi Chern Tan, L. Elisa Celis.* [[pdf](https://arxiv.org/pdf/1911.01485.pdf)]

5. (Gender in word embeddings; ACL 2019 Workshop) **Measuring bias in contextualized word representations. / Quantifying Social Biases in Contextual Word Representations.** *Keita Kurita, Nidhi Vyas, Ayush Pareek, Alan W Black, and Yulia Tsvetkov.* [[pdf](https://arxiv.org/pdf/1906.07337.pdf)]

6. (Gender in coreference resolution; NAACL 2018) **Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods.** *Jieyu Zhao, Tianlu Wang, Mark Yatskar, Vicente Ordonez, Kai-Wei Chang.* [[pdf](https://www.aclweb.org/anthology/N18-2003.pdf)]

7. (Gender in coreference resolution; NAACL 2018) **Gender Bias in Coreference Resolution.** *Rudinger, Jason Naradowsky, Brian Leonard, Benjamin Van Durme.*

8. (Gender and race in sentiment analysis; \*SEM 2018) **Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems.** *Svetlana Kiritchenko, Saif Mohammad.* [[pdf](https://www.aclweb.org/anthology/S18-2005.pdf)]

9. (Gender in POS tagging and parsing; ACL 2019) **Women’s Syntactic Resilience and Men’s Grammatical Luck: Gender-Bias in Part-of-Speech Tagging and Dependency Parsing.** *Aparna Garimella, Carmen Banea, Dirk Hovy, Rada Mihalcea.* [[pdf](https://www.aclweb.org/anthology/P19-1339.pdf)]

10. (Gender in relation extraction; ACL 2020) **Towards Understanding Gender Bias in Relation Extraction.** *Andrew Gaut, Tony Sun, Shirlyn Tang, Yuxin Huang, Jing Qian, Mai ElSherief, Jieyu Zhao, Diba Mirza, Elizabeth Belding, Kai-Wei Chang, William Yang Wang.* [[pdf](https://www.aclweb.org/anthology/2020.acl-main.265.pdf)] [[video](https://slideslive.com/38929244/towards-understanding-gender-bias-in-neural-relation-extraction)] [[data](https://www.aclweb.org/anthology/attachments/2020.acl-main.265.Dataset.zip)]

11. (Gender in MT; Neural Computing and Applications 2019) **Assessing Gender Bias in Machine Translation – A Case Study with Google Translate.** *Marcelo O. R. Prates, Pedro H. C. Avelar, Luis Lamb.* [[pdf](https://arxiv.org/pdf/1809.02208)]

12. (Gender in MT; ACL 2020) **Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem.** *Danielle Saunders, Bill Byrne.* [[pdf](https://arxiv.org/pdf/2004.04498.pdf)]

13. (Gender in MT; EMNLP Findings 2020) **Automatically Identifying Gender Issues in Machine Translation using Perturbations.** *Hila Gonen, Kellie Webster.* [[pdf](https://arxiv.org/pdf/2004.14065.pdf)]

14. (Gender in coreference resolution; ACL 2020) **Toward Gender-Inclusive Coreference Resolution.** *Yang Trista Cao, Hal Daumé III.* [[pdf](https://arxiv.org/pdf/1910.13913.pdf)]

15. (Gender in NER; ACM 2019) **Man is to Person as Woman is to Location: Measuring Gender Bias in Named Entity Recognition.** *Ninareh Mehrabi, Thamme Gowda, Fred Morstatter, Nanyun Peng, Aram Galstyan.* [[pdf](https://arxiv.org/pdf/1910.10872.pdf)]

16. (TACL 2018) **Mind the GAP: A Balanced Corpus of Gendered Ambiguous Pronouns.** *Kellie Webster, Marta Recasens, Vera Axelrod, Jason Baldridge* [[pdf](https://arxiv.org/pdf/1810.05201.pdf)]

17. (EMNLP 2017) **Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints.** *Jieyu Zhao, Tianlu Wang, Mark Yatskar, Vicente Ordonez, Kai-Wei Chang.* [[pdf](https://arxiv.org/pdf/1707.09457.pdf)]

18. (ACL 2020) **Mitigating Gender Bias Amplification in Distribution by Posterior Regularization.** *Shengyu Jia, Tao Meng, Jieyu Zhao, Kai-Wei Chang.* [[pdf](https://arxiv.org/pdf/2005.06251.pdf)]

19. (Bias in dialog; AIES 2017) **Ethical Challenges in Data-Driven Dialogue Systems.** _Peter Henderson, Koustuv Sinha, Nicolas Angelard-Gontier, Nan Rosemary Ke, Genevieve Fried, Ryan Lowe, Joelle Pineau_.
    [[pdf](https://arxiv.org/pdf/1711.09050.pdf)]


#### Demographics vs. NLP Model Performance

1. (African American English; EMNLP 2016) **Demographic Dialectal Variation in Social Media: A Case Study of African-American English.** *Su Lin Blodgett, Lisa Green, Brendan O'Connor.* [[pdf](https://arxiv.org/pdf/1608.08868.pdf)]
2. (African American English; PNAS 2020) **Racial Disparity in Automated Speech Recognition.** *Allison Koenecke, Andrew Nam, Emily Lake, Joe Nudell, Minnie Quartey, Zion Mengesha, Connor Toups, John Rickford, Dan Jurafsky, and Sharad Goel.*
3. (2020 ACL) **Social Biases in NLP Models as Barriers for Persons with Disabilities.** *Ben Hutchinson, Vinodkumar Prabhakaran, Emily Denton, Kellie Webster, Yu Zhong, Stephen Denuyl.* [[pdf](https://arxiv.org/pdf/2005.00813.pdf)]
4. (ACL 2017 Workshop) **Social Bias in Elicited Natural Language Inferences.** *Rachel Rudinger, Chandler May, Benjamin Van Durme.* [[pdf](https://www.aclweb.org/anthology/W17-1609.pdf)]
5. (Interspeech 2017) **Effects of talker dialect, gender and race on accuracy of Bing speech and YouTube automatic captions.** *Rachael Tatman, Conner Kasten.* [[pdf](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/1746.PDF)]
6. (Annual Review of Political Science 2016) **Race as a Bundle of Sticks: Designs that Estimate Effects of Seemingly Immutable Characteristics.** *Maya Sen, Omar Wasow.* [[pdf](https://scholar.harvard.edu/files/msen/files/race_causality.pdf)]
7. (KDD 2017 Workshop) **Racial Disparity in Natural Language Processing: A Case Study of Social Media African-American English.** *Su Lin Blodgett, Brendan O'Connor.* [[pdf](https://arxiv.org/pdf/1707.00061.pdf)]

#### Algorithmic fairness

1. (FAccT 2021) **Re-imagining Algorithmic Fairness in India and Beyond.** _Nithya Sambasivan, Erin Arnesen, Ben Hutchinson, Tulsee Doshi, Vinodkumar Prabhakaran_. [[pdf](https://arxiv.org/pdf/2101.09995.pdf)] [[criticism](https://gist.github.com/yoavg/79dc84593dc696e99ebd8d8f878d92f3)]

   [Summary] Current research on AI ethics is US-centric, not easily transferrable to other countries.

#### Caveats of Large Language Models

1. (FAccT 2021) **On the Dangers of Stochastic Parrots: Can Languae Models be Too Big.** _Emily M. Bender, Timnit Gebru, Angelina McMillan-Major, Shmargaret Shmitchell_. [[pdf](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf)] [[criticism](https://gist.github.com/yoavg/9fc9be2f98b47c189a513573d902fb27)]
   <br> [Summary] Warns large LM's issues, e.g., climate problem, bias, etc.

### 5.4 Can we save energy when training NLP models? - GreenNLP

1. (ACL 2019) **Energy and policy considerations for deep learning in NLP.** _Emma Strubell, Ananya Ganesh, Andrew McCallum_. [[pdf](https://www.aclweb.org/anthology/P19-1355.pdf)] [[video](https://vimeo.com/384787604)]
2. (CACM 2020) **Green AI.** _Roy Schwartz, Jesse Dodge, Noah A Smith, Oren  Etzioni_. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3381831)] [[video](https://www.youtube.com/watch?v=KnOpWgUCtaM&ab_channel=AssociationforComputingMachinery%28ACM%29)]
3. (arXiv 2020) **Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning.** _Peter Henderson, Jieru Hu, Joshua Romoff, Emma Brunskill, Dan Jurafsky, Joelle Pineau_ [[pdf](https://arxiv.org/pdf/2002.05651.pdf)]

### 5.5 Be alert of recommendation systems

1. (2019 SSRN) **Recommender systems and their ethical challenges.** _Silvia Milano, Mariarosaria Taddeo, and Luciano Floridi_. [[pdf](https://link.springer.com/content/pdf/10.1007/s00146-020-00950-y.pdf)]

### 5.6 Equip AI with the same morals as humans

1. (2020 EMNLP) **Social Chemistry 101: Learning to Reason about Social and Moral Norms.** *Maxwell Forbes, Jena D. Hwang, Vered Shwartz, Maarten Sap, Yejin Choi*. [[pdf](https://arxiv.org/pdf/2011.00620.pdf)]
2. (2019 arXiv) **BERT has a Moral Compass: Improvements of ethical and moral values of machines.** *Patrick Schramowski, Cigdem Turan, Sophie Jentzsch, Constantin Rothkopf, Kristian Kersting*. [[pdf](https://arxiv.org/pdf/1912.05238.pdf)]

## More reading (for Systematic learning)

### Courses

1. **Stanford CS 384: Ethical and Social Issues in NLP.** _Dan Jurafsky_. [[lectures](https://web.stanford.edu/class/cs384/)]
2. **Computational Ethics for NLP.** [Yulia Tsvetkov](http://www.cs.cmu.edu/~ytsvetko/) and [Alan Black](http://www.cs.cmu.edu/~awb/). [[lectures](http://demo.clab.cs.cmu.edu/ethical_nlp2020/)]
3. **Ethics in NLP.** [Emily Bender](http://faculty.washington.edu/ebender/). [[lectures](https://faculty.washington.edu/ebender/2017_575/)]

## Engagement from Non-Academic Areas

### Non-Profit Movements

- (EA Movement) 80,000 Hours -> Career advice to design your career time (80,000 hours) in the rational way to optimize social good.

## Resources of (general) AI for social good

1. **Introduction to Key Concepts in AI and Machine Learning for Good.** _James Weis, Geeticka Chauhan_. [[slides](https://drive.google.com/file/d/1Bgls-veTF0vMlEm-0xerbMsQm7MGccxw/view)]

### Gov AI@Oxford, CHAI by Stuart Russell@Berkeley promotes AI that can be compatible with humans

2. (Call for AI-Human Cooperation) **Open Problems in Cooperative AI.** _Allan Dafoe, Edward Hughes, Yoram Bachrach, Tantum Collins, Kevin R. McKee, Joel Z. Leibo, Kate Larson, Thore Graepel_. [[pdf](https://arxiv.org/pdf/2012.08630.pdf)]

### Nick Bostrom: prioritize prevention of existential risks

1. (2013) **Existential risk prevention as global priority.** _Nick Bostrom_

### Other materials

1. (2019) 24.131: Ethics of Technology [[reading list](https://www.pqwhite.com/uploads/1/2/8/3/128333712/ethics_of_technology_syllabus_final_12.3.pdf)]
2. (Discussion of community engagement, ICLR 2020) **Participatory Problem Formulation for Fairer Machine Learning Through Community Based System Dynamics.**
   _Donald Martin Jr., Vinodkumar Prabhakaran, Jill Kuhlberg, Andrew Smart, William S. Isaac_. [[pdf](https://arxiv.org/pdf/2005.07572.pdf)]

## Acknowledgements

Lots of credits to the [reading list](https://web.stanford.edu/class/cs384/) of Stanford CS384.
