# UbiComp and IMWUT reading notes

## A1 Pro2Assist 2026
This system paper makes its procedural-assistance gap concrete before introducing perception, context extraction, and reasoning modules. It evaluates overall behavior, component contributions, out-of-domain behavior, overhead, and user experience separately [pro2]. Adopted here: connect each design challenge to a module and an evaluation; distinguish timing from task understanding. Boundary: individual procedural assistance does not establish team-level physiological value. Full-text reading focus: Introduction, Background and Motivation, System Design, Evaluation, Discussion and Limitations.
## A2 DeepFeature 2026
The paper uses a motivation study to identify context-specific feature selection and implementation problems, then evaluates generation, verification, refinement, ablations, sensitivity, and overhead [deep]. Adopted here: show why each proposed component is necessary and test it independently. Boundary: biosignal prediction performance on its tasks is not evidence for social-need inference. Full-text reading focus: Motivation Study, Framework Design, Experimental Evaluation, Discussion.
## A3 Human Heterogeneity Invariant Stress Sensing 2025
The paper links a deployment problem to inter- and intra-person physiological variation and compares in- and out-of-distribution performance, with ablation and platform-level runtime evidence [hhiss]. Adopted here: unseen-team testing, explicit variability, and resource measurements. Boundary: stress generalization does not validate social-intent labels. Full-text reading focus: dataset descriptions, heterogeneity motivation, framework, evaluation, discussion.
## A4 CRoP 2025
The paper formalizes within-person context change separately from ordinary personalization and evaluates its approach across datasets, alternative mechanisms, and runtime [crop]. Adopted here: define what is held out, what personalization data are available, and how context changes affect evaluation. Boundary: a personalized model is not automatically robust across collaborative tasks. Full-text reading focus: Motivation, Problem Statement, Approach, Experiments, Empirical Justification, Ablation, Runtime and Limitations.
## A5 Animo 2019
The system design is followed by an in-situ study, usage evidence, and qualitative findings about connection and interpretation [p38]. Adopted here: describe what users actually do with a sensing interface and retain mismatches in meaning as findings. Boundary: lightweight social connection is distinct from task coordination or intervention efficacy. Full-text reading focus: System, Methods, Results, Discussion.
## A6 Exploring User Expectations of Proactive AI Systems 2020
The paper defines levels of proactivity, captures expectations in context, and interprets differences by use case and user characteristics [expect]. Adopted here: make initiative and user choice explicit and investigate assistance in its intended situation. Boundary: reported preferences do not alone establish behavioral effectiveness. Full-text reading focus: Terminology, Capturing User Expectations, Dataset, Findings, Discussion.
## A7 Opportune Moments for Proactive Interactions with Smart Speakers 2020
The study uses a purpose-built experience-sampling device, pilot tests, field collection, and activity coding to investigate interruptibility in domestic routines [speaker]. Adopted here: study timing and channel availability, including social context, before selecting an intervention policy. Boundary: domestic conversational availability is not a ready-made teamwork policy. Full-text reading focus: Methods, Activity Categorization, Results, Discussion.
## A8 Detection of Artifacts in Ambulatory Electrodermal Activity Data 2020
The paper builds a labeled dataset, distinguishes artifact detection from overall signal quality, compares alternatives, and discusses segmentation and annotation limitations [artifacts]. Adopted here: report usable coverage, annotation disagreement, and quality failure before psychological interpretation. Boundary: clean EDA is a measurement requirement, not proof of a support need. Full-text reading focus: Dataset, annotation and detection methods, evaluation, Limitations and Future Work.
## A9 Calm Commute 2020
The controlled intervention study specifies conditions, apparatus, hypotheses, physiological measures, task performance, and safety-related outcomes [calm]. Adopted here: measure whether support interferes with the ongoing task and separate manipulation checks from intervention effects. Boundary: findings from a closed driving circuit cannot establish outcomes in XR teams. Full-text reading focus: Methodology, Analysis and Results, Discussion, Limitations.
## A10 StressSense 2012
The paper begins with a concrete sensing deployment challenge and evaluates adaptation across speakers and acoustic environments, alongside a smartphone implementation [stresssense]. Adopted here: justify variability handling through the intended deployment and evaluate feasible operation. Boundary: voice-based stress sensing is not direct peripheral physiology and is not a social-behavior decoder. Full-text reading focus: Introduction, system and model adaptation, evaluation, implementation and conclusion.
# B Claim and Evidence Boundaries
Multimodal sensing can support individual assistance. Direct precedents: Pro2Assist, GuideAI, AwareLLM, and Sensing What Surveys Miss {pro2,guide,aware,sensing}. Boundary: these findings do not establish the proposed multi-human policy.
Interpersonal physiological patterns can inform analysis of collaboration. Direct and synthesis evidence: coupling, shared arousal, teammate prediction, and multimodal collaboration studies {p8,p18,p52,p57}. Boundary: association and prediction do not prove that a prompt is warranted.
Synchrony requires contextual interpretation. Evidence includes critical and systematic reviews and the 2026 medical-dyad study {p32,p49,p44,p23,huang}. Boundary: do not equate synchrony with agreement, learning, or successful teamwork.
Medical sensing and debriefing have substantial precedent. Evidence includes VR teamwork assessment, VORTeX, a debriefing dashboard, and physiological simulation studies {p66,p4,p26,p67,p69}. Boundary: a dashboard evaluation is not a prospective trial of trainee learning.
Educational support must be evaluated at the learner and group levels. Evidence includes shared-regulation, scaffolding, ICAP, and learning-performance research {p29,p51,p10,p62}. Boundary: assisted task completion is not retained independent capability.
The proposed contribution remains a hypothesis. The primary test is whether multi-person physiology improves decisions and outcomes beyond an otherwise comparable behavioral agent. The contribution must be revised if the results show redundancy, unacceptable burden, or harmful interventions.


