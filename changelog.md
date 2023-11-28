====================																																																																																	
	11-28-2023																																																																																
====================																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	core:	Fix	continuous	crash	issue	in	persistent	apps	[Hari	Raj	Vijayakumar]																																																																						
-	SystemUI:	Use	color	accent	for	charging	animation	[Genkzsz11]																																																																									
																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	[TMP]	remove	some	feature	[ralf979]																																																																												
-	Blackiron:	Pulse:	Vertical	mirror	[2/2]	[TikkiTikki]																																																																											
-	Blackiron:	Pulse:	Custom	gravity	and	Center	mirrored	[2/2]	[TikkiTikki]																																																																								
-	Blackiron:	Solid	render:	Round	lines	[2/2]	[TikkiTikki]																																																																										
-	Blackiron:	Add	customization	for	Lockscreen	Media	Art	[2/2]	[ralf979]																																																																								
																																																																																	
																																																																																	
*	vendor/blackiron																																																																																
-	switch	to	beta	build	[ralf979]																																																																												
-	soong:	Add	qti	vibrator	effect	stream	config	[Arian]																																																																									
																																																																																	
																																																																																	
====================																																																																																	
	11-27-2023																																																																																
====================																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	SystemUI:	add	back	BluetoothController::getDevices	[Tobias	Merkel]																																																																											
-	Optionally	have	System-scheduled	backups	act	as	migrations	[Tommy	Webb]																																																																								
-	NPMS:	Remove	support	for	SDK	sandbox	UIDs	[Tommy	Webb]																																																																								
-	Confirm	device	credentials	with	the	proper	user	[Oliver	Scott]																																																																								
-	Fix	unlock	notifications	for	multiple	profiles	[t-m-w]																																																																										
-	Show	hidden	apps	on	secondary	users'	app	lists	[Oliver	Scott]																																																																							
-	Hide	hidden	apps	from	all	apps	except	system	[Oliver	Scott]																																																																							
-	Start	profiles	before	finishing	user	boot	when	finishing	user	switch	[Oliver	Scott]																																																																					
-	AudioService:	Remove	Analog	Dock	from	fixed-volume	devices	[Vachounet]																																																																									
-	Automatically	start	all	work	profiles	[Tommy	Webb]																																																																										
-	Allow	creating	multiple	work	profiles	via	sysprop	[Tommy	Webb]																																																																								
-	Adapt	Open	With	chooser	for	multiple	profiles	[t-m-w]																																																																									
-	Do	not	show	logout	button	on	lockscreen	[Tommy	Webb]																																																																								
-	Support	logging	out	secondary	users	[Tommy	Webb]																																																																										
-	Support	work	profiles	on	full	secondary	users	[Oliver	Scott]																																																																								
-	Enable	backup	service	by	default	for	all	users	[Oliver	Scott]																																																																							
-	Pause	apps	feature	[Oliver	Scott]																																																																												
-	BatteryStatsViewer:	Fix	theme	[Michael	Bestas]																																																																												
-	BatteryStatsViewer:	Fix	initial	activity	after	launch	[Michael	Bestas]																																																																									
-	BatteryStatsViewer:	Add	summary	for	IA	preference	[Michael	Bestas]																																																																									
-	BatteryStatsViewer:	Remove	some	hardcoded	strings	[Michael	Bestas]																																																																										
-	Create	IA	entry	for	BatteryStatsViewer	[Oliver	Scott]																																																																										
-	SettingsLib:	Change	collapse	mode	to	scale	[Blaster4385]																																																																										
-	SettingsLib:	Change	collapsed	header	color	to	match	background	color	[Rizky	Benggolo]																																																																						
-	Support	per-UID	VPN	lockdown	policy	[Tommy	Webb]																																																																										
-	Stop	domain	verification	delegated	from	UIDs	blocked	by	network	policy	[Oliver	Scott]																																																																					
-	Firewall:	Transport-based	toggle	support	(1/3)	[Oliver	Scott]																																																																										
-	Firewall:	Migrate	to	POLICY_REJECT_ALL	[Tommy	Webb]																																																																											
-	Firewall:	Network	access	toggle	support	[Oliver	Scott]																																																																										
-	Implement	backup/restore	for	network	policy	[Oliver	Scott]																																																																										
-	Split	network	policy	XML	parsing	into	read/write	helper	functions	[Oliver	Scott]																																																																						
-	SystemUI:	Bring	in	drawable	for	statusbar	firewall	toggle	[Michael	Bestas]																																																																							
-	Implement	firewall	status	bar	indicator	[Oliver	Scott]																																																																										
-	Settings.Global:	Add	UIDS_ALLOWED_ON_RESTRICTED_NETWORKS	[Chirayu	Desai]																																																																												
-	SystemUI:	Make	isLargeScreen()	use	correct	API	for	getting	window	metrics	[LuK1337]																																																																						
-	Fix	bug	Device	that	can't	support	adoptable	storage	cannot	read	the	sdcard.	[sangho.yoon]																																																																				
-	Screenrecord:	Remember	last	used	blinking	dot	position	[Ido	Ben-Hur]																																																																								
-	Screenrecord:	Save	preferences	for	permission	dialog	[Pranav	Vashi]																																																																									
-	Screenrecord:	Add	summary	for	HEVC	encoding	[Pranav	Vashi]																																																																									
-	Screenrecord:	Add	an	option	to	use	HEVC	[Ido	Ben-Hur]																																																																								
-	Screenrecord:	Slightly	optimize	loading/saving	preferences	[Pranav	Vashi]																																																																										
-	Screenrecord:	Allow	to	reduce	3	second	screen	record	timer	[maitreya29]																																																																							
-	SystemUI:	Export	RecordingService	for	External	Usage	[cjybyjk]																																																																										
-	Screenrecord:	Add	an	option	to	record	for	longer	[Ido	Ben-Hur]																																																																							
-	Screenrecord:	Make	low	quality	bitrate	scalable	per	device	[Ido	Ben-Hur]																																																																							
-	Screenrecord:	Save	and	load	set	preferences	[Ido	Ben-Hur]																																																																									
-	Screenrecord:	add	blinking	stop	dot	and	low	quality	options	[ezio84]																																																																							
-	SystemUI:	Add	delete	action	to	screen	recorder	notification	[Sourajit	Karmakar]																																																																							
-	Pulse:	Remove	ConfigController	dependency	[Pranav	Vashi]																																																																											
-	Allow	profile	owner	to	set	user_setup_complete	secure	setting	[Oliver	Scott]																																																																							
-	ColorContoller:	Fix	getting	default	accent	color	[varund7726]																																																																										
-	Fix	disabling	power	menu	completely	on	secured	locscreen	[Pranav	Vashi]																																																																							
-	SystemUI:	Prevent	systemui	crash	when	reinflating	QS	[minaripenguin]																																																																									
-	Pulse:	Implement	pulse	color	based	album	art	[1/2]	[Pranav	Vashi]																																																																							
-	Pulse:	Detach	pulse	view	only	when	attached	[Pranav	Vashi]																																																																								
-	Pulse:	Solid	renderer	round	lines	[1/2]	[TikkiTikki]																																																																										
-	Pulse:	Set	current	Refresh	rate	as	FPS	animation	value	[Stallix]																																																																							
-	Pulse:	Add	more	NPE	checks	[DarkJoker360]																																																																											
-	Pulse:	Extend	to	Ambient	Screen	[spezi77]																																																																											
-	Pulse	initial	checkin	for	Android	13	[1/2]	[bigrushdog]																																																																									
-	SystemUI:	Add	API	for	runtime	taskbar	config	[Danny	Lin]																																																																								
-	SystemUI:	Allow	limiting	AOD	&	ambient	display	refresh	rate	via	overlay.	[Ido	Ben-Hur]																																																																				
-	Fix	crash	with	protected	content	with	ElectronBeam/Scale	screen-off	animation	[Matt	Filetto]																																																																						
-	fwb:	Screen	off	animations	[1/2]	[Kshitij	Gupta]																																																																										
-	SystemUI:	Add	Smart	Pixels	tile	[Adin	Kwok]																																																																										
																																																																																	
																																																																																	
*	manifest																																																																																
-	manifest:	track	more	repo	from	lineage	[ralf979]																																																																										
																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	add	defoult	string	[ralf979]																																																																												
