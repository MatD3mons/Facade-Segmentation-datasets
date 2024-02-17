# FacadeSegmentation

https://imagine.enpc.fr/~marletr/publi/PAMI-2018-Gadde-et-al.pdf

## Requirement

```
sudo apt install unzip
```

## eTRIMS Image Database

The eTRIMS dataset consists of 60 non-rectified images. Facades in this dataset are more irregular and follow only weak architectural principles. Again, we split the data into 5 equal sets for cross-validation.

```
wget https://www.ipb.uni-bonn.de/projects/etrims_db/downloads/etrims-db_v1.zip -O eTRIMS.zip
unzip eTRIMS.zip
```

| eTRIMS     | Images | Objects |
|------------|--------|---------|
| Building   | 60     | 142     |
| Car        | 27     | 67      |
| Door       | 53     | 85      |
| Pavement   | 56     | 76      |
| Road       | 49     | 51      |
| Sky        | 60     | 71      |
| Vegetation | 56     | 194     |
| Window     | 60     | 1016    |
| Total      | 60     | 1702    |

```
@techreport{ korc-forstner-tr09-etrims,
             author = "Kor{\v c}, F. and F{\" o}rstner, W.",
             title = "{eTRIMS} {I}mage {D}atabase for Interpreting Images of Man-Made Scenes",
             number = "TR-IGG-P-2009-01",
             month = "April",
             year = "2009",
             institute = "Dept. of Photogrammetry, University of Bonn",
             url = "http://www.ipb.uni-bonn.de/projects/etrims_db/" }
```