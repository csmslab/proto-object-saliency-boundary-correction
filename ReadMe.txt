Modified Proto-Object Based Visual Saliency Model (MATLAB code)

This model is a slightly modified version of Russell et al.
The border ownership calculation is changed to reduce false activities along the image boundaries.
The detail is written in T. Uejima, E. Niebur, and R. Etienne-Cummings. "Proto-Object Based Saliency Model with Second-Order Texture Feature", BioCAS2018.

===============================================================================
How to Use

(1) Add the folder of "ProtoObjectSaliencyBC" and its subfolders to your MATLAB path.
(2) Run "result=runProtoSal('filename')"

===============================================================================
References

1. T. Uejima, E. Niebur, and R. Etienne-Cummings, “Proto-Object Based Saliency Model with Second-Order Texture Feature,” in 2018 IEEE Biomedical Circuits and Systems Conference (BioCAS), 2018, pp. 1–4.
2. A. F. Russell, S. Mihalaş, R. von der Heydt, E. Niebur, and R. Etienne-Cummings, “A model of proto-object based saliency,” Vision Res., vol. 94, pp. 1–15, 2014.