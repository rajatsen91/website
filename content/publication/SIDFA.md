+++
abstract = "Finite automata is widely used for Deep Packet Inspection (DPI) of network traffic. Two types of automata employed for this purpose are Non-deterministic Finite Automata (NFA) and Deterministic Finite Automata (DFA). An NFA suffers from a large memory bandwidth per character due to multiple active states. A DFA, in comparison, ensures a linear processing time of O(1) for memory based architectures. However, the DFA state explosion conditions commonly occurring in today's NIDS rule-sets, render the automata with practically infeasible memory space requirements. To avoid state blowup we propose a semi-deterministic automata, Sub-expression Integrated DFA (SI-DFA), that ensures processing time of a single standard DFA. Rules are broken into sub-expressions at blowup conditions and compiled into a single DFA along with an association table, to correctly encapsulate equivalent automata. We list the rare cases in regular expressions for which sub-expression Integration is incorrect and present methodology to detect their occurrences. We evaluate SI-DFA on real-world rule-sets like Bro, Snort and Linux filters and compare their performance with the state-of-the-art hybrid automata solutions. SI-DFA renders a 66-97% reduction in processing bandwidth, up to 68% lower space requirement and an improvement trend with increasing rule complexity when compared to the traditional solutions."
authors = ["Subhashini krishnasamy", "Rajat Sen", "Sewoong Oh", "Sanjay Shakkottai"]
date = "2013-07-08"
image = ""
image_preview = ""
math = true
publication = "In High Performance Switching and Routing (HPSR), 2013 IEEE 14th International Conference on (pp. 164-170). IEEE."
title = "Si-dfa: Sub-expression integrated deterministic finite automata for deep packet inspection"
url_code = ""
url_dataset = ""
url_pdf = "https://pdfs.semanticscholar.org/f849/904b58ac1174f60cc9931739effff21bbd49.pdf"
url_project = ""
url_slides = ""
url_video = ""
+++