## Source reference keys

[p3] Saleema Amershi, Dan Weld, Mihaela Vorvoreanu, Adam Fourney, Besmira Nushi, Penny Collisson, Jina Suh, Shamsi Iqbal, Paul N. Bennett, Kori Inkpen, Jaime Teevan, Ruth Kikin-Gil, and Eric Horvitz. 2019. Guidelines for Human-AI Interaction. In Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery, 1–13. https://doi.org/10.1145/3290605.3300233

[calm] Stephanie Balters, Matthew L. Mauriello, So Yeon Park, James A. Landay, and Pablo E. Paredes. 2020. Calm Commute: Guided Slow Breathing for Daily Stress Management in Drivers. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 4, 1, Article 38 (2020), 1-19. https://doi.org/10.1145/3380998

[p4] Jacob Barker, Doga Demirel, Cullen Jackson, Anna Johansson, Robbin Miraglia, Darian Hoagland, Stephanie B. Jones, John Mitchell, Daniel B. Jones, and Suvranu De. 2026. Integrating virtual reality and large language models for team-based non-technical skills training and evaluation in the operating room. npj Digital Surgery 1, 1, Article 10 (2026). https://doi.org/10.1038/s44484-026-00009-3

[p6] Karen L. Blackmore, Shamus P. Smith, Jacqueline D. Bailey, and Benjamin Krynski. 2024. Integrating Biofeedback and Artificial Intelligence into eXtended Reality Training Scenarios: A Systematic Literature Review. Simulation & Gaming 55, 3 (2024), 445–478. https://doi.org/10.1177/10468781241236688

[speaker] Narae Cha, Auk Kim, Cheul Young Park, Soowon Kang, Minkyu Park, Jae-Gil Lee, Sangsu Lee, and Uichin Lee. 2020. Hello There! Is Now a Good Time to Talk?: Opportune Moments for Proactive Interactions with Smart Speakers. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 4, 3, Article 74 (2020), 1-28. https://doi.org/10.1145/3411810

[p8] Guillaume Chanel, Mireille Betrancourt, Thierry Pun, Donato Cereghetti, and Gaelle Molinari. 2013. Assessment of Computer-Supported Collaborative Processes Using Interpersonal Physiological and Eye-Movement Coupling. In 2013 Humaine Association Conference on Affective Computing and Intelligent Interaction. IEEE, 116–122. https://doi.org/10.1109/acii.2013.26

