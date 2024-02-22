## Optimized E-PIX configuration for a cancer registry (Example)

### About
This configuration was created as part of a final thesis on the optimization of record linkage processes in a cancer registry using the example of the [Clinical Cancer Registry Mecklenburg Western Pomerania](https://www.kkr-mv.de/).

### Details
The tests carried out with a reference data set using this configuration were able to achieve a high link quality with a recall of 0.9992 and a precision of 0.9978. These results indicate that synonym errors can be reliably detected using this configuration and that only a few false positive results are obtained.
In addition, the configuration is able to take into account certain criteria that can lead to linking errors, including typos, transposed digits, twin pairs and the different use of diacritics. In particular, the configuration stands out for its ability to reliably and correctly identify multiple value fields. 

### Special features
High link quality with reference data set: Recall 0.9992, Precision 0.9978 
- Reliable identification of synonym errors
- Minimal number of false positive results

Consideration of criteria that can lead to linking errors:
- Typing errors
- transposed digits
- Twin pairs
- Different data formats
- Different use of diacritics

Special strength: Reliable correct identification of multiple value fields

### E-PIX
![Download E-PIX](https://www.ths-greifswald.de/en/researchers-general-public/e-pix/)

### Configuration

![Configuration-File](https://github.com/ths-community/E-PIX-example-configurations/blob/main/cancer-registry/matching-config-for-domain-CancerRegistry.xml)

### Contact
Date: 2024-02-22
Contact person: Aileen Stehn
