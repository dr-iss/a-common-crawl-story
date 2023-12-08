<!--  Carla JACQUES, Matthieu ROUBI, Marie SEGUY, Zita VON BONIN, Driss ZEGHARI  -->

<html lang="fr-FR">
    <head>
        <meta charset='utf-8'>
        <link rel="stylesheet" href="site.css">
        <title>La_base_de_données_Common_Crawl</title>
    </head>

  <body>
    <a id="Titre">Common Crawl Data Base</a>
    <script async="" src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<h1 id="titre">Qu'est ce que Common Crawl ?</h1>

<h2 id="partie">Introduction</h2>

<p>Le « Common Crawl Data Set » (plus souvent appelé « Common Crawl ») est un jeu de données extrêmement riche, proposé au public par une organisation éponyme américaine à but non-lucratif. Les archives incorporées dans ce jeu remontent jusqu’à 2008, et il est mis à jour à une fréquence mensuelle. Le code permettant le traitement de ses données est open source, et depuis 2012, Amazon Web Services permet également l’accès au Common Crawl à travers son « public data set ».<p>
  
<pict><img src="https://24pm.com/images/2023/04/21/chat-gpt-data-sources.jpg" class="center" border="3"/></pict>

<p>Ce jeu de données est considéré comme l’un des plus conséquents au monde, et est composé à plus ou moins 58% de documents anglophones. Le Common Crawl a notamment été utilisé pour entraîner le grand modèle de langage GPT-3 d’Open AI.</p>
 
<p>Au vu des nombreuses controverses autour de ce jeu de données, notamment liées à son utilisation de sites protégés ou aux inégalités linguistiques dans ses sources, nous chercherons ici à contribuer à l’analyse critique de son contenu.<p>

<h2>Aperçu de Common Crawl</h2>

<h3>L'histoire de Common Crawl</h3>

<p>La base de données "Common Crawl" a été lancée en 2008 par Gil Elbaz, fondateur de la société de technologie de la publicité Applied Semantics, et par d'autres acteurs majeurs du domaine de la technologie et de la recherche. Elle a été créée dans le but de collecter et d'archiver des données provenant de milliards de pages web à travers le monde pour produire un “snapshot” d’internet c’est-à-dire une représentation d’internet à un moment donné.</p>

<p>Au fil des années, cette initiative a pris de l'ampleur, atteignant des dimensions impressionnantes. En 2021, la base de données "Common Crawl" avait indexé et stocké plus de 100 milliards de pages web, totalisant des pétaoctets d'informations. Ce corpus de données massif est continuellement mis à jour à travers des crawls réguliers du web, permettant ainsi d'offrir un accès à jour et étendu à des chercheurs, des développeurs et des organisations dans le monde entier.</p>
 
<p>Cette ressource considérable a joué un rôle essentiel dans le développement de nombreuses technologies, notamment dans le domaine de l'intelligence artificielle, du traitement du langage naturel, de la recherche en sciences sociales, et bien d'autres. La base de données "Common Crawl" est devenue un pilier fondamental pour la recherche et l'innovation, offrant un accès libre et ouvert à des quantités massives de données web pour des applications variées.</p>

<pict ><img src="https://i.insider.com/51685809eab8ea1d71000001?width=750&format=jpeg&auto=webp" class="center" border="3"></pict>

<titreimage id="idphoto" class="center">Gil Elbaz</titreimage>

<p>Pour plus d'informations sur cette base de données, découvrez cette base de données vous même: <a href="https://commoncrawl.org/overview">Site Officiel: Common Crawl</a>.</p>

<h3>Gestionnaire</h3>

<p>L’équipe de l’organisation comporte une vingtaine d’individus, dont 9 sont actifs dans le ‘Advisory Board’. A la tête du Common Crawl se trouve le fondateur, Gil Elbaz, suivi de Rich Skrenta, le directeur général, ainsi que Greg Lindahl, le directeur technique en chef. Parmi les ingénieurs se trouvent Sebastian Nagel, Julien Nioche, ou encore Paul Lazar.<p>
  
<p>La liste complète des gestionnaires du Common Crawl est disponible <a href="https://commoncrawl.org/team">Ici</a>.<p> 
 
