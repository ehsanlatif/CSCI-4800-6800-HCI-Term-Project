## Related Work
The history of collaborative porgamming can be traced back to decades [[1]](#1), when the first time collaboration considered an essential part of programming learning. Since then, operational and applicable collaborative systems have been developed and widely used.

To ensure the usefulness of an interactive, real-time, constructive collaborative programming system, two aspects are needed: one is how to design or select a reliable and valid interaction used by the system, and the other is how to maintain the log/history of edits in system to support students learning and teachers' instructions. Students' written scripts, tests, inquiry activities, and interactions and collaborations also realize acollaboration,  feedback, and guidance through the synchronization frameworks[[2]](#2).

These diverse collaborative programing tools need well-designed systems to link the collaboration information to learning. Greller and Drachsler[[3]](#3) proposed a generic framework for the learning analytics process. They identified six dimensions that can also be used as a checklist for a system design: 
1. Stakeholders - what are the data subjects and clients,
2. Objectives - what does the information from the data contribute to,
3. Data - the protection and open access of different educational data,
4. Instruments - what educational services are provided to support the objectives of educational stakeholders,
5. External limitations - the fairness, privacy, and other application environment considerations as the system collecting and using data,
6. Internal limitations - the required competencies as the clients using the system. 

Among the six dimensions, stakeholders, objectives, and instruments are preset by the system designer, while the other three dimensions, data, external and internal limits, are gradually determined during the design, development, and implementation process. 

High drop-out rates are observed at the university level as a result of the existing exam system, with students either quitting school or changing their majors. Additionally, a significant gender discrepancy is evident. In turn, society now faces a rising lack of qualified programmers. A weekly course where students learn from and teach one another has been formed using the COOL (cooperative open learning)[[4]](#4) concept as a means of addressing this. The course emphasizes software development and applies the peer-learning and peer-teaching COOL idea. It will need more data to establish a link between the program's implementation and the reduced dropout rate.

The use of pair programming as a component of the learning and evaluation process for introductory programming is discussed in an action research study [[5]](#5). In order to assess the effects of pair programming on student performance and confidence in programming, as well as to acquire insights into its real-world applications, module data has been used across a three-year cycle. Within-subject research supports earlier findings that overall student performance has improved. In particular, pairwise communication, creating dispute resolution protocols, and the development of professional abilities are areas where the actual implementation of pair programming for learning and evaluation needs to be improved, according to qualitative study.

By enabling users to alter and update content for a specific syllabus, open educational resources (OERs) address these issues. An openly accessible educational resource (OER)[[6]](#6) can simply be defined as a free textbook. With a focus on collaboration and idea sharing, the Atelier project[[7]](#7) intends to provide an online platform that fosters an environment similar to an atelier. It was developed for the Community of Practice made up of University of Twente students, student assistants, and instructors who teach Processing programming in the first year of the bachelor's program in Creative Technology (CreaTe). CreaTe is a design tool with a foundation in electrical and computer engineering. It highlights the value it placed on individual innovation, ingenuity, cross-disciplinary teams, experimenting, and reflection in its own design culture. The purpose of Atelier is to promote the growth of a community of practice in which in-person training is an essential element. It is not intended to replace one-on-one tutoring, on purpose.

Software development can be carried out utilizing a variety of approaches. The majority involve standard edit-compile-run cycles. However, some people employ interactive non-coding settings or even live programming environments [[8]](#8). File management capabilities (naming, versioning, paths on the file system), editing support (refactoring, auto-completion, etc.), and runtime safety features (type systems in programming languages, assertion mechanisms, unit-testing affordances, etc.) are all examples of system support features.
Live programming environments add additional liveness to complement traditional features[[9]](#9). In some cases, liveness can help a programmer write program code more quickly by providing semantic feedback. As opposed to a slower, laborious rate brought on by the burden of additional required operations on the side of the programmer, this may assist the human communicate thoughts at a rate closer to the rate of thought.

### Comparison Table
Table below indicates the significant features of existing solutions:
| Solution      |   Problem Addressed   | pros  | Cons | Guidelines/Principles |
| ------------------ |---------------------- | ----- | ---- | --------------------- |
| COOL[[4]](#4)         | Peer-learning         | Easy programming, Fill gender-gap | One way of programming practice | Seek universal usability |
| Pair Programming[[5]](#5)     | Programing learning challanges | Pair programming used as part of the learning  | Traditional windows programming considered | Principles of pair programming and Collaboration |
| Open educational resources (OERs)[[6]](#6) | Comprehensive programming resource | Allowing students to update and customize materials | Can cause conflict of interest among conventional teacher and students | Keep users in control|
| Atelier [[7]](#7) | Collaborative programming tool | Autonomous design, creative thinking, multidisciplinary teams, tinkering and reflection | Missing real-time programming  | Community of Practice |

## References
<a id="1">1.</a> 
John T. Nosek. 1998. The case for collaborative programming. Commun. ACM 41, 3 (March 1998), 105–108. https://doi.org/10.1145/272287.272333

<a id="2">2.</a>
Heisawn Jeong, Cindy E. Hmelo-Silver, Kihyun Jo, Ten years of Computer-Supported Collaborative Learning: A meta-analysis of CSCL in STEM education during 2005–2014, Educational Research Review.

<a id="3">3.</a>
Greller & Drachsler. (2012). Translating learning into numbers: A generic framework for learning analytics. Journal of Educational Technology & Society.

<a id="4">4.</a>
Corinna Kröhn, Sara Hinterplattner, and Barbara Sabitzer. 2020. Towards an Implementation of a Peer-Learning and Peer-Teaching Group in Programming. In Proceedings of the 2020 ACM Conference on Innovation and Technology in Computer Science Education (ITiCSE '20). Association for Computing Machinery, New York, NY, USA, 559. https://doi-org.proxy-remote.galib.uga.edu/10.1145/3341525.3393971

<a id="5">5.</a>
Ian McChesney. 2016. Three Years of Student Pair Programming: Action Research Insights and Outcomes. In Proceedings of the 47th ACM Technical Symposium on Computing Science Education (SIGCSE '16). Association for Computing Machinery, New York, NY, USA, 84–89. https://doi-org.proxy-remote.galib.uga.edu/10.1145/2839509.2844565

<a id="6">6.</a>
Cengiz Günay and Anca Doloc-Mihu. 2021. An Open Educational Resource for an Agile Software Engineering Course. In Proceedings of the 22st Annual Conference on Information Technology Education (SIGITE '21). Association for Computing Machinery, New York, NY, USA, 51–52. https://doi-org.proxy-remote.galib.uga.edu/10.1145/3450329.3476849

<a id="7">7.</a>
Ansgar Fehnker, Angelika Mader, Arthur Rump, Margot Rutgers, Lotte Steenmeijer, and Chris Witteveen. 2020. Atelier: an online platform for programming tutorials. In Proceedings of the 9th Computer Science Education Research Conference (CSERC '20). Association for Computing Machinery, New York, NY, USA, Article 15, 1–2. https://doi-org.proxy-remote.galib.uga.edu/10.1145/3442481.3442511

<a id="8">8.</a>
Tomas Petricek. 2019. Histogram: You have to know the past to understand the present. University of Kent. http://tomasp.net/histogram/

<a id="9">9.</a>
Hans J. Scholl. 2019. Overwhelmed by brute force of nature: First response management in the wake of a catastrophic incident. In EGOV 2019, I. Lindgren et al (Ed.). Vol. LNCS 11685. Springer Nature Switzerland AG, 105–124.