[p9] Adam Cheng, Walter Eppich, Vincent Grant, Jonathan Sherbino, Benjamin Zendejas, and David A Cook. 2014. Debriefing for technology‐enhanced simulation: a systematic review and meta‐analysis. Medical Education 48, 7 (2014), 657–666. https://doi.org/10.1111/medu.12432

[p10] Michelene T. H. Chi, and Ruth Wylie. 2014. The ICAP Framework: Linking Cognitive Engagement to Active Learning Outcomes. Educational Psychologist 49, 4 (2014), 219–243. https://doi.org/10.1080/00461520.2014.965823

[p11] Francesco Chiossi, Robin Welsch, Steeven Villa, Lewis Chuang, and Sven Mayer. 2022. Virtual Reality Adaptation Using Electrodermal Activity to Support the User Experience. Big Data and Cognitive Computing 6, 2 (2022), 55. https://doi.org/10.3390/bdcc6020055

[p13] Simon Cooper, Robyn Cant, Joanne Porter, Ken Sellick, George Somers, Leigh Kinsman, and Debra Nestel. 2010. Rating medical emergency teamwork performance: Development of the Team Emergency Assessment Measure (TEAM). Resuscitation 81, 4 (2010), 446–452. https://doi.org/10.1016/j.resuscitation.2009.11.027

[p14] Mutlu Cukurova, Rose Luckin, Eva Millán, and Manolis Mavrikis. 2018. The NISPI framework: Analysing collaborative problem-solving from students' physical interactions. Computers & Education 116 (2018), 93–109. https://doi.org/10.1016/j.compedu.2017.08.007

[p15] Belle Dang, Luna Huynh, Faaiz Gul, Carolyn Rosé, Sanna Järvelä, and Andy Nguyen. 2025. Human– AI collaborative learning in mixed reality: Examining the cognitive and socio‐emotional interactions. British Journal of Educational Technology 56, 5 (2025), 2078–2101. https://doi.org/10.1111/bjet.13607

[gaze] Valdemar Danry, Javier Hernandez, Andrew Wilson, Pattie Maes, and Judith Amores. 2026. From Gaze to Guidance: Interpreting and Adapting to Users' Cognitive Needs with Multimodal Gaze-Aware AI Assistants. Accepted paper, ACM Symposium on User Interface Software and Technology (UIST 2026); author version arXiv:2604.08062. https://arxiv.org/abs/2604.08062

[p18] Muhterem Dindar, Sanna Järvelä, Andy Nguyen, Eetu Haataja, and Ahsen Çini. 2022. Detecting shared physiological arousal events in collaborative problem solving. Contemporary Educational Psychology 69, Article 102050 (2022). https://doi.org/10.1016/j.cedpsych.2022.102050

[p21] Milou A. Feijt, Joyce H.D.M. Westerink, Yvonne A.W. De Kort, and Wijnand A. IJsselsteijn. 2023. Sharing biosignals: An analysis of the experiential and communication properties of interpersonal psychophysiology. Human–Computer Interaction 38, 1 (2023), 49–78. https://doi.org/10.1080/07370024.2021.1913164

[artifacts] Shkurta Gashi, Elena Di Lascio, Bianca Stancu, Vedant Das Swain, Varun Mishra, Martin Gjoreski, and Silvia Santini. 2020. Detection of Artifacts in Ambulatory Electrodermal Activity Data. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 4, 2, Article 44 (2020), 1-31. https://doi.org/10.1145/3397316

[p23] Ilanit Gordon, and Ronny P. Bartsch. 2026. Correlates of interpersonal physiological synchrony and sources of empirical heterogeneity. Nature Reviews Psychology 5, 3 (2026), 201–215. https://doi.org/10.1038/s44159-026-00535-4

[p25] Eetu Haataja, Jonna Malmberg, Muhterem Dindar, and Sanna Järvelä. 2022. The pivotal role of monitoring for collaborative problem solving seen in interaction, performance, and interpersonal physiology. Metacognition and Learning 17, 1 (2022), 241–268. https://doi.org/10.1007/s11409-021-09279-3