<p>Nous sommes honorés d’avoir pu nous entretenir avec le directeur général, Rich Skrenta, au sujet de ce projet.<p>

<h3>Financement</h3>

<p>Au-delà du financement par la fondation personnelle de Gil Elbaz, la base de données "Common Crawl" tire ses financements de différentes sources. Les subventions provenant de fondations philanthropiques comme la Fondation Bill & Melinda Gates, la Fondation Alfred P. Sloan et la Fondation Gordon & Betty Moore jouent un rôle majeur dans le financement à long terme de l'initiative. Ces subventions sont généralement allouées pour des projets spécifiques visant à améliorer les capacités de collecte de données, à développer de nouvelles technologies d'indexation ou à rendre les données plus accessibles aux utilisateurs finaux.<p>

<p>En outre, "Common Crawl" reçoit des soutiens financiers substantiels de la National Science Foundation (NSF) aux États-Unis et de l'Union européenne, à travers des programmes de financement de la recherche ou des initiatives liées à l'innovation technologique. Ces fonds contribuent à la réalisation des crawls réguliers, à l'infrastructure serveur et au développement d'outils pour l'analyse des données. L'organisation établit également des partenariats avec des entreprises technologiques majeures (comme Digital Pebble, DuckDuck Go ou ML Commons), offrant des accès privilégiés à la base de données en échange de soutien financier ou de ressources matérielles pour l'infrastructure informatique.<p>

<h3>Sources</h3>

<p>"Common Crawl" collecte des données en utilisant des robots d'indexation sur diverses sources en ligne accessibles au public, telles que des sites web publics, des forums et des réseaux sociaux. Ces robots parcourent le web en suivant les liens hypertextes pour enregistrer le contenu des pages. Ils sont supposés respecter les directives d'exclusion des robots (fichiers robots.txt) pour limiter la collecte selon les indications des sites visités.</p>
 
<p>L'initiative utilise également des méthodes d'échantillonnage pour tenter de garantir une représentation variée dans son index. Cependant, les données collectées peuvent être influencées par des biais inhérents au web, tels que des régions géographiques sur-représentées ou des secteurs d'activité plus fréquemment indexés. Ces pratiques de collecte soulèvent des préoccupations concernant la qualité, la neutralité et la représentativité des données extraites, pouvant potentiellement impacter la fiabilité des informations fournies pour la recherche et le développement d’intelligences artificielles.</p>

<p>Pour aller plus loin <a href="https://www.youtube.com/watch?v=sdtnQ_qluIo">Cliquez Ici</a><p> 

<h1>Méthodologie de l'enquête</h1>

<p>Dans le cadre de nos recherches afin de trouver une base de données pertinente sur laquelle enquêter, nous avons pris connaissance dans un article du Washington Post intitulé « Inside the secret list of websites that make AI like ChatGPT sound smart ». Cet article qui a été publié en avril 2023 a pour but d’éclaircir les sources d’informations de l’IA, afin de comprendre comment elle est construite, mais également comment elle est influencée lorsqu’elle répond aux utilisateurs. À ces fins, le Washington Post a donc décidé d’analyser l'un de ces ensembles de données afin de révéler les types de sites web qui entrent dans les données d'une IA.<p>

<p>Souhaitant construire notre propre avis sur la question, nous avons décidé de nous concentrer sur la base de données Common Crawl qui, comme indiqué précédemment, a été utilisée pour entraîner le modèle de langage GPT-3 développé par Open AI. Lors de son annonce en 2020 GPT-3 était le plus gros modèle de langage jamais développé avec 175 milliards de paramètres.<p>
 
<p>Nous avons donc formulé plusieurs questions pour guider notre analyse: de quoi est constituée la base Common Crawl ? Qui l’a créée, ? Dans quel but ? Quelles sont ses limites ? Quels sont les enjeux et les défis que devra relever une telle base de données et les intelligences artificielles qui l’utilisent?<p> 
 
