This is the software  of our PCWLAD method:

---------------------------------------------------------------------------------------------------
<PCWLAD method is used for paper verification and scientific research>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
----------------------------------------------------------------------------------------------------

Please cite our paper if you use our software for your research. 

This program is provided for research purposes only. Any commercial use is prohibited. If you are interested in a commercial use, please contact the copyright holder. 

You can find gui_pcwladprocess.exe in the release folder and run it. For usage, please refer to GUIDE.gif. The interface design uses QT and is accelerated in parallel. QT source code address: https://github.com/ZhangShuaiH/QT/tree/master/demos/lib. The program is developed on the VS2022 platform, c++. 

Data description:
LC08b2_sub1.tif and LC08B10_sub1.tif, LC08b2_sub2.tif and LC08B10_sub2.tif are well registered, and the registration accuracy is better than 0.04 pixels, which is taken as the true value.
To evaluate the sub-pixel accuracy of the algorithm:
Translate LC08B10_sub1 by -1.4 pixels in the x direction and -1.6 pixels in the y direction to obtain the image LC08B10offset_sub1.tif;
Translate LC08B10_sub2 by -2.7 pixels in the x direction and -2.3 pixels in the y direction to obtain the image LC08B10offset_sub2.tif;
Translate 0040_nir.tiff by 5.5 pixels in the x direction and 6.4 pixels in the y direction to obtain the image 0040_niroffset.tiff;
Translate 0000_nir.tiff by 8.3 pixels in the x direction and 3.6 pixels in the y direction to obtain the image 0000_niroffset.tiff;

Please report bugs to huangtaosaf@csu.edu.cn.

tao huang
2025

