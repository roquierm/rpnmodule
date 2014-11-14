<h1>rpnmodule</h1>
rpnmodule is a project aiming to provide a base library for running educational content.
It'll provide common features for 8 base module types (maybe more in the future):
<ul>
    <li>blackbox - a mathematical module to calculate values back and forth 4 -(x4)-> 16 (sample: http://www.rpn.ch/hosting/iclasse/html5/integrationHTML5/nombres/9_sequNbBN_8.html)</li>
    <li>cardmaze - a maze of card in which you can navigate using questions on card and response on adjacent card (sample: http://www.rpn.ch/hosting/iclasse/MMF/6_html/L1_26_6_Indicatif_Laby_Sequ_1.html)</li>
    <li>clock - a clock you can manipulate to display a given hour (sample: http://www.rpn.ch/hosting/iclasse/html5/integrationHTML5/horloge/9_sequHorloge_1.html)</li>
    <li>dragdropsorting - items you can drag and drop in list of containers to sort (sample: http://www.rpn.ch/hosting/iclasse/MMF/8_html/L1_26_8_FormVerb_TriSac_Sequ_1.html)</li>
    <li>gapfull - (sample: http://www.rpn.ch/hosting/iclasse/AideEval/10/html/AE_AccordGramm_1_5.html)</li>
    <li>gapsimple - (sample: http://www.rpn.ch/hosting/iclasse/AideEval/10/html/AE_ParticipePasse_1_2.html)</li>
    <li>marker - (sample: http://www.rpn.ch/hosting/iclasse/html5/Fra_9_html/L1_36_9_JO_Indicatif_Present_3.html)</li>
    <li>mqc -</li>
</ul>
<h2>Main options</h2>
<ul>
    <li>sequrl - the url where to find json module sequence datas. Default: seq.json</li>
    <li>solurl - the url where to find json module sequence solutions. Default: sol.json</li>
    <li>mediaurl - the url where to find medias (images, sound or video) defined in the sequence medias. Default: medias/</li>
    <li>returnurl - the url launched at end of sequence. Default: ..</li>
    <li>warnonexit - do the module sequence has to display a waring message (html onbeforeunload classic warning)? default: false</li>
    <li>onsequenceend - default: the function(){}</li>
    <li>onmoduleend - default: function(){}</li>
    <li>language - which language to use for labels? Default:fr available: fr,en</li>
</ul>

<h2>Module specific options</h2>