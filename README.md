# <center>Digit Recognition Task</center>
<div style="text-align: center;">
    <div style="display: inline-block; text-align: left;">
        Time：2024.5.11<br>
        HUST Machine Learning
    </div>
</div>

### File Structure<br>
· `experiment`: Entry function is defined in this file with single parameter `train`. While setting `True`, program will read csv file and reference.<br><br>
· `evaluate`: This section will load parameter from `params/model.json` and invoke `utils.Evaluate` for evaluation. Result will be printed on screen.<br><br>
· `train`: This section is a simple implementation of method and class for training model.<br><br>

| Folder     | Function      | Files                                                                  |
|------------|---------------|------------------------------------------------------------------------|
| layers     | nerual network definition       | AvgPooling、Conv2d、DepthWise、Linear、Relu                                | 
| data       | training & evaluation set     | test.csv、train.csv                                                     | 
| outputs    | output files  | ...                                                                    | 
| params     | loading parameter        | model.json、model.pt                                                    |  
| other_mode | other model implementation    | SVM、DescisionTree                                                      | 



