Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-2
<br>
<ol>

 <li>Use a program of your choice (Matlab, your own, etc) to generate ten 256×256 images with graylevel 128 corrupted with additive, zero-mean Gaussian noise with standard deviation 2.0. Use the procedures EST NOISE in Chapter 2 of Trucco and Verri, to estimate the noise in the images. Discuss your results. Note: do not discard the images as you will use them in the next problem.</li>

 <li>Filter the noisy images generated for the previous problem with a 3×3 box filter. Use EST NOISE to estimate the noise of the output images. Discuss your results.</li>

 <li>Generate a 2D Gaussian filter mask with standard deviation 1.4. Find two equivalent 1-D masks sothat they can be used to smooth images applying the separability property.</li>

 <li>Consider the following two averaging filters used to clean images:</li>

</ol>

<table width="116">

 <tbody>

  <tr>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="23">1</td>

   <td width="23">1</td>

  </tr>

 </tbody>

</table>

<u>1</u>

5Avg. Filter (a)

<table width="116">

 <tbody>

  <tr>

   <td width="23">1</td>

   <td width="23">2</td>

   <td width="23">4</td>

   <td width="23">2</td>

   <td width="23">1</td>

  </tr>

 </tbody>

</table>

<u>1</u>

10Avg. Filter (b)

<ul>

 <li>An 1 × 10 image <em>I</em>ˆ(<em>x</em>) has gray level values as follows:</li>

</ul>

<table width="305">

 <tbody>

  <tr>

   <td width="30">10</td>

   <td width="30">10</td>

   <td width="30">10</td>

   <td width="30">10</td>

   <td width="30">10</td>

   <td width="30">40</td>

   <td width="30">40</td>

   <td width="30">40</td>

   <td width="30">40</td>

   <td width="30">40</td>

  </tr>

 </tbody>

</table>

Filter the given image with the average filters (a) and (b) (ignoring the borders).

<ul>

 <li>Compare the two given filters in terms of computational cost and the variance of the noise ofthe filtered images, when they are applied to images with additive, uncorrelated Gaussian noise with zero mean and variance <em>σ</em><sup>2</sup>.</li>

</ul>

<ol start="5">

 <li>An image contains a thin vertical line, one pixel thick. It has a gray level of 50 and lies on a backgroundof salt and pepper noise having gray values of 100 and 0, respectively, where the probability(pepper) = 0.3 and the probability(salt)=0.7, and the probability of salt and pepper are independent of each other. A horizontal 1×3 operator with values (-1,2,-1) is applied to this image. Find the probability distribution for the output values when the operator is centered at a pixel: on the line adjacent to the line</li>

 <li>An 8×8 image <em>I</em>(<em>i,j</em>) has pixel values following the equation <em>I</em>(<em>i,j</em>) = |<em>i </em>− <em>j</em>| with <em>i,j </em>= 0<em>,</em>1<em>,…,</em>7 Find the output image obtained by applying a 3×3 median filter on the image <em>I</em>. (Assume that the border pixels are not changed)</li>

 <li>Consider a 1D step profile</li>

</ol>

Work out the result of applying the median filtering with <em>n </em>= 3 and compare the result with the output of filtering with the averaging mask 1<em>/</em>4[1 2 1].

1