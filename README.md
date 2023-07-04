# LocalEnergyImage-Paper-With-Code
Local energy-based image region segmentation using Legendre polynomials

This repository presents an algorithm for local energy-based image to be used with the L2S or Krawtchouk segmentation algorithm. While traditional segmentation algorithms rely solely on pixel intensities, they often struggle to accurately segment textured or heterogeneous images. To address this limitation, we leverage the local energy of the image as a representative factor for textured images. By calculating the energy of the image within a window, based on the sum of squares of components in the gray level co-occurrence matrix, we capture the spatial relationship between pixel intensities.
The energy of an image ranges from zero to one, depending on its complexity. In homogeneous images, low-frequency components dominate and result in higher energy values. However, strong boundaries in the image can divide homogeneous regions into smaller parts, reducing their energy. By utilizing local energy, we achieve a more suitable representation of the image for segmentation purposes. The energy is calculated for each window, and the image is segmented based on the energy of each window, allowing for accurate identification of regions. Additionally, the local energy approach considers the complexity of the image by taking into account the spatial relationship between pixel intensities. As a result, it effectively displays and segments textured images. To accomplish this, we inject the locally calculated energy into the L2S or Krawtchouk algorithms. This approach enables the creation of an energy function in the domain of the reproduced image.Top of Form

If you find this work useful in your research, please consider citing the following paper:

M. Mahmoudian and M. Niazi, "Local energy-based image region segmentation using Legendre polynomials," J. Electron. Imaging, vol. 32, no. 3, p. 033016, Jun. 2023.
You can access the paper at: 

 https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-32/issue-3/033016/Local-energy-based-image-region-segmentation-using-Legendre-polynomials/10.1117/1.JEI.32.3.033016.short?SSO=1