<p>Ainsi, afin de répondre à ces questions, nous avons décidé de diriger notre enquête sur deux axes. D’une part, de manière plus théorique, nous avons tenté de comprendre la structure, le fonctionnement et l’utilité de cette base de données en interviewant trois personnes impliquées à leur façon dans l’utilisation de Common Crawl ou de l’IA.<p>
 
<p>Pour en apprendre plus, nous avons eu la chance de pouvoir interviewer, François Yvon, chercheur émérite en matière de Large Langage Model, Margaux Vulliet journaliste reconnue en média et tech, qui a déjà effectué des enquêtes afin de découvrir les bases de données utilisées pour former les IA et enfin Rich Skrenta qui est le directeur général actuel de Common Crawl.<p> 

<p>Dans un deuxième axe et de manière plus pratique, nous avons nous même tenter d’analyser la base de données de Common Crawl en utilisant la méthodologie présentée ci-dessous.<p> 

<h2>Interviews</h2>

<h3>Une interview avec le directeur général actuel de Common Crawl : Rich Skrenta</h3>


<pict><img src="https://assets-global.website-files.com/647b1c7a9990bad2048d3711/6480671ff32d469e9cea78d9_rich-skrenta-300x300-1.jpg" class="center" border="3"></pict>

<p>Lorsque l'on aborde la question complexe du fonctionnement et l’utilisation d’une telle base de données, il est essentiel de donner la parole à ceux qui sont directement impliqués dans la recherche de solutions. Ainsi pour comprendre l'origine, le fonctionnement, ainsi que les objectifs de ce projet, nous avons eu le privilège de mener une interview approfondie avec Rich Skrenta, l’executive director actuel de Common Crawl, le 29 novembre 2023 à travers Googlemeet.</p>

<p> Rich Skrenta est un programmeur informatique américain et entrepreneur de la Silicon Valley qui a créé le moteur de recherche internet Blekko. Avant de travailler pour Common Crawl, Rich Skrenta a travaillé chez Meta notamment comme « web crawler » et a créé « a search engine » qu’il a ensuite revendu avant de se consacrer entièrement à la mission de Common Crawl. Rich Skrenta nous a expliqué leur ambition de créer, avec Common Crawl, une archive du web gratuite et ouverte au public pour le développement de la recherche et de l'innovation.</p>

<p> Lisez <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">le résumé de l'interview</a> pour en apprendre plus sur cette entretien ou découvrez en plus sur son parcours <a href="https://commoncrawl.org/team/rich-skrenta-director">Site Officiel de Common Crawl</a> pour en apprendre plus.</p>

<h3>Une interview avec un chercheur : François Yvon</h3>

<pict ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQi0ruYyiFkOC7668NChNMG3cGa_UFsQ4ILysYwLj14Cd6mdTlz" class="center" border="3"></pict>

<p> Ensuite, pour mieux comprendre la valeur d'une base de données comme common crawl sur un plan pratique d'entrainement d'IA et ses limites techniques, nous avons eu le plaisir d’interviewer François Yvon, un spécialiste du traitement automatique des langues, un domaine à la frontière entre l’IA, l’informatique et la linguistique. François Yvon est actuellement directeur de recherche Centre national de la recherche scientifique (CNRS) et exerce ses fonctions dans l'équipe MLIA (Machine Learning & Deep Learning for Imformation Access) de l'Institut des systèmes intelligents et de robotique (ISIR - CNRS/Sorbonne Université).</p> 
  
<p>Ses activités de recherche couvrent un large spectre de thématiques en traitement automatique des langues, de la morphologie computationnelle à la fouille de textes et les méthodes d'apprentissage structurées. Il se concentre aujourd'hui sur les traitements multilingues, à ces fins il a été impliqué dans le développement de BLOOM également appelé BigScience Large Open-science Open-access Multilingual language Model.</p>
  
<p>Ayant une grande expertise dans le domaine des Large Langage Model, François Yvon nous a permis de mieux comprendre la valeur d’une base de données comme Common Crawl sur un plan pratique concernant l'entraînement d’une IA, mais également d’identifier les limites techniques de ces bases de données comme la surreprésentation des données en anglais.</p>

<p> Lisez la <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">Transcription mot pour mot de l'interview</a> ou découvrez en plus sur son parcours <a href="https://www.isir.upmc.fr/personnel/yvon/">Site ISIR</a> pour en apprendre plus.</p>

