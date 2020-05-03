Python 3.5.5 :: Anaconda, Inc.
-------------------
LAB:

(base) jayne@lpc:~/Documentos/FineTuning$ pwd
/home/jayne/Documentos/FineTuning


--------------------
Personal:

(AnomalyDetectionCVPR2018) jayne@jayne-X555LD:~/Documentos/MESTRADO/PESQUISA$ jupyter notebook

--------------------

New Machine:

Clone o repositório a seguir:
`git clone https://github.com/devjaynemorais/AnomalyDetectionCVPR2018`


Crie um ambiente de nome 'Env_ExtractFeaturesC3D' com base no env 'Env_ExtractFeaturesC3D.yml' exportado.
Obs.: Verifique se já não existe um enviroment com esse mesmo nome na sua máquina. Caso já exista, execute `conda env remove --name Env_ExtractFeaturesC3D`

`conda env create -f Env_ExtractFeaturesC3D.yml`

# Mude o Back-end para o Theano
$ cd $HOME
$ cd .keras/
$ nano keras.json
>> substitua 'tensorflow' por 'theano' na variável 'backend'

Ative o seguinte enviroment: `source activate Env_ExtractFeaturesC3D`

Execute `jupyter notebook` no terminal e abra o arquivo `ExtraindoAtivacoesModeloComNovidade-vfinal`

Obs.: Atente para os paths de diretório, é necessário modificar de acordo com seu usuário.

Output: Arquivo .csv gerado pela notebook de extração de ativações.


Obs.: Os arquivos com as características C3D extraídas do DATASET UCF-Crimes encontram-se disponíveis para download em: https://www.dropbox.com/s/af6kmpu6zwcuump/out-20190514T004829Z-001.zip?dl=0

Links relacionados dos downloads: 
https://github.com/rajanjitenpatel/C3D_feature_extraction
https://github.com/WaqasSultani/AnomalyDetectionCVPR2018/issues/39
https://www.gitmemory.com/karliell
