# Proteomics
Information on my proteomics analyses

# Installing FragPipe and DIA-NN

Create a `fragpipe` conda env:

```{}
conda create -n fragpipe
```

Then activate when ready:

```{}
conda activate fragpipe
```

Inatall FragPipe:

```{}
conda install -c bioconda fragpipe
```

Run `fragpipe --help`:

```{}
fragpipe --help                                         
                                                                                                                   
Please accept the academic license.                                                                                
                                                                                                                   
FragPipe uses tools that are available freely for academic research and educational purposes only.                 
                                                                                                                   
Please provide license keys for MSFragger and IonQuant with the --msfragger_key and --ionquant_key flags. By passing these, you verify that you have read the ACADEMIC licenses for the MSFragger and IonQuant tools. You may obtain these keys by agreeing to the terms at http://msfragger-upgrader.nesvilab.org/upgrader/ and https://msfragger.arsci.com/ionquant/.     
```

You will need to acquire academic use licence keys for MSFragger and IonQuant

* Go to: [MSFragger](http://msfragger-upgrader.nesvilab.org/upgrader/). Fill out your information, accept the agreements, and ask for a licence key (check the box). Copy this and save.

* Go to: [IonQuant](https://msfragger.arsci.com/ionquant/)