<h3>Une interview avec une journalise : Margaux Vulliet</h3>

<pict><img src="https://www.medianes.org/content/images/size/w320/2023/11/photoMV.jpg" class="center" border="3"></pict>

<p> Enfin, pour avoir un regard journalistique critique qui peut éclairer sur les enjeux sociétaux et juridiques d'utilisation de Common Crawl, nous avons également eu le plaisir d’interviewer Margaux Vulliet, une journaliste spécialisée en technologie, qui a écrit l’article « De Chatgpt à bard : voilà à quoi ressemblent les bases de données utilisées pour former les IA » pour BMTV en avril 2023.</p>

<p>L’interview de cette dernière, nous a éclairés sur les enjeux sociétaux et juridiques que peuvent entraîner l’utilisation de Common Crawl.<p>
  
<p>Lisez <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">le résumé de l'interview</a> ou découvrez en plus sur son parcours <a href="https://www.medianes.org/author/margaux/">Site Personnel</a> pour en apprendre plus.</p>

<h1>Méthodologie d'extraction des données</h1>

<p>Pour le deuxième volet de notre analyse, nous avons tenté d’aller au contact même de la base de données et d’en extraire par nous-mêmes certaines informations. Pour cela nous avons concentré notre analyse sur le crawl d’octobre 2023 (CC-MAIN-2023-40).<p>

<p>Pour chaque crawl, Common Crawl met plusieurs types de fichiers à disposition, dont certains (notamment les fichiers WARC, qui regroupent toute l’information) pèsent près de 98 To. Très vite, le poids de ces fichiers est devenu une véritable difficulté. N’étant pas dotés d’ordinateurs à mémoire vive et puissance de calcul suffisantes, le traitement des fichiers prenait parfois plusieurs minutes puis finissait par échouer.<p> 

<p>Pour contourner ce problème, nous avons décidé d’utiliser Athena, une plateforme d’analyse de données intégrée aux Amazon Web Services (AWS). Athena ne requiert ni création d’un serveur pour analyser les données, ni de les télécharger au préalable. En effet, les crawls sont stockés sur les serveurs d’Amazon, il suffit donc simplement de diriger Athena vers la source des données pour être en mesure de les analyser. Ce sont des avantages considérables pour des étudiants en droit ayant des connaissances limitées en informatique et programmation. <p> 

<p>Athena utilise un langage de type SQL (Structured Query Language) pour analyser les données et en extraire les informations intéressantes. Premièrement, nous avons tenté une analyse langagière en dénombrant les sites web contenus dans le crawl par langues. L’objectif de cette analyse est de comparer la représentation des différentes langues dans le crawl d’octobre 2023 avec les études sur la proportion des langues dans l’ensemble du web.<p> 

<p>Nous avons ensuite décidé de concentrer notre analyse sur les sites web en français pour comprendre sur quoi se fonderait un LLM francophone utilisant un crawl pour ses données d'entraînement. Pour cela, nous avons extrait la liste des domaines les plus représentés dans les sites francophones, en nous limitant à ceux qui apparaissent au moins 100 fois. À titre d’illustration, nous avons pu déterminer que le domaine cnrs.fr apparaît 361 559 fois.<p> 

<p>Enfin, nous avons également extrait 500 urls francophones aléatoires afin de les examiner un par un et de les catégoriser en fonction du type de site web (blog, presse, site de vente…) et du sujet traité (commercial, scientifique, information, culture…). Définir de telles catégories et le niveau de détail s’est révélé ardu étant donné la diversité des contenus. Nous nous sommes donc arrêtés sur celles présentées à la page suivante, qui nous permettent d’obtenir une première vue d’ensemble du type de sites francophones inclus dans le crawl d’octobre 2023.<p> 

<p>Nous avons d'abord catégorisé les sites url par sujets:</p>

