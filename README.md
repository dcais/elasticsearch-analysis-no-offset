Analysis with no offset
==================================

This project removed setOffset method from tokenizer to avoid offsets backoff error when
writing index after Elastic Search 6.x



how to user ?
--------------

build and install from elastic-search-plugin-in , and
replace word_delimiter_graph with word_delimiter_graph_no_offset