-	Blackiron:Pulse	initial	checkin	for	Android	12	[2/2]	[Pranav	Vashi]																																																																								
-	Blackiron:	Screen	off	animations	[2/2]	[Author:	bigrushdog]																																																																										
-	Blackiron:	Smart	Pixels	[2/2]	[Adin	Kwok]																																																																											
																																																																																	
																																																																																	
====================																																																																																	
	11-26-2023																																																																																
====================																																																																																	
																																																																																	
*	device/qcom/sepolicy_vndr/legacy-um																																																																																
-	sepolicy:	Label	idle_state	node	[BeYkeRYkt]																																																																												
																																																																																	
																																																																																	
*	device/qcom/sepolicy_vndr/sm8450																																																																																
-	sepolicy:	Label	idle_state	node	[BeYkeRYkt]																																																																												
																																																																																	
																																																																																	
*	device/qcom/sepolicy_vndr/sm8550																																																																																
-	sepolicy:	Label	idle_state	node	[BeYkeRYkt]																																																																												
																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	SystemUI:	Smart	Pixels	[1/2]	[Joe	Maples]																																																																											
-	KeyguardIndication:	Set	wakelock	on	doze	only	when	required	[Pranav	Vashi]																																																																							
-	Avoid	crash	when	dream	starts	[Daisuke	Sakamoto]																																																																										
-	Fix	WifiInjector	instance	exception	if	WifiService	disabled	[Liu	Zhen]																																																																								
-	fwb:	unblock	volume	icon	(again)	[Dmitrii]																																																																											
-	base:	change	background	activity	start	mode	to	allow	for	widget	configure	[maxwen]																																																																					
-	SystemUI:	Don't	force	small	clock	when	media	isn't	allowed	on	keyguard	[Ido	Ben-Hur]																																																																				
																																																																																	
																																																																																	
*	vendor/qcom/opensource/power																																																																																
-	power:	Increase	kMinInteractiveDuration	to	1	second	[Vladimir	Mikhailov]																																																																									
-	power:	Release	interaction	lock	when	idle	state	is	detected	[Vladimir	Mikhailov]																																																																						
-	power:	Don't	hint	if	previous	duration	covers	current	duration	[Vladimir	Mikhailov]																																																																						
-	power:	Use	kMinInteractiveDuration	value	for	detecting	a	fling	[Vladimir	Mikhailov]																																																																							
																																																																																	
																																																																																	
*	vendor/qcom/opensource/vibrator																																																																																
-	vibrator:	Add	support	for	awinic_haptic	input	device	[TheStrechh]																																																																									
																																																																																	
																																																																																	
====================																																																																																	
	11-25-2023																																																																																
====================																																																																																	
																																																																																	
*	manifest																																																																																
-	manifest:	track	some	repo	from	yaap	for	Tele*	CLO	[ralf979]																																																																							
																																																																																	
																																																																																	
====================																																																																																	
	11-24-2023																																																																																
====================																																																																																	
																																																																																	
*	device/blackiron/sepolicy																																																																																
-	sepolicy:	Move	in	pocket	service	sepolicy	[Pranav	Vashi]																																																																									
																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	SystemUI:	Add	monet	customization	[1/2]	[Pranav	Vashi]																																																																										
-	PhoneWindowManager:	Update	Case	number	of	long	press	action	[ralf979]																																																																								
-	SystemUI:	Launch	power	menu	from	QS	only	if	enabled	[DarkJoker360]																																																																							
-	Hide	power	menu	on	secure	lockscreen	[1/2]	[Altaf-Mahdi]																																																																									
-	PhoneWindowManager:	Pocket	Judge:	Don't	mess	with	power	button	to	reject	call	[Ido	Ben-Hur]																																																																				
-	base:	Pocket	Judge:	Don't	go	to	sleep	while	on	call	[Ido	Ben-Hur]																																																																					
-	pocket	mode:	Update	style	to	latest	OOS	specs	[minaripenguin]																																																																								
-	PocketJudge:	Allow	to	register	vendor	proximity	sensor	[Hikari-no-Tenshi]																																																																									
-	PocketLock:	Make	using	light	sensor	optional	[Laker]																																																																										
-	SystemUI:	Improve	pocket	mode	layout	[Anushek	Prasal]																																																																										
-	base:	Redo	Pocket	mode	view	like	OOS	[Jyotiraditya	Panda]																																																																								
-	Fix	an	edge	case	in	KeyguardUpdateMonitor	pocket	callback	[paphonb]																																																																								
-	PocketJudge:	allow	register	vendor	pocket	sensor	[DennySPb]																																																																										
-	PocketLock:	fix	flickering	on	animations	[jhenrique09]																																																																											
-	Pocket	lock:	Add	config_pocketModeSupported	overlay	[jhenrique09]																																																																											
-	pocket:	introduce	pocket	bridge	[Chris	Lahaye]																																																																											
-	pocket:	Reduce	sleep	timeout	for	pocket	lock	[RadixCube]																																																																									
-	pocket:	Use	MD2	lock	drawable	[Anushek	Prasal]																																																																										
-	Pocket	lock	improvements	[Henrique	Silva]																																																																												
-	pocket:	Fix	pocket	lock	view	for	display	cutouts	[TheStrix]																																																																								
-	pocket:	Adjust	sleep	timeout	for	pocket	lock	view	to	10	secs	[TheStrix]																																																																					
-	PocketService:	Adjust	light	sensor	rate	to	400ms	[Alex	Naidis]																																																																								
-	pocket:	Add	hardware	acceleration	and	properly	maintain	SYSTEM_UI	flags	[Chris	Lahaye]																																																																						
-	policy:	introduce	pocket	lock	*	Block	touch	screen	and	keys	inputs	when	device	is	in	pocket.	*	Safe-door	to	disable	pocket	lock	within	long	press	power	button	if	sensors	do	not	behave	correctly	after	PocketManager.isDeviceInPocket()	returns	true.	*	Window	uses	TYPE_SYSTEM_ERROR	flag	with	ensure	high	priority	over	the	lockscreen	and	other	high	priority	windows.	*	Do	not	illuminate	buttons	when	pocket	lock	is	showing.	*	Disable	fingerprint	events	and	gestures	when	in	pocket	*	Be	friendly	towards	Keypress	Boost	[Carlo	Savignano]
-	pocket:	introduce	pocket	judge	[Carlo	Savignano]																																																																											
																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	Add	monet	customization	[2/2]	Signed-off-by:	Pranav	Vashi	<neobuddy89@gmail.com>	Signed-off-by:	Dmitrii	<bankersenator@gmail.com>	[Pranav	Vashi]																																																																			
-	Blackiron:	Hide	power	menu	on	secure	lockscreen	[2/2]	[Altaf-Mahdi]																																																																								
-	Blackiron:	Add	kill	button	to	notification	guts	[2/2]	[SpiritCroc]																																																																								
-	Blackiron:	Live	Volume	Steps	[2/2]	[Meticulus]																																																																											
																																																																																	
																																																																																	
*	packages/apps/Settings																																																																																
-	Settings:	Add	pocket	lock	toggle	[Chris	Lahaye]																																																																										
																																																																																	
																																																																																	
*	vendor/support																																																																																
-	support:	import	SystemSettingColorPickerPrefeerence	[ralf979]																																																																													
																																																																																	
																																																																																	
																																																																																	
																																																																																	
====================																																																																																	
	11-24-2023																																																																																
====================																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	Add	monet	customization	[2/2]	Signed-off-by:	Pranav	Vashi	<neobuddy89@gmail.com>	Signed-off-by:	Dmitrii	<bankersenator@gmail.com>	[Pranav	Vashi]																																																																			
																																																																																	
																																																																																	
====================																																																																																	
	11-23-2023																																																																																
====================																																																																																	
																																																																																	
*	device/blackiron/sepolicy																																																																																
-	sepolicy:	Move	in	pocket	service	sepolicy	[Pranav	Vashi]																																																																									
																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	SystemUI:	Add	monet	customization	[1/2]	[Pranav	Vashi]																																																																										
