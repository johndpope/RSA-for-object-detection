# RSA for object detection

Codebase for Recurrent Scale Approximation for Object Detection in CNN in ICCV 2017, [[arXiv]](PDF is coming soon). Here we provid the training and testing code for `scale-forecast network` and `recurrent scale approximation unit (RSA)`. Meanwhile models for face detection trained on some open datasets are also provided for a quick demo.

Please follow the steps below:

## Directory structure

`train/`: Training code for `scale-forecast network` and `RSA`

`predict/`: Predicting code for whole pipeline.

`afw_gtmiss.mat`: Revised annotation mentioned in `Sec.4.1`

## Runing training code

Training code will be released soon, stay tuned  :)

## Runing testing code

1. Compile [CaffeMex_v2](https://github.com/sciencefans/CaffeMex_v2/) with matlab interface 

2. Add `CaffeMex_v2/matlab/` to matlab searching path

3. See tips in `predict/script_start.m` and run

4. After processing for few minutes, the detection and alignment results will be shown on a image window. Please click the image window for viewing all results.


## Q&A


## Still having questions?

Feel free to drop us an email sharing your ideas.

## Citation
Please kindly cite our work in your publications if it helps your research:

    @inproceedings{liu_2017_recurrent,
      Author = {Yu Liu, Hongyang Li, Junjie Yan et al.},
      Title = {Recurrent Scale Approximation for Object Detection in CNN},
	  Journal = {IEEE International Conference on Computer Vision},
	  Year = {2017}
    }
