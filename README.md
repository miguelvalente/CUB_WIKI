# CUB_WIKI

In the original [DataSet Repo](https://github.com/EthanZhu90/ZSL_PP_CVPR17)  (_Elhosein et .al_) there is no difference between CUBird_Sentences and CUBird_WikiArticles. In here you find the CUBird_WikiArticles as one single piece of text with numbered sentences removed as well as some standard data splits. This repo only exist for ease of use (wget/git clone). Refer to original authors for any questions.


Two different types of splits for CUB:
 1. Proposed Split 2.0 from _Zero-Shot Learning - A ComprehensiveEvaluation of the Good, the Bad and the Ugly_ 
 2. Easy and Hard Split from _Elhosein et .al_ (No Test Set)


NOTE: Most if not all papers in ZSL/GZSL use the file _proposed_split.txt_. I'd recommend sticking to this split.

set_id

* train set = 1
* val set = 0
* test set = 2

seen_unseen

* unseen = 0
* seen = 1

Files Structure for Proposed Split

    img_id   set_id  seen_unseen
