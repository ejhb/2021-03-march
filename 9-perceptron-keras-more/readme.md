# Neural Network,  Perceptron, Keras and more

Etude du perceptron

* https://lucidar.me/fr/neural-networks/simplest-perceptron/

Etudier et reproduire les 2 tutos, de regréssion linéaire et non-linéaire de Lulu

* https://lucidar.me/fr/neural-networks/curve-fitting-nonlinear-regression/

Exercices poursuivant le tuto de régression non-linéaire : 

* Modifier le nombre de layer cachée et de nombre d'unit sur les layer : qu'observer vous au niveaux des performances (utiliser la MSE)
* Trouver un moyen d'afficher la convergences du modéles aux cours des itérations (afficher le dans un graphique).
* Modifier le modéle pour pouvoir apprendr le modéle sur des données en deux dimensions (un plan) (afficher ce plan et la version apprise du modéle.)

# Veilles

activation function

* https://machinelearningmastery.com/choose-an-activation-function-for-deep-learning/
* https://deeplylearning.fr/cours-theoriques-deep-learning/fonction-dactivation/

hidden layer/design

* https://machinelearningmastery.com/how-to-configure-the-number-of-layers-and-nodes-in-a-neural-network/
* https://towardsdatascience.com/beginners-ask-how-many-hidden-layers-neurons-to-use-in-artificial-neural-networks-51466afa0d3e

Dropout /Regularisation

* https://stackoverflow.com/questions/53893206/how-to-create-a-sparse-layer-in-keras-i-e-not-all-neurons-are-connected-to-eac
* https://keras.io/api/layers/regularization_layers/dropout/


Solver/optimizer

* https://medium.datadriveninvestor.com/overview-of-different-optimizers-for-neural-networks-e0ed119440c3
* https://mlfromscratch.com/optimizers-explained/
* https://datascience.stackexchange.com/questions/10523/guidelines-for-selecting-an-optimizer-for-training-neural-networks



# Dependencies

install keras and tensorflow

Note: If you encounter some issue installing tensorflow with python3.9 (and pip), as sugested here link :

    https://stackoverflow.com/questions/62830862/how-to-install-python3-8-on-debian-10


Jupyter notebook failed to launch. 
Error: Traceback (most recent call last):
  File "/home/joshua/.vscode/extensions/ms-toolsai.jupyter-2021.3.619093157/pythonFiles/vscode_datascience_helpers/daemon/daemon_python.py", line 54, in _decorator
    return func(self, *args, **kwargs)
  File "/home/joshua/.vscode/extensions/ms-toolsai.jupyter-2021.3.619093157/pythonFiles/vscode_datascience_helpers/jupyter_daemon.py", line 108, in m_exec_module_observable
    self._start_notebook(args, cwd, env)
  File "/home/joshua/.vscode/extensions/ms-toolsai.jupyter-2021.3.619093157/pythonFiles/vscode_datascience_helpers/jupyter_daemon.py", line 154, in _start_notebook
    from notebook import notebookapp as app
  File "/home/joshua/anaconda3/lib/python3.8/site-packages/notebook/notebookapp.py", line 64, in <module>
    raise ImportError(_("The Jupyter Notebook requires tornado >= 5.0, but you have %s") % tornado.version)
ImportError: The Jupyter Notebook requires tornado >= 5.0, but you have 4.5.3

Failed to run jupyter as observable with args notebook --no-browser --notebook-dir="/home/joshua/Documents/git-workspace" --config=/tmp/4a08aa38-06d3-4cf5-aff4-0eeba526bec0/jupyter_notebook_config.py --NotebookApp.iopub_data_rate_limit=10000000000.0