# Watermarking
Combined DWT-DCT Digital Image Watermarking
DWT-DCT digital picture watermarking system that is undetectable and reliable. 
The algorithm uses a combination of the Discrete Wavelet Transform (DWT) and the Discrete Cosine Transform (DCT) to watermark a given digital image.
The watermarking methods that just use the DWT transform perform better when the two transforms are combined, according to performance evaluation results.
Digital watermarking is anticipated to have numerous real-world uses, including those in picture databases, digital cameras, medical imaging, and video-on-demand services. 
When it comes to typical picture modifications like compression, filtering, rotation, scaling, cropping, collusion assaults, and many other digital signal processing operations, a digital watermarking technique must be undetectable and resistant to them all. 
In numerous applications of digital signal processing, the DCT and DWT transforms have been widely used. 
We briefly describe the two transformations in this section and discuss how they apply to the implementation of digital watermarking. 
Both Discrete Cosine Transform (DCT) and Discrete Wavelet Transform (DWT) are signal processing techniques that are widely used for signal analysis, compression, and filtering. 
DCT is commonly used in image and audio compression, where it is used to reduce the amount of data needed to represent an image or audio signal without significantly affecting the quality of the signal.
DCT achieves this by transforming the signal from the time domain to the frequency domain, where the high-frequency components can be discarded or quantized with less precision than the low-frequency components, since they contribute less to the overall signal.
On the other hand, DWT is used for both signal analysis and signal compression. 
The DCT is a type of Fourier transform that transforms a signal from the spatial domain into the frequency domain.
It does this by breaking the signal down into a set of cosine functions with different frequencies, amplitudes, and phases. 
The resulting coefficients represent the signal in terms of its frequency content, rather than its spatial content.
 DCT is applied to the image blocks to convert them from the spatial domain to the frequency domain. 
 The DCT coefficients of the blocks are then modified by adding or subtracting a watermark signal, which is a sequence of bits that represent the copyright or ownership information.
In DWT-based watermarking, the original image is first transformed into its wavelet coefficients using the DWT.
The wavelet coefficients are then modified by adding the watermark to specific coefficients, which are chosen based on their perceptual importance. 
The modified wavelet coefficients are then transformed back into the original image using the inverse DWT to produce the watermarked image.
The main advantage of DWT-based watermarking is that it can provide good frequency localization of the watermark, which can improve the robustness of the watermark against common signal processing attacks such as compression and noise addition. 
