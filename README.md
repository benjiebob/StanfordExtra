# StanfordExtra
12k labelled instances of dogs in-the-wild with 2D keypoint and segmentations. 

Dataset released with our ECCV 2020 paper: *Who Left the Dogs Out? 3D Animal Reconstruction with Expectation Maximization in the Loop*.

- [Project page](https://sites.google.com/view/wldo/home)
- [Paper](https://arxiv.org/abs/2007.11110)

![](splash.png)

## Download

To use StanfordExtra you will require the annotations and the original images files. 

- Annotations are available by filling in the [Google form](https://forms.gle/sRtbicgxsWvRtRmUA). On completion, you will receive an email with the download link.
- Images are available as a downloadable by visiting the [Stanford Dogs](http://vision.stanford.edu/aditya86/ImageNetDogs/) webpage. Download the "Images" tar file.

## Installation

- The `demo.ipynb` code can be adapted work with the full StanfordExtra dataset. To do this, editing the following lines to match with your Stanford Dogs download and your StanfordExtra download:

```
# edit this to the location of the extracted StanfordDogs tar file (e.g. /.../Images).
img_dir = "sample_imgs"

# edit this to the location of the downloaded full dataset .json
json_loc = "StanfordExtra_sample.json"
```

## Methods using StanfordExtra

You may be interested in our work performing monocular 3D shape and pose reconstruction for animal subjects. If so, check out the following repositories:

- [Who Left the Dogs Out?](https://github.com/benjiebob/WLDO)
- [SMALify](https://github.com/benjiebob/SMALify)

If you have a method that makes use of StanfordExtra please do [let us know](mailto:bjb56@cam.ac.uk;ob312@cam.ac.uk)! Community feedback greatly helps us justify future dataset work.

## Versioning
Version | Date | Comment
--- | --- | ---
StanfordExtra_V12 | 01 Feb 2021 | Added missing validation set images, added WLDO splits, fixed compressed segmentations
StanfordExtra_V1 | 01 Sept 2020 | Original dataset release

## Comments
You may also find the other datasets useful for your animal work:
- [Animal Pose Dataset](https://sites.google.com/view/animal-pose/)
- [RGBD-Dog Dataset](https://github.com/CAMERA-Bath/RGBD-Dog)
- [BADJA](https://github.com/benjiebob/BADJA)

We are also delighted to hear about your animal-related research! Please do visit [Ben's webpage](http://www.biggs.ai) if you would like to get in touch.

## Acknowledgements

If you make use of this annotation dataset, please cite the following paper:

```
@inproceedings{biggs2020wldo,
  title={{W}ho left the dogs out?: {3D} animal reconstruction with expectation maximization in the loop},
  author={Biggs, Benjamin and Boyne, Oliver and Charles, James and Fitzgibbon, Andrew and Cipolla, Roberto},
  booktitle={ECCV},
  year={2020}
}
```

and the [Stanford Dog Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) from which the images are derived:

```
@inproceedings{KhoslaYaoJayadevaprakashFeiFei_FGVC2011,
  author = "Aditya Khosla and Nityananda Jayadevaprakash and Bangpeng Yao and Li Fei-Fei",
  title = "Novel Dataset for Fine-Grained Image Categorization",
  booktitle = "First Workshop on Fine-Grained Visual Categorization, IEEE Conference on Computer Vision and Pattern Recognition",
  year = "2011",
  month = "June",
  address = "Colorado Springs, CO",
}
```

## Licensing
(c) Benjamin Biggs, Oliver Boyne, James Charles, Andrew Fitzgibbon and Roberto Cipolla. Department of Engineering, University of Cambridge 2020

By downloading this dataset, you agree to the [Creative Commons Attribution-NonCommercial 4.0 International license](https://creativecommons.org/licenses/by-nc-sa/4.0/). This license allows users to use, share and adapt the dataset, so long as credit is given to the authors (e.g. by citation) and the dataset is not used for any commercial purposes.

THIS SOFTWARE AND ANNOTATIONS ARE PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