-	PhoneWindowManager:	Update	Case	number	of	long	press	action	[ralf979]																																																																								
-	SystemUI:	Launch	power	menu	from	QS	only	if	enabled	[DarkJoker360]																																																																							
-	Hide	power	menu	on	secure	lockscreen	[1/2]	[Altaf-Mahdi]																																																																									
-	PhoneWindowManager:	Pocket	Judge:	Don't	mess	with	power	button	to	reject	call	[Ido	Ben-Hur]																																																																				
-	base:	Pocket	Judge:	Don't	go	to	sleep	while	on	call	[Ido	Ben-Hur]																																																																					
-	pocket	mode:	Update	style	to	latest	OOS	specs	[minaripenguin]																																																																								
-	PocketJudge:	Allow	to	register	vendor	proximity	sensor	[Hikari-no-Tenshi]																																																																									
-	PocketLock:	Make	using	light	sensor	optional	[Laker]																																																																										
-	SystemUI:	Improve	pocket	mode	layout	[Anushek	Prasal]																																																																										
-	base:	Redo	Pocket	mode	view	like	OOS	[Jyotiraditya	Panda]																																																																								
-	Fix	an	edge	case	in	KeyguardUpdateMonitor	pocket	callback	[paphonb]																																																																								
-	PocketJudge:	allow	register	vendor	pocket	sensor	[DennySPb]																																																																										
-	PocketLock:	fix	flickering	on	animations	[jhenrique09]																																																																											
-	Pocket	lock:	Add	config_pocketModeSupported	overlay	[jhenrique09]																																																																											
-	pocket:	introduce	pocket	bridge	[Chris	Lahaye]																																																																											
-	pocket:	Reduce	sleep	timeout	for	pocket	lock	[RadixCube]																																																																									
-	pocket:	Use	MD2	lock	drawable	[Anushek	Prasal]																																																																										
-	Pocket	lock	improvements	[Henrique	Silva]																																																																												
-	pocket:	Fix	pocket	lock	view	for	display	cutouts	[TheStrix]																																																																								
-	pocket:	Adjust	sleep	timeout	for	pocket	lock	view	to	10	secs	[TheStrix]																																																																					
-	PocketService:	Adjust	light	sensor	rate	to	400ms	[Alex	Naidis]																																																																								
-	pocket:	Add	hardware	acceleration	and	properly	maintain	SYSTEM_UI	flags	[Chris	Lahaye]																																																																						
-	policy:	introduce	pocket	lock	*	Block	touch	screen	and	keys	inputs	when	device	is	in	pocket.	*	Safe-door	to	disable	pocket	lock	within	long	press	power	button	if	sensors	do	not	behave	correctly	after	PocketManager.isDeviceInPocket()	returns	true.	*	Window	uses	TYPE_SYSTEM_ERROR	flag	with	ensure	high	priority	over	the	lockscreen	and	other	high	priority	windows.	*	Do	not	illuminate	buttons	when	pocket	lock	is	showing.	*	Disable	fingerprint	events	and	gestures	when	in	pocket	*	Be	friendly	towards	Keypress	Boost	[Carlo	Savignano]
-	pocket:	introduce	pocket	judge	[Carlo	Savignano]																																																																											
-	SystemUI:	Allow	disabling	clipboard	overlay	[1/2]	[Adithya	R]																																																																									
-	AlertSlider:	Fixup	implementation	on	A14	[Pranav	Vashi]																																																																										
-	Add	kill	button	to	notification	guts	[1/2]	[Daniel	Koman]																																																																								
-	base:	Live	Volume	Steps	[1/2]	[Meticulus]																																																																											
-	Add	Alert	Slider	user	interface	[SQUASHED]	[Chris	Crump]																																																																									
-	Add	config	overlay	for	battery	info	update	[ShevT]																																																																									
-	Update	battery	info	every	second	when	device	is	charging	[SagarMakhar]																																																																							
-	Phone	ringtone	setting	for	Multi	SIM	device	[1/3]	[Ting	Yu]																																																																							
-	libs:	hwui:	Avoid	system	crash	if	font	contains	invalid/null	font	data	[minaripenguin]																																																																					
																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	Hide	power	menu	on	secure	lockscreen	[2/2]	[Altaf-Mahdi]																																																																								
-	Blackiron:	Add	kill	button	to	notification	guts	[2/2]	[SpiritCroc]																																																																								
-	Blackiron:	Live	Volume	Steps	[2/2]	[Meticulus]																																																																											
-	Blackiron:	Allow	disabling	ripple	effect	on	unlock	[2/2]	[Pranav	Vashi]																																																																							
-	Blackiron:	Fingerprint	authentication	vibration	[2/2]	[beanstown106]																																																																											
																																																																																	
																																																																																	
*	packages/apps/Settings																																																																																
-	Settings:	Add	pocket	lock	toggle	[Chris	Lahaye]																																																																										
-	Settings:	Allow	disabling	clipboard	overlay	[2/2]	[Adithya	R]																																																																									
-	Settings:	Follow	Accent	color	on	search	button	[StarkDroid]																																																																									
-	Settings:	fix	crash	[nift4]																																																																													
-	Phone	ringtone	setting	for	Multi	SIM	device	[2/3]	[Ting	Yu]																																																																							
																																																																																	
																																																																																	
*	packages/services/Telecomm																																																																																
-	Phone	ringtone	setting	for	Multi	SIM	device	[3/3]	[Ting	Yu]																																																																							
																																																																																	
																																																																																	
*	vendor/support																																																																																
-	support:	import	SystemSettingColorPickerPrefeerence	[ralf979]																																																																													
																																																																																	
																																																																																	
====================																																																																																	
	11-22-2023																																																																																
====================																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	Fingerprint	authentication	vibration	[1/2]	[beanstown106]																																																																												
-	base:	allow	disabling	ripple	effect	on	unlock	[1/2]	[Rishawn]																																																																								
-	BatteryService:	Add	support	for	oem	fast	charger	detection	[Pranav	Vashi]																																																																							
-	Avoid	casting	network	traffic	to	StatusBarIconView	to	prevent	crash	[SpiritCroc]																																																																							
-	SystemUI:	Increase	QS	brightness	slider	margins	[minaripenguin]																																																																										
-	SystemUI:	Remove	brightness	slider	top	margin	[minaripenguin]																																																																										
-	SystemUI:	Add	current	divider	config	for	lockscreen	charging	[Pranav	Vashi]																																																																							
-	LockscreenCharging:	squashed	(1/3)	[maxwen]																																																																													
-	NavigationHandle:	Only	register	callbacks	when	attached	[Ido	Ben-Hur]																																																																									
-	SystemUI:	NavigationHandle:	Don't	show	on	keyguard	or	doze	[Ido	Ben-Hur]																																																																							
-	Allow	disabling	qs	on	secure	lockscreen	[1/2]	[jhonboy121]																																																																									
-	SystemUI:	Allow	toggling	privacy	indicators	[1/2]	[Pranav	Vashi]																																																																									
-	SystemUI:	Kill	old	privacy	indicator	icons	completely	[Pranav	Vashi]																																																																								
-	SystemUI:	Refactor	brightness	slider	paddings	[minarypenguin]																																																																											
-	Brightness	slider:	Fix	issues	with	media	mode	[Pranav	Vashi]																																																																								
-	SystemUI:	Clean	up	and	fix	QQS	Brightness	slider	padding	[timjosten]																																																																							
-	Bring	back	QQS	brightness	slider	[Pranav	Vashi]																																																																										
-	Revert	Remove QQS brightness controller	[Mayur]																																																																														
-	Allow	tuning	position	for	brightness	slider	[maxwen]																																																																										
-	preloaded-classes:	Remove	SubscriptionController	classes	as	they	no	more	exist	[Master]																																																																							
-	incall	vibration	options	[1/3]	[beanstown106]																																																																												
-	remove	battery	from	statusbar	prefs	[ralf979]																																																																											
-	SystemUI:	Allow	hiding	QS	footer	data	usage	[1/2]	[Adithya	R]																																																																							
-	SystemUI:	QS	footer	data	usage	improvements	and	cleanup	[Adithya	R]																																																																							
-	SystemUI:	Show	QS	data	usage	suffix	only	when	necessary	[Adithya	R]																																																																						
-	[SQUASH]	SystemUI:	Show	daily	data	usage	in	QS	footer	[Adithya	R]																																																																						
																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	LockscreenCharging:	squashed	(3/3)	[xyyx]																																																																												
