% !TeX program = pdflatex
% !BIB program = biber

\documentclass[12pt,a4paper]{article}

% Encoding and language
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage[british]{babel}

% Typography and page layout
\usepackage{newtxtext}
\usepackage{newtxmath}
\usepackage[
margin=1in,
includefoot
]{geometry}
\usepackage{microtype}
\usepackage{setspace}
\usepackage{textcomp}
\usepackage{enumitem}
\usepackage[style=american]{csquotes}
\usepackage{xurl}

% Chicago author-date citations
\usepackage[
authordate,
backend=biber,
dashed=false,
isbn=false,
doi=true,
url=true
]{biblatex-chicago}
\addbibresource{references.bib}
\biburlbigskip=0mu
\biburlnumskip=0mu
\biburlucskip=0mu
\biburllcskip=0mu

\usepackage[hidelinks]{hyperref}

% Paragraphs and spacing
\doublespacing
\frenchspacing
\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}
\setlength{\emergencystretch}{2em}

% Bibliography: single-spaced entries, blank line between entries
\AtBeginBibliography{\singlespacing}
\setlength{\bibitemsep}{\baselineskip}
\setlength{\bibhang}{0.5in}

% Heading hierarchy
\setcounter{secnumdepth}{3}
\setcounter{tocdepth}{2}

\setlist[itemize]{
	leftmargin=*,
	topsep=0.5\baselineskip,
	itemsep=0.25\baselineskip,
	parsep=0pt
}

\pagestyle{plain}

\title{Draft for discussion}
\author{Máté Mokrai}
\date{15 November 2026}

