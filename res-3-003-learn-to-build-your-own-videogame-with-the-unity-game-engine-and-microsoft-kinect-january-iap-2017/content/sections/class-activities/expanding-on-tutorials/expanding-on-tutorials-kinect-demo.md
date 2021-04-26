---
about_this_resource_text: <p>Mark Vrablic demonstrates how the Unity game engine connects
  to the Microsoft Kinect. The guided tutorial that students have completed called
  &ldquo;roll-a-ball&rdquo; is a game normally driven by arrow keys on a standard
  keyboard. In this video, Mark shows how to modify the game to have the controls
  be dictated by the position of the user&rsquo;s hands and other body parts in space.</p>
course_id: res-3-003-learn-to-build-your-own-videogame-with-the-unity-game-engine-and-microsoft-kinect-january-iap-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: JJRijRD4l-g
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: Video-YouTube-Stream
  type: Video
  uid: 91c426995c784172f2cb3b66b32fefc3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/JJRijRD4l-g/default.jpg
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e8937e9b9b964491ea8b0201e1b152be
- id: 3Play-3PlayYouTubeid-MP4
  media_location: JJRijRD4l-g
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0be8cb7ebcafa6e956315bbb9ade4d85
- id: JJRijRD4l-g.srt
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  technical_location: https://ocw.mit.edu/resources/res-3-003-learn-to-build-your-own-videogame-with-the-unity-game-engine-and-microsoft-kinect-january-iap-2017/class-activities/expanding-on-tutorials/expanding-on-tutorials-kinect-demo/JJRijRD4l-g.srt
  title: 3play caption file
  type: null
  uid: ba9a8e65e08bfccd6dbafde0b4b0559b
- id: JJRijRD4l-g.pdf
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  technical_location: https://ocw.mit.edu/resources/res-3-003-learn-to-build-your-own-videogame-with-the-unity-game-engine-and-microsoft-kinect-january-iap-2017/class-activities/expanding-on-tutorials/expanding-on-tutorials-kinect-demo/JJRijRD4l-g.pdf
  title: 3play pdf file
  type: null
  uid: 6bd986dfad6714fc809c3630403dd934
- id: Subtitle-3Play YouTube id-SRT
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: Subtitle-3Play YouTube id-SRT-English - US
  type: Subtitle
  uid: d487c94df284325159598b13f6cb843d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0fdacd2df9f5e3b7a3278ce9095dba21
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITRES.3-003IAP17/MITRES_3-003IAP17_Class_Activities_09_300k.mp4
  parent_uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1d895953390562ede4d281cb851f9d99
