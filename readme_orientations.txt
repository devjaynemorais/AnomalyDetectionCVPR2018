# Crie um ambiente anaconda python 3.5
jayne@jayne-X555LD:~/Documentos/MESTRADO/PESQUISA/AnomalyDetectionCVPR2018$ conda create -n AnomalyDetectio
nCVPR2018 python=3.5 anaconda

# Liste todos seus ambientes conda
(AnomalyDetectionCVPR2018) jayne@jayne-X555LD:~/Documentos/MESTRADO/PESQUISA/AnomalyDetectionCVPR2018$ cond
a env list

# Ative seu ambiente criado
jayne@jayne-X555LD:~/Documentos/MESTRADO/PESQUISA/AnomalyDetectionCVPR2018$ source activate AnomalyDetectio
nCVPR2018

# Instale as dependências
(AnomalyDetectionCVPR2018) jayne@jayne-X555LD:~/Documentos/MESTRADO/PESQUISA/AnomalyDetectionCVPR2018$ pip
install -r requirements.txt

# Mude o Back-end para o Theano
$ cd $HOME
$ cd .keras/
$ nano keras.json
>> substitua 'tensorflow' por 'theano'