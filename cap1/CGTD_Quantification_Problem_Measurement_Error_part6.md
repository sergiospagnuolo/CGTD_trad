**The Problem of Measurement Error**

In practice, nothing can be measured perfectly.

A random sample has a margin of error due to sampling, but *every*quantification has error for one reason or another. The length of a table cannot be measured much finer than the tick marks on whatever ruler you use, and the ruler itself was created with finite precision. Every physical sensor has noise, limited resolution, calibration problems, and other unaccounted variations. Humans are never completely consistent in their categorizations, and the world is filled with special cases. And I've never seen a database that didn't have a certain fraction of corrupted or missing or simply nonsensical entries, the result of glitches in increasingly complex data-generation workflows.

Error creeps in, and the data never quite matches the description on the box. Anyone who works with data has had this beaten into them by experience.

Even simple counts break down when you have to count a lot of things. We've all sensed that large population figures are somewhat fictitious. Are there really 536,348 people in your hometown, as the number on the "Welcome To ..." sign suggests? If the sign said 540,000, we would know to treat it as a rough figure, yet far too often we're willing to imagine that every last digit is accurate.

There are analogous difficulties with counting the number of people at a protest, the number of intravenous drug users in a city, or the number of stars in the galaxy. Even counting the number of distinct names in a large database can require complex estimation algorithms, given the constraints of distributed storage and finite memory.[20](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations) Large counts are usually estimates, which differ from the true value by some amount.

But we gain hugely if we can say something about the accuracy of our data. Our answer to "how long is the table?" might be "52 inches, to the nearest eighth of an inch."

Reliable data includes measures of error: *how much* the reported information is expected to differ from the reality it represents. There are many standard ways to report the accuracy of different kinds of data. Figures might be "accurate to the nearest quarter pound" or use more technical notation like ± and ideas like "standard error" and "confidence interval." For a large database you could report or estimate the number of bad entries. The modern census has a second wave to estimate coverage and therefore error. In many fields it's considered shoddy work to report a figure without giving some idea of the accuracy. Maybe we should say the same for journalism.

The idea of measurement error is the idea of quantified uncertainty. This is one of the tremendous achievements of modern thought---the recognition that knowing *how much* we don't know has great value. Not all data comes with measurement errors attached. Sometimes you have to read the fine print to find out, or call someone and ask. But if you do not know and cannot reasonably guess the sources and magnitudes of possible error, then you don't really know what the data means.