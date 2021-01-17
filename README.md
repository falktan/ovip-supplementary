# OViP - Supplementary Material

This is some supplementary material for OViP, which is here:
[https://github.com/falktan/ovip](https://github.com/falktan/ovip)

## Sample usage
When opening the app, it allows to take a photo.

<img src="img\processing.jpg" height="400">

It then applies optical character recognition (OCR) to make the text available for usage.

<img src="img\finished.jpg" height="400">

Any text can be marked and be copied. If it is a URL also an option to directly open it in the browser is provided.

<img src="img\marked_url.jpg" height="400">

Similarily, if it is a phone number it can directly be called.

<img src="img\marked_number.jpg" height="400">

## Benchmark

In this section OViP is compared to Google Lens.
The main advantage of OViP over Google Lens is, that it does not need to send data to any third party and that it is open source. In addition it also works offline.

To compare the performance when recognizing text, a couple of samples were taken and the results compared.
Not too surprisingly Google Lens performs much better.

Here are screenshots of how Google Lens performed. It recognized all examples correctly

<img src="img\lens_01.jpg" height="400">
<img src="img\lens_02.jpg" height="400">
<img src="img\lens_03.jpg" height="400">

All further images listed here were correctly recognized by Google Lens, so to avoid too many images they will not be added here. Instead we focus on what OViP did or did not recognize.

Here are a couple of images that OViP did recognize correctly. All of those were fairly simple tasks:

<img src="img\ovip_01_processing.jpg" height="400">
<img src="img\ovip_01_finished.jpg" height="400">

<img src="img\ovip_02_processing.jpg" height="400">
<img src="img\ovip_02_finished.jpg" height="400">

<img src="img\ovip_03_processing.jpg" height="400">
<img src="img\ovip_03_finished.jpg" height="400">

Here is an example of an image that was not recognized correctly

<img src="img\ovip_04_processing.jpg" height="400">
<img src="img\ovip_04_finished.jpg" height="400">

In the following image, OViP did not recognize the text at all (below 0.5 threshold):

<img src="img\ovip_05_finished.jpg" height="400">

So in summary, OVIP recognized 3 of those 5 examples correctly. It recognized one partially and one not at all. Google Lens did recognize all of those images correctly.
Hence, there is clearly room for improvement on the algorithms used for OViP.
On the upside, at least for images taken under good conditions, OViP already proved to work.
