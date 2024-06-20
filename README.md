# KAPR
KAPR Dataset

The Knowledge Acquisition Passage Retrieval Dataset consists of 5000 passages accross 20 science domains.
Subject matter experts have evaluate 50 passages for 5 topics per domain on both relevance and informativeness.

Both aspects are judged with an ordinal three-point scale, with 0 being not relevant/informative at all, 1 being partially relevant/informative, and 2 being very relevant/informative. 

**Relevance**
A passage is considered very relevant (2) when it only covers the concept, clearly discusses said concept, and there is no other piece of information discussed in such passages. It becomes less relevant when other concepts are discussed in the passage as well or when it only discusses a specific aspect of the concept.

**Informativeness** 
Assesses the amount of information about the concept contained in the passage. A very informative snippet should answer questions such as:
- How much would an average user learn about the concept after reading the passage?
- How much “educational” (or background information) or “essential” information about the concept is included in the passage?
- Does the snippet provide an answer to “what CONCEPT is?” like questions?

