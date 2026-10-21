+91	98405	54007			·			patric@clarioserv.com			·			16/24,	91st	Street,	Ashok	Nagar,	Chennai	600083
WEBSITE	REVIEW
Procon	Infra	LLP	Website	
Review
UI	and	content	corrections	for	procon-website-dev.vercel.app
PREPARED	BY Patric,	ClarioServ
DATE 14	October	2026
VERSION 1.0
Procon	Infra	LLP	Website	Review
ClarioServ		·		Service	in	focus Page	2 of	6
Summary
This	review	covers	the	Procon	Infra	LLP	development	site	at	procon-website-dev.vercel.app.	The	homepage	
was	checked	at	desktop	and	mobile	widths,	along	with	links,	images	and	metadata.	Every	page	was	read:	
Home,	About,	Capabilities,	the	four	capability	pages,	Process,	Why	Us,	Projects	and	Contact.
All	internal	links	work	and	there	are	no	console	errors.	The	issues	are	about	content,	consistency	and	finish,
not	broken	functionality.
Priority:		Five	items	must	be	fixed	before	the	site	goes	live.	They	are	listed	first,	in	Section	2.
Section Focus Priority
1. Must	fix	before	launch Placeholders,	unverified	figures,	contact	form,	
director	details,	stock	photos High
2. Content	corrections Naming,	consistency,	tone,	spelling,	labels Medium
3. UI	and	layout Logo,	favicon,	mobile	hero,	readability,	overlaps Medium
4. Technical	and	SEO Social	previews,	headings,	URLs,	images,	schema Medium
5. Capability	pages PEB,	Composite	and	MEP	page	content Medium
Must	fix	before	launch
• Placeholder	text	is	live. The	About	page	shows	“[Bio	to	be	provided]”	under	both	leadership	profiles.
• The	verification	disclaimer	is	public. The	homepage	and	Projects	page	both	carry	the	asterisks	and	the	
note	“*All	project	values	and	technical	figures	are	subject	to	internal	verification…”.	Confirm	the	figures	
(Rs	10	Cr,	16	EOT	+	24	semi-gantry	cranes)	and	remove	the	asterisks	and	the	note.
• The	contact	form	doesn’t	seem	to	be	connected. Its	submit	target	is	the	homepage.	The	“Thank	you…	
within	one	business	day”	message	is	already	in	the	page	markup.	Connect	it	to	a	real	handler	(Formspree,	
an	email	service	or	a	backend)	and	test	it.
• The	director’s	name	doesn’t	match	across	pages. About	says	“Raghunath,	Managing	Partner”.	Contact	
says	“A.	Ragunath,	Director”	(email	Ragunath@…).	Settle	the	spelling	and	the	title.	Also	check	whether	a	
personal	mobile	number	(9942902085)	should	be	public.	If	it	stays,	format	it	as	+91	99429	02085.
• Stock	photos	are	presented	as	Procon’s	work. Every	image	is	from	Pexels,	including	the	three	project	
cards.	One	alt	text	reads	“Procon	engineers	reviewing	drawings…”,	which	isn’t	true.	Use	real	project	and	
site	photos,	especially	for	SAFETAB,	Sai	Nadha	and	Schwing	Stetter.
Procon	Infra	LLP	Website	Review
ClarioServ		·		Service	in	focus Page	3 of	6
Content	corrections
• “Established	1989”	is	ambiguous. The	footer	says	“Part	of	Royal	Fab	Group	|	Established	1989”,	which	
reads	as	if	Procon	was	founded	in	1989.	Use	“Part	of	Royal	Fab	Group	(est.	1989)”	or	give	Procon’s	own	
founding	year.
• The	process	steps	don’t	match. The	homepage	shows	5	steps	and	the	Process	page	has	9.	The	hero	
animation	uses	another	5	(Civil	works,	Steel	erection,	Envelope	and	floors,	MEP	and	utilities,	
Commissioning).	Add	“5	of	9	stages”	or	a	note	pointing	to	the	full	methodology.	The	label	also	varies:	
“Fabrication	&	Civil	Works”	on	the	homepage,	“Fabrication	/	Civil	Works”	on	Process.
• Names	don’t	match	between	nav	and	pages:
– The	nav	says	“Capabilities”,	but	that	page’s	browser	title	is	“Services	|	Procon	Infra	LLP”,	and	the	
breadcrumbs	say	“Home/Services/…”.
– “MEP	&	Utilities”	appears	in	the	nav,	“MEP	&	Utility	Coordination”	on	Capabilities	and	in	the	form	
dropdown,	and	the	file	is	named	“mep-utility”.
– Both	“Metalscope”	and	“Metalscope	India”	are	used.
– The	nav	says	“Why	Us”,	the	footer	says	“Why	Procon”.
• “One	accountable	team”	is	overused. It	appears	in	the	H1,	two	H2s,	a	bullet,	and	the	Why	Procon	
heading.	Keep	it	in	the	H1	and	reword	the	rest.
• The	Process	page	tone	doesn’t	match. Lines	like	“Zero	compromise,	every	step”	and	“Commitment	
delivered,	every	time”	are	generic	slogans,	while	the	rest	of	the	site	is	measured.	Make	them	specific	or	
remove	them.
• Status	label: “Under	Progress”	isn’t	idiomatic.	Use	“In	Progress”	or	“Under	Execution”.	The	latter	
matches	“under	execution”	in	the	section	intro.
• British	and	American	spelling	are	mixed: “mobilisation”	on	the	homepage,	“mobilization”	on	Process.	
Pick	Indian/British	English	and	apply	it	everywhere.
• Button	capitalisation	varies: “Discuss	Your	Project”	and	“Discuss	your	project”,	“View	our	projects”	and	
“View	Our	Projects”,	and	“Learn	About	Us”.	Use	one	style.
• “Sai	Nadha	Plastics”: check	the	client’s	official	spelling.
• Alt	text: “MEP	HVAC	coordination	render”	describes	a	photo,	not	a	render.
UI	and	layout
• The	header	logo	is	too	small. It	shows	at	about	65px	wide,	so	“WOW”	and	“WAY	OF	WORKING”	can’t	be	
read,	on	desktop	or	mobile.	Use	a	horizontal	version	of	the	logo,	or	drop	the	tagline	in	the	header.
• The	favicon	is	the	full	logo	as	a	JPG. Make	a	square	icon	(the	building	mark	only)	as	PNG	or	SVG,	plus	
an	apple-touch-icon.
Procon	Infra	LLP	Website	Review
ClarioServ		·		Service	in	focus Page	4 of	6
• The	mobile	hero	has	problems:
– The	3D	plant	model	sits	below	the	fold,	leaving	a	large	empty	band.
– The	stage	progress	bar	shows	only	numbers	(01–05)	without	labels.
– It	loads	with	stage	05	highlighted	instead	of	01.
• The	scroll-reveal	paragraph	is	hard	to	read. In	“We	engineer	it,	source	it…”,	most	of	the	text	is	very	
light	grey	until	you	scroll.	Readers	who	skim	or	don’t	scroll	far	see	it	as	faded.	Raise	the	starting	contrast.
• The	back-to-top	button	overlaps	content. It	covers	“Part	of	Royal	Fab	Group”	in	the	footer’s	bottomright	corner	on	desktop.	On	mobile	it	sits	over	body	text.	Add	bottom	padding	to	the	footer,	or	move	or	
shrink	the	button.
• Phone	and	email	aren’t	clickable. Make	them	tel:	and	mailto:	links.	This	matters	on	mobile.
• Contact	page: consider	adding	a	Google	Map	embed	and	a	WhatsApp	link.	Both	are	common	for	Indian	
B2B	sites.
Technical	and	SEO
• There	are	no	Open	Graph	or	Twitter	tags,	so	links	shared	on	WhatsApp	or	LinkedIn	will	show	no	image	
or	title	preview.
• Heading	levels	skip	from	H2	to	H4	(the	process	steps	and	the	footer	column	titles).	Use	H3,	or	style	the	
footer	titles	as	non-headings.
• Pages	use	.html	URLs	(/about.html).	Turn	on	Vercel’s	cleanUrls	for	/about.
• Images	load	from	images.pexels.com.	Once	real	photos	replace	them,	host	them	locally	in	WebP	with	
width	and	height	set.
• Add	LocalBusiness/Organization	schema	with	the	address	and	phone	number,	plus	a	sitemap.xml	and	
robots.txt.
Capability	pages:	PEB,	Composite,	MEP
The	biggest	problem	across	all	three	pages	is	headings	with	no	text	under	them.	They	look	unfinished.
Issues	on	all	three	pages
• Feature	headings	have	no	descriptions. The	PEB	page	has	6	(Engineered	Excellence,	Precision	
Fabrication	and	others).	Composite	has	16	(8	capabilities	and	8	advantages).	MEP	has	6	(Code	Compliant,	
Expert	Team	and	others).	Add	one	line	under	each	heading,	or	turn	them	into	a	compact	icon	row.
• The	hero	images	have	empty	alt	text, and	each	hero	photo	is	reused	further	down	the	same	page.
• Alt	text	promises	things	the	photos	don’t	show. On	PEB	and	MEP	the	alt	text	says	“BIM	model”	or	
“BIM	renders”,	but	the	images	are	generic	Pexels	photos.	Use	real	BIM	screenshots	or	correct	the	alt	text.
Procon	Infra	LLP	Website	Review
ClarioServ		·		Service	in	focus Page	5 of	6
• Abbreviations	aren’t	explained: PEB,	GA,	IAQ,	VRF/VRV,	STP,	ETP.	Spell	each	one	out	the	first	time	it	
appears	on	a	page.
• The	breadcrumb	says	“Services”	while	the	nav	says	“Capabilities”. This	is	the	same	naming	issue	as	
on	the	main	Capabilities	page.
PEB	&	Structural	Steel
• Metalscope’s	relationship	to	Procon	is	unclear. The	meta	description	calls	it	Procon’s	“PEB	division”.	
The	body	describes	it	as	part	of	the	wider	group.	Pick	one	accurate	description	and	use	the	same	name	
every	time	(“Metalscope	India	Pvt	Ltd”	first,	then	“Metalscope”).
• “High-capacity”	is	used	three	times	without	any	figures. Add	real	numbers:	tonnage	per	month,	
facility	area,	crane	capacity,	maximum	span.
• Some	claims	need	wording	or	backing, for	example	“snag-free	handover”	and	“state-of-the-art”.	Soften	
them	or	support	them	with	a	fact.
Composite	Construction
• Check	the	shear	stud	specification. It	pairs	IS	2062	(structural	plate)	with	ASTM	A108	(stud	material).	
Confirm	with	the	engineering	team	that	this	is	intended	and	say	which	standard	applies	to	which	part.
• The	box	girder	section	seems	out	of	place. It	reads	like	a	separate	product	dropped	into	the	composite	
page.	Either	explain	how	box	girders	relate	to	composite	construction	or	give	them	their	own	section	
heading.
• Some	content	is	repeated. “Stronger.	Faster.	Smarter.	Sustainable.”	appears	twice,	and	“Smaller	
columns”	and	“Smaller	Column	Sizes”	say	the	same	thing.
• Claims	about	seismic	performance,	foundation	loads	and	sustainability	have	no	evidence. Add	a	
figure	or	a	project	example,	or	soften	the	wording.
• Spelling	is	mixed: “Optimise”	and	“Design	Optimization”	appear	on	the	same	page.
MEP	&	Utilities
• The	page	title	doesn’t	match	the	nav. The	title	says	“MEP	&	Utility	Coordination”,	while	the	nav	and	
eyebrow	say	“MEP	&	Utilities”.
• Testing	&	Commissioning	is	unfinished. It	has	no	bullets	and	no	image,	unlike	the	other	five	service	
blocks.
• “Clash-free	design”	reads	as	a	guarantee. Reword	it	as	“clash	detection	and	resolution	before	site	
work”.
• Cable	routing	appears	twice, under	Electrical	and	again	(as	cable	management)	under	Utilities.	Merge	
the	two	or	make	them	clearly	different.
• The	final	call	to	action	is	inconsistent. Its	second	button	is	“Our	Process”,	where	other	pages	use	“View	
Our	Projects”.	Pick	one	pattern	for	all	capability	pages.
Procon	Infra	LLP	Website	Review
ClarioServ		·		Service	in	focus Page	6 of	6
• The	approach	heading	reads	as	a	list	of	verbs: “Coordinate,	design,	optimize,	execute,	deliver”.	
Replace	it	with	a	real	heading,	for	example	“How	we	deliver	MEP”.