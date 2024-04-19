# Urban Water Detection

The orginal dataset, *Landcover.ai* was obtained as .tif files of approximately 9000 (x) 9000 resolution and the necessary features were mined using techniques described in the Research Paper. Then a single image was cropped into 500 images, on average, with 500(x)500 resolution. Using the masks (with 4 labels given in the dataset were Building; Water; Road and Background) given in the dataset, the images that contained water were separated. Then these images were manually labelled into four categories, namely Lake; River; Small River and Paddy Fields and used as Dataset for the mask RCNN model. 