\begin{document}
	
	\maketitle
	\thispagestyle{plain}
	
	% ============================================================
	% 1. THE PUZZLE
	% ============================================================
	
	\section{The puzzle}
	
	The EU has no fiscal union. National budgets stay national, and member
	states remain divided over extending common fiscal powers and permanent
	risk-sharing. Many member states have been sceptical about broadening the
	integration towards anything that could be read as a ``transfer union''.
	Despite that, over the years, the EU has gained fiscal influence through
	bodies that sit outside the EU budget. The ECB took on sovereign risk
	through bond buying. The ESM lends to governments against capital put up
	by the member states. Banking union established common supervision and
	resolution arrangements, while further financial risk-sharing remained
	contested.
	
	The EIB belongs in this picture. There is a growing number of published
	works on it, but gaps remain. The EIB does not fund its own lending from
	the EU budget. It raises its money by selling bonds on the financial
	markets, and investors lend to it cheaply, at the best (AAA) rates, because
	the 27 member states own it. Each state has subscribed a share of the
	Bank's capital, but most of that capital is not paid in. It is
	``callable'': the states are legally obliged to pay it if the Bank ever
	needs it to meet its obligations. So the Bank borrows cheaply on the
	strength of the member states' promise, and then lends that money on to
	governments, regions and firms, or uses it to guarantee their loans. The
	risks it carries are backed in the end by the member states, and for some
	programmes by the EU budget. Over the years, the member states have
	widened what the EIB may finance and how much it may lend, without
	necessarily requiring additional paid-in capital.
	
	% ============================================================
	% 2. LITERATURE REVIEW
	% ============================================================
	
	\section{Literature review}
	
	\subsection{The broader literature}
	
	\subsubsection{The ECB}
	
	The ECB was not designed as a fiscal body. The Treaty forbids it from
	financing governments directly, and the original idea was that markets
	would discipline governments while the central bank stayed out of public
	finance \parencite{yiangou2013}. \textcite{degrauwe2013} argued that the
	ECB should act as lender of last resort in government bond markets, as
	central banks do in countries that borrow in their own currency, while
	\textcite{buiter2012} argued that the ECB was already performing this
	function while denying it, to avoid the charge of breaching the Treaty.
	Its programmes, the Securities Markets Programme, the promise of Outright
	Monetary Transactions and the cheap long-term loans to banks, brought
	government bond yields in Italy, Spain and Portugal down considerably
	\parencite{krishnamurthy2018}. In the pandemic, the ECB set up the Pandemic
	Emergency Purchase Programme to facilitate record fiscal deficits, a
	paradigm shift carried out without any legislative change
	\parencite{vantklooster2022}. In 2020, Eurosystem purchases absorbed around
	83 per cent of the increase in euro area government debt
	\parencite{bateman2024}. The literature keeps returning to one condition:
	a central bank backstop is credible when it enjoys fiscal backing, that
	is, when governments stand behind its possible losses
	\parencite{corsetti2016}. In the euro area no single treasury stands behind
	the ECB, so this backing is partial and contested.
	
	\subsubsection{The ESM and EFSF}
	
	The ESM and its predecessor, the EFSF, were set up as crisis lenders to
	euro-area governments that had lost market access. The EFSF was created
	in 2010 as a company under Luxembourg law, technically neither in the
	Commission nor in the Council, and it was initially charged with managing
	\texteuro{}440 billion in member-state guarantees. It was then replaced
	by a permanent bail-out institution, the ESM, inaugurated in October 2012
	\parencite{gocaj2013}. Germany and the Netherlands treated
	\texteuro{}500 billion of lending capacity as the absolute maximum, and
	much of the negotiation was about increasing the funds' capacity without
	raising member states' contributions or guarantees
	\parencite{smeets2019}. The design reflected what the largest contributor
	would accept. Germany backed intergovernmental loans tied to national
	reforms, and demanded the Fiscal Compact in return for access to the
	funds \parencite{donnelly2021}. More far-reaching proposals for permanent
	common debt and generalised grants were not adopted, even during the
	COVID-19 crisis, although NextGenerationEU introduced temporary common
	borrowing and grants \parencite{howarthquaglia2021}. Some national
	parliaments gained a say over each decision on financial assistance,
	which changed the bargaining between governments
	\parencite{moschella2017}. And the lenders took a senior position: the
	share of public debt held by preferred creditors such as the ESM rose
	substantially during the crisis, pushing private lenders into a junior
	position \parencite{steinkamp2014}. These articles showcase how the ESM
	expanded euro-area fiscal capacity while keeping its use subject to
	member-state control and conditionality.
	
	\subsubsection{Banking union}
	
	Banking union emerged between 2012 and 2014 as a significant transfer of
	national sovereignty to the EU's supranational institutions, above all the
	ECB, meant to sever the ties between banks and states
	\parencite{epstein2016}. It was planned on five components: a single
	rulebook, single supervision, a single framework for resolving failing
	banks, a common deposit guarantee scheme and a common fiscal backstop.
	Member states' positions on the resolution fund depended on whether they
	were likely to be net contributors to it
	\parencite{howarthquaglia2014}. Germany refused to accept a European
	Deposit Insurance Scheme, even after the Commission published its draft
	in November 2015 \parencite{howarthquaglia2018}. Germany and the Netherlands
	pushed for risk reduction in southern banking systems, while Italy pushed
	for more public backstops and state aid \parencite{donnelly2018}. For
	Germany, breaking the ``vicious circle'' between banks and sovereigns was
	the main objective, and its preferences were shaped by ordoliberal ideas
	\parencite{schaefer2016}. When Italy's failing banks were resolved in
	2016--17, the law was bent, and some of the discretion used was not
	entirely within EU law \parencite{donnellyasimakopoulos2020}. Governments
	accepted common rules and authorities, but remained reluctant to extend
	financial risk-sharing where national taxpayers could ultimately bear
	the costs.
	
	\subsubsection{What the EIB shares with them, and where it differs}
	
	The EIB shares with these institutions a role in expanding European
	financial capacity, but its mechanisms are different. Unlike the ECB, it
	cannot create money and instead raises funds on capital markets. Unlike
	the ESM, it is an established EU institution whose existing structure can
	be used to pursue new policy objectives. Banking union primarily
	centralises supervision and resolution, whereas the EIB provides
	investment finance through loans and guarantees. Its financial strength
	rests partly on member-state capital commitments, although losses do not
	automatically translate into national budgetary liabilities. The extent
	to which this financing constitutes fiscal capacity depends on how it
	enables the EIB to influence member states' fiscal policies, including
	through financing conditions and investment selection.
	
	\subsection{My literature, summarised}
	
	My literature review groups the EIB literature into three readings,
	compared on capability, conduct and control. The labels are mine.
	
	\begin{itemize}
		\item \textbf{Adaptive Bank (limited fiscal capacity):} banking logic
		wins. Even in the COVID-19 crisis the EIB kept to mainly low-risk lending
		through commercial banks, and its reforms were incremental change,
		``layering'', along an existing path \parencite{howarthkavvadia2024}.
		
		\item \textbf{Quasi-Fiscal Investment State (fiscal capacity):} the EIB
		has become a centre of gravity in the EU's long-standing attempts to
		increase its investment firepower, the nucleus of a ``somewhat hidden''
		European investment state whose reach is still to be determined
		\parencite{mertens2019}. The EIB sits among the EU's off-balance-sheet
		fiscal agencies, which give policymakers room to pursue public goals
		outside the budget \parencite{gutersandu2022}.
		
		\item \textbf{Financialised State (no fiscal capacity of its own):} the
		off-balance-sheet approach turns governments into risk managers in the
		service of private investors \parencite{braun2018}, and fiscally
		constrained states ``derisk'' private investment instead of spending
		directly \parencite{gabor2025}.
	\end{itemize}
	
	My position is a qualified Quasi-Fiscal Investment State reading. There
	is a growing number of published works on the EIB, but gaps remain. The
	papers reviewed do not directly measure the EIB's influence over member
	states' fiscal policies as defined here. These readings offer competing
	perspectives through which to interpret the EIB's role.
	
	% ============================================================
	% 3. THE STRUCTURE OF THE ESSAY
	% ============================================================
	
	\section{The structure of the essay}
	
	\subsection{Theoretical approach: historical institutionalism}
	
	I am considering historical institutionalism to examine how the EIB's
	existing arrangements shape responses to new pressures and how successive
	decisions affect its subsequent role.
	
	\begin{itemize}
		\item \textbf{Earlier arrangements and path dependence:}
		The EIB's mandate, capital and lending rules condition the responses
		available to governments. The question is whether earlier decisions make
		particular routes easier to pursue and alternatives harder to adopt.
		\textcite{verdun2015} examines inherited institutional arrangements in the
		euro-area crisis response, while \textcite{howarthkavvadia2024} examine
		continuity and incremental change in the EIB's COVID-19 lending.
		
		\item \textbf{Timing and sequencing:}
		The order of pressures, institutional changes and financing decisions
		matters. \textcite{gocaj2013} examine how earlier crisis decisions shaped
		the options available in subsequent responses.
		
		\item \textbf{Feedback and institutional change:}
		Responses to immediate demands can generate consequences that shape later
		choices \parencite{jones2016}. Critical junctures and layering may help
		explain particular changes where the evidence supports them, rather than
		being assumed features of every response
		\parencite{gocaj2013,streeck2005}.
	\end{itemize}
	
	\subsection{Research question}
	
	How and to what extent do responses to internal and external pressures,
	when routed through the European Investment Bank, shape the Bank's
	influence over member states' fiscal policies, and how does national
	fiscal space condition that influence?
	
	\subsection{Hypothesis}
	
	When responses to internal or external pressures are routed through the
	EIB, the Bank's fiscal capacity, understood as its influence over member
	states' fiscal policies, is expected to grow more in member states with
	tighter fiscal constraints than in those with greater fiscal space.
	
	This does not imply that fiscally comfortable states avoid the EIB. The
	expectation concerns how consequential its involvement becomes for
	national fiscal choices.
	
	The fiscal-space expectation rests on the argument that governments
	facing tighter constraints have fewer financing alternatives, making the
	terms and availability of EIB support potentially more consequential.
	
	\subsection{The chain}
	
	Internal or external pressure \(\rightarrow\) institutional response
	through the EIB \(\rightarrow\) financing instruments and institutional
	decisions \(\rightarrow\) fiscal influence, with national fiscal space
	moderating the relationship.
	
	\begin{itemize}
		\item \textbf{Independent variable: pressure}
		\begin{itemize}
			\item An event, political initiative or institutional decision that calls for a
			European response. It is external when it comes from outside the EU and
			internal when it comes from EU institutions or member states, and it need
			not be a crisis. Examples include the war in Ukraine in 2022, COVID-19 in
			2020 and the G20 review of multilateral development banks' capital
			adequacy in 2022, an external institutional initiative that the EIB links
			to its later Statute amendment. Each pressure is dated when it is first
			documented and distinguished from the institutional decisions taken in
			response to it.
		\end{itemize}
		
		\item \textbf{Mechanism: the choice of the EIB route, including steering}
		\begin{itemize}
			\item Governments respond through an institution that already exists.
			Political actors put forward priorities and proposals, but these do not
			automatically become financing. The EIB assesses operations and its Board
			of Directors decides on financing, with formal roles for the Commission
			and the member state concerned. These procedures can filter and
			condition the investment supported. The research would examine how this
			authority is exercised and whether it influences national financing and
			investment decisions. The Bank's financing terms may make its involvement
			more consequential where governments face tighter constraints.
		\end{itemize}
		
		\item \textbf{Financing instruments}
		\begin{itemize}
			\item Loans, guarantees and their conditions, including how financial risks are
			allocated between the EIB, borrowers and any national or EU-level backing
			arrangements.
		\end{itemize}
		
		\item \textbf{Dependent variable: fiscal capacity}
		\begin{itemize}
			\item The EIB's influence over member states' fiscal policies. The research
			would investigate this influence through financing relationships and
			evidence of national policy choices shaped by EIB involvement. Its precise
			operationalisation remains to be developed.
		\end{itemize}
		
		\item \textbf{Moderator: national fiscal space}
		\begin{itemize}
			\item Government debt and deficit as percentages of GDP, the ten-year sovereign
			borrowing spread over Germany and excessive deficit procedure status
			would describe national fiscal circumstances. Each indicator would be
			considered separately, using its value before a financing decision to
			investigate whether fiscal constraints condition reliance on the EIB.
			Their subsequent development would also be followed as part of the
			empirical investigation below.
		\end{itemize}
		
		\item \textbf{Scope}
		\begin{itemize}
			\item The EU-27 over 2020--2026, focusing on EIB operations with governments and
			other public-sector bodies. Defence provides the empirical application,
			with earlier observations used where helpful for comparison. Private
			defence-industry financing is outside the scope.
		\end{itemize}
	\end{itemize}
	
	\subsection{Investigating fiscal capacity: proposed approach}
	
	I would examine how national fiscal circumstances and expenditure in the
	selected policy area develop over time, alongside the timing and extent
	of EIB involvement. Financing records and evidence of institutional
	decisions would help investigate whether, and how, the EIB influences
	national fiscal choices. The precise measures and the approach to
	attributing changes to EIB involvement remain to be developed.
	
	\begin{itemize}
		\item \textbf{Fiscal circumstances and their development:}
		Debt, deficits, sovereign borrowing spreads and excessive deficit
		procedure status would be tracked alongside expenditure and EIB
		financing. Their earlier values describe the conditions under which
		governments seek financing; their later development helps examine what
		happens during and after EIB involvement. Changes in these indicators
		would not independently establish an EIB effect. Nor must influence appear
		as improved fiscal indicators: EIB involvement may enable or shape
		investment while expenditure or debt rises.
		
		\item \textbf{Financing significance:}
		One possible approach is to examine EIB financing relative to national
		expenditure in the policy area, country by country and year by year.
		\textcite{bateman2024} provide a precedent for examining institutional
		financing relative to a fiscal aggregate through their analysis of
		central-bank purchases against increases in government debt.
		\textcite{howarthkavvadia2024} examine the composition of EIB lending using
		the Bank's statistics. These approaches could inform the investigation,
		although neither directly measures the fiscal influence proposed here.
		Total expenditure and investment would remain distinct, as would signed
		financing, disbursements and guarantee exposures.
		
		\item \textbf{Institutional steering:}
		Project records, eligibility requirements, approval conditions and
		published Board minutes could help investigate how EIB involvement shapes
		supported investment. Changes between proposals and signed operations
		would require explanation rather than automatically being treated as
		evidence of steering. Interviews could supplement documentary evidence
		where access allows. The availability of evidence on rejected proposals
		or internal deliberations remains a limitation.
		
		\item \textbf{The off-budget part:}
		The EIB's balance sheet is distinct from national government accounts,
		and the treatment of individual operations depends on the borrower and
		financing arrangement. The investigation would distinguish lending to
		general government from financing of public entities statistically
		classified outside it, and distinguish direct financing from contingent
		risk-bearing. A defensible method for capturing the resulting fiscal
		influence remains to be developed. Possible starting points include the
		classification of contingent liabilities in \textcite{polackova1998}, the
		interconnected balance-sheet approach of \textcite{gutersandu2022} and the
		institutional mapping in \textcite{laudage2026}. These could help identify
		where financing and risks sit, but would need further evidence to
		establish influence over national policy.
	\end{itemize}
	
	\subsection{Broader contribution: EU fiscal integration}
	
	The research asks whether growing EIB influence over national fiscal
	choices could represent an incremental step towards further EU fiscal
	integration without a comprehensive fiscal union. This connects to work
	examining how successive institutional responses can deepen integration
	through incomplete arrangements \parencite{jones2016}. The relevant
	question is whether EIB involvement creates more durable EU-level
	influence over national financing and investment decisions. It could also
	support common priorities while preserving substantial national control.
	The defence case would help investigate these possibilities, with any
	implications for other policy areas assessed in light of their
	institutional differences.
	
	% ============================================================
	% 4. CASE STUDY
	% ============================================================
	
	\section{Case study: defence}
	
	\subsection{Why defence}
	
	The war in Ukraine is the clearest recent pressure. EU-27 defence
	spending reached \texteuro{}418 billion in 2025 (2.2\% of GDP) and is
	projected at \texteuro{}454 billion in 2026 (2.4\%). Recent reporting
	highlights the challenge of financing higher European defence expenditure
	within national fiscal constraints. This makes defence a timely case for
	examining the EIB's role: how its financing develops alongside national
	spending, how governments use it and whether its significance differs
	according to their fiscal circumstances. The EIB operates alongside other
	European defence financing initiatives, including SAFE, the
	\texteuro{}150 billion defence loan programme managed by the European
	Commission and adopted in May 2025. The study would consider SAFE as an
	alternative source of financing while keeping its loans separate from EIB
	financing in the analysis.
	
	In 2025, after EU leaders called on the Bank in March, the EIB broadened
	eligibility and turned its Strategic European Security Initiative into a
	permanent security and defence policy goal. EIB Group security and defence
	financing rose from \texteuro{}1.2 billion in 2024 to \texteuro{}4.4 billion
	in 2025, around 5\% of its financing inside the EU, and the target for 2026
	is \texteuro{}4.5 billion. These are Group totals, and the clients include
	public authorities, companies, financial institutions, and equity or
	guarantee providers. My analysis uses only the public-sector operations.
	Weapons and ammunition remain excluded.
	
	\subsection{Case hypothesis}
	
	EIB defence loans and guarantees are expected to become more significant
	relative to national defence spending over time, particularly in fiscally
	constrained states, where their availability and conditions may have
	greater influence over national financing and investment decisions.
	
	\subsection{Proposed comparison}
	
	The study compares EU member states over 2020--2026, examining whether EIB
	defence financing becomes more significant relative to national defence
	spending in countries facing tighter fiscal constraints. It tracks how
	these differences evolve alongside changes in national fiscal
	circumstances and the use of EIB financing.
	
	This places the study in comparative politics by comparing national
	financing responses within a shared European institutional setting. The
	analysis follows the sequence from the war in Ukraine in 2022 through
	changes in EIB financing opportunities to their uptake by national
	governments.
	
	\subsection{Research design for the case}
	
	\begin{itemize}
		\item \textbf{Country-year comparison:}
		Track national defence expenditure and investment alongside EIB
		public-sector defence financing over 2020--2026, relating their development
		to each country's debt, deficit, sovereign borrowing spread and excessive
		deficit procedure status.
		
		\item \textbf{Financing significance:}
		Examine EIB financing relative to national defence expenditure and its
		increase after 2022. Keep loans and guarantees separate and distinguish
		signed financing from disbursements. The baseline for measuring
		expenditure growth remains to be determined.
		The coverage of the EIB financing series would depend on available project
		records; missing observations would be distinguished from confirmed zero
		financing.
		
		\item \textbf{Institutional steering:}
		Examine project records, eligibility rules and financing conditions to
		investigate how EIB involvement shapes national investment decisions.
		Interviews could supplement the documentary evidence where access allows.
	\end{itemize}
	
	Figures for 2026 would be identified as completed observations, budgets,
	projections, targets or year-to-date amounts, as appropriate. These are
	proposed approaches to investigating fiscal influence; the precise
	operationalisation remains to be developed.
	
	\subsection{Sources for the case study}
	
	% Source annotations retained from the Word document.
	% Complete publication details and URLs appear in References.
	
	\begin{itemize}
		\item \textcite{eda2026}, \citetitle{eda2026}, 16 July 2026.
		EU-27 defence spending in 2025 and the 2026 projection (p.~4).
		
		\item \textcite{odstrcilova2026}, \citetitle{odstrcilova2026},
		\emph{EU Perspectives}, 9 November 2026.
		The end of temporary flexibility in 2028, the call to prepare, and the
		pointer to joint purchases and SAFE.
		
		\item \textcite{bonini2026}, \citetitle{bonini2026},
		\emph{Eunews}, 9 November 2026.
		Italy's defence flexibility.
		
		\item \textcite{commission2026}, \citetitle{commission2026},
		29 October 2026.
		SAFE as EU lending of \texteuro{}150 billion, adopted in May 2025.
		
		\item \textcite{eib2026}, \citetitle{eib2026}, 6 May 2026.
		The permanent security and defence goal replacing SESI, financing in
		2024 and 2025, the 2026 target, the range of clients and the exclusion
		of weapons (pp.~23--24).
	\end{itemize}
	
	% ============================================================
	% REFERENCES
	% ============================================================
	
	\clearpage
	\printbibliography[
	heading=bibintoc,
	title={References}
	]
	
\end{document}
