Acknowledgments

Thank you to the Tow Center for Digital Journalism for the fellowship that supported the writing of this work. I could not have done this otherwise. I'm indebted to Mark Hansen for reading not one but two long drafts and providing expansive feedback. Andrew Gelman kindly reviewed the "Analysis" chapter and really shaped my thinking on causation. Kenneth Prewitt read the material on census and race with an expert eye; any remaining blunders are my own. I'm indebted to research directors Taylor Owen and Claire Wardle for their patient efforts as they shepherded me through the process over nearly two years. I'm deeply grateful to Emily Bell for her support over the years, and the fantastic opportunity to teach at Columbia. My warmest shout-out to the students of my Frontiers of Computational Journalism course, who taught me what it is to teach---and sometimes schooled me with their own work. You've been more influential than you know. And thank you to Sara for helping me find the book's title.

*March 2016*

Footnotes

[i](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) You might as well expand that to the relationship between story and science. It's a vexing question. See, for example, Gelman and Basbøll.[84](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[ii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) The classic discussion of the human creation of categories is Sorting Things Out: Classification and Its Consequences.[85](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[iii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For a thorough discussion of race on the census, see Snipp.[86](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[iv](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For a fantastic list of 20 reasons why quantification is difficult in psychology, see Meehl.[87](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[v](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For a really excellent exposition of the problems of counting "mass shooting," see Watt. [88](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[vi](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Nehemiah 11:1.