-	Blackiron:	allow	disabling	qs	on	secure	lockscreen	[2/2]	[jhonboy121]																																																																								
-	Blackiron:	Allow	toggling	camera/mic	privacy	indicator	[2/2]	[Pranav	Vashi]																																																																								
-	Blackiron:	Improve	location	privacy	indicator	toggle	[2/2]	[jhonboy121]																																																																									
-	Blackiron:	allow	toggling	location	privacy	indicator	[2/2]	[jhonboy121]																																																																									
-	Blackiron:	Port	brightness	slider	changes	[2/2]	[Pranav	Vashi]																																																																									
-	Blackiron:	Move	Brightness	Sileder	in	QS	settings	[ralf979]																																																																									
-	Blackiron:	Incall	vibration	option	[3/3]	*	this	works	with	google	and	aosp	dialer	:)	[beanstown106]																																																																		
-	Blackiron:	Move	battery	styles	to	seperate	fragment	[Tejasvp25]																																																																									
-	Blackiron:	Update	battery	Customization	[Pranav	Vashi]																																																																											
-	Blackiron:	move	power	menu	in	button	settings	[ralf979]																																																																									
-	Blackiron:	update	status	bar	drawable	[ralf979]																																																																											
																																																																																	
																																																																																	
*	packages/apps/Settings																																																																																
-	Settings:	Black	theme	[2/3]	[SagarMakhar]																																																																												
																																																																																	
																																																																																	
*	packages/services/Telecomm																																																																																
-	Telecomm:	Incall	vibration	options	[2/3]	[beanstown106]																																																																											
																																																																																	
																																																																																	
*	packages/services/Telephony																																																																																
-	Telephony:	Adapt	to	S	style	[ReallySnow]																																																																											
-	Telephony:	use	Build.VERSION.INCREMENTAL	to	check	for	system	update	[maxwen]																																																																								
-	Telephony:	Mark	enhanced_4g_lte_mode_title_variant	as	untranslatable	[Michael	Bestas]																																																																										
																																																																																	
																																																																																	
*	system/core																																																																																
-	core:	Lockscreen	Charging	(2/3)	[xyyx]																																																																												
																																																																																	
																																																																																	
====================																																																																																	
	11-21-2023																																																																																
====================																																																																																	
																																																																																	
