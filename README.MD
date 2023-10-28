# Defending Object Detection Models against Image Distortions 
# Official implementation![Overview of prposed method](figures/AIS-I_flowchart.png)

## News

**`23-10-2023`**: The paper is accepted at WACV2024


## Installation
Our code is built upon the code provided by [Michaelis et al.](https://github.com/bethgelab/imagecorruptions). To 
use our code, first install the neccesary libraries by following the steps detailed [here](https://github.com/bethgelab/imagecorruptions).

## Run
* Specify the input path to the folder containing images for generating distorted samples in ``` sav_path = ``` in ``` main ```.
* Specifiy the txt file with absolute path of all the input images and replace this txt file with ``` input_images_list.txt ```.


## Citation
Please consider cite if our work is useful for your research:

```Bibtex
@InProceedings{Oduro2024Def,
  author       = "Mark Ofori-Oduro and Maria Amer",
  title        = "Defending Object Detection Models against Image Distortions",
  booktitle    = "IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) ",
  year         = "2024",
  pages        = "8",
  month        = "Jan. 4-8",
  address      = "Waikoloa, Hawaii",
}
```


DISCLAIMER:
This software is provided by the copyright holders and contributors "as is" and any express or implied warranties, including, but not  limited to, the implied warranties of merchantability and fitness for 
a particular purpose are disclaimed. In no event shall the Concordia University, Vidpro Lab members, or 
contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or 
profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.