inline_embed_id: 46094641expandingontutorialskinectdemo57839956
layout: video
order_index: null
parent_uid: 48db19f328478c3be3ad7ce69c5aa9e0
related_resources_text: ''
short_url: expanding-on-tutorials-kinect-demo
technical_location: https://ocw.mit.edu/resources/res-3-003-learn-to-build-your-own-videogame-with-the-unity-game-engine-and-microsoft-kinect-january-iap-2017/class-activities/expanding-on-tutorials/expanding-on-tutorials-kinect-demo
template_type: Tabbed
title: 'Expanding on Tutorials: Kinect Demo'
transcript: <p><span m='16104'>PROFESSOR:</span> <span m='16352'>OK.</span> <span
  m='16600'>So</span> <span m='16830'>at</span> <span m='16950'>this</span> <span
  m='17160'>point,</span> <span m='17920'>we</span> <span m='18130'>have</span> <span
  m='18380'>our</span> <span m='18750'>roller ball</span> <span m='19120'>demo.</span>
  <span m='19650'>Now,</span> <span m='20040'>we</span> <span m='20280'>would like</span>
  <span m='20490'>to</span> <span m='20610'>interface</span> <span m='21150'>with</span>
  <span m='21300'>the</span> <span m='21400'>Kinect.</span> <span m='22470'>To</span>
  <span m='22560'>do</span> <span m='22740'>this,</span> <span m='23460'>we're</span>
  <span m='23550'>going</span> <span m='23670'>to</span> <span m='23730'>use</span>
  <span m='24170'>the</span> <span m='24260'>simple</span> <span m='24525'>Kinect</span>
  <span m='25910'>Unity</span> <span m='26250'>package.</span> <span m='26976'>It's</span>
  <span m='27340'>over</span> <span m='27540'>here.</span> <span m='28630'>So</span>
  <span m='29330'>in the</span> <span m='29590'>simple Kinect</span> <span m='29900'>package</span>
  <span m='30210'>there</span> <span m='30640'>is a</span> <span m='30770'>prefab.</span>
  <span m='31560'>You</span> <span m='31710'>can</span> <span m='31830'>drag</span>
  <span m='32110'>this</span> <span m='32360'>prefab</span> <span m='33210'>into</span>
  <span m='33520'>your</span> <span m='33690'>game</span> <span m='34740'>and</span>
  <span m='34890'>it</span> <span m='35040'>will</span> <span m='35610'>initiate</span>
  <span m='36110'>the</span> <span m='36260'>Kinect</span> <span m='36630'>and</span>
  <span m='37350'>do</span> <span m='37530'>all</span> <span m='37940'>the</span>
  <span m='38030'>stuff</span> <span m='38380'>that's</span> <span m='38610'>required</span>
  <span m='38920'>for that.</span> </p><p><span m='42390'>So</span> <span m='42470'>now,</span>
  <span m='43120'>when</span> <span m='43280'>I</span> <span m='43370'>start</span>
  <span m='43610'>my</span> <span m='43760'>game,</span> <span m='45671'>the</span>
  <span m='46168'>Kinect</span> <span m='46665'>will</span> <span m='47162'>turn</span>
  <span m='47659'>on.</span> <span m='48660'>And</span> <span m='49800'>it's</span>
  <span m='49930'>not</span> <span m='50370'>going to</span> <span m='50810'>do</span>
  <span m='50960'>anything</span> <span m='51290'>yet</span> <span m='51550'>because</span>
  <span m='51740'>I</span> <span m='51970'>haven't</span> <span m='52450'>interfaced</span>
  <span m='52755'>it.</span> <span m='55560'>So,</span> <span m='56720'>now</span>
  <span m='57000'>I</span> <span m='57330'>want</span> <span m='57640'>my ball</span>
  <span m='57995'>that</span> <span m='58440'>we</span> <span m='58560'>created</span>
  <span m='58830'>previously</span> <span m='59730'>to</span> <span m='59820'>follow</span>
  <span m='60150'>my</span> <span m='60300'>right</span> <span m='60510'>hand</span>
  <span m='60770'>sign.</span> <span m='61890'>So</span> <span m='62040'>what</span>
  <span m='62160'>we're</span> <span m='62260'>going</span> <span m='62380'>to</span>
  <span m='62430'>do</span> <span m='64769'>is</span> <span m='64950'>go</span> <span
  m='65290'>into</span> <span m='66180'>our</span> <span m='66300'>player</span> <span
  m='68550'>and</span> <span m='68640'>we're</span> <span m='68740'>going</span> <span
  m='68820'>to add</span> <span m='68920'>a script.</span> <span m='70170'>The</span>
  <span m='70430'>script</span> <span m='70690'>that</span> <span m='70910'>we're</span>
  <span m='71130'>going to</span> <span m='71475'>add</span> <span m='71820'>is</span>
  <span m='72180'>the</span> <span m='72760'>follow</span> <span m='73070'>join.</span>
  <span m='73860'>You</span> <span m='73980'>can</span> <span m='74100'>find</span>
  <span m='74370'>it</span> <span m='74730'>in</span> <span m='77170'>scripts,</span>
  <span m='80155'>no,</span> <span m='82050'>Kinect</span> <span m='82320'>stuff.</span>
  <span m='82490'>There</span> <span m='82880'>it is</span> <span m='84220'>and</span>
  <span m='84510'>follow join.</span> <span m='84720'>So</span> <span m='85020'>let's</span>
  <span m='85290'>drag it on to</span> <span m='85410'>our</span> <span m='85560'>player,</span>
  <span m='90350'>and</span> <span m='90470'>then</span> <span m='90620'>we</span>
  <span m='90880'>need</span> <span m='91140'>to</span> <span m='91820'>fill</span>
  <span m='92060'>out</span> <span m='92310'>which</span> <span m='92670'>object</span>
  <span m='92990'>we would</span> <span m='93220'>like to</span> <span m='93400'>track.</span>
  </p><p><span m='97610'>So in</span> <span m='97820'>this</span> <span m='98030'>case</span>
  <span m='98230'>I'd</span> <span m='98470'>like</span> <span m='98620'>to</span>
  <span m='98760'>follow my</span> <span m='99100'>right</span> <span m='99320'>hand.</span>
  <span m='100300'>And</span> <span m='100400'>you can</span> <span m='100600'>find</span>
  <span m='101350'>that</span> <span m='101670'>I</span> <span m='102050'>have a</span>
  <span m='102430'>right</span> <span m='102670'>hand</span> <span m='102925'>object</span>
  <span m='103180'>here.</span> <span m='105535'>So</span> <span m='105960'>you can</span>
  <span m='106380'>drag</span> <span m='106670'>this</span> <span m='106860'>right</span>
  <span m='107100'>hand</span> <span m='107564'>object</span> <span m='111740'>into</span>
  <span m='112010'>the</span> <span m='112100'>player</span> <span m='112490'>controller</span>
  <span m='112775'>script.</span> <span m='116330'>So</span> <span m='116480'>that's</span>
  <span m='116680'>the</span> <span m='116840'>tracked</span> <span m='117080'>object.</span>
  <span m='119570'>And</span> <span m='119830'>now</span> <span m='120120'>the ball
  should</span> <span m='120490'>follow my</span> <span m='120840'>right hand.</span>
  </p><p></p><p><span m='129750'>So</span> <span m='130245'>you can</span> <span m='130759'>see
  it there</span> <span m='130930'>in</span> <span m='131130'>the</span> <span m='131270'>scene.</span>
  <span m='131610'>As I</span> <span m='131950'>move</span> <span m='132130'>my</span>
  <span m='132610'>hand</span> <span m='133090'>closer</span> <span m='133310'>to
  the</span> <span m='133725'>Kinect,</span> <span m='134140'>it</span> <span m='134555'>moves</span>
  <span m='134970'>closer</span> <span m='135180'>to</span> <span m='135665'>the camera.</span>
  <span m='136150'>In</span> <span m='136320'>many</span> <span m='136480'>gamines,</span>
  <span m='136910'>this</span> <span m='137020'>isn't</span> <span m='137200'>what</span>
  <span m='137350'>You'd</span> <span m='137470'>want</span> <span m='137710'>though.</span>
  <span m='138520'>So</span> <span m='138970'>inside</span> <span m='139410'>that</span>
  <span m='139600'>follow</span> <span m='139780'>join</span> <span m='139840'>script</span>
  <span m='140650'>there</span> <span m='141210'>is</span> <span m='141370'>an</span>
  <span m='141630'>to</span> <span m='142000'>invert</span> <span m='142380'>each</span>
  <span m='142610'>access.</span> <span m='143470'>Since</span> <span m='143740'>the</span>
  <span m='143830'>z-axis</span> <span m='144540'>is</span> <span m='144820'>one</span>
  <span m='145000'>goes</span> <span m='145320'>toward</span> <span m='145650'>the</span>
  <span m='146050'>camera,</span> <span m='146540'>in</span> <span m='146640'>this</span>
  <span m='146680'>case,</span> <span m='147500'>we're</span> <span m='147580'>going
  to</span> <span m='147800'>invert the</span> <span m='148250'>z-axis.</span> <span
  m='150460'>So</span> <span m='150610'>now,</span> <span m='151070'>when</span> <span
  m='151230'>we click</span> <span m='151510'>play,</span> <span m='152810'>as I move</span>
  <span m='153310'>my</span> <span m='153700'>hand</span> <span m='153970'>forward,</span>
  <span m='156790'>the</span> <span m='156880'>ball</span> <span m='157120'>moves</span>
  <span m='157390'>forward</span> <span m='157720'>within</span> <span m='158320'>the</span>
  <span m='158410'>world</span> <span m='158680'>space,</span> <span m='159440'>and</span>
  <span m='159670'>back,</span> <span m='161350'>left,</span> <span m='161620'>right,</span>
  <span m='164180'>up,</span> <span m='164650'>down,</span> <span m='165290'>etc.</span>
  <span m='167320'>So</span> <span m='167470'>now,</span> <span m='168160'>with</span>
  <span m='168310'>my</span> <span m='168430'>right</span> <span m='168700'>hand,</span>
  <span m='169380'>I</span> <span m='169460'>can</span> <span m='169690'>control</span>
  <span m='170130'>the</span> <span m='170170'>ball.</span> </p><p><span m='173710'>All</span>
  <span m='173950'>of</span> <span m='173980'>the</span> <span m='174170'>pick-ups</span>
  <span m='174680'>should</span> <span m='174820'>still</span> <span m='175030'>work</span>
  <span m='175380'>as</span> <span m='175560'>they</span> <span m='175660'>did</span>
  <span m='175820'>before</span> <span m='177002'>and</span> <span m='177360'>the</span>
  <span m='177560'>game</span> <span m='177750'>can</span> <span m='177880'>still</span>
  <span m='178090'>be</span> <span m='178240'>won.</span> <span m='179730'>So</span>
  <span m='180140'>I'm</span> <span m='180550'>getting</span> <span m='180820'>all</span>
  <span m='181050'>the</span> <span m='181420'>pick-ups</span> <span m='181895'>with</span>
  <span m='182370'>my</span> <span m='182845'>right</span> <span m='183320'>hand.</span>
  <span m='183795'>Have to</span> <span m='184270'>go</span> <span m='184745'>back
  it up</span> <span m='185220'>a little.</span> <span m='188070'>It's</span> <span
  m='188190'>just</span> <span m='188400'>like</span> <span m='188580'>using</span>
  <span m='188910'>a</span> <span m='188970'>mouse</span> <span m='189450'>or</span>
  <span m='189830'>arrow keys,</span> <span m='190140'>but in</span> <span m='190470'>3D.</span>
  <span m='194710'>So</span> <span m='194890'>as you can</span> <span m='195290'>see,</span>
  <span m='195530'>that still</span> <span m='195620'>works.</span> <span m='196387'>Your</span>
  <span m='196824'>turn.</span> <span m='199010'>So</span> <span m='199230'>now,</span>
  <span m='199790'>let's</span> <span m='199870'>say we want</span> <span m='200020'>to</span>
  <span m='200080'>track</span> <span m='200290'>something</span> <span m='200680'>other</span>
  <span m='200920'>than</span> <span m='201040'>our</span> <span m='201370'>right</span>
  <span m='201530'>hand.</span> <span m='203491'>You can</span> <span m='203870'>adjust</span>
  <span m='204260'>this</span> <span m='204660'>in</span> <span m='204880'>the</span>
  <span m='205000'>moving</span> <span m='205480'>object</span> <span m='205790'>parent.</span>
  <span m='207340'>So</span> <span m='207620'>I</span> <span m='207890'>have</span>
  <span m='208090'>a</span> <span m='208200'>detect</span> <span m='208420'>joint</span>
  <span m='208840'>script</span> <span m='209050'>attached to</span> <span m='209530'>here</span>
  <span m='210280'>and</span> <span m='210480'>this</span> <span m='210730'>has</span>
  <span m='211370'>a</span> <span m='211490'>track</span> <span m='211830'>joint</span>
  <span m='212070'>option.</span> <span m='212830'>You</span> <span m='212950'>can</span>
  <span m='213040'>change</span> <span m='213400'>this</span> <span m='215200'>to</span>
  <span m='215350'>be</span> <span m='215890'>any</span> <span m='216300'>joint</span>
  <span m='216660'>you</span> <span m='217105'>like.</span> </p><p><span m='218440'>So</span>
  <span m='218740'>let's</span> <span m='219010'>say</span> <span m='220570'>I</span>
  <span m='220670'>want</span> <span m='220900'>to</span> <span m='221050'>do</span>
  <span m='222370'>my</span> <span m='222550'>left</span> <span m='222940'>and.</span>
  <span m='224050'>I'll select</span> <span m='224500'>the</span> <span m='224860'>hand</span>
  <span m='225190'>left</span> <span m='225480'>object,</span> <span m='226974'>which</span>
  <span m='227970'>is</span> <span m='228468'>somewhere.</span> <span m='230958'>There</span>
  <span m='231456'>it is.</span> <span m='235950'>And</span> <span m='236070'>then,</span>
  <span m='236520'>for</span> <span m='237090'>the</span> <span m='237180'>sake</span>
  <span m='237480'>of</span> <span m='237840'>making</span> <span m='238350'>things</span>
  <span m='238590'>make</span> <span m='238730'>sense,</span> <span m='239430'>rename</span>
  <span m='239820'>my</span> <span m='239970'>object</span> <span m='240423'>to</span>
  <span m='241330'>left</span> <span m='241610'>hand</span> <span m='241790'>object.</span>
  <span m='247290'>So</span> <span m='247550'>now</span> <span m='247780'>that this</span>
  <span m='247960'>is</span> <span m='248080'>called</span> <span m='248510'>left
  hand</span> <span m='248670'>object,</span> <span m='249820'>we</span> <span m='249910'>want</span>
  <span m='250060'>to</span> <span m='250120'>make</span> <span m='250240'>sure</span>
  <span m='250670'>that</span> <span m='251030'>the</span> <span m='251410'>object</span>
  <span m='251680'>attached</span> <span m='252010'>to</span> <span m='252350'>the</span>
  <span m='252850'>player controller,</span> <span m='253270'>follow</span> <span
  m='253600'>join,</span> <span m='254200'>is</span> <span m='254470'>indeed</span>
  <span m='254830'>the</span> <span m='255100'>left</span> <span m='255370'>hand</span>
  <span m='255550'>object</span> <span m='256350'>as</span> <span m='257040'>is</span>
  <span m='257470'>visible</span> <span m='257980'>right</span> <span m='258160'>here.</span>
  <span m='260360'>So</span> <span m='260380'>now</span> <span m='261760'>when</span>
  <span m='261910'>I</span> <span m='261970'>click</span> <span m='262240'>play,</span>
  <span m='264560'>it</span> <span m='265050'>should follow</span> <span m='265330'>my</span>
  <span m='265450'>left</span> <span m='265690'>hand</span> <span m='265900'>not my</span>
  <span m='266250'>right</span> <span m='266420'>hand.</span> <span m='269836'>If</span>
  <span m='270324'>the Kinect can</span> <span m='270812'>find me.</span> <span m='271788'>There</span>
  <span m='272276'>it is.</span> <span m='274730'>And</span> <span m='274880'>so</span>
  <span m='275205'>I</span> <span m='275530'>can</span> <span m='275720'>move my</span>
  <span m='276010'>left hand</span> <span m='276340'>forward,</span> <span m='276760'>left,</span>
  <span m='277510'>right,</span> <span m='277860'>up,</span> <span m='278263'>down,</span>
  <span m='278666'>etc.</span> <span m='279782'>So</span> <span m='280204'>now,</span>
  <span m='280626'>let's</span> <span m='281050'>say we</span> <span m='281220'>want
  to try</span> <span m='281570'>multiple joints at the</span> <span m='281920'>same</span>
  <span m='282220'>time.</span> </p><p><span m='284280'>This</span> <span m='284440'>whole</span>
  <span m='284610'>moving</span> <span m='285110'>objects</span> <span m='285420'>parent</span>
  <span m='285890'>part</span> <span m='286160'>can be</span> <span m='286540'>duplicated.</span>
  <span m='287510'>So</span> <span m='287950'>Control</span> <span m='288070'>D</span>
  <span m='288940'>or</span> <span m='289210'>Command</span> <span m='289490'>D</span>
  <span m='289770'>to</span> <span m='290130'>duplicate.</span> <span m='291780'>And</span>
  <span m='291890'>we</span> <span m='292010'>can</span> <span m='292130'>now</span>
  <span m='293280'>create</span> <span m='293490'>a</span> <span m='293900'>left had</span>
  <span m='294040'>object</span> <span m='294330'>and a</span> <span m='294620'>right</span>
  <span m='294850'>hand</span> <span m='295322'>object.</span> <span m='296740'>So</span>
  <span m='298420'>let's</span> <span m='298570'>go</span> <span m='298720'>back</span>
  <span m='299020'>to</span> <span m='299190'>being</span> <span m='299520'>hand-right</span>
  <span m='303281'>and</span> <span m='303774'>rename</span> <span m='304760'>this.</span>
  </p><p></p><p><span m='311670'>So I'm</span> <span m='312000'>going to add</span>
  <span m='312280'>another</span> <span m='312490'>sphere</span> <span m='312660'>to</span>
  <span m='312930'>my</span> <span m='313060'>scene</span> <span m='314820'>in</span>
  <span m='314940'>order</span> <span m='315210'>to</span> <span m='316140'>have</span>
  <span m='316320'>another</span> <span m='316620'>object</span> <span m='316950'>for</span>
  <span m='317352'>my</span> <span m='317754'>game.</span> <span m='318560'>So</span>
  <span m='318780'>let's</span> <span m='319105'>create</span> <span m='319430'>a</span>
  <span m='319710'>sphere.</span> <span m='322100'>And</span> <span m='322220'>then</span>
  <span m='322430'>I'm</span> <span m='322550'>going</span> <span m='322820'>it</span>
  <span m='322910'>so</span> <span m='323120'>that</span> <span m='323510'>my</span>
  <span m='323660'>right</span> <span m='323900'>hand</span> <span m='324110'>follows</span>
  <span m='324450'>this</span> <span m='324620'>one</span> <span m='324980'>since</span>
  <span m='325180'>my</span> <span m='325270'>left</span> <span m='325550'>hand</span>
  <span m='325850'>already</span> <span m='326230'>follows</span> <span m='326570'>the
  player.</span> <span m='330434'>So</span> <span m='330917'>in Kinect</span> <span
  m='331400'>stuff,</span> <span m='331890'>follow</span> <span m='332280'>join.</span>
  <span m='332840'>Drag</span> <span m='333200'>it</span> <span m='333560'>right</span>
  <span m='333760'>on</span> <span m='334020'>to</span> <span m='334260'>that</span>
  <span m='334545'>sphere.</span> <span m='337480'>OK.</span> <span m='339190'>So</span>
  <span m='339370'>now,</span> <span m='339850'>I</span> <span m='339940'>want</span>
  <span m='340340'>this</span> <span m='340540'>to follow</span> <span m='340830'>my</span>
  <span m='340990'>right</span> <span m='341230'>hand</span> <span m='341570'>object,</span>
  <span m='341910'>so</span> <span m='342130'>I'm going to</span> <span m='342350'>drag</span>
  <span m='342710'>that</span> <span m='342890'>in</span> <span m='343225'>as</span>
  <span m='343560'>my</span> <span m='343690'>track</span> <span m='343970'>joint.</span>
  <span m='347014'>And</span> <span m='347478'>now</span> <span m='347942'>that</span>
  <span m='348410'>sphere</span> <span m='348665'>should</span> <span m='348920'>follow</span>
  <span m='349390'>my right hand,</span> <span m='349735'>while the</span> <span m='350080'>other
  follows</span> <span m='350400'>my left.</span> </p><p></p><p><span m='361280'>So</span>
  <span m='361550'>I</span> <span m='361650'>didn't</span> <span m='361870'>set</span>
  <span m='362160'>the</span> <span m='362470'>invert</span> <span m='362760'>option
  on that</span> <span m='363230'>one though,</span> <span m='363700'>so</span> <span
  m='363900'>as I move</span> <span m='364290'>forward,</span> <span m='364970'>they</span>
  <span m='365270'>each</span> <span m='365770'>go</span> <span m='366010'>in</span>
  <span m='366170'>opposite</span> <span m='366380'>directions.</span> <span m='368920'>But</span>
  <span m='369280'>otherwise,</span> <span m='370070'>left and right</span> <span
  m='370850'>work</span> <span m='371080'>as</span> <span m='371260'>you'd</span>
  <span m='371380'>expect,</span> <span m='371830'>and</span> <span m='372180'>up</span>
  <span m='372530'>and down.</span> <span m='373190'>So</span> <span m='373630'>let's</span>
  <span m='373750'>say</span> <span m='374260'>I</span> <span m='374380'>want</span>
  <span m='374530'>to</span> <span m='374600'>try</span> <span m='374800'>a</span>
  <span m='374870'>different</span> <span m='375160'>joint.</span> <span m='378751'>Like,</span>
  <span m='379240'>let's</span> <span m='379480'>make my</span> <span m='379750'>left
  hand</span> <span m='380165'>object</span> <span m='380760'>be</span> <span m='380980'>my</span>
  <span m='381220'>head.</span> <span m='383905'>We'll</span> <span m='384382'>go</span>
  <span m='384859'>to</span> <span m='385336'>that moving object</span> <span m='385820'>parent
  ,</span> <span m='386984'>change</span> <span m='387406'>it</span> <span m='387830'>to
  head</span> <span m='388170'>here.</span> <span m='389150'>And</span> <span m='389240'>let's</span>
  <span m='389460'>rename</span> <span m='390070'>this</span> <span m='390370'>to</span>
  <span m='390858'>head.</span> </p><p></p><p><span m='406010'>Now,</span> <span m='407050'>my</span>
  <span m='407520'>right</span> <span m='407760'>hand</span> <span m='408300'>controls</span>
  <span m='408740'>the</span> <span m='408980'>sphere that we</span> <span m='409200'>just</span>
  <span m='409380'>added</span> <span m='409880'>and</span> <span m='410050'>my</span>
  <span m='410190'>head</span> <span m='410520'>controls</span> <span m='410760'>the</span>
  <span m='410850'>player.</span> <span m='412810'>So,</span> <span m='414350'>where</span>
  <span m='414500'>is</span> <span m='414650'>my</span> <span m='414740'>right hand?</span>
  <span m='415080'>There is</span> <span m='415250'>my</span> <span m='415470'>right</span>
  <span m='415650'>hand.</span> <span m='416980'>Where</span> <span m='417150'>is</span>
  <span m='417400'>my head?</span> <span m='417990'>Can we</span> <span m='418390'>see</span>
  <span m='418860'>it?</span> <span m='418970'>Can I get</span> <span m='419190'>it</span>
  <span m='419370'>in?</span> </p><p></p><p><span m='425022'>It's</span> <span m='425514'>down</span>
  <span m='426006'>here.</span> <span m='428470'>You</span> <span m='428560'>can</span>
  <span m='428650'>see it up</span> <span m='429055'>on</span> <span m='429460'>scene</span>
  <span m='429820'>view.</span> <span m='430640'>I'm</span> <span m='431910'>struggling</span>
  <span m='432450'>to</span> <span m='432550'>get</span> <span m='432730'>bearings.</span>
  <span m='436716'>Oh,</span> <span m='437200'>I</span> <span m='437330'>never</span>
  <span m='437500'>set</span> <span m='437720'>invert</span> <span m='438180'>axis.</span>
  <span m='438930'>That</span> <span m='439390'>would</span> <span m='439850'>explain</span>
  <span m='440070'>that.</span> </p><p></p><p><span m='443557'>Probably going</span>
  <span m='444038'>to--</span> </p><p></p><p><span m='452700'>It</span> <span m='452840'>was</span>
  <span m='453120'>on</span> <span m='453400'>player,</span> <span m='453810'>right?</span>
  <span m='456768'>No,</span> <span m='457261'>it was not.</span> <span m='457754'>It
  was on the</span> <span m='458247'>sphere.</span> </p><p></p><p><span m='477480'>Hope</span>
  <span m='477770'>I can</span> <span m='477890'>re-enter</span> <span m='478370'>myself</span>
  <span m='478720'>in world</span> <span m='479200'>space.</span> <span m='481120'>There
  it is.</span> <span m='482600'>So,</span> <span m='483210'>as</span> <span m='483470'>I</span>
  <span m='483540'>move</span> <span m='483660'>my</span> <span m='483810'>head</span>
  <span m='484330'>left</span> <span m='484760'>and</span> <span m='484890'>right,</span>
  <span m='485912'>up</span> <span m='486260'>and</span> <span m='486540'>down,</span>
  <span m='487510'>and</span> <span m='487920'>my</span> <span m='488070'>hand,</span>
  <span m='488700'>they</span> <span m='488820'>all</span> <span m='488970'>go</span>
  <span m='489130'>properly.</span> <span m='490320'>Each</span> <span m='490620'>object's</span>
  <span m='490950'>position</span> <span m='491330'>can</span> <span m='491400'>be</span>
  <span m='491520'>addressed</span> <span m='491880'>by</span> <span m='492060'>other</span>
  <span m='492270'>objects.</span> <span m='493290'>And</span> <span m='493320'>so</span>
  <span m='493470'>this</span> <span m='493650'>is</span> <span m='493770'>how</span>
  <span m='493970'>you</span> <span m='494150'>can</span> <span m='494750'>gather</span>
  <span m='495120'>your</span> <span m='495240'>data</span> <span m='496750'>to</span>
  <span m='497160'>use</span> <span m='497490'>however</span> <span m='497790'>you</span>
  <span m='497910'>like.</span> </p>
type: course
uid: 10a97d8ace6b2c59f6c96b89fc3dc5e8

---
None