[p26] Bryan Harmer, Jacob Erickson, Shane Ross, Dhruv Bhatnagar, Stephen Dowker, Hyunmin Park, Alanson P. Sample, Sarah Hartley, James Cooke, Michael Cole, and Vitaliy Popov. 2026. Development and Evaluation of a Multimodal Debriefing Dashboard for Virtual Reality Cardiac Arrest Simulation. Simulation in Healthcare: The Journal of the Society for Simulation in Healthcare 21, 1 (2026), 48–56. https://doi.org/10.1097/sih.0000000000000901

[p27] Yugo Hayashi. 2020. Gaze awareness and metacognitive suggestions by a pedagogical conversational agent: an experimental investigation on interventions to support collaborative learning process and performance. International Journal of Computer-Supported Collaborative Learning 15, 4 (2020), 469–498. https://doi.org/10.1007/s11412-020-09333-3

[huang] Xiaoshan Huang, Conrad Borchers, Jiayi Zhang, and Susanne P. Lajoie. 2026. Physiological and Semantic Patterns in Medical Teams Using an Intelligent Tutoring System. Accepted short paper, International Conference on Artificial Intelligence in Education (AIED 2026); author version arXiv:2603.29950. https://arxiv.org/abs/2603.29950

[p29] Sanna Järvelä, Andy Nguyen, and Allyson Hadwin. 2023. Human and artificial intelligence collaboration for socially shared regulation in learning. British Journal of Educational Technology 54, 5 (2023), 1057–1076. https://doi.org/10.1111/bjet.13325

[p31] Manu Kapur. 2008. Productive Failure. Cognition and Instruction 26, 3 (2008), 379–424. https://doi.org/10.1080/07370000802212669

[crop] Sawinder Kaur, Avery Gump, Yi Xiao, Jingyu Xin, Harshit Sharma, Nina R. Benway, Jonathan L. Preston, and Asif Salekin. 2025. CRoP: Context-wise Robust Static Human-Sensing Personalization. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 9, 2 (2025), 1-34. https://doi.org/10.1145/3729483

[p32] Sadaf Kazi, Salar Khaleghzadegan, Julie V. Dinh, Mark J. Shelhamer, Adam Sapirstein, Lee A. Goeddel, Nnenna O. Chime, Eduardo Salas, and Michael A. Rosen. 2021. Team Physiological Dynamics: A Critical Review. Human Factors: The Journal of the Human Factors and Ergonomics Society 63, 1 (2021), 32–65. https://doi.org/10.1177/0018720819874160

[feeling] Jeonghyun Kim, Yugyeong Jung, Junmo Lee, Kwangyoung Lee, Hwajung Hong, and Uichin Lee. 2026. When Feeling and Physiology Diverge: Understanding Dual-Indicator Stress Sensemaking and Micro-Interventions in an Emotional-Labor Workplace. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 10, 2, Article 49 (2026), 1-46. https://doi.org/10.1145/3810198

[p34] Geonsun Lee, Dae Yeol Lee, Guan-Ming Su, and Dinesh Manocha. 2024. “May I Speak?”: Multi-Modal Attention Guidance in Social VR Group Conversations. IEEE Transactions on Visualization and Computer Graphics 30, 5 (2024), 2287–2297. https://doi.org/10.1109/tvcg.2024.3372119

[p35] Xiaoran Li, Wanqing Hu, Yanyan Li, and Ziqi Mao. 2023. Exploring what synchronized physiological arousal can reveal about the social regulatory process in a collaborative argumentation activity. Frontiers in Psychology 13, Article 1042970 (2023). https://doi.org/10.3389/fpsyg.2022.1042970

[p37] Zhidian Lin, Allison Jing, Ziyuan Qu, Fabio Zambetta, and Ryan M. Kelly. 2026. Mapping the Landscape of Affective Extended Reality: A Scoping Review of Biodata-Driven Systems for Understanding and Sharing Emotions. In Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery, 1–30. https://doi.org/10.1145/3772318.3791012