<table border="1">
  <thead>
    <tr>
      <th>Sujet</th>
      <th>Définition/exemple</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Développement personnel</td>
      <td>Développement personnel</td>
    </tr>
    <tr>
      <td>Commercial</td>
      <td>L'oject premier est de vendre un bien ou un service</td>
    </tr>
    <tr>
      <td>Culture</td>
      <td>Tout ce qui est a trait à des évènements artistiques, historiques, évènementiel,etc.</td>
    </tr>
    <tr>
      <td>Information</td>
      <td>Articles d'information ou d'association</td>
    </tr>
    <tr>
      <td>Professionnel</td>
      <td>Description d'une entreprise (ex: site d'un cabinet d'avocats)</td>
    </tr>
    <tr>
      <td>Académique</td>
      <td>Journaux académique, recherche (ex: Cairn)</td>
    </tr>
    <tr>
      <td>Administration</td>
      <td>En référence à des sites pubilcs ou des démarches administratives</td>
    </tr>
    <tr>
      <td>Légal</td>
      <td>En référence à des sites traitant de droit</td>
    </tr>
    <tr>
      <td>Illicite</td>
      <td>pornographie, sites complotistes, extrêmes</td>
    </tr>
    <tr>
      <td>Politique/religieux</td>
      <td>Partis politiques ou promotion de religions</td>
    </tr>
    <tr>
      <td>Sport</td>
      <td>Associations sportives, sites de sport</td>
    </tr>
    <tr>
      <td>Economie/Finance</td>
      <td>Banque de France, sites boursiers</td>
    </tr>
    <tr>
      <td>Science/Statistique</td>
      <td>Insee, publications scientifiques</td>
    </tr>
    <tr>
      <td>Autre</td>
      <td>tout le reste</td>
    </tr>
  </tbody>
</table>

<p>Nous avons ensuite catégorisé les sites url par types:</p>

<table border="1">
  <tr>
    <th>Listes des types retenus</th>
  </tr>
  <tr>
    <td>Site de vente</td>
  </tr>
  <tr>
    <td>Encyclopédie</td>
  </tr>
  <tr>
    <td>Évenementiel</td>
  </tr>
  <tr>
    <td>Presse</td>
  </tr>
  <tr>
    <td>Journal Académique</td>
  </tr>
  <tr>
    <td>Site d'identification</td>
  </tr>
  <tr>
    <td>Site personnel</td>
  </tr>
  <tr>
    <td>Associatif</td>
  </tr>
  <tr>
    <td>Site de vente</td>
  </tr>
  <tr>
    <td>Vidéos/Photos</td>
  </tr>
  <tr>
    <td>Forum</td>
  </tr>
  <tr>
    <td>Recherche</td>
  </tr>
  <tr>
    <td>Annuaire</td>
  </tr>
  <tr>
    <td>Autre</td>
  </tr>
</table>

<h2 id="Le processus">Le processus</h2>

<p>Exemple d'une requête SQL pour trouver les domaines francophones représentés plus de 100 fois: <p>

<p>Nous avons d'abord créé le tableau contenant les données que nous avons synchronisé avec le serveur de Common Crawl<p>
  
<h3>Nous avons ensuite exécuté la commande suivante afin de dénombrer les domaines francophones représentées plus de 100 fois</h3>

<table border="2">
        <tr>
            <td>SELECT COUNT(*) AS count,<br />
        url_host_registered_domain<br />
        FROM "ccindex"."ccindex"<br />
        WHERE crawl = 'CC-MAIN-2023-40'<br />
        AND subset = 'warc'<br />
        AND url_host_tld = 'fr'<br />
        GROUP BY  url_host_registered_domain<br />
        HAVING (COUNT(*) >= 100)<br />
        ORDER BY  count DESC</td></tr> </table>
        

<h3>Résultat obtenu</h3>

<p>Les 5 premières lignes</p>

<table border="1">
  <tr>
    <th>Numéro</th>
    <th>Count</th>
    <th>url_host_registered_domain</th>
  </tr>
  <tr>
    <td>1</td>
    <td>1427932</td>
    <td>free.fr</td>
  </tr>
  <tr>
    <td>2</td>
    <td>418451</td>
    <td>lefirgaro.fr</td>
  </tr>
  <tr>
    <td>3</td>
    <td>361559</td>
    <td>cnrs.fr</td>
  </tr>
  <tr>
    <td>4</td>
    <td>199026</td>
    <td>online.fr</td>
  </tr>
  <tr>
    <td>5</td>
    <td>165030</td>
    <td>orange.fr</td>
  </tr>
