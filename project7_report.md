# CS304 Project 7

### local/aishell_prepare_dict.sh $data/resource_aishell || exit 1;
This step is to prepare the dictionary resources. It takes an input as the path where *lexicon.txt* is placed then creates the following files under *data/local/dict*:
* *nonsilence_phones.txt*. It contains all unique phones provided in lexicon.txt
* *silence_phones.txt*. It contains the silence phone. 
* *optional_silence.txt*. ?
* *extra_questions.txt*. ?

### local/aishell_data_prep.sh $data/data_aishell/wav \$data/data_aishell/transcript || exit 1;