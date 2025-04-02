Calculating DELAB (CIEDELAB) and CIEDE2000 is essential in color science because these metrics provide a quantifiable assessment of color differences as perceived by the human eye. DELAB, based on the CIE Lab* color space, serves to evaluate color variations in a way that aligns more closely with human vision, accounting for factors such as luminance and chromaticity. DE2000, an advanced revision of DELAB, incorporates additional adjustments to better reflect perceptual uniformity and handle color discrepancies more accurately. These calculations are crucial in various applications, including quality control in manufacturing, color matching in design, and medical imaging, ensuring consistency and fidelity in color representation across different contexts. Understanding and accurately measuring color differences helps industries uphold standards and meet consumer expectations, affirming the significance of these calculations in color science.


# Calculate Delta ELAB (XYZ2DeltaElab.m)
This function calculates the delta E LAB between two sets of XYZ values


# Calculate Delta E 2000 (DE2000.m)
This function (DE2000) calculates color difference between an Lab_r (from Actual reflectance) and Lab_Pr (from XYZ predicted) representing actual reflectance and predicted reflectance under specified illuminants and observers. It processes the input XYZ values to convert them into LAB color space using the CIE color matching functions and the specified illuminant, allowing for a perceptually relevant assessment of color differences. 
