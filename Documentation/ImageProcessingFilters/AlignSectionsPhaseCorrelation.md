Align Sections Phase Correlation {#alignsectionsphasecorrelation}
=====

## Group (Subgroup) ##
ImageProcessing (ImageProcessing)

## Description ##
Aligns sections using phase correlation:
   1. Adjacent slices are fourier transformed
   2. Fourier transform of the reference slice is multiplied by the complex conjugate of the moving slice
   3. The result is normalized and inverse fourier transformed
   4. The peak intensity in the resulting image corresponds to the best shift


## Parameters ##
| Name             | Type |
|------------------|------|
| Selected Array | String |


## Required Arrays ##

| Type | Default Array Name | 
|------|--------------------|
| UInt8  | ImageData     |


## Created Arrays ##

None


## Authors: ##

**Contact Info:** Will Lenthe willlenthe@gmail.com

**Copyright:** 2015 BlueQuartz Software, LLC

**Contact Info:** dream3d@bluequartz.net

**Version:** 1.0.0

**License:**  See the License.txt file that came with DREAM3D.




See a bug? Does this documentation need updated with a citation? Send comments, corrections and additions to [The DREAM3D development team](mailto:dream3d@bluequartz.net?subject=Documentation%20Correction)