[sensing] Ailin Liu, Yesmine Karoui, Fiona Draxler, Frauke Kreuter, and Francesco Chiossi. 2026. Sensing What Surveys Miss: Understanding and Personalizing Proactive LLM Support by User Modeling. In Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery. https://doi.org/10.1145/3772318.3791191

[p39] Fannie Liu, Chunjong Park, Yu Jiang Tham, Tsung-Yu Tsai, Laura Dabbish, Geoff Kaufman, and Andrés Monroy-Hernández. 2021. Significant Otter: Understanding the Role of Biosignals in Communication. In Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery, 1–15. https://doi.org/10.1145/3411764.3445200

[p38] Fannie Liu, Mario Esparza, Maria Pavlovskaia, Geoff Kaufman, Laura Dabbish, and Andrés Monroy-Hernández. 2019. Animo: Sharing Biosignals on a Smartwatch for Lightweight Social Connection. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 3, 1 (2019), 1–19. https://doi.org/10.1145/3314405

[deep] Kaiwei Liu, Yuting He, Bufang Yang, Mu Yuan, Chun Man Victor Wong, Ho Pong Andrew Sze, Guoliang Xing, Zhenyu Yan, and Hongkai Chen. 2026. DeepFeature: LLM-Empowered Context-aware Feature Generation for Wearable Biosignals. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 10, 3, Article 131 (2026). https://doi.org/10.1145/3831996

[p41] Yang Liu, Tingting Wang, Kun Wang, and Yu Zhang. 2021. Collaborative Learning Quality Classification Through Physiological Synchrony Recorded by Wearable Biosensors. Frontiers in Psychology 12, Article 674369 (2021). https://doi.org/10.3389/fpsyg.2021.674369

[stresssense] Hong Lu, Denise Frauendorfer, Mashfiqui Rabbi, Marianne Schmid Mast, Gokul Chittaranjan, Andrew T. Campbell, Daniel Gatica-Perez, and Tanzeem Choudhury. 2012. StressSense: Detecting Stress in Unconstrained Acoustic Environments Using Smartphones. In Proceedings of the 2012 ACM Conference on Ubiquitous Computing. Association for Computing Machinery, 351-360. https://doi.org/10.1145/2370216.2370270

[p42] Guido Makransky, and Gustav B. Petersen. 2021. The Cognitive Affective Model of Immersive Learning (CAMIL): a Theoretical Research-Based Model of Learning in Immersive Virtual Reality. Educational Psychology Review 33, 3 (2021), 937–958. https://doi.org/10.1007/s10648-020-09586-2

[p43] Jonna Malmberg, Eetu Haataja, Tapio Seppänen, and Sanna Järvelä. 2019. Are we together or not? The temporal interplay of monitoring, physiological arousal and physiological synchrony during a collaborative exam. International Journal of Computer-Supported Collaborative Learning 14, 4 (2019), 467–490. https://doi.org/10.1007/s11412-019-09311-4

[p44] Oded Mayo, Michal Lavidor, and Ilanit Gordon. 2021. Interpersonal autonomic nervous system synchrony and its association to relationship and performance – a systematic review and meta-analysis. Physiology & Behavior 235, Article 113391 (2021). https://doi.org/10.1016/j.physbeh.2021.113391

[p61] Society for Psychophysiological Research Ad Hoc Committee on Electrodermal Measures. 2012. Publication recommendations for electrodermal measurements. Psychophysiology 49, 8 (2012), 1017–1034. https://doi.org/10.1111/j.1469-8986.2012.01384.x

[expect] Christian Meurisch, Cristina A. Mihale-Wilson, Adrian Hawlitschek, Florian Giger, Florian Müller, Oliver Hinz, and Max Mühlhäuser. 2020. Exploring User Expectations of Proactive AI Systems. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 4, 4, Article 146 (2020), 1-22. https://doi.org/10.1145/3432193

[p46] Clara Moge, Katherine Wang, and Youngjun Cho. 2022. Shared User Interfaces of Physiological Data: Systematic Review of Social Biofeedback Systems and Contexts in HCI. In CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery, 1–16. https://doi.org/10.1145/3491102.3517495

[p47] Andy Nguyen, Sanna Järvelä, Carolyn Rosé, Hanna Järvenoja, and Jonna Malmberg. 2023. Examining socially shared regulation and shared physiological arousal events with multimodal learning analytics. British Journal of Educational Technology 54, 1 (2023), 293–312. https://doi.org/10.1111/bjet.13280

[p49] Richard V. Palumbo, Marisa E. Marraccini, Lisa L. Weyandt, Oliver Wilder-Smith, Heather A. McGee, Siwei Liu, and Matthew S. Goodwin. 2017. Interpersonal Autonomic Physiology: A Systematic Review of the Literature. Personality and Social Psychology Review 21, 2 (2017), 99–141. https://doi.org/10.1177/1088868316628405

[p51] Laura Claudia Johanna Pflieger, Tamara Baumann, Melanie Hartmann, Laura Koch, Florian Kern, Peter Kullmann, Silke Grafe, Marc Erich Latoschik, and Maria Bannert. 2026. Exploring Scaffolding Mechanisms for Learning Regulation in Immersive Collaborative VR Environments. Technology, Knowledge and Learning. Advance online publication. https://doi.org/10.1007/s10758-026-09959-6

[p52] Yinuo Qin, Richard T. Lee, Weijia Zhang, Xiaoxiao Sun, and Paul Sajda. 2025. Physiologically informed predictability of a teammate’s future actions forecasts team performance. iScience 28, 5, Article 112429 (2025). https://doi.org/10.1016/j.isci.2025.112429

[p53] Yinuo Qin, Richard T. Lee, and Paul Sajda. 2026. Covert perception of AI adversely impacts team performance and changes physiological dynamics despite human-level AI competence. npj Artificial Intelligence 2, 1, Article 71 (2026). https://doi.org/10.1038/s44387-026-00130-1

[aware] Amog Rao, Utkarsh Agarwal, Amol Harsh, and Siddharth Siddharth. 2026. AwareLLM: A Proactive Multimodal Ecosystem for Personalized Human-AI Collaboration to Enhance Productivity. arXiv preprint arXiv:2605.09625. https://arxiv.org/abs/2605.09625

[p57] Bertrand Schneider, Gahyun Sung, Edwin Chng, and Stephanie Yang. 2021. How Can High-Frequency Sensors Capture Collaboration? A Review of the Empirical Links between Multimodal Metrics and Collaborative Constructs. Sensors 21, 24, Article 8185 (2021). https://doi.org/10.3390/s21248185

[p56] Bertrand Schneider, Yong Dich, and Iulian Radu. 2020. Unpacking the relationship between existing and new measures of physiological synchrony and collaborative learning: a mixed methods study. International Journal of Computer-Supported Collaborative Learning 15, 1 (2020), 89–113. https://doi.org/10.1007/s11412-020-09318-2

[p59] Fred Shaffer, and J. P. Ginsberg. 2017. An Overview of Heart Rate Variability Metrics and Norms. Frontiers in Public Health 5, Article 258 (2017). https://doi.org/10.3389/fpubh.2017.00258

[guide] Ananya Shukla, Chaitanya Modi, Satvik Bajpai, and Siddharth Siddharth. 2026. GuideAI: A Real-time Personalized Learning Solution with Adaptive Interventions. In Proceedings of the 31st International Conference on Intelligent User Interfaces. Association for Computing Machinery, 1218-1234. https://doi.org/10.1145/3742413.3789125

[p62] Nicholas C. Soderstrom, and Robert A. Bjork. 2015. Learning Versus Performance: An Integrative Review. Perspectives on Psychological Science 10, 2 (2015), 176–199. https://doi.org/10.1177/1745691615569000

[p63] Stephan Streuber, Sarah Rogula, Maria Alejandra Quirós-Ramírez, and Jens Pruessner. 2026. Remote collaboration in virtual reality induces physiological synchrony comparable to face-to-face interaction. Scientific Reports 16, 1, Article 3721 (2026). https://doi.org/10.1038/s41598-026-35955-y

