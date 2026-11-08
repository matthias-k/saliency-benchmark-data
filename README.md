# MIT/Tübingen Saliency Benchmark: test images

Test images of the [MIT/Tübingen Saliency Benchmark](https://saliency.tuebingen.ai) datasets, packed for
download, so that you can compute your model's predictions and submit them
(see the [submission instructions](https://saliency.tuebingen.ai/submission.html)).
The files are attached to the [releases](../../releases) of this repository.

Only the images are included. The fixations on the test images are held out; all scores on the
benchmark come from our evaluation.

| Dataset | File | Images | Size |
|---|---|---|---|
| COCO-Freeview | `COCO-Freeview_test_images.zip` | 1000 | 374 MB |

MIT300 and CAT2000 test images are hosted by MIT, see the
[submission instructions](https://saliency.tuebingen.ai/submission.html).

The archives contain the original image files, unchanged, in one folder per dataset, and a
README.txt with sources and citations. Name your
prediction files like the images (see the submission instructions).

SHA-256 checksums:

```
a427c382080ae791b7c3e119bd9caed5dc45f1c221cda9cdab8470c4be4dd08a  COCO-Freeview_test_images.zip
```

## Sources and citations

If you use the images, please cite the original datasets and respect their terms of use.

**COCO-Freeview**: the 1000 test images of COCO-Freeview, which are part of the COCO-Search18 images
([project page](https://sites.google.com/view/cocosearch/coco-freeview)), taken from
[MS COCO](https://cocodataset.org) (images from Flickr, see the
[COCO terms of use](https://cocodataset.org/#termsofuse)).

- Chen, Y., Yang, Z., Chakraborty, S., Mondal, S., Ahn, S., Samaras, D., Hoai, M., & Zelinsky, G. (2022).
  Characterizing Target-absent Human Attention. CVPR Workshops, 5027–5036.
  https://doi.org/10.1109/cvprw56347.2022.00551
- Chen, Y., Yang, Z., Ahn, S., Samaras, D., Hoai, M., & Zelinsky, G. (2021). COCO-Search18 fixation dataset
  for predicting goal-directed attention control. Scientific Reports, 11.
  https://doi.org/10.1038/s41598-021-87715-9

Please also cite the benchmark when you report its scores, see https://saliency.tuebingen.ai.