</table>

<p>Regardez <a href="https://docs.google.com/spreadsheets/d/1-1nmO2qQYdBU6d9_HH1OjAhMYWz4gSsP/edit#gid=1641676625">l'analyse des 500 url</a> pour avoir plus de détails.</p>

<h1>L'analyse de nos résultats</h1>

<h2>Les sujets des sites</h2>

<p><img src="https://pbs.twimg.com/media/GAsl_CCXMAEdDec?format=jpg&name=medium" class="center" border="3"/></p>

<p>En analysant les 500 sites web extraits du crawl d’octobre, nous avons pu noter qu’un quart des sites traitent d’un sujet commercial, 17% traitent de sujets culturels face à seulement 5% en matière académique et 3% en matière politique/ religieuse. La répartition des sujets étant, dès lors, très hétérogène, des biais peuvent apparaître chez un LLM qui utiliserait directement ces données.</p>

<p>De plus, sur les 475 sites fonctionnels analysés, seuls 2% se sont avérés présenter du contenu sensible (dont 2 URLs qui renvoyaient vers de la pornographie). La proportion reste donc assez faible, bien loin pour nous de constituer une source d’inquiétude quant aux biais des données. Cela dit, peut-être aurions nous trouvé un résultat différent en analysant un échantillon plus grand et plus représentatif du crawl (en incluant par exemple toutes les langues).</p>

<h2>Les types de sites</h2>

<p><img src="https://pbs.twimg.com/media/GAsl5cZWcAAsnhO?format=jpg&name=medium" class="center" border="3"/></p>

<p>Concernant le type de documents proposés dans chaque site, la plupart de ces plateformes sont, sans surprise au vu des résultats précédents, des sites de ventes (28%). Nous avons également trouvé de nombreux blogs (17%) qui, par leur nature, risquent de comporter des fautes d’orthographe susceptibles de se répercuter sur un LLM. Dans une moindre mesure,on observe aussi des articles presse (8%) ou encore de recherche (6%).</p>

<h2>Les sites francophones</h2>

<p><img src="https://pbs.twimg.com/media/GAsluBhXwAETUZv?format=jpg&name=medium" class="center" border="3"/></p>

<p>Assez surprenamment, c’est le domaine de l’opérateur téléphonique Free qui est le plus représenté dans les sites francophones. Avec près de 1,4 millions de pages (soit 2,66% du total des sites francophones), il dépasse de loin le domaine du journal Le Figaro, second sur la liste, qui compte 418 000 pages pour 0,78% du total. D’autres sources non négligeables sont le site du CNRS, de la Banque de France, ou encore de l’École Normale Supérieure de Lyon. Il existe donc une certaine diversité des sources francophones, bien que Free semble accaparer une part importante qui risque de biaiser certains LLMs. </p>

<h2>Les langues</h2>

<p><img src="https://pbs.twimg.com/media/GAslznHWwAAemSk?format=jpg&name=medium" class="center" border="3"/></p>

<p>Détachons-nous des sites francophones et examinons la répartition des langues au sein du crawl d’octobre 2023. Logiquement, l’anglais domine de manière flagrante avec 58% des pages rédigées dans cette langue (ce qui corrobore les dires de Rich Skrenta). Le français n’arrive qu’en 7eme place avec 90 millions de pages et 3,7% du total. Ces résultats sont finalement assez cohérents avec les études sur la répartition des langues sur le web, qui placent l’anglais en premier avec 63,7% et le français en 4eme avec 2,5%. Bien que rééquilibrant légèrement la répartition, le crawl reste représentatif de l’état du web, en harmonie avec son objectif affiché  et réaffirmé par Rich Skrenta: construire une archive du Web.</p>

<h1>Les difficultés  de Common Crawl</h1>

<h2>Les limites</h2>

<p>Aussi louable soit-il, cet objectif reste difficile à atteindre. Internet étant un espace en constante expansion, Common Crawl ne peut évidemment pas donner une représentation complète du Web.</p>

