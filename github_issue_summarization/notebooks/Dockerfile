FROM gcr.io/kubeflow-images-public/tensorflow-1.6.0-notebook-cpu
RUN pip install ktext
RUN pip install annoy
RUN pip install --upgrade google-cloud
RUN pip install sklearn h5py
RUN pip install nltk
RUN pip install matplotlib
RUN pip install pydot

COPY train.py /workdir/train.py
COPY trainer.py /workdir/trainer.py
COPY seq2seq_utils.py /workdir/seq2seq_utils.py