[p65] Sebastian Wallot, Andreas Roepstorff, and Dan Mønster. 2016. Multidimensional Recurrence Quantification Analysis (MdRQA) for the Analysis of Multidimensional Time-Series: A Software Implementation in MATLAB and Its Application to Group-Level Data in Joint Action. Frontiers in Psychology 7, Article 1835 (2016). https://doi.org/10.3389/fpsyg.2016.01835

[pulse] Zhiyuan Wang, Subigya Nepal, Ariful Islam, Indrajeet Ghosh, Xinyu Chen, Katharine E. Daniel, Laura E. Barnes, and Philip Chow. 2026. PULSE: Agentic Investigation with Passive Sensing for Proactive Affective Intervention in Cancer Survivorship. arXiv preprint arXiv:2605.17679. https://arxiv.org/abs/2605.17679

[p67] Rafael Wespi, Andrea N. Neher, Tanja Birrenbach, Stefan K. Schauber, Marie Ottilie Frenkel, Helmut Schrom-Feiertag, Thomas C. Sauter, and Juliane E. Kämmer. 2025. Physiological team dynamics explored: physiological synchrony in medical simulation training. Advances in Simulation 10, 1, Article 5 (2025). https://doi.org/10.1186/s41077-025-00335-5

[p66] Rafael Wespi, Lukas Schwendimann, Andrea Neher, Tanja Birrenbach, Stefan K. Schauber, Tanja Manser, Thomas C. Sauter, and Juliane E. Kämmer. 2024. TEAMs go VR—validating the TEAM in a virtual reality (VR) medical team training. Advances in Simulation 9, 1, Article 38 (2024). https://doi.org/10.1186/s41077-024-00309-z

[children] Zekun Wu, Man Su, Huiyong Li, Tomohiro Nagashima, and Anna Maria Feit. 2026. Gaze-Informed Proactive AI Assistance for Children's Picture Exploration. arXiv preprint arXiv:2607.00445. https://arxiv.org/abs/2607.00445

[hhiss] Yi Xiao, Harshit Sharma, Sawinder Kaur, Dessa Bergen-Cico, and Asif Salekin. 2025. Human Heterogeneity Invariant Stress Sensing. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 9, 3, Article 142 (2025), 1-42. https://doi.org/10.1145/3749465

[pro2] Lilin Xu, Bufang Yang, Siyang Jiang, Kaiwei Liu, Kaiyuan Hou, Yuang Fan, Hongkai Chen, Zhenyu Yan, and Xiaofan Jiang. 2026. Pro2Assist: Continuous Step-aware Proactive Assistance with Multi-modal Egocentric Perception for Long-horizon Procedural Tasks. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 10, 3, Article 178 (2026). https://doi.org/10.1145/3832022

[p69] Lixiang Yan, Dragan Gašević, Vanessa Echeverria, Linxuan Zhao, Yueqiao Jin, Xinyu Li, and Roberto Martinez-Maldonado. 2025. In Sync or Out of Sync? Understanding Stress and Learning Performance in Collaborative Healthcare Simulations through Physiological Synchrony and Arousal. International Journal of Artificial Intelligence in Education 35, 4 (2025), 2421–2452. https://doi.org/10.1007/s40593-025-00475-9

[p70] Chi-Lan Yang, Keigo Matsumoto, Songping Yu, Leo Sawada, Kiyoaki Arakawa, Daisuke Yamada, and Hideaki Kuzuoka. 2023. Understanding the effect of a virtual moderator on people’s perception in remote discussion using social VR. Frontiers in Virtual Reality 4, Article 1198024 (2023). https://doi.org/10.3389/frvir.2023.1198024

[vital] Di Zhu, Yu Yvonne Wu, Hong Jia, Aaqib Saeed, Vassilis Kostakos, and Ting Dang. 2026. VitalAgent: A Tool-Augmented Agent for Reactive and Proactive Physiological Monitoring over Wearable Health Data. arXiv preprint arXiv:2605.29483. https://arxiv.org/abs/2605.29483