<p>Son exhaustivité présente certaines limites, car Common Crawl se concentre seulement sur les pages web sans archiver des contenus photographiques et vidéographiques qui font partie de l’internet, et ce d’autant plus que les réseaux sociaux et les “memes” prolifèrent. Ainsi, une partie du web qui contient des éléments socio-culturels, artistiques, politiques, et historiques n'est pas représentée dans l’archive mensuelle. Néanmoins, crawler des photos et des vidéos nécessiterait une capacité de stockage de données considérable, il y a donc aussi des limites physiques et financières à la capacité d'exhaustivité de Common Crawl.</p>

<p>Par ailleurs, rappelons que Common Crawl est régulièrement utilisée comme source des données d’entraînement des LLMs. Avec 58% des pages internet crawlées en anglais, ces données sont extrêmement biaisées vers la langue de Shakespeare, ce qui laisse à penser qu’un LLM sera probablement moins performant dans les autres langues. Cette limite fait l’objet d’initiatives gouvernementales puisque l’Union Européenne et l’Indonésie se sont rapprochées de Common Crawl pour qu’il travaille à plus crawler leurs langues qu'elles soient nationales ou régionales.</p>

<p>Attardons-nous davantage sur le thème de la qualité du contenu crawlé par Common Crawl. Comme nous avons nous-mêmes pu l’observer, certaines pages sont redondantes ou mènent à des contenus illicites. Pour l’instant, les pages crawlées par Common Crawl sont déterminées par un modèle mathématique qui donne un score à ces pages en fonction de leur trafic. Par conséquent, certaines pages peuvent être crawlées deux fois à cause d’un changement de date. Ainsi, Common Crawl travaille à développer une indexation des pages web basé sur “harmonic centrality”, c'est-à-dire le nombre de liens qui mènent à une page. Par ailleurs, en crawlant des pages webs, Common Crawl prend connaissance de milliards d'autres liens qui mènent à d'autres pages internet: c'est ce qu'on appelle la "URL Frontier". Dès lors, Common Crawl va tenter de sélectionner une partie de ces URLs pour les crawler le mois prochain et ainsi permettre une représentation du web de meilleure qualité.</p>

<p>Enfin - et c’est là la dernière limite quant à l’utilisation des crawls comme données d'entraînement - Common Crawl ne procède pas à un “semantic-based filtering”, c'est-à- dire qu’il n y a pas de nettoyage des données pour éliminer les contenus haineux, illicites, ou redondants. Ainsi, le nettoyage de la base de données est laissé aux développeurs qui vont l’utiliser. Néanmoins, il est important de noter que la modération/filtrage de contenus et la détermination du caractère haineux ou illicite est une problématique dure à traiter, car cette caractérisation peut varier d’un pays à un autre et cela revient à ériger des entreprises privées en juge de la liberté d’expression.</p>

<h2>Les enjeux</h2>

<p>Avec l'avènement de LLMs et d’intelligence artificielle comme ChatGPT qui utilise la base de données Common Crawl à 60% pour sourcer ses informations, la connaissance des limites des bases données d’indexation de pages web comme Common Crawl est cruciale pour mieux aborder ces outils. En effet, la base de données Common Crawl est utilisée pour développer des outils comme ChatGPT. Dès lors, la qualité et l’exhaustivité des contenus tant linguistiquement qu'en variété de contenus sont clés pour la création de LLMs qui soient basés sur une représentation proportionnée et qualitative d’Internet et donc des sociétés humaines.<p>

<p>La prévalence de l’anglais dans des crawlers comme Common Crawler ralenti le développement de LLMs dans d’autres langues comme le français. Ainsi, des bases de données comme common crawl revêtent un aspect stratégique dans la course au développement de LLMs et d’intelligences artificielles comme le démontre l’existence d’une initiative de l’Union européenne de créer un crawler/index de pages web pour s’affranchir d’entreprises américaines et avoir une autonomie stratégique dans le domaine. De plus, cette omniprésence de l’anglais est l’une des raisons d’être du projet Bloom (auquel la France a apporté son concours) qui vise à créer un modèle multilingue à travers un corpus plus divers incluant des textes non répertoriés sur le web, parfois de meilleure qualité grammaticale et syntaxique (à ce sujet, voir l’interview de François Yvon).<p>