*	frameworks/base																																																																																
-	SystemUI:	refresh	system	icons	on	theme	change	[Tobias	Merkel]																																																																								
-	SystemUI:	Remove	existing	icon	group	if	its	overriding	[Adithya	R]																																																																							
-	Network	traffic	mode	for	status	bar	[2/3]	*	Complete	re-write	with	proper	slot	in	status	bar	*	Refactor	stats	calc	based	on	crdroidandroid/android_lineage-sdk@02eddd4	*	Retained	optimized	code	and	formatting	[Pranav	Vashi]																																																		
-	StatusBarIconController:	Avoid	crash	due	to	incorrect	casting	[Adithya	R]																																																																								
-	SystemUI:	Introduce	dynamic	VoLTE	&	VoWiFi	icons	@neobuddy89:	*	Clean	up	unrequired	derps.	Adapted	for	A14.	*	Disabled	by	default.	[SagarMakhar]																																																												
-	SystemUI:	Add	ability	to	toggle	bluetooth	battery	level	[1/2]	[Pranav	Vashi]																																																																						
-	base:	Rearrange	bluetooth	icon	on	statusbar	[Adithya]																																																																										
-	SystemUI:	Fix	refactored	Bluetooth	icon	crash	[Pranav	Vashi]																																																																									
-	SystemUI:	Use	red	color	for	low	bluetooth	battery	[Adithya	R]																																																																							
-	SystemUI:	Refactor	statusbar	bluetooth	icon	[Adithya	R]																																																																										
-	Revert	SystemUI: Update BT battery level from OOS	[ralf979]																																																																														
-	SystemUI:	Fix	up	status	bar	start	side	content	layout	[Pranav	Vashi]																																																																						
-	BluetoothControllerImpl:	Synchronize	mConnectedDevices	access	[jhonboy121]																																																																												
-	apex:	Prevent	illegal	state	exception	caused	by	GMS	concurrent	alarms	[minaripenguin]																																																																						
-	fixup!	SystemUI:	Redraw	display	cutout	on	overlay	changes	[Omkar	Chandorkar]																																																																							
-	SystemUI:	Redraw	display	cutout	on	overlay	changes	[Adithya	R]																																																																								
-	SystemUI:	Scale	mobile	data	type	icon	with	font	size	[Adithya	R]																																																																						
-	SystemUI:	Improve	statusbar	mobile	type	icons	padding	[Adithya	R]																																																																								
-	fixup!	SystemUI:	Make	the	volume	dialog	expandable	[Sebastiano	Barezzi]																																																																								
-	base:	make	per-app	work	with	multi	audio	focus	[El	Dainosor]																																																																							
-	SystemUI:	New	per-app	volume	icon	[ReallySnow]																																																																											
-	Revert	VolumeDialogImpl: Fix cuttered layout when on setup or lock task mode	[lemezohaib]																																																																														
-	base:	support	per-app	volume	[2/3]	[cjybyjk]																																																																											
-	SystemUI:	Add	separated	notification	volume	control	to	VolumePanelDialog	[someone5678]																																																																								
-	core:	Enable	smart	battery	for	everyone	[mydongistiny]																																																																										
-	audio:	Don't	play	sound	effects	if	stream	is	muted	[Steve	Kondik]																																																																						
-	Toast:	Perform	text	scrolling	for	long	toast	texts	[minaripenguin]																																																																								
-	core:	Improve	notification	toast	format	and	fix	for	apps	<	sdk	29	[minaripenguin]																																																																				
-	fixup!	Match	legacy	toast	view	with	SystemUI	[SagarMakhar]																																																																									
-	neko/Cat:	Mark	FLAG_IMMUTABLE	PendingIntent	with	FLAG_MUTABLE	[PainKiller3]																																																																										
-	core:	Catch	OOB	when	returning	pooled	string	[minaripenguin]																																																																									
-	Match	legacy	toast	view	with	SystemUI	[SagarMakhar]																																																																										
-	BrightnessUtils:	Conditionally	use	low	gamma	implementation	for	brightness	curve	[SagarMakhar]																																																																							
-	[SQUASH]	Feature:	reticker	[1/2]	[someone5678]	*	Based	on	crDroid	Android's	cleaned	A12	commit	[1]	*	Forward	port	to	Android	14	QPR1	*	Follow	the	Material	You	styles	*	Show	text	only	if	icon	is	null	*	Import	SystemUIToast	icon	retrieving	logic	and	adapt	it	*	Use	EXTRA_TITLE	and	EXTRA_TEXT	as	content	[Dil3mm4]																													
-	fixup!	SystemUI:	Add	double	tap	to	sleep	gesture	[someone5678]																																																																								
-	Ignore	cgroup	creation	errors	[Pierre-Hugues	Husson]																																																																											
-	SystemUI:	Grant	ACCESS_FINE_LOCATION	permission	[someone5678]																																																																												
-	libs:	hwui:	Silence	OpenGL	swap	behavior	failures	[minaripenguin]																																																																									
-	ApplicationPackageManager:	Merge	Tensor	list	[someone5678]																																																																												
-	SystemUI:	Add	switch	data	saver	icon	[xyyx]																																																																										
-	base:	SystemUI:	add	VPN	to	the	icon	blacklist	in	tuner	[maxwen]																																																																						
-	Device	policy:	Fix	security	exception	caused	by	uid/packagename	mismatch	[minaripenguin]																																																																							
-	Fix	logspam	from	AppIdleHistory	on	first	boot	[Eric	Biggers]																																																																								
-	PackageManager:	Create	missing	userdata	directory	[Arnab	Sen]																																																																										
-	Fix	incorrect	parameter	transfer	when	setting	wallpaper	component	[Ge	Tianxiong]																																																																							
-	StrictMode:	fix	race	condition	in	onVmPolicyViolation	[Tomislav	Novak]																																																																									
-	TunerServiceImpl:	Blacklist	Settings.System	from	tuner	reset	[dianlujitao]																																																																										
-	Tuner:	Don't	clear	out	prefs,	it's	not	disabled	[Joe	Maples]																																																																							
-	SystemUI:	Reset	QS	on	UI	mode	change	[althafvly]																																																																									
-	base:	Don't	send	interaction	hint	for	unnecessary	events	[Alex	Naidis]																																																																							
-	SystemUI:	Resolve	crash	when	updating	control	list	services	[minaripenguin]																																																																								
-	SystemUI:	fix	antiquated	TunerActivity	bugs	[nift4]																																																																											
-	InputMethodUtils:	Fix	system	bootloop	when	no	IME	found	[Pranav	Vashi]																																																																							
-	SystemUI:	give	access	to	CHANGE_CONFIGURATION	permission	[dlwlrma123]																																																																										
-	SystemUI:	fix	SliceView	layout	[Anay	Wadhera]																																																																											
-	base:	Bring	back	suspend	app	perms	[ender1324]																																																																										
-	Fix	phone	restarts	after	SD	card	formatted	as	internal	storage	[Bo	Ye]																																																																					
-	ConfigurationController:	Prevent	app	crash	on	orientation	change	[minaripenguin]																																																																									
-	Prevent	some	key	system	applications	from	losing	storage	permissions	[Õ?áÕÇ×Þ»Ü]																																																																							
-	Sometimes	Screen	does	not	wake	up	while	receiving	whatsapp	video	call	[Aditya	Jadhav]																																																																				
-	fwb:	Add	missing	android.permission.REGISTER_STATS_PULL_ATOM	launcher3	permission	[karthik1896]																																																																										
-	SystemUI:	QSTileImpl:	bail	out	early	in	handleLongClick	if	getLongClickIntent	returns	null	[Alfred	Mathew]																																																																				
-	Conditionally	disable	uncrypt	for	ota	[Henrique	Silva]																																																																										
-	services:	Fix	ArrayIndexOutOfBoundsException	on	`updateContentCaptureOptions`	[minaripenguin]																																																																											
-	Use	try-with-resources	to	avoid	accidentaly	leaking	unclosed	objects.	[Mateus	Azis]																																																																							
-	Revert	Fix boot animation alpha multiplication computations	[Dmitrii]																																																																														
-	KernelCpuUidTimeReader:	Always	check	if	`remove_uid_range`	file	exists	[minaripenguin]																																																																									
-	BootReceiver:	Return	early	if	trace_pipe	doesn't	exists	[minaripenguin]																																																																									
-	ViewGroup:	Remove	child	parent	when	a	new	view	is	added	[mydongistiny]																																																																						
-	SystemUI:	Grant	READ_PHONE_STATE	permission	[Martin	Bouchet]																																																																											
-	Don't	fail	setDeviceConnectionState	if	not	implemented	in	hal	[Aaron	Kling]																																																																							
-	CompanionDeviceManager:	This	uses	the	MANAGE_COMPANION_DEVICES	permission	[Sourajit	Karmakar]																																																																									
-	Allow	required	Android	Auto	permissions	[Dylanger	Daly]																																																																										
-	Fix	secondary	user	crash	with	system	user	locked	[Tommy	Webb]																																																																							
-	DisplayPowerController:	Disable	log	spam	[TheHardGamer]																																																																												
-	fwb:	silence	debug	spam	from	image	resolver	[Dmitrii]																																																																									
-	fwb:	silence	useless	resources	warning	spam	[Dmitrii]																																																																										
-	SystemUI:	Enable	camera	&	flashlight	keyguard	affordance	[Adithya	R]																																																																								
-	SystemUI:	Reduce	keyguard	indication	text	padding	[minaripenguin]																																																																										
-	SystemUI:	Allow	media	player	actions	to	condense	more	[Ido	Ben-Hur]																																																																							
-	SystemUI:	media_session_expanded:	Total	time	should	be	before	next	[Ido	Ben-Hur]																																																																							
-	NotificationMenuRow:	fix	logspam	[tejasvp25]																																																																													
-	BrightnessUtils:	Allow	maintainer	to	set	desired	brightness	curve	impl	[minaripenguin]																																																																							
-	base:	Fix	brightness	slider	curve	for	some	devices	[SagarMakhar]																																																																								
-	fwb:	remove	spammy	wallet	lockscreen	icon	error	[Dmitrii]																																																																									
-	Intent:	Fix	launch	of	permission	revoke	activity	from	playstore	[jhenrique09]																																																																							
-	Don't	request	render	in	GLSurfaceView.GLThread	ctr	[Oleg	Ladin]																																																																									
-	Avoid	needless	Integer.valueOf()	object	allocation.	[Tobias	Thierer]																																																																										
-	Kill	some	lockscreen	related	animations	[Umang96]																																																																											
-	Speed	up	StatusBar	[Chet	Kener]																																																																												
-	fwb:	unblock	volume	icon	on	keyguard	[Dmitrii]																																																																										
-	When	a	user	is	unlocked,	it	will	install	provider,	but	it	cannot	publish	Provider	successfully,we	need	add	pr.installProvider	before	scheduleInstallProvider	[xieliangzhuo]																																																												
-	SystemUI:	Switch	notification	background	to	monet	on	heads	up	[DillerOFire]																																																																							
-	data:	Add	missing	systemui	permissions	[Pranav	Temkar]																																																																										
-	Add	missing	INTERACT_ACROSS_USERS_FULL	permission	[AdrianDC]																																																																												
-	hwui:	Remove	logspam	cause	by	early	animation	handle	check	[minaripenguin]																																																																							
-	ProcessList:	Catch	Security	exception	when	starting	a	frozen	package	[minaripenguin]																																																																							
-	OomAdjuster:	Remove	excessive	log	[Andrzej	Perczak]																																																																											
-	jobscheduler:	disable	debug	[TheHardGamer]																																																																													
-	SystemUI:	Disable	nav	bar	auto	dim	[TheHardGamer]																																																																										
-	AppProfiler:	dont	be	so	hectic	on	cpu	battery	stats	[Simao	Gomes	Viana]																																																																					
-	Revert	Change battery saver tile to launch battery saver page	[TheHardGamer]																																																																														
-	base:	disable	DBG	[TheHardGamer]																																																																													
-	base:	fixup	17db0bce5a52514863ba36eb4077c80f78abd94a	[TheHardGamer]																																																																													
-	FeatureFlags:	Enable	systemui	volume	panel	by	default	[Jason	Edson]																																																																								
-	Force	disable	PlayServices	OTA	checks	[ezio84]																																																																											
-	keyguard:	Actually	kill	Fancy	Colon	[Joe	Maples]																																																																										
-	Revert	Taller volume dialog slider on taller screens	[minaripenguin]																																																																														
-	SystemUI:	Align	keyguard	carrier	text	with	status	bar	[Andy	CrossGate	Yan]																																																																						
-	display:	Don't	reset	brightness	adjustment	on	clearUserDataPoints()	[LibXZR]																																																																									
-	SystemUI:	Apply	surface	color	to	brightness	icons	[Harsh	Pal]																																																																								
-	QS	Tile:	Make	QS	Ripple	animation	more	prominent	[StarkDroid]																																																																								
-	QS	Tile:	Set	ripple	color	to	accent	by	default	[StarkDroid]																																																																							
-	Reland	"Don't enable jdwp by default on userdebug builds""  [Mythri Alle]"																																																																															
-	AppProfiler:	dont	be	so	hectic	on	cpu	battery	stats	[Simao	Gomes	Viana]																																																																					
-	core:	Add	dark	mode	support	for	`colorAccentPrimary`	[strwbrry143]																																																																									
-	fixup!	SettingsLib:	Fix	switch	bg	state	on	color	[str-br]																																																																								
-	Improve	dark	mode	switch	color	transition	[str143]																																																																										
-	DisplayDeviceRepository:	Don't	spam	log	when	display	state	changes	[Adithya	R]																																																																							
-	Revert	Remove fixed grant of READ_PHONE_STATE and cleanup	[micky387]																																																																														
-	Framelayout:	Fix	NPE	when	view	is	missing	[Pranav	Vashi]																																																																								
-	Move	PackageManager	new	user	logic	after	dispatching	[LibXZR]																																																																									
-	Dividers:	not	here	[Dil3mm4]																																																																													
-	ChangeReporter:	Silence	log	spam	[tejasvp25]																																																																												
-	SystemUI:	CustomTile:	add	a	null	check	before	loadDrawable	invocation	in	default	icon	[jhonboy121]																																																																				
-	SystemUI:	Fix	QS	customizer	corner	radius	[Pranav	Vashi]																																																																									
-	SettingsLib:	Fix	the	collapsing	toolbar	bg	color	[str-br]																																																																									
-	base:	Allow	Launcher3	to	use	android.permission.FORCE_STOP_PACKAGES	[Pranav	Vashi]																																																																									
-	fwb:Add	android.permission.WRITE_APN_SETTINGS	[karthik1896]																																																																														
-	SystemUI:	Link	style	elements	to	config_dialogCornerRadius	[Pranav	Vashi]																																																																									
-	fwb:	Link	more	elements	to	`config_dialogCornerRadius	`	[minaripenguin]																																																																									
-	DisplayPowerController:	Don't	apply	brightness	adjustment	if	NaN	[LibXZR]																																																																									
-	SystemUI:	Respect	Statusbar	left	padding	in	keyguard	carrier	[timjosten]																																																																								
-	Fix	screen	flickering	when	using	one	handed	mode	[timjosten]																																																																								
-	SystemUI:	Better	QS	detail	clip	animation	[dongwan0605.kim]																																																																										
-	telephony:	SmsMessage:	Bring	newFromCDS	method	back	[SamarV-121]																																																																										
-	StorageManager:	Add	dummy	inCryptKeeperBounce	method	[SamarV-121]																																																																											
-	Keyguard	-	Treat	messages	to	lock	with	priority	[Matt	Pietal]																																																																							
-	SystemUI:	Remove	unused	resources	[Michael	Bestas]																																																																											
-	base:	Remove	aosp's	'show	battery	percentage'	setting	[razorloves]																																																																									
-	SystemUI:	Enable	smart	replies	for	apps	that	target	APIs	lower	than	28	[Diab	Neiroukh]																																																																			
-	base:	Set	ic_avatar_user	and	ic_avatar_guest_user	to	follow	system	accent	[elpaablo]																																																																							
-	SQLiteDatabase:	Catch	corrupt	exception	during	transaction	[muzbit.kim]																																																																										
-	StatusBarIconController:	Guard	yet	another	function	from	cast	exception	[Ido	Ben-Hur]																																																																							
-	(Point)	Only	calculate	sin	and	cos	once	[Till	Kottmann]																																																																								
-	base:	use	a	double	click	effect	for	charging	if	there	is	no	amplitude	control	support	[jhonboy121]																																																																	
-	aapt:	Use	a	std::map	instead	of	a	SortedVector	[Christopher	R.	Palmer]																																																																						
-	SystemUI:	Add	missing	init	for	isDeviceProvisioned	in	PhoneStatusBarPolicy	[maxwen]																																																																								
-	core:	Fix	menu	popup	ripple	[timjosten]																																																																											
-	services:	ActiveServices:	drop	uid	check	when	notifying	newly	registered	callbacks	[jhonboy121]																																																																						
-	fix	error	com.google.android.gms.persistent	[rc420head]																																																																													
-	config:	Allow	gms	to	access	persistent	data	partition	[Demon000]																																																																								
-	ProcessList:	Silence	lmkd	retries	logspam	[strwbrry143]																																																																											
-	development:	Address	NPE	when	removing	preferences	out	of	developer	options	[Alex	Cruz]																																																																					
-	base:	get	the	most	of	the	media	artwork	colors	[El	Dainosor]																																																																						
-	privapp-permissions:	Grant	missing	TelephonyProvider	perm.	[spezi77]																																																																											
-	base:	Supress	telephony	crashing	platform	[Pranav	Vashi]																																																																										
-	base:	PSSSSST!	disable	some	DEBUG	logspill	[maxwen]																																																																										
-	SystemUI:	Disable	all-caps	for	smart	reply	button	text	[Adithya	R]																																																																							
-	SystemUI:	Mark	colorBackgroundDrawable	as	protected	[Anay	Wadhera]																																																																										
-	base:	Reduce	horizontal	spacing	around	location	icon	[Adithya	R]																																																																								
-	AutoFillUI:	Don't	show	a	null	toast	[Ido	Ben-Hur]																																																																									
-	libs:	hwui:	Build	using	ThinLTO	[mydongistiny]																																																																											
-	hwui:	Compile	without	no-omit-frame-pointer	[Sourajit	Karmakar]																																																																											
-	libhwui:	compile	for	performance	[Vaisakh	Murali]																																																																											
-	libhwui:	enable	O3	when	compiling	for	perf	[Vaisakh	Murali]																																																																								
-	libhwui:	remove	deprecated	perf	flags	[Vaisakh	Murali]																																																																										
-	Add	support	for	app	signature	spoofing	[Danny	Lin]																																																																									
-	gmscompat:	expand	background	activity	launch	shim	to	all	core	GMS	apps	[Dmitry	Muhomor]																																																																				
-	exempt	telephony	service	from	the	new	package	visibility	restrictions	[Dmitry	Muhomor]																																																																						
-	do	not	delete	compiled	code	(OAT	files)	of	hibernated	apps	[Dmitry	Muhomor]																																																																					
-	PackageSpec:	make	validator	into	an	interface	[Dmitry	Muhomor]																																																																									
-	gmscompat:	enable	DynamiteLoader	v2	[Dmitry	Muhomor]																																																																											
-	remove	no	longer	used	Context.registerReceiver()	wrapper	[Dmitry	Muhomor]																																																																									
-	fixup!	integrate	Google's	eUICC	LPA	app	[Dmitry	Muhomor]																																																																									
-	fixup!	add	helpers	for	system_server	extensions	[Dmitry	Muhomor]																																																																									
-	fixup!	Wi-Fi	auto	turn	off	[Dmitry	Muhomor]																																																																										
-	fixup!	Bluetooth	auto	turn	off	[Dmitry	Muhomor]																																																																										
-	charging:	Allow	using	vibration	without	sounds	[xyyx]																																																																										
-	services:	Fix	google	apps	permission	denials	[minaripenguin]																																																																										
-	PixelPropsUtils:	Make	CTS/Play	Integrity	pass	again	[chiteroman]																																																																										
-	PixelPropsUtils:	Use	RecentPixel	instead	of	individual	model	name	[someone5678]																																																																								
-	SystemUI:	add	haptic	feedback	for	qs	tiles	[Wahid	Khan]																																																																								
-	ApplicationPackageManager:	Add	a	config	for	device	with	Tensor	SoC	[someone5678]																																																																							
-	PixelPropsUtils:	Drop	pixel	codenames	and	checks	[someone5678]																																																																										
-	PixelPropsUtils:	Add	a	config	to	enable/disable	prop	imitation	[Chris	Crawford]																																																																							
-	PixelPropsUtils:	Update	fingerprints	to	November	2023	release	[Joey	Huab]																																																																								
-	PixelPropsUtils:	Fix	GMS	drain	triggered	by	an	outdated	ROM	build	date	[Tim	Josten]																																																																				
-	PixelPropsUtils:	Bring	in	Pixel	8	series	changes	[Joey	Huab]																																																																								
-	PixelPropsUtils:	Update	fingerprints	to	September	2023	release	[Joey	Huab]																																																																								
-	PixelPropsUtils:	Stop	spoofing	some	google	apps	[aswin7469]																																																																										
-	PixelPropsUtils:	Partial	spoofing	improvement	[minaripenguin]																																																																												
-	PixelPropsUtils:	Refactor	logic	and	cleanup	[Henrique	Silva]																																																																										
-	base:	ApplicationPackageManager:	Return	early	for	Tensor	check	[someone5678]																																																																									
-	base:	ApplicationPackageManager:	Exclude	PE	2021	Midyear	from	tensor	pixel	list	[someone5678]																																																																						
-	base:	ApplicationPackageManager:	Block	Tensor	features	for	Recorder	[someone5678]																																																																									
-	PixelPropsUtils:	Update	fingerprints	to	August	2023	release	[Joey	Huab]																																																																								
-	PixelPropsUtils:	Spoof	all	wallpaper	packages	to	Pixel	7	Pro	[someone5678]																																																																							
-	PixelPropsUtils:	Set	HARDWARE,	ID	values	[someone5678]																																																																											
-	PixelPropsUtils:	Correctly	spoof	unstable	process	[someone5678]																																																																											
-	PixelPropsUtils:	Remove	pixel	tablet	spoof	for	Weather	[jhenrique09]																																																																									
-	PixelPropsUtils:	Spoof	to	Pixel	5a	by	default	[someone5678]																																																																									
-	PixelPropsUtils:	Update	fingerprints	to	July	2023	release	[Joey	Huab]																																																																								
-	PixelPropsUtils:	Refactor	[Joey	Huab]																																																																													
-	ApplicationPackageManager:	Adjust	Tensor	workaround	[someone5678]																																																																												
-	core:	ApplicationPackageManager:	Remove	p21+	features	from	featuresPixel	[someone5678]																																																																									
-	core:	block	2021/22	pixel	features	to	ASI	and	pixel	launcher	[aswin7469]																																																																						
-	ApplicationPackageManager:	Extend	freeform	window	feature	to	all	apps	[minaripenguin]																																																																								
-	Prevent	apps	from	crashing	if	internet	permission	is	revoked.	[minaripenguin]																																																																							
-	stop	Microsoft	apps	from	crashing	without	INTERNET	permission	[Dmitry	Muhomor]																																																																							
-	PixelPropsUtils:	Enable	new	Velvet	Weather	UI	[Sourajit	Karmakar]																																																																									
-	PixelPropsUtils:	Add	emojiwalls	and	cinematiceffects	pkgs	[aswin7469]																																																																										
-	Revert	PixelPropUtils: Spoof userdebug to pixel launcher	[aswin7469]																																																																														
-	[SQUASH]	Introduce	PixelPropsUtils	[jhenrique09]																																																																													
-	Revert	Squashed Import of PixelPropsUtils	[ralf979]																																																																														
-	Revert	PixelPropsUtils: Replace Pixel 7 Pro with Pixel 8 Pro	[ralf979]																																																																														
-	core:	camera2:	StreamConfigurationMap:	add	constructor	for	MIUI	camera	[Pulkit077]																																																																								
-	Not	run	hideDotView	as	an	animation	[Bin	Huang]																																																																									
-	Camera:	Allow	setting	fallback	physical	ID	for	logical	camera	[2/2]	[Adithya	R]																																																																					
-	display:	Handle	zero	auto	brightness	adjustment	[Adithya	R]																																																																									
-	Merge	tag	'android-14.0.0_r14'	into	u14	[ralf979]																																																																											
-	TurnerServices:	add	missing	parsInteger	method	[ralf979]																																																																											
-	SystemUI:	Port	statusbar	brightness	control	[Alberto97]																																																																											
-	SystemUI:	Hide	call	strength	icons	[SagarMakhar]																																																																											
-	BrightnessController:	Don't	update	slider	from	DisplayManager	callback	if	user	is	changing	brightness	[jhonboy121]																																																																				
-	SystemUI:	Port	brightness	slider	changes	[Alberto97]																																																																											
-	core:	pm:	Allow	wildcard	in	RRO	system	property	value	checks	[Luca	Stefani]																																																																					
-	Allow	Panic	to	silently	uninstall	packages.	[Chirayu	Desai]																																																																									
-	Avoid	Settings	app	NPE	on	broken	packages	[t-m-w]																																																																									
-	Allow	to	suppress	notifications	sound	if	screen	is	ON	[1/2]	[ezio84]																																																																						
-	SystemUI:	Less	boring	heads	up	option	[1/2]	[ezio84]																																																																									
-	SystemUI:	Hide	notifications	when	quickly	expanding	QS	[Adithya	R]																																																																								
-	GlobalActionsDialogLite:	Dismiss	the	dialog	when	restarting	SystemUI	[ezio84]																																																																									
-	frameworks:	Add	restart	systemui	shortcut	to	power	menu	[1/2]	[ezio84]																																																																							
-	Add	a	panic	trigger	to	Global	actions	[Chirayu	Desai]																																																																								
-	SystemUI:	Add	SCREEN_GESTURE	as	a	CameraLaunchSourceModel	[resist15]																																																																										
-	SystemUI:	Disable	clock	auto	hide	feature	for	QS	[LuK1337]																																																																								
-	frameworks:	Add	support	for	clock	auto-hiding	[C?®dric	Bellegarde]																																																																									
-	ChargingControl:	Additional	log	lines	for	deadline	[Tommy	Webb]																																																																									
-	ChargingControl:	Retry	setting	deadline	if	it	fails	[Tommy	Webb]																																																																								
-	ChargingControl:	Drop	default	values	for	initially	zero	variables	[Luofan	Chen]																																																																							
-	ChargingControl:	Return	early	if	lineage	health	HAL	is	not	found	[Luofan	Chen]																																																																					
-	ChargingControl:	Don't	set	deadline	if	charging	control	is	not	enabled	[Luofan	Chen]																																																																					
-	ChargingControl:	Use	ServiceManager.waitForDeclaredService()	[LuK1337]																																																																													
-	ChargingControl:	No	need	to	log	a	crash	when	not	supported	[Michael	W]																																																																					
-	ChargingControl:	Handle	cancel	toggle	correctly	if	bypass	is	not	supported	[Luofan	Chen]																																																																					
-	ChargingControl:	Add	cancel	toggle	for	limit	done	notification	[Luofan	Chen]																																																																							
-	ChargingControl:	Reset	internal	states	on	settings	change	[Luofan	Chen]																																																																								
-	ChargingControl:	Set	a	small	margin	for	devices	with	bypass	support	[Luofan	Chen]																																																																					
-	base:	Add	static	isChargingControlSupported(ctx)	method	[LuK1337]																																																																											
-	base:	Implement	Lineage	health	service	Change-Id:	I772ccf6d323c24d681aa8468bf4318c7b73bd3f5	Signed-off-by:	Mohammad	Hasan	Keramat	J	<ikeramat@protonmail.com>	[Luofan	Chen]																																																																		
-	base:	Extract	base	class	for	lineage	base	feature	So	that	it	can	be	shared	in	multiple	components	[Luofan	Chen]																																																														
-	base:	Settings:	Add	settings	for	charging	control	[Danny	Trunk]																																																																								
-	SystemUI:	Respect	the	old	good	Show passwords	preference	[alk3pInjection]																																																																									
-	SystemUI:	Check	if	primitive	vibrations	are	supported	in	new	quick	affordances	[Fabian	Leutenegger]																																																																				
-	SystemUI:	Require	unlocking	to	use	sensitive	QS	tiles	[Danny	Lin]																																																																							
-	SystemUI:	Add	VPN	tile	[Danny	Baumann]																																																																											
-	SystemUI:	Add	NFC	tile	to	default	[Adithya	R]																																																																									
-	SystemUI:	Restore	wifi	and	cellular	QS	tiles	[Michael	Bestas]																																																																								
-	SystemUI:	Add	reading	mode	tile	[Joey]																																																																											
-	Report	success	on	every	fingerprint	removal	[Kishan	Dudhatra]																																																																									
-	SystemUI:	show	ime	switcher	+	cursor	keys	if	we	have	space	[nift4]																																																																					
-	PhoneWindowManager:	only	handle	long	press	on	back	key	if	using	it	[nift4]																																																																					
-	VolumeDialogImpl:	Add	STREAM_NOTIFICATION	row	[LuK1337]																																																																												
-	SystemUI:	Enable	cast	tile	without	Wi-Fi	connection	[nift4]																																																																									
-	Fix	multi-user	silent	notifications	on	lockscreen	[Tommy	Webb]																																																																									
-	InputDevices:	Fix	Hungarian	language	overlay	[Sean	McCreary]																																																																										
-	MetaKeyKeyListener:	Disable	locking	of	toggled	modifier	keys	[Sean	McCreary]																																																																								
-	SystemUI:	Make	battery	clickable	again	[Michael	W]																																																																										
-	PhoneWindowManager:	Fix	wakeup	and	long-press	actions	of	assistant	key	[kyasu]																																																																							
-	JobScheduler:	Respect	allow-in-power-save	perm	[Tommy	Webb]																																																																											
-	SystemUI:	Respect	single-touch	wakeup	setting	on	rear	&	front	fps	devices	[Michael	Bestas]																																																																				
-	VolumeDialogImpl:	Fix	cut	layout	when	on	setup	or	lock	task	mode	[jhenrique09]																																																																					
-	SystemUI:	DreamTile:	Enable	for	everyone	[Ido	Ben-Hur]																																																																										
-	SystemUI:	Avoid	using	null	Context	in	onTuningChanged()	[kxxt]																																																																									
-	SystemUI:	SideFpsEventHandler:	Don't	crash	without	FingerprintManager	[Michael	W]																																																																									
-	Fallback	ESC	to	BACK	[Aaron	Kling]																																																																											
-	base:	Lower	protection	level	of	lineageos	permissions	[Erfan	Abdi]																																																																								
-	Keyguard:	Add	option	to	scramble	pin	layout	when	unlocking	(2/2).	[Adnan]																																																																						
-	services:	fix	quickswitch	with	gesture	pill	disabled	[nift4]																																																																									
-	wm:	fix	APPEARANCE_LOW_PROFILE_BARS	not	working	in	non-fullscreen	app	[nift4]																																																																								
-	base:	Introduce	LiveDisplay	from	Lineage	[Erfan	Abdi]																																																																										
-	SettingsProvider:	Setup	default	resources	For	following	settings:	*	Settings.Secure.VOLUME_PANEL_ON_LEFT	*	Settings.System.FORCE_SHOW_NAVBAR	[Erfan	Abdi]																																																																				
-	LineageHardwareManager:	Introduce	keys	swap	feature	support	[Arian]																																																																										
-	blackiron:	preference:	Import	SettingsHelper	[Erfan	Abdi]																																																																											
-	Add	support	for	runtime	toggle	of	navbar	[Bruno	Martins]																																																																								
-	Always	add	second	arrow	in	front	on	long	swipe	[someone5678]																																																																							
-	Flip	back	gesture	canvas	if	started	from	left	[someone5678]																																																																								
-	Cancel	long	swipe	for	cancelBack	in	navigation	gesture	[someone5678]																																																																								
-	Extends	Use double click effect for long swipe	[someone5678]																																																																														
-	Implement	edge	long	swipe	gesture	to	new	back	gesture	affordance	[someone5678]																																																																						
-	Implement	edge	long	swipe	gesture	[Nico]																																																																											
-	util:	Import	PackageManagerUtils	from	sdk	[Erfan	Abdi]																																																																										
-	Camera	button	support	[HazouPH]																																																																													
-	PhoneWindowManager:	Add	support	for	back	key	long	press	customization	[LuK1337]																																																																							
-	fw/b:	Allow	customisation	of	navbar	app	switch	long	press	action	[Sam	Mortimer]																																																																					
-	PhoneWindowManager:	Implement	press	home	to	answer	call	[Oleksandr	Byelkin]																																																																								
-	PhoneWindowManager:	Tap	volume	buttons	to	answer	call	[martincz]																																																																									
-	PhoneWindowManager:	Forward	port	long	press	back	to	kill	app	[Danesh	Mondegarian]																																																																						
-	VolumeKeyHandler:	Adapt	for	12	[Erfan	Abdi]																																																																											
-	VolumeKeyHandler:	Add	support	for	skipping	tracks	with	remote	control	[ezio84]																																																																							
-	PhoneWindowManager:	add	VolumeKeyHandler	[Simon	Shields]																																																																												
-	Reimplement	device	hardware	wake	keys	support	[LuK1337]																																																																										
-	fwb:	Re-introduce	keyboard	backlight	brightness	control	[Bruno	Martins]																																																																									
-	PowerManager:	Allow	to	distinguish	different	keypresses	[Corinna	Vinschen]																																																																									
-	PowerManagerService:	Allow	to	light	up	buttons	only	when	pressed	[Anas	Karbila]																																																																						
-	fw/b:	Button	backlight	brightness	[Ricardo	Cerqueira]																																																																											
-	SystemUI:	runtime	configurable	audio	panel	location	[a.derendyaev]																																																																										
-	VolumeDialogImpl:	Don't	hide	the	default	stream	when	adjusting	the	music	stream	[Arian]																																																																					
-	Forward	port	'Swap	volume	buttons'	(1/3)	[nadlabak]																																																																										
-	frameworks/base:	Lights	notifications	brightness	support	[Adrian	DC]																																																																										
-	frameworks/base:	Battery	and	Notification	Lights	[Sam	Mortimer]																																																																										
-	Import	LineageNotification	from	lineage	sdk	[Erfan	Abdi]																																																																										
-	SystemUI:	Fix	position	and	orientation	of	arrow	keys	in	navbar	[Wolfram	Liebchen]																																																																					
-	SystemUI:	add	left	and	right	virtual	buttons	while	typing	[Roman	Birg]																																																																						
-	fwb:	Redesign	seekbar	[SagarMakhar]																																																																													
-	Battery	Styles:	Add	customization	for	QS	[Pranav	Vashi]																																																																									
-	ThemeOverlayController:	Remove	repeated	monet	check	[Pranav	Vashi]																																																																										
-	Battery	Styles:	Use	single	low	level	warning	config	[Pranav	Vashi]																																																																							
-	Battery	Styles:	Update	plus	color	for	battery	[Pranav	Vashi]																																																																								
-	Battery	Styles:	Hide	plus	when	showing	battery	percentage	inside	icon	[Christian	Oder]																																																																					
-	Battery	Styles:	Allow	setting	percent	view	on	left	[1/2]	[703joko]																																																																							
-	Battery	Styles:	Introduce	Battery	Landscape	[1/2]	[703joko]																																																																										
-	Battery	Styles:	Fix	signal	icon	padding	with	Hidden	style	[Ezio	Lacandia	Bijelkic]																																																																					
-	Battery	Styles:	Show	a	bolt	ÔÜí	when	charging	[ezio84]																																																																								
-	Battery	Styles:	Introduce	full	circle	battery	style	[Christian	Oder]																																																																								
-	Battery	Styles:	Readd	dotted	Circle	to	Kotlin	impl	[Christian	Oder]																																																																							
-	Battery	Styles:	Improvements	and	clean	up	for	more	customizations	[Pranav	Vashi]																																																																						
-	SystemUI:	Bring	back	good	ol'	circle	battery	style	[Luca	Stefani]																																																																							
-	base:	Fix	Black	theme	not	applied	immediately	[someone5678]																																																																									
-	SystemUI:	mark	reevaluateSystemTheme	as	protected	so	we	can	access	it	[Anay	Wadhera]																																																																					
-	base:	SystemUI:	Add	Black	theme	[1/3]	[SagarMakhar]																																																																										
-	Don't	skip	theme	application	if	it's	already	current	[Michael	Bestas]																																																																							
-	base:	disable	debug	[TheHardGamer]																																																																													
-	BatteryMeterView:	Fix	NPE	that	occurs	when	onDensityOrFontScaleChanged()	is	called.	[spezi77]																																																																							
-	Revert	SystemUI: Bring back good ol' circle battery style	[ralf979]																																																																														
																																																																																	
																																																																																	
*	packages/apps/Settings																																																																																
-	Settings:	remove	battery	style	from	statusbar	[ralf979]																																																																										
-	reorder	AM_PM	stile	option	[ralf979]																																																																												
																																																																																	
																																																																																	
*	vendor/blackiron																																																																																
-	vendor:	theme:	AndroidBlackTheme:	Turn	more	color	components	to	black	[someone5678]																																																																							
-	BlackTheme:	Adjust	luminance	for	neutral	shades	800	and	above	[minaripenguin]																																																																							
-	themes:	Black	theme	[3/3]	[SagarMakhar]																																																																												
-	Revert	blackiron: Import BlackTheme overlay package from Lineage	[ralf979]																																																																														
																																																																																	
																																																																																	
====================																																																																																	
	11-20-2023																																																																																
====================																																																																																	
																																																																																	
*	packages/apps/BlackironSettings																																																																																
-	Blackiron:	Add	ability	to	toggle	bluetooth	battery	level	[2/2]	[Pranav	Vashi]																																																																						
-	Blackiron:	Network	traffic	mode	for	status	bar	[3/3]	[Pranav	Vashi]																																																																							
																																																																																	
																																																																																	
*	packages/apps/Settings																																																																																
-	Settings:	update	power	menu	action	[ralf979]																																																																											

