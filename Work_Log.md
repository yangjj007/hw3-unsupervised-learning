# HW3 work log

- Recorded the unchanged starter notebook in local Git before editing.
- Chrome opened the Colab upload dialog. Its file chooser rejected the starter because the extension lacked file-URL access. Continued in a local Jupyter kernel and kept the Colab dialog available for manual upload.
- Implemented the NumPy assignment/update steps and the unsmoothed TF-IDF calculation. Ran Part 1 from a fresh kernel and confirmed the provided shape checkpoint passed and the TF-IDF tables rendered.
- Installed UMAP locally. Pip reported version conflicts between pre-existing packages unrelated to the notebook. The staged notebook runs did not import the packages named in those warnings.
- Implemented vectorization, K-Means on the shared 50-D features, and inverse-transform top terms. The first dataset load downloaded and cached 20 Newsgroups. The run produced 3,944 initial rows and 3,775 retained documents. Used the output to answer Q2.1–Q2.3, then saved the stage in Git.
- Ran PCA and UMAP on the same 50-D representation and inspected both figures. Recorded trustworthiness of 0.6973 and 0.9565 and silhouette of 0.3105 and 0.3006, respectively. Used those results for Q3.1 and Q3.2.
- Ran the contingency table, majority-vote purity, and the four-panel plot. The run produced 83.66% purity. Checked both rows of the panel against the contingency table before answering Q4.1 and Q4.2.