<p>En outre, la qualité du contenu demeure un enjeu tout aussi important. Un <a href="https://www.lemonde.fr/pixels/article/2016/03/24/a-peine-lancee-une-intelligence-artificielle-de-microsoft-derape-sur-twitter_4889661_4408996.html">bot développé par Microsoft</a> qui devait apprendre à faire la conversatoin en interagissant avec les utilisateurs de Twitter est devenu misogyne, raciste, antisémite, et xénophobe après une journée seulement d’interaction avec les utilisateurs de Twitter. Ainsi, le fait que Common Crawl recense des sites avec du contenu illégal ou sensible, de nombreux sites commerciaux plutôt que des pages informatives, ou encore des blogs avec de nombreuses fautes d'orthographe, peut mener au développement de LLMs et des I.A qui reproduisent et exacerbent les limites de l’internet d’aujourd’hui. Dans notre analyse, 21% des sites sont des blogs ou des forums qui, par leur nature, sont susceptibles de comporter des fautes. Dès lors, le nettoyage et le filtrage des bases de données sont essentiels pour développer des LLMs et I.A de qualités.<p> 

<p>Néanmoins, le filtrage et nettoyage des données n’est, d’une part, jamais neutre, et d’autre part, difficile à mettre en place. Au cours de notre entretien avec François Yvon, il a pu mentionner certains outils automatisés pour nettoyer les données. Semblables à des “truelles”, ces outils définissent certaines règles pour éliminer les sites indésirables. Toutefois, au vu de la grande diversité des sites web, certains passeront toujours entre les mailles du filet et se retrouveront dans le jeu d’entraînement des IAs. Un enjeu crucial pour l’avenir sera de développer des outils plus précis pour éliminer le contenu qui porterait préjudice à un entraînement neutre des LLMs (si tant est qu’un tel entraînement existe).</p>

<p>Enfin, se pose également la question de la propriété intellectuelle. Des voix s’élèvent notamment quant à l’utilisation de données sous licences par les LLMs à travers Common Crawl. Si certaines règles et protection permettent de restreindre l’accès de certaines pages aux robots (en ce sens, plusieurs entreprises ont restreint l’accès au crawler de ChatGPT), les crawlers continuent d’archiver des sites sous licences, qui sont utilisés plus tard par des LLMs. L’avenir des crawler et des LLMs se jouera donc aussi sur un plan juridique, puisque des voix s’élèvent pour protéger les contenus, ce qui réduirait considérablement la quantité de données disponibles à l'entraînement.</p>

<h1>Conclusion</h1>

<p>Common Crawl est une base de données qui a été lancée par Gil Elbaz dans le but de créer une archive du web gratuite et entièrement publique en rassemblant dans des dossiers tous les liens url d'internet. En vue de l'objectif de l'organisation, la base de données en elle-même présente surtout des problèmes de représentation linguistiques mais l'organisation ne se souhaite pas refuser ou interdire la prise en compte de certains sites puisque Common Crawl voudrait à une archive complète d'internet. En revanche, il est admis qu'il est important qu'un filtre soit ensuite utilisé pour gérer leur utilisation avec les IA.</p>
<h1>Pour aller plus loin</h1>

<h2>Les premières interviews sur ce projet</h2>

<p>Écoutez vous même Gil Elbaz parler du projet lors du lancement de Common Crawl il y a plus de dix ans: <a href="https://www.youtube.com/watch?v=sdtnQ_qluIo">Écouter l'interview</a><p> 

<p>Cette vidéo nous a été conseillé par Rich Skrenta</p>

<h2>Updates via les réseaux sociaux</h2>

<p>Un effort constant de partager les nouveautés et les actualités de l'organisation avec le public notamment à travers twitter:</p>

<blockquote class="twitter-tweet">
  <a href="[https://twitter.com/commoncrawl/status/1671408229589581825?s=46&t=aj6GX9IxEIsWGRYl-HJUjg]"></a>
</blockquote>