[vii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For more on these two unemployment surveys and the difference between them, see U.S. Bureau of Labor Statistics. [89](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[viii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Actually 60,000 randomly chosen households, which is about 150,000 people. See U.S. Census Bureau. [90](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[ix](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Similar, but not identical, because Bernoulli initially considered sampling "with replacement," where each person might be chosen more than once. This is probably because sampling with replacement is mathematically simpler, and Bernoulli worked with approximate formulas that become more accurate as the number of samples increases, rather than the very large numbers involved in calculating the number of possibilities directly, which require computers.

[x](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) I'm indebted to Mark Hansen for the phrasing of these two key sentences.

[xi](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Before I get hate mail: Yes, it is wrong to say that there is a 90 percent chance that the true value falls within a 90-percent confidence interval. The contortions of frequentist statistics require us to say instead that our method of constructing the confidence interval will include the true value for 90 percent of the possible samples, but we don't know anything at all about this particular sample. The distinction is subtle but real. It's also usually irrelevant for this type of sampling margin of error computation, where the confidence interval is numerically very close to the Bayesian credible interval, which actually does contain the true value with 90 percent probability. See e.g. Vanderplas.[91](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[xii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Whether or not anything is "truly" random is a metaphysical question. Perhaps the universe is fully deterministic and everything is fated in advance. Or perhaps more data or better knowledge would reveal subtle connections. But from a practical point of view, we only care if these fluctuations are random to us. Randomness, chance, noise: There is always something in the data which follows no discernable pattern, caused by factors we cannot explain. This doesn't mean that these factors are unexplainable. There may be trends or patterns we aren't seeing, or additional data that might be used to explain what looks like chance. For example, we might one day discover that the number of assaults is driven by the weather. But until we discover this relationship, we have no ability to predict or explain the variations in the assault rate so we have little choice but to treat them as random.

[xiii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For a fantastic history of these ideas, see Ian Hacking's The Emergence of Probability.[92](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[xiv](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Although the mathematics turn out the same, there's a useful distinction between something which we must treat as random because we don't know the correct answer (epistemic uncertainty) and something which has intrinsic randomness in its future course (aleatory uncertainty). The difference is important in risk management, where our uncertainty might be reduced if we did more research, or we might be up against fundamental limits of prediction.

[xv](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Peirce's simple argument assumes complete statistical independence between the positions of every stroke in a signature. That's dubious, because if you move one letter while signing, the rest of the letters will probably have to move too. A more careful analysis[93](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations) shows that an exact signature match is much more likely than one in 530 but still phenomenally unlikely to happen by chance.

[xvi](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) For a baggage-free introduction to applied Bayesian stats I recommend McElreath's *Statistical Rethinking*, or his marvelous lecture videos.[94](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[xvii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) I'm referencing the butterfly effect, the idea that the disturbances from a butterfly flapping its wings might eventually become a massive hurricane. More generally, this is the idea that small perturbations are routinely magnified into huge changes. The early chaos theorist Edward Lorenz came up with the butterfly analogy while studying weather prediction in the early 1960s. In practice, this uncertainty amplification effect means there will be random variations in our data, due to specific unrepeatable circumstances, that we cannot ever hope to understand.

[xviii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) This type of independent events model is also called a *Poisson distribution*, after the French mathematician Siméon Denis Poisson, who first worked through the math in the 1830s. But the nice thing about using a simulation of our intersection is that it's not necessary to know the mathematical formula for the Poission distribution. Simply flipping independent coins gives the same result. Simulation is a revolutionary way to do statistics because it so often turns difficult mathematics into easy code.

[xix](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Maybe both of your hypotheses are wrong, and something else entirely happened. Maybe your models, which are pieces of code, aren't good representations of your hypotheses, which are ideas expressed in language. Maybe your data is the result of both a working stoplight and some amount of luck. Maybe the intersection was rebuilt after the second year with wider lanes and a new stoplight, and it's really the wider lanes that caused the change. Maybe the bureaucracy that collects this data changed the definition of "accident" to exclude smaller collisions. Or maybe you added up the numbers wrong.

[xx](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Unemployment versus investment chart from Mankiw.[95](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[xxi](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) But sometimes it *is* possible to tell which of two variables is the cause and which is the effect just from the data, by exploiting the fact that noise in the cause shows up in the effect but not vice versa. See Mooij et al.[96](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

[xxii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Michael Keller, private communication.

[xxiii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) I found this circulating on the Internet, and was unable to figure out who made it. Much love to the unknown creator.

[xxiv](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) It probably wasn't Bertrand Russell who first said, "The mark of a civilized human is the ability to look at a column of numbers, and weep." But per <http://quoteinvestigator.com/2013/02/20/moved-by-stats/>there is a history of quoting and misquoting a similar phrase. The original text is Russell's The Aims of Education:

> The next stage in the development of a desirable form of sensitiveness is sympathy. There is a purely physical sympathy: A very young child will cry because a brother or sister is crying. This, I suppose, affords the basis for the further developments. The two enlargements that are needed are: first, to feel sympathy even when the sufferer is not an object of special affection; secondly, to feel it when the suffering is merely known to be occurring, not sensibly present. The second of these enlargements depends mainly upon intelligence. It may only go so far as sympathy with suffering which is portrayed vividly and touchingly, as in a good novel; it may, on the other hand, go so far as to enable a man to be moved emotionally by statistics. This capacity for abstract sympathy is as rare as it is important.

Many others attribute the pithier quote to Russell, but the original source for that is nowhere to be found. I really like the shorter quote no matter where it ultimately came from; it's a fine string of words.

[xxv](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) I'll use *reader* as a generic name for the consumer of a story, with apologies to reporters working in other formats.

[xxvi](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Totally fun to say.

[xxvii](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#footnotes) Lifetime odds of being struck by lightning estimated at 1 in 12,000 by NOAA, based on 2004--2013 averages.[97](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

Citations

1.  Denise Schmandt-Besserat, "Tokens and Writing: The Cognitive Development,"SCRIPTA (2009): 145--154, http://sites.utexas.edu/dsb/files/2014/01/TokensWriting_the_Cognitive_Development.pdf.
2.  "Table A-15: Alternative Measures of Labor Underutilization," U.S. Bureau ofLabor Statistics, http://www.bls.gov/news.release/empsit.t15.htm.
3.  Jonathan Stray, "Ethics in Data Journalism: Margin of Error in Bureau of La-bor Statistics Reports," Data Driven Journalism, 15 January 2016, http://datadrivenjournalism.net/news_and_analysis/ethics_in_data_journalism_margin_of_error_in_bureau_of_labor_statistics_rep.
4.  George Cobb, "The Introductory Statistics Course: a Ptolemaic Curriculum,"Technology Innovations in Statistics Education, 1 (2007), http://escholarship.org/uc/item/6hb3k0nz.
5.  James C. Scott, Seeing Like a State (New Haven: Yale University Press, 1998).
6.  David Hestenes, "Oersted Medal Lecture 2002: Reforming the Mathematical Lan-guage of Physics," American Journal of Physics, 104 (2003), http://dx.doi.org/10.1119/1.1522700.
7.  Brian Gratton and Myron P. Guttman, "Hispanics in the United States 1850--1990," Historical Methods, 3 (2000), http://www.latinamericanstudies.org/immigration/Hispanics-US-1850-1990.pdf.
8.  David Niose, "Anti-Intellectualism Is Killing America," Psychology Today, 23 June2015, https://www.psychologytoday.com/blog/our-humanity-naturally/201506/anti-intellectualism-is-killing-america.
9.  G. Kitson Clark, The Making of Victorian England (New York: Routledge, 1962),
10. Chris Davis and Matthew Doig, "State Scraps Felon Voter List," Sarasota Herald-Tribune, 12 July 2004, http://www.heraldtribune.com/article/20040712/NEWS/
11. Matt Waite, "Handling Data About Race and Ethnicity," OpenNews Source, 20June 2014, https://source.opennews.org/en-US/learning/handling-data-about-race-and-ethnicity/.
12. "Sixteenth Decennial Census of the United States, Instructions to Enumerators,Population and Agriculture," U.S. Census Bureau, 1940, http://www.census.gov/history/pdf/1940instructions.pdf.
13. Jens Manuel Krogstad and Mark Hugo Lopez, "'Mexican,' 'Hispanic,' 'Latin Amer-ican' Top List of Race Write-ins on the 2010 Census," Pew Research Center, 4 April2014, http://www.pewresearch.org/fact-tank/2014/04/04/mexican-hispanic-and-latin-american-top-list-of-race-write-ins-on-the-2010-census/.
14. "Directive No. 15 as Adopted on May 12, 1977," U.S. Census Bureau, 1977, http://wonder.cdc.gov/wonder/help/populations/bridged-race/directive15.html.
15. Jerzy Wojewoda et al., "Hysteretic Effects of Dry Friction: Modelling and Ex-perimental Studies," Philosophical Transactions of the Royal Society A, 1866 (2008),http://rsta.royalsocietypublishing.org/content/366/1866/747.
16. "Employment Situation Technical Note," U.S. Bureau of Labor Statistics, 2015,http://www.bls.gov/news.release/empsit.tn.htm.
17. Neil Irwin and Kevin Quealy, "How Not to Be Misled by the Jobs Report," TheNew York Times, 1 May 2013, http ://www.nytimes.com/2014/05/02/upshot/how-not-to-be-misled-by-the-jobs-report.html?_r=0.
18. "How the Government Measures Unemployment," U.S. Bureau of Labor Statis-tics, 2015, http://www.bls.gov/cps/cps_htgm.htm.
19. "Employment Situation Technical Note."
20. Marianne Durand and Philippe Flajolet, "Loglog Counting of Large Cardinal-ities," in ESA (2003), 605--617, http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.12.2718.
21. Sir Arthur Conan Doyle, "The Adventure of the Blanched Soldier," in The Case-Book of Sherlock Holmes (1927), 54.
22. Mike Bostock et al., "One Report, Diverging Perspectives," The New York Times,5 October 2012, http ://www. nytimes.com/interactive/2012/10/05/business/economy/one-report-diverging-perspectives.html.
23. James Fallows, "Why to Get More Than 1 Newspaper, iPad Edition," The At-lantic, 22 October 2013, http://www.theatlantic.com/national/archive/2013/10/why-to-get-more-than-1-newspaper-ipad-edition/280772/.
24. Kypros Kypri et al., "Effects of Restricting Pub Closing Times on Night-timeAssaults in an Australian City," Addiction, 2 (2011), http://onlinelibrary.wiley.com/enhanced/doi/10.1111/j.1360-0443.2010.03125.x/.
25. Ibid.
26. Nate Silver, The Signal and the Noise: Why So Many Predictions Fail---But SomeDon't (New York: Penguin, 2012), 484.
27. Ibid.
28. Sanjoy Mahajan, Street-Fighting Mathematics: The Art of Educated Guessingand Opportunistic Problem Solving (Cambridge: MIT Press, 2010).
29. Meier and Zabell, "Benjamin Peirce and the Howland Will."
30. Ian Hacking, "Telepathy: Origins of Randomization in Experimental Design," Isis, 3 (1998), http://www.jstor.org/stable/234674.
31. Gerard E. Dalal, "Why P=0.05?" http://www.jerrydallal.com/LHSP/p05.htm.
32. Anders Hald, "On the History of Maximum Likelihood in Relation to Inverse Probability and Least Squares," Statistical Science, 2 (1999), http://www.jstor.org/stable/2676741.
33. Robert Kass and Adrian Raftery, "Bayes Factors," Journal of the American Statistical Association, 430 (1995), http://www.jstor.org/stable/2291091.
34. Sharon Bertsch McGrayne, The Theory That Would Not Die: How Bayes' Rule Cracked the Enigma Code, Hunted Down Russian Submarines, and Emerged Triumphantfrom Two Centuries of Controversy (New Haven: Yale University Press, 2011).
35. Steven Raphael and Jens Ludwig, Evaluating Gun Policy: Effects on Crime and Violence (Chicago: Brookings Institution Press, 2003), 251--277, http://home.uchicago.edu/ludwigj/papers/Exile_chapter_2003.pdf.
36. Ibid.
37. Steven D. Levitt, "Understanding Why Crime Fell in the 1990s: Four Factors That Explain the Decline and Six That Do Not," The Journal of Economic Perspectives, 1 (2004).
38. Raphael and Ludwig, Evaluating Gun Policy: Effects on Crime and Violence.
39. Kypri et al., "Effects of Restricting Pub Closing Times on Nighttime Assaultsin an Australian City."
40. Raphael and Ludwig, Evaluating Gun Policy: Effects on Crime and Violence.
41. Occupational Mortality: The Registrar General's Decennial Supplement for England and Wales, 1970--1972 (London: Her Majesty's Stationery Office, 1978), http://lib.stat.cmu.edu/DASL/Datafiles/SmokingandCancer.html.
42. Franz H. Messerli, "Chocolate Consumption, Cognitive Function, and Nobel Laureates," New England Journal of Medicine (2012): 1562--1564.
43. Greg Mankiw, "A Striking Scatterplot," 29 March 2011, http://gregmankiw.blogspot.com/2011/03/striking-scatterplot.html.
44. Ibid.
45. Christian Rudder, "Exactly What to Say in a First Message," OKCupid blog,2009, http://blog.okcupid.com/index.php/online-dating-advice-exactly-what-to-say-in-a-first-message/.
46. Milberger et al, "Tobacco Manufacturers' Defence Against Plaintiffs' Claims ofCancer Causation: Throwing Mud at the Wall and Hoping Some of It Will Stick," Tobacco Control (December 2006): iv17--iv26, http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2563590/.
47. Andrew Gelman, "Statistics for Cigarette Sellers," Chance, 3 (2012), http://www.stat.columbia.edu/~gelman/research/published/ChanceEthics4.pdf.
48. Bikaramjit Mann and Evan Wood, "Confounding in Observational Studies Explained," The Open Epidemiology Journal (2012), http://benthamopen.com/contents/pdf/TOEPIJ/TOEPIJ-5-18.pdf.
49. James F. Pagel, Natalie Forister, and Carol Kwiatkowki, "Adolescent Sleep Disturbance and School Performance: The Confounding Variable of Socioeconomics," Journal of Clinical Sleep Medicine, 1 (2007).
50. Judea Pearl, Causality: Models, Reasoning, and Inference, 2nd Edition (Cambridge: Cambridge University Press, 2009).
51. Danial Kaplan, Statistical Modeling: A Fresh Approach, Second Edition (ProjectMosaic, 2012).
52. John Stuart Mill, A System of Logic, Vol. 1 (: 1843), 455.
53. Matt Apuzzo and Adam Goldman, "Documents Show NY Police Watched Devout Muslims," Associated Press, 6 September 2011, http://www.ap.org/Content/AP-In-The-News/2011/Documents-show-NY-police-watched-devout-Muslims.
54. Philip Kitcher, The Advancement of Science: Science Without Legend, Objectivity Without Illusions (Oxford: Oxford University Press, 1993).
55. Daniel Kahneman, Thinking Fast and Slow (New York: Farrar, Straus and Giroux, 2013).
56. Jr. Richards J. Heuer, The Psychology of Intelligence Analysis (: CIA, 1999), https://www.cia.gov/library/center-for-the-study-of-intelligence/csi-publications/books-and-monographs/psychology-of-intelligence-analysis/art11.html.
57. Charles Sanders Peirce, "Some Consequences of Four Incapacities," Journal ofSpeculative Philosophy (1868): 140--157.
58. Tamara Munzner, "Visualization," in Fundamentals of Computer Graphics, Third Edition, ed. Peter Shirley and Steve Marschner (AK Peters, 2009), 675--707, http://www.cs.ubc.ca/labs/imager/tr/2009/VisChapter/.
59. Justin McCarthy, "Most Americans Still See Crime Up Over Last Year," Gallup, 21 November 2014, http://www.gallup.com/poll/179546/americans-crime-last-year.aspx.
60. Ibid.
61. Ruth Hamill, Timothy DeCamp Wilson, and Richard E. Nisbett, "Insensitivity to Sample Bias: Generalizing From Atypical Cases," Journal of Personality and Social Psychology, 4 (1980).
62. Ibid.
63. Ibid.
64. Ibid.
65. Ibid.
66. Angela Fagerlin, Catharine Wang, and Peter A. Ubel, "Reducing the Influence of Anecdotal Reasoning on People's Health Care Decisions: Is a Picture Worth a Thousand Statistics?" Medical Decision Making, 4 (2005).
67. Stray.
68. Jessica M. Pollak and Charis E. Kubrin, "Crime in the News: How Crimes, Offenders and Victims Are Portrayed in the Media," Journal of Criminal Justice and Popular Culture, 1 (2007).
69. Miguel Ríos, "The Geography of Tweets," Twitter, 31 May 2013, https://blog.twitter.com/2013/the-geography-of-tweets.
70. Moritz Stefaner, "The VIZoSPHERE, 2011," 2011, http://www. visualizing .org/full-screen/29391.
71. "Special Coverage of the 2014 Midterms," FiveThirtyEight, 4 November 2014, http://fivethirtyeight.com/live-blog/special-coverage-the-2014-midterms/?#livepress-update-20137747.
72. The New York Times, "Who Will Win the Senate?" 4 November 2014, http://www.nytimes.com/newsgraphics/2014/senate-model/.
73. Elke Weber, "From Subjective Probabilities to Decision Weights: The Effect of Asymmetric Loss Functions on the Evaluation of Uncertain Outcomes and Events,"Psychological Bulletin, 2 (1994).
74. Adam J. L. Harris and Adam Corner, "Communicating Environmental Risks:Clarifying the Severity Effect in Interpretations of Verbal Probability Expressions," Journal of Experimental Psychology: Learning, Memory, and Cognition, 6 (2011).
75. Ulrich Hoffrage et al., "Representation Facilitates Reasoning: What Natural Frequencies Are and What They Are Not," Cognition (2002), http://www.sciencedirect.com/science/article/pii/S0010027702000501.
76. "Visualizing Smoking Risk," Stubborn Mule, 21 October 2010, http://www.stubbornmule.net/2010/10/visualizing-smoking-risk/.
77. Ibid.
78. Phillip E. Tetlock, Expert Political Judgment: How Good Is It? How Can We Know? (Princeton: Princeton University Press, 2005).
79. Ibid.
80. Ibid.
81. Paul Meehl, Clinical Versus Statistical Prediction: A Theoretical Analysis and a Review of the Evidence (Minneapolis: University of Minnesota, 1954).
82. Quinn McNemar, "Review of Clinical Versus Statistical Prediction: A Theoretical Analysis and a Review of the Evidence by Paul E. Meehl," The American Jour-nal of Psychology, 3 (September 1955).
83. William M. Grove et al., "Clinical Versus Mechanical Prediction: A Meta-analysis,"Psychological Assessment, 1 (2000).
84. Paul Meehl, "Causes and Effects of My Disturbing Little Book," Journal of Per sonality Assessment, 3 (1986).