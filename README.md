# This is an early prototype for the ADIPEC paper "Applying Machine Learning NLP Algorithm for Reconciliation Geology and Petrophysics in Rock Typing"
## Please check the paper in this repo  📄spe-216223-ms-2.pdf or here: [Applying Machine Learning NLP Algorithm for Reconciliation Geology and Petrophysics in Rock Typing](https://www.researchgate.net/publication/374382818_Applying_Machine_Learning_NLP_Algorithm_for_Reconciliation_Geology_and_Petrophysics_in_Rock_Typing?utm_source=twitter&rgutm_meta1=eHNsLWc5TklQQmZ2Ym85MWVHWmp3UEg5eXRGcWNYVnoyWWUvdmhwdm9uOExVT1gxdHdiVEFZL3JrZDI2RHBCWGNBYTVTazFkV0NKTmVHZ2JEZXhqclZuNU9Ydz0%3D)

# thinSectionDescripToLASCII

**Problem**:    almost impossible to use thin section description for rock typing. Lots of plain text of every sample needed to be read.

**Aim**:        improve rock typing to improve "Porosity-Permeability"

**Solution**:   convert the text using pattern recognition, plain text => squared logs

**Tools**:      large language model (LLM) -- Open AI API (model = 'gpt-3.5-turbo')

**How**:        parameter = noun, value of the parameter = adjective describing the noun

![image](https://user-images.githubusercontent.com/64559090/226631352-445649aa-d128-4e82-a85e-bb8c743e5750.png)
