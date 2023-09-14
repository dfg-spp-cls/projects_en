---
title: Comparative Annotation to Explore and Explain Text Similarities (CompAnno)
excerpt: Julia Nantke & Nils Reiter
lang: en
---

***Julia Nantke & Nils Reiter***

The project CompAnno develops a comparative annotation framework for the exploration
and explanation of text similarities regarding the representation of character properties. We
focus our approach of comparative annotation on the category of literary character, because
it is central to the composition of literary texts in general as well as for establishing,
describing and interpreting intertextual relations. In contrast to existing and frequently used
annotation approaches, comparative annotation rests on the simultaneous observation and
comparison of multiple text snippets. Character properties are initially assigned manually in
comparison of the snippets. Collecting annotations for a large number of pairs allows to
establish a ranking of similarity, which in turn will be used to train a machine learning
system. The comparative annotation process results in a partial ordering for each property.
The main benefit of this approach is that besides supporting intertextual annotation it
generally allows the annotation of abstract, interpretation-related textual features like the
description and characterization of literary characters.
We employ various technical methods that offer different perspectives on the task at hand.
Basically, three perspectives can be differentiated: 1. If cast as a document retrieval task, a
technical system can provide a user with snippets that are similar to the one they are
investigating. This reveals (potentially new) intertextual relations, but requires an efficiently
computable similarity function, which is constructed from assignments of property values to
individual snippets. 2. If the problem is cast as a ranking task, a system can provide a
ranking of provided snippets according to some property’s value. This has many other
benefits and use-cases, besides comparison, as it provides access to (some aspects of)
characterization in general. 3. If similarity itself is taken into focus, a ranking system can be
applied to pairs of snippets, and provide, over a set of snippets, a ranking of all the pairs of
snippets according to their similarity. In this case, similarity is also caused by the absence or
small value of a property (e.g., two snippets can be similar because the characters are not
malicious). In all cases, we support the re-integration of these quantitative results into literary
studies discourse by providing guiding information for their interpretation.
The project thus aims at two concrete outcomes: On the one hand, we develop the first
framework for computer-based investigation of intertextuality and text similarity, that goes
beyond text re-use and does not assume a fixed corpus. On the other hand, we provide a
new way of working with interpretative categories, which are common in computational
literary studies.
