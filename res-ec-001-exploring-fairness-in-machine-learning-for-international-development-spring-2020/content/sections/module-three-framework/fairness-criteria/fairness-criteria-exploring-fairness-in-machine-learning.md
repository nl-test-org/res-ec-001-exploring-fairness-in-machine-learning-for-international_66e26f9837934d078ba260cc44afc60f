---
about_this_resource_text: ''
course_id: res-ec-001-exploring-fairness-in-machine-learning-for-international-development-spring-2020
embedded_media:
- id: Video-YouTube-Stream
  media_location: euwc0va-7Vo
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: Video-YouTube-Stream
  type: Video
  uid: efc76362f1a3a43a3f89495c4a03f041
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/euwc0va-7Vo/default.jpg
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a20ccc9dc57f71e0fc8976e45488347a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: euwc0va-7Vo
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a31f902e7d9f499f0efcfebe07803c51
- id: euwc0va-7Vo.srt
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  technical_location: https://ocw.mit.edu/resources/res-ec-001-exploring-fairness-in-machine-learning-for-international-development-spring-2020/module-three-framework/fairness-criteria/fairness-criteria-exploring-fairness-in-machine-learning/euwc0va-7Vo.srt
  title: 3play caption file
  type: null
  uid: 3694633835a7cd53b565240dd8a4bade
- id: euwc0va-7Vo.pdf
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  technical_location: https://ocw.mit.edu/resources/res-ec-001-exploring-fairness-in-machine-learning-for-international-development-spring-2020/module-three-framework/fairness-criteria/fairness-criteria-exploring-fairness-in-machine-learning/euwc0va-7Vo.pdf
  title: 3play pdf file
  type: null
  uid: 00dd52b120b8732b9a571fde9a4bab79
- id: Caption-3Play YouTube id-SRT
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3112be0fdb4fb2a1ff07ee398c0ec483
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ff0232f4bdc2a82304e18bfd0a7162a2
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITRES_EC-001S20/MITRES_EC_001S20_video05_300k.mp4
  parent_uid: b27a4187a36cd5d8a74830e44b38730b
  title: Video-Internet Archive-MP4
  type: Video
  uid: cdb7632c84420061a137213ab76e01b3
inline_embed_id: 42741400fairnesscriteriaexploringfairnessinmachinelearning60721934
layout: video
order_index: null
parent_uid: 1c0498f44dcaffcb365a4a06ad7bbeb4
related_resources_text: ''
short_url: fairness-criteria-exploring-fairness-in-machine-learning
technical_location: https://ocw.mit.edu/resources/res-ec-001-exploring-fairness-in-machine-learning-for-international-development-spring-2020/module-three-framework/fairness-criteria/fairness-criteria-exploring-fairness-in-machine-learning
template_type: Embed
title: Fairness Criteria, Exploring Fairness in Machine Learning
transcript: <p><span m='0'>[MUSIC PLAYING]</span> </p><p></p><p><span m='6430'>MIKE
  TEODORESCU:</span> <span m='6625'>Hello,</span> <span m='6820'>and</span> <span
  m='6940'>welcome</span> <span m='7220'>to this</span> <span m='7330'>module on</span>
  <span m='7700'>choices</span> <span m='8050'>of</span> <span m='8140'>fairness</span>
  <span m='8440'>criteria.</span> <span m='9280'>My name is</span> <span m='9440'>Mike</span>
  <span m='9660'>Teodorescu.</span> <span m='10210'>I'm an</span> <span m='10390'>assistant</span>
  <span m='10660'>professor</span> <span m='11000'>of</span> <span m='11050'>information</span>
  <span m='11440'>systems</span> <span m='11860'>at</span> <span m='11920'>Boston</span>
  <span m='12220'>College,</span> <span m='12510'>as</span> <span m='12640'>was</span>
  <span m='12880'>a</span> <span m='12910'>visiting</span> <span m='13240'>scholar</span>
  <span m='13540'>at</span> <span m='13630'>MIT</span> <span m='13990'>D-Lab.</span>
  <span m='14640'>What we'll</span> <span m='14840'>cover in</span> <span m='15100'>this</span>
  <span m='15250'>module</span> <span m='15580'>will be</span> <span m='15700'>the</span>
  <span m='15760'>concept</span> <span m='16120'>of</span> <span m='16210'>confusion</span>
  <span m='16600'>matrix,</span> <span m='17290'>as</span> <span m='17410'>well</span>
  <span m='17530'>as</span> <span m='17640'>three</span> <span m='17810'>popular</span>
  <span m='18190'>examples</span> <span m='18820'>of</span> <span m='19360'>fairness</span>
  <span m='19660'>criteria--</span> <span m='20470'>demographic</span> <span m='20980'>parity,</span>
  <span m='21880'>equalized</span> <span m='22090'>odds,</span> <span m='22600'>and</span>
  <span m='22690'>equalized</span> <span m='22960'>opportunity.</span> </p><p><span
  m='25610'>Some</span> <span m='25820'>countries</span> <span m='26150'>have</span>
  <span m='26300'>laws</span> <span m='26570'>that</span> <span m='26660'>protect</span>
  <span m='26960'>specific</span> <span m='27320'>groups</span> <span m='27530'>of</span>
  <span m='27620'>people</span> <span m='27980'>from</span> <span m='28130'>discrimination</span>
  <span m='29270'>based</span> <span m='29480'>on</span> <span m='29540'>certain</span>
  <span m='29810'>attributes.</span> <span m='31490'>As</span> <span m='31610'>we</span>
  <span m='31720'>review</span> <span m='31930'>in</span> <span m='32030'>the</span>
  <span m='32090'>previous</span> <span m='32570'>video,</span> <span m='33480'>these</span>
  <span m='33590'>are</span> <span m='33650'>called</span> <span m='33920'>protected</span>
  <span m='34310'>attributes.</span> <span m='35630'>Some</span> <span m='35840'>examples</span>
  <span m='36380'>are</span> <span m='36470'>on</span> <span m='36560'>this</span>
  <span m='36650'>slide.</span> <span m='38650'>Regardless</span> <span m='39070'>of</span>
  <span m='39140'>the</span> <span m='39190'>legal</span> <span m='39430'>landscape,</span>
  <span m='39940'>machine</span> <span m='40210'>learning</span> <span m='40480'>has</span>
  <span m='40690'>the</span> <span m='40750'>potential</span> <span m='41190'>to produce</span>
  <span m='41620'>unfair</span> <span m='41950'>outcomes</span> <span m='42850'>for</span>
  <span m='43000'>certain</span> <span m='43210'>groups</span> <span m='43390'>of</span>
  <span m='43480'>people.</span> <span m='45020'>As</span> <span m='45170'>an</span>
  <span m='45260'>algorithm</span> <span m='45500'>designer,</span> <span m='46460'>one</span>
  <span m='46670'>should</span> <span m='46820'>make</span> <span m='47000'>clear</span>
  <span m='47240'>choices</span> <span m='47540'>about</span> <span m='47720'>fairness</span>
  <span m='48050'>criteria.</span> <span m='49520'>Some</span> <span m='49760'>criteria</span>
  <span m='50180'>will</span> <span m='50360'>be</span> <span m='50540'>reviewed</span>
  <span m='51080'>in</span> <span m='51170'>the</span> <span m='51260'>next</span>
  <span m='51470'>few</span> <span m='51560'>slides.</span> </p><p><span m='54910'>[?
  In the ?]</span> <span m='55010'>previous</span> <span m='55190'>video,</span> <span
  m='55570'>we</span> <span m='55670'>also</span> <span m='55730'>discussed</span>
  <span m='56180'>case</span> <span m='56420'>of</span> <span m='56540'>fairness</span>
  <span m='56910'>through</span> <span m='57090'>unawareness,</span> <span m='58020'>which</span>
  <span m='58460'>refers</span> <span m='58910'>to</span> <span m='59030'>leaving</span>
  <span m='59390'>out</span> <span m='59750'>the</span> <span m='59960'>protected</span>
  <span m='60320'>attributes</span> <span m='60970'>out</span> <span m='61150'>of</span>
  <span m='61240'>your</span> <span m='61370'>model.</span> <span m='62190'>And</span>
  <span m='62270'>we</span> <span m='62320'>also</span> <span m='62460'>explained</span>
  <span m='62810'>why</span> <span m='63050'>this</span> <span m='63200'>is</span>
  <span m='63320'>not</span> <span m='63500'>a</span> <span m='63560'>good</span>
  <span m='63680'>choice.</span> <span m='64519'>Specifically,</span> <span m='64970'>you</span>
  <span m='65060'>may</span> <span m='65209'>end</span> <span m='65360'>up</span>
  <span m='65570'>with</span> <span m='65930'>other</span> <span m='66200'>attributes</span>
  <span m='66640'>that</span> <span m='66740'>correlate</span> <span m='67130'>with</span>
  <span m='67300'>protected</span> <span m='67760'>attributes,</span> <span m='68630'>and</span>
  <span m='68840'>you</span> <span m='68900'>may</span> <span m='69080'>end</span>
  <span m='69200'>up</span> <span m='69290'>discriminating</span> <span m='70520'>inadvertently</span>
  <span m='71300'>nonetheless.</span> </p><p><span m='74110'>In</span> <span m='74200'>order</span>
  <span m='74350'>to</span> <span m='74470'>go</span> <span m='74620'>into</span>
  <span m='74770'>additional</span> <span m='75160'>fairness</span> <span m='75520'>criteria,</span>
  <span m='75970'>we</span> <span m='76060'>need</span> <span m='76210'>to</span>
  <span m='76300'>discuss</span> <span m='76660'>some</span> <span m='76780'>additional</span>
  <span m='77080'>concepts.</span> <span m='78750'>Consider</span> <span m='79140'>you</span>
  <span m='79260'>have</span> <span m='79890'>a</span> <span m='80010'>binary</span>
  <span m='80370'>classifier.</span> <span m='81750'>For</span> <span m='81900'>example,</span>
  <span m='82510'>you're</span> <span m='82530'>looking</span> <span m='82830'>at</span>
  <span m='82890'>decision</span> <span m='83610'>of</span> <span m='84090'>hire</span>
  <span m='84630'>or</span> <span m='84750'>not</span> <span m='84990'>hired</span>
  <span m='85830'>or</span> <span m='86070'>to</span> <span m='86250'>lend</span>
  <span m='86490'>credit</span> <span m='86940'>and not</span> <span m='87210'>to</span>
  <span m='87330'>lend</span> <span m='87510'>credit.</span> <span m='88380'>If</span>
  <span m='88500'>we</span> <span m='88590'>want</span> <span m='88750'>to</span>
  <span m='88860'>look</span> <span m='89130'>at</span> <span m='89700'>the</span>
  <span m='90060'>predictions</span> <span m='90840'>for</span> <span m='91350'>a</span>
  <span m='91410'>model</span> <span m='91970'>that</span> <span m='92050'>would</span>
  <span m='92160'>do</span> <span m='92310'>such</span> <span m='92490'>a</span> <span
  m='92550'>binary</span> <span m='92760'>classification,</span> <span m='93540'>we</span>
  <span m='93720'>would</span> <span m='93840'>look</span> <span m='94500'>at</span>
  <span m='94590'>the</span> <span m='94650'>predicted</span> <span m='95040'>values.</span>
  </p><p><span m='95420'>We could</span> <span m='95520'>bucket</span> <span m='95850'>them</span>
  <span m='96120'>in</span> <span m='96300'>four</span> <span m='96540'>categories--</span>
  <span m='97580'>true</span> <span m='97830'>positives,</span> <span m='98430'>which</span>
  <span m='98640'>would</span> <span m='98730'>be</span> <span m='98850'>correctly</span>
  <span m='99240'>classified</span> <span m='99750'>as</span> <span m='99870'>positive,</span>
  <span m='100830'>true</span> <span m='101010'>negative,</span> <span m='101490'>correctly</span>
  <span m='101880'>classified</span> <span m='102300'>as</span> <span m='102390'>negative,</span>
  <span m='103230'>false</span> <span m='103590'>positives,</span> <span m='104130'>which</span>
  <span m='104310'>would</span> <span m='104430'>be</span> <span m='105210'>values</span>
  <span m='105570'>that were</span> <span m='105720'>incorrectly</span> <span m='106260'>classified</span>
  <span m='106710'>as</span> <span m='106830'>positive</span> <span m='107460'>by</span>
  <span m='107600'>the</span> <span m='107700'>algorithm,</span> <span m='108570'>false</span>
  <span m='108870'>negatives,</span> <span m='109320'>which</span> <span m='109500'>would</span>
  <span m='109590'>be</span> <span m='109710'>values</span> <span m='110010'>incorrectly</span>
  <span m='110490'>classified</span> <span m='110880'>as</span> <span m='110970'>negative.</span>
  <span m='112240'>And,</span> <span m='112260'>if</span> <span m='112350'>we</span>
  <span m='112440'>were</span> <span m='112590'>to</span> <span m='113160'>add</span>
  <span m='113560'>the</span> <span m='113790'>the true</span> <span m='114030'>positives</span>
  <span m='114285'>to</span> <span m='114540'>the</span> <span m='114750'>true</span>
  <span m='114840'>negatives</span> <span m='115350'>and</span> <span m='115830'>divide</span>
  <span m='116250'>that</span> <span m='116550'>by</span> <span m='117350'>all</span>
  <span m='117540'>four,</span> <span m='118270'>we</span> <span m='118450'>would</span>
  <span m='118590'>end</span> <span m='118740'>up</span> <span m='118890'>with</span>
  <span m='119040'>the</span> <span m='119160'>value</span> <span m='119550'>of</span>
  <span m='119610'>the</span> <span m='119730'>accuracy</span> <span m='120330'>of</span>
  <span m='120480'>the</span> <span m='120570'>model.</span> <span m='121530'>In</span>
  <span m='121680'>this</span> <span m='121830'>example</span> <span m='122310'>where</span>
  <span m='122520'>accuracy</span> <span m='123240'>is</span> <span m='123540'>this</span>
  <span m='123720'>fraction,</span> <span m='124650'>an</span> <span m='124770'>accuracy</span>
  <span m='125190'>of</span> <span m='125250'>0.5</span> <span m='125970'>is</span>
  <span m='126060'>the</span> <span m='126120'>same</span> <span m='126480'>as</span>
  <span m='126720'>a</span> <span m='126780'>random</span> <span m='127140'>classification.</span>
  </p><p><span m='128970'>Now</span> <span m='129509'>we</span> <span m='129660'>should</span>
  <span m='129810'>look</span> <span m='130199'>at</span> <span m='130380'>accuracy</span>
  <span m='131220'>carefully</span> <span m='131980'>and</span> <span m='132480'>see</span>
  <span m='132780'>that</span> <span m='132930'>it</span> <span m='133020'>doesn't</span>
  <span m='133290'>tell</span> <span m='133410'>us</span> <span m='133560'>anything</span>
  <span m='133890'>about</span> <span m='134060'>the</span> <span m='134370'>prediction</span>
  <span m='134760'>of</span> <span m='134880'>negatives.</span> <span m='135360'>It</span>
  <span m='135450'>could</span> <span m='135600'>mislead</span> <span m='136020'>us</span>
  <span m='136220'>if</span> <span m='136270'>two</span> <span m='136410'>classes</span>
  <span m='136830'>were</span> <span m='137070'>imbalanced,</span> <span m='137790'>for</span>
  <span m='137970'>example,</span> <span m='138520'>if</span> <span m='138570'>90%</span>
  <span m='139140'>of</span> <span m='139230'>the</span> <span m='139290'>sample</span>
  <span m='140160'>is</span> <span m='140370'>positives,</span> <span m='141060'>and</span>
  <span m='141150'>10%</span> <span m='141630'>is</span> <span m='141750'>negatives.</span>
  <span m='142620'>For</span> <span m='142800'>that,</span> <span m='143040'>we</span>
  <span m='143160'>have</span> <span m='143370'>other</span> <span m='144240'>additional</span>
  <span m='144600'>criteria</span> <span m='144990'>we</span> <span m='145110'>could</span>
  <span m='145260'>go</span> <span m='145500'>into</span> <span m='145980'>deeper,</span>
  <span m='146370'>such</span> <span m='146700'>as</span> <span m='146910'>MCC</span>
  <span m='147390'>score</span> <span m='148200'>and</span> <span m='148350'>AUC</span>
  <span m='148770'>score.</span> </p><p><span m='151940'>The</span> <span m='152040'>true</span>
  <span m='152220'>positives,</span> <span m='152910'>true</span> <span m='153090'>negatives,</span>
  <span m='153570'>false</span> <span m='153870'>positives,</span> <span m='154130'>and</span>
  <span m='154390'>false</span> <span m='154530'>negatives</span> <span m='155130'>are,</span>
  <span m='155880'>oftentimes,</span> <span m='156440'>represented</span> <span m='156810'>in</span>
  <span m='156970'>a</span> <span m='157200'>2</span> <span m='157410'>by</span> <span
  m='157560'>2</span> <span m='157740'>matrix</span> <span m='158160'>form</span>
  <span m='158820'>called</span> <span m='159060'>a</span> <span m='159120'>confusion</span>
  <span m='159540'>matrix.</span> <span m='161160'>This</span> <span m='161340'>is</span>
  <span m='161400'>simply</span> <span m='162000'>an</span> <span m='162150'>easier</span>
  <span m='162480'>presentation</span> <span m='163170'>for</span> <span m='163380'>us</span>
  <span m='163560'>to</span> <span m='163920'>see</span> <span m='164160'>the</span>
  <span m='164340'>behavior</span> <span m='164730'>of</span> <span m='164790'>the</span>
  <span m='164880'>classifier.</span> </p><p><span m='167870'>The</span> <span m='167960'>first</span>
  <span m='168200'>additional</span> <span m='168590'>fairness</span> <span m='168920'>criteria</span>
  <span m='169670'>is</span> <span m='169820'>called</span> <span m='170060'>demographic</span>
  <span m='170630'>parity.</span> <span m='171900'>It's</span> <span m='171980'>a</span>
  <span m='172040'>criterion</span> <span m='172550'>for</span> <span m='172880'>what's</span>
  <span m='173120'>called</span> <span m='173390'>group-level</span> <span m='173810'>fairness.</span>
  <span m='175560'>This</span> <span m='175740'>criterion</span> <span m='176160'>specify</span>
  <span m='176880'>that</span> <span m='177240'>the</span> <span m='177420'>outcome,</span>
  <span m='177930'>which</span> <span m='178260'>here</span> <span m='178470'>is</span>
  <span m='178560'>denoted</span> <span m='178920'>by</span> <span m='179160'>a</span>
  <span m='179190'>y</span> <span m='179430'>hat,</span> <span m='179790'>is</span>
  <span m='180030'>independent</span> <span m='180660'>of</span> <span m='180810'>the</span>
  <span m='180900'>protected</span> <span m='181410'>attribute</span> <span m='182010'>A.</span>
  <span m='183300'>For</span> <span m='183540'>example,</span> <span m='184780'>the</span>
  <span m='184880'>probability</span> <span m='185310'>of</span> <span m='185400'>being</span>
  <span m='185670'>hired</span> <span m='186120'>is</span> <span m='186300'>independent</span>
  <span m='186840'>of</span> <span m='187020'>the</span> <span m='187110'>gender.</span>
  </p><p><span m='189610'>There</span> <span m='189760'>are</span> <span m='189820'>multiple</span>
  <span m='190150'>problems</span> <span m='190450'>with</span> <span m='190540'>demographic</span>
  <span m='191050'>parity.</span> <span m='192130'>One</span> <span m='192400'>would</span>
  <span m='192580'>be</span> <span m='192730'>the</span> <span m='192880'>definition</span>
  <span m='193450'>that</span> <span m='193540'>we</span> <span m='193630'>just</span>
  <span m='193810'>discussed</span> <span m='194290'>would</span> <span m='194410'>not</span>
  <span m='194620'>hold</span> <span m='195040'>if</span> <span m='195220'>we</span>
  <span m='195340'>had</span> <span m='196030'>individuals</span> <span m='196570'>who
  would</span> <span m='196720'>be</span> <span m='196840'>members</span> <span m='197350'>of</span>
  <span m='197560'>multiple</span> <span m='197980'>protected</span> <span m='198400'>groups.</span>
  <span m='199300'>By</span> <span m='199510'>enforcing</span> <span m='200140'>group-level</span>
  <span m='200590'>fairness</span> <span m='200980'>for</span> <span m='201100'>one</span>
  <span m='201310'>attribute,</span> <span m='201770'>we</span> <span m='201880'>would</span>
  <span m='202060'>still</span> <span m='202270'>violate</span> <span m='202750'>the</span>
  <span m='202840'>group</span> <span m='202990'>fairness</span> <span m='203350'>for</span>
  <span m='203500'>other</span> <span m='203710'>attributes</span> <span m='204430'>or</span>
  <span m='204550'>combinations</span> <span m='205240'>of</span> <span m='205360'>attributes,</span>
  <span m='205750'>such</span> <span m='205960'>as</span> <span m='206020'>subgroups</span>
  <span m='206800'>of</span> <span m='206950'>the</span> <span m='207010'>population.</span>
  </p><p><span m='209310'>Furthermore,</span> <span m='209910'>while</span> <span
  m='210120'>enforcing</span> <span m='210630'>group-level</span> <span m='211080'>fairness,</span>
  <span m='211560'>for</span> <span m='211710'>example,</span> <span m='212100'>the</span>
  <span m='212190'>same</span> <span m='212460'>hiring</span> <span m='212750'>grade</span>
  <span m='212970'>for</span> <span m='213120'>females</span> <span m='213570'>and</span>
  <span m='213660'>males,</span> <span m='214620'>that</span> <span m='214830'>could</span>
  <span m='214980'>still</span> <span m='215220'>be</span> <span m='215340'>unfair</span>
  <span m='215700'>to</span> <span m='215820'>individuals.</span> <span m='216870'>It</span>
  <span m='216960'>could</span> <span m='217110'>force</span> <span m='217410'>the</span>
  <span m='217530'>algorithm</span> <span m='217750'>to</span> <span m='217950'>drop</span>
  <span m='218200'>otherwise</span> <span m='218610'>qualified</span> <span m='219070'>individuals</span>
  <span m='219630'>just</span> <span m='219900'>to</span> <span m='219990'>achieve</span>
  <span m='220320'>independence</span> <span m='220800'>of</span> <span m='220920'>outcome</span>
  <span m='221190'>of</span> <span m='221280'>the</span> <span m='221400'>attribute.</span>
  <span m='224700'>Fairness</span> <span m='225120'>at</span> <span m='225180'>the</span>
  <span m='225270'>group</span> <span m='225540'>level</span> <span m='225840'>could,</span>
  <span m='226170'>potentially,</span> <span m='226770'>be</span> <span m='227100'>unfair</span>
  <span m='227610'>at</span> <span m='227700'>the</span> <span m='227790'>individual</span>
  <span m='228180'>level.</span> </p><p><span m='229300'>For</span> <span m='229380'>example,</span>
  <span m='230050'>if</span> <span m='230190'>we</span> <span m='230310'>have</span>
  <span m='230910'>a</span> <span m='231000'>high</span> <span m='231300'>rate</span>
  <span m='231540'>of</span> <span m='231600'>false</span> <span m='231930'>positives,</span>
  <span m='232800'>we</span> <span m='232950'>could</span> <span m='233160'>end</span>
  <span m='233310'>up--</span> <span m='233610'>and</span> <span m='233790'>a</span>
  <span m='233850'>low</span> <span m='234030'>rate</span> <span m='234210'>of</span>
  <span m='234270'>false</span> <span m='234540'>negatives,</span> <span m='234990'>it</span>
  <span m='235070'>could</span> <span m='235200'>still</span> <span m='235410'>end</span>
  <span m='235590'>up</span> <span m='235680'>being</span> <span m='235920'>unfair</span>
  <span m='236280'>to</span> <span m='236370'>individuals</span> <span m='237120'>in</span>
  <span m='237300'>that</span> <span m='237540'>we</span> <span m='237660'>could</span>
  <span m='237840'>hire</span> <span m='238110'>people</span> <span m='238410'>who</span>
  <span m='238650'>are</span> <span m='239310'>without</span> <span m='239670'>merit</span>
  <span m='240420'>at</span> <span m='240720'>the</span> <span m='240900'>disadvantage</span>
  <span m='241770'>of</span> <span m='242280'>other</span> <span m='242490'>individuals</span>
  <span m='243030'>who</span> <span m='243120'>could</span> <span m='243330'>be</span>
  <span m='243480'>qualified</span> <span m='244560'>and</span> <span m='244650'>should</span>
  <span m='244860'>be</span> <span m='244980'>hired,</span> <span m='245790'>but,</span>
  <span m='245970'>due</span> <span m='246150'>to</span> <span m='246390'>the</span>
  <span m='246630'>group-level</span> <span m='247200'>fairness</span> <span m='247660'>criterion,</span>
  <span m='248550'>we</span> <span m='248730'>have</span> <span m='249000'>to</span>
  <span m='249420'>hire</span> <span m='249750'>some</span> <span m='250080'>who</span>
  <span m='250290'>are</span> <span m='250350'>not</span> <span m='250590'>qualified</span>
  <span m='251160'>from</span> <span m='251400'>one</span> <span m='251580'>of</span>
  <span m='251640'>the</span> <span m='251730'>groups.</span> </p><p><span m='253820'>The</span>
  <span m='253940'>sweet</span> <span m='254210'>spot</span> <span m='254510'>would</span>
  <span m='254630'>be</span> <span m='254780'>low</span> <span m='255020'>false</span>
  <span m='255290'>negatives</span> <span m='255710'>and</span> <span m='255800'>low</span>
  <span m='256010'>false</span> <span m='256279'>positives,</span> <span m='256820'>which</span>
  <span m='257000'>would</span> <span m='257149'>be</span> <span m='257300'>fair,</span>
  <span m='258019'>potentially,</span> <span m='258440'>to</span> <span m='258560'>both
  the</span> <span m='258800'>individual</span> <span m='259310'>and the</span> <span
  m='259519'>group</span> <span m='259760'>level.</span> <span m='261019'>We</span>
  <span m='261110'>could</span> <span m='261260'>also</span> <span m='261470'>end</span>
  <span m='261589'>up</span> <span m='261769'>in</span> <span m='261890'>the</span>
  <span m='262250'>top</span> <span m='262520'>right</span> <span m='262730'>corner,</span>
  <span m='263090'>which</span> <span m='263240'>would</span> <span m='263330'>be</span>
  <span m='263420'>the</span> <span m='263510'>worst-case</span> <span m='263870'>scenario,</span>
  <span m='264800'>low</span> <span m='265010'>accuracy,</span> <span m='266060'>unfair</span>
  <span m='266390'>to</span> <span m='266480'>individuals,</span> <span m='267310'>but</span>
  <span m='267410'>potentially</span> <span m='267860'>fair</span> <span m='268040'>for</span>
  <span m='268160'>the</span> <span m='268250'>group</span> <span m='268550'>where</span>
  <span m='268700'>we</span> <span m='268820'>have</span> <span m='269570'>high</span>
  <span m='269780'>false</span> <span m='270050'>negatives</span> <span m='270410'>and</span>
  <span m='270490'>high</span> <span m='270650'>false</span> <span m='270860'>positives.</span>
  </p><p><span m='274210'>A</span> <span m='274320'>stricter</span> <span m='274740'>criterion</span>
  <span m='275200'>is</span> <span m='275380'>equalized</span> <span m='275870'>odds,</span>
  <span m='276460'>which</span> <span m='276640'>means</span> <span m='276940'>matching</span>
  <span m='277360'>both</span> <span m='277630'>of</span> <span m='277690'>true</span>
  <span m='277900'>positive</span> <span m='278410'>rate</span> <span m='278770'>and</span>
  <span m='278920'>the</span> <span m='279010'>false</span> <span m='279310'>positive</span>
  <span m='279730'>rate</span> <span m='280510'>for</span> <span m='280660'>different</span>
  <span m='280930'>values</span> <span m='281200'>of</span> <span m='281290'>the</span>
  <span m='281380'>protected</span> <span m='281740'>attribute.</span> <span m='283150'>This</span>
  <span m='283330'>is</span> <span m='283450'>much</span> <span m='283690'>harder</span>
  <span m='283870'>to</span> <span m='284020'>achieve</span> <span m='284350'>than</span>
  <span m='284470'>demographic</span> <span m='284980'>parity,</span> <span m='285760'>but</span>
  <span m='285970'>it is</span> <span m='286120'>one</span> <span m='286300'>of</span>
  <span m='286360'>the</span> <span m='286450'>higher</span> <span m='286720'>levels</span>
  <span m='287020'>of</span> <span m='287140'>algorithmic</span> <span m='287620'>fairness.</span>
  </p><p><span m='289150'>In</span> <span m='289240'>this</span> <span m='289420'>case,</span>
  <span m='290060'>rather</span> <span m='290260'>than</span> <span m='290410'>predicting</span>
  <span m='290860'>the</span> <span m='290950'>same</span> <span m='291250'>average</span>
  <span m='291580'>risk</span> <span m='291850'>across</span> <span m='292150'>subgroups</span>
  <span m='292690'>of</span> <span m='292750'>protected</span> <span m='293110'>social</span>
  <span m='293470'>attributes,</span> <span m='294550'>like</span> <span m='294880'>in</span>
  <span m='295030'>demographic</span> <span m='295510'>parity,</span> <span m='296460'>equalized</span>
  <span m='296930'>odds</span> <span m='297180'>is</span> <span m='297260'>stricter</span>
  <span m='297850'>in</span> <span m='297970'>that</span> <span m='298090'>it</span>
  <span m='298180'>forces</span> <span m='298600'>equality</span> <span m='299080'>only</span>
  <span m='299410'>among</span> <span m='299680'>individuals</span> <span m='300220'>who</span>
  <span m='300310'>reach</span> <span m='300550'>similar</span> <span m='300940'>outcomes.</span>
  <span m='302260'>In</span> <span m='302440'>the</span> <span m='302950'>hiring</span>
  <span m='303240'>example</span> <span m='303700'>that</span> <span m='303790'>we've</span>
  <span m='303910'>discussed</span> <span m='304360'>in</span> <span m='304450'>the</span>
  <span m='304570'>previous</span> <span m='304900'>video,</span> <span m='306040'>this</span>
  <span m='306220'>implies</span> <span m='306640'>that</span> <span m='306730'>the</span>
  <span m='306790'>probability</span> <span m='307270'>of</span> <span m='307330'>a</span>
  <span m='307390'>qualified</span> <span m='307870'>applicant</span> <span m='308230'>to</span>
  <span m='308290'>be</span> <span m='308410'>hired</span> <span m='309120'>and</span>
  <span m='309260'>the</span> <span m='309340'>probability</span> <span m='309790'>of</span>
  <span m='309850'>an</span> <span m='309970'>unqualified</span> <span m='310720'>applicant</span>
  <span m='311140'>to be</span> <span m='311350'>incorrectly</span> <span m='311680'>hired</span>
  <span m='312460'>should</span> <span m='312670'>be</span> <span m='312790'>the</span>
  <span m='312880'>same</span> <span m='313270'>across</span> <span m='313660'>genders.</span>
  </p><p><span m='317030'>A</span> <span m='317270'>milder</span> <span m='317420'>version</span>
  <span m='317870'>of</span> <span m='318050'>equalized</span> <span m='318500'>odds</span>
  <span m='318740'>is</span> <span m='318860'>equalized</span> <span m='319250'>opportunity</span>
  <span m='319820'>where</span> <span m='319970'>we're</span> <span m='320150'>only</span>
  <span m='320510'>concerned</span> <span m='321080'>with</span> <span m='321270'>treating</span>
  <span m='321530'>fairly</span> <span m='322460'>those</span> <span m='322760'>who</span>
  <span m='322880'>are</span> <span m='322970'>determined</span> <span m='323450'>to</span>
  <span m='323540'>be</span> <span m='323690'>worthy</span> <span m='324050'>of</span>
  <span m='324170'>acceptance,</span> <span m='325550'>i.e.</span> <span m='325820'>dependent</span>
  <span m='326210'>variable</span> <span m='326540'>is</span> <span m='326660'>equal</span>
  <span m='326870'>to</span> <span m='326990'>1,</span> <span m='327680'>or</span>
  <span m='328280'>they're</span> <span m='328490'>worthy</span> <span m='328760'>of</span>
  <span m='328850'>being</span> <span m='329030'>hired,</span> <span m='330020'>worthy</span>
  <span m='330210'>of</span> <span m='330320'>being</span> <span m='330530'>admitted,</span>
  <span m='330950'>and</span> <span m='331040'>so</span> <span m='331280'>on.</span>
  <span m='332560'>Equalized</span> <span m='333020'>opportunity</span> <span m='333440'>is</span>
  <span m='333530'>not</span> <span m='333740'>concerned</span> <span m='334070'>with</span>
  <span m='334220'>rejecting</span> <span m='334580'>people</span> <span m='334850'>fairly</span>
  <span m='335270'>across</span> <span m='335570'>protected</span> <span m='335980'>groups.</span>
  </p><p><span m='337140'>So</span> <span m='337250'>to</span> <span m='337320'>speak,</span>
  <span m='337670'>the</span> <span m='337790'>false</span> <span m='338120'>positive</span>
  <span m='338540'>rates</span> <span m='338930'>and</span> <span m='339070'>the</span>
  <span m='339130'>true</span> <span m='339290'>positive</span> <span m='339660'>rates</span>
  <span m='339890'>do</span> <span m='339980'>not</span> <span m='340280'>both</span>
  <span m='340610'>need</span> <span m='340730'>to</span> <span m='340850'>be</span>
  <span m='340970'>equal</span> <span m='341270'>across</span> <span m='341480'>the</span>
  <span m='341580'>protected</span> <span m='341870'>categories.</span> <span m='342830'>We</span>
  <span m='342980'>only</span> <span m='343190'>need</span> <span m='343400'>the</span>
  <span m='343520'>true</span> <span m='343730'>positive</span> <span m='344140'>rate</span>
  <span m='344300'>to</span> <span m='344420'>be</span> <span m='344570'>equal</span>
  <span m='344870'>across</span> <span m='345170'>protected</span> <span m='345530'>categories.</span>
  <span m='347410'>In</span> <span m='347530'>a</span> <span m='347590'>way,</span>
  <span m='348040'>equalized</span> <span m='348420'>opportunity</span> <span m='348930'>is</span>
  <span m='349060'>less</span> <span m='349300'>interventionist</span> <span m='349990'>than</span>
  <span m='350080'>equalized</span> <span m='350470'>odds,</span> <span m='351280'>and</span>
  <span m='351580'>it</span> <span m='351700'>may</span> <span m='351850'>be</span>
  <span m='351970'>more</span> <span m='352180'>achievable,</span> <span m='353230'>depending</span>
  <span m='353710'>on</span> <span m='353890'>your</span> <span m='354100'>individual</span>
  <span m='354640'>situation</span> <span m='355420'>and</span> <span m='355660'>implementation</span>
  <span m='356350'>challenges.</span> </p><p><span m='358720'>In</span> <span m='358870'>the</span>
  <span m='358960'>example</span> <span m='359530'>of</span> <span m='359830'>hiring,</span>
  <span m='360820'>we</span> <span m='360970'>only</span> <span m='361330'>are</span>
  <span m='361510'>concerned</span> <span m='361990'>with</span> <span m='362110'>individuals</span>
  <span m='362680'>who are</span> <span m='362860'>worthy</span> <span m='363400'>of</span>
  <span m='363640'>being</span> <span m='363880'>hired,</span> <span m='364630'>i.e.</span>
  <span m='364900'>the</span> <span m='365080'>actual</span> <span m='365800'>qualified</span>
  <span m='366310'>applicants.</span> <span m='367000'>And,</span> <span m='367340'>out</span>
  <span m='367480'>of</span> <span m='367570'>the</span> <span m='367680'>rejected</span>
  <span m='368110'>applicants,</span> <span m='368530'>we</span> <span m='368620'>may</span>
  <span m='368780'>be</span> <span m='368930'>sometimes</span> <span m='369260'>rejecting</span>
  <span m='369620'>unfairly.</span> </p><p><span m='372610'>Here's</span> <span m='372740'>some</span>
  <span m='372890'>review</span> <span m='373100'>questions</span> <span m='373550'>for</span>
  <span m='374450'>the</span> <span m='374510'>last</span> <span m='374750'>two</span>
  <span m='374840'>videos.</span> <span m='375950'>What</span> <span m='376190'>is</span>
  <span m='376310'>demographic</span> <span m='376820'>parity?</span> <span m='377960'>What</span>
  <span m='378170'>is</span> <span m='378320'>fairness</span> <span m='378640'>through</span>
  <span m='378790'>unawareness?</span> <span m='380580'>Is</span> <span m='380760'>fairness</span>
  <span m='381150'>at the</span> <span m='381270'>group</span> <span m='381510'>level</span>
  <span m='381840'>always</span> <span m='382110'>the</span> <span m='382200'>best?</span>
  <span m='383490'>What</span> <span m='383670'>is</span> <span m='383760'>a</span>
  <span m='383820'>confusion</span> <span m='384210'>matrix?</span> <span m='386020'>What</span>
  <span m='386180'>is</span> <span m='386290'>the</span> <span m='386350'>equality</span>
  <span m='386740'>of</span> <span m='386860'>odds</span> <span m='387040'>criterion?</span>
  <span m='387540'>And when</span> <span m='387760'>might</span> <span m='387990'>you
  want</span> <span m='388180'>to</span> <span m='388240'>use</span> <span m='388420'>it?</span>
  </p><p><span m='391150'>This</span> <span m='391230'>course</span> <span m='391500'>is</span>
  <span m='391560'>sponsored</span> <span m='392040'>by</span> <span m='392400'>the</span>
  <span m='392580'>USAID</span> <span m='393330'>grant</span> <span m='393840'>through</span>
  <span m='393950'>MIT</span> <span m='394170'>D-Lab.</span> <span m='395520'>And</span>
  <span m='395760'>this</span> <span m='395910'>is</span> <span m='396000'>joint</span>
  <span m='396270'>work</span> <span m='396540'>with</span> <span m='396690'>my</span>
  <span m='396810'>faculty</span> <span m='397200'>colleagues</span> <span m='397500'>Lily</span>
  <span m='397710'>Morse</span> <span m='398160'>and</span> <span m='398310'>Gerald</span>
  <span m='398580'>Kane</span> <span m='399000'>from</span> <span m='399180'>Boston</span>
  <span m='399480'>college</span> <span m='400470'>and</span> <span m='400730'>research</span>
  <span m='400950'>assistant</span> <span m='401400'>Yazeed</span> <span m='401640'>Awwad</span>
  <span m='401970'>from</span> <span m='402120'>MIT</span> <span m='402440'>D-Lab.</span>
  <span m='405390'>If</span> <span m='405510'>you</span> <span m='405570'>would</span>
  <span m='405640'>like</span> <span m='405780'>to</span> <span m='405870'>learn</span>
  <span m='406080'>more</span> <span m='406290'>about</span> <span m='406500'>this,</span>
  <span m='406950'>please</span> <span m='407190'>consult</span> <span m='407490'>the</span>
  <span m='407550'>following</span> <span m='407850'>references.</span> <span m='410040'>Thank</span>
  <span m='410150'>you</span> <span m='410210'>so</span> <span m='410300'>much</span>
  <span m='410480'>for</span> <span m='410570'>watching</span> <span m='410810'>this</span>
  <span m='410930'>video.</span> <span m='411960'>We</span> <span m='411980'>hope</span>
  <span m='412130'>you</span> <span m='412190'>find it</span> <span m='412430'>useful</span>
  <span m='413060'>and</span> <span m='413180'>you'll</span> <span m='413300'>continue</span>
  <span m='413660'>watching</span> <span m='413990'>the</span> <span m='414050'>rest</span>
  <span m='414230'>of</span> <span m='414290'>the</span> <span m='414380'>class.</span>
  </p><p><span m='415880'>[MUSIC PLAYING]</span> </p><p></p>
type: course
uid: b27a4187a36cd5d8a74830e44b38730b

---
None