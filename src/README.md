using ELmo word embeddings and many sentence embedding techniques(MR, Random-BiLSTM, tf-idf weighted)

func_XX : the packages to be imported, stores useful functions
get_XXX_elmo/embedding: use tensorflow to donwload elmo embeddings of dataset
MR_XX: use MR sentence embedding techniques on elmo embeddings(A simple but tough to beat...)
random_bilstm_XXX: use  Random-BiLSTM
train_elmo,val_test_elmo: max,ave,concat of elmo embeddings classification use svm and mlp
test_XX: maybe useless
