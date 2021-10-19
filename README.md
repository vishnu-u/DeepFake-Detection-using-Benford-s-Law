# DeepFake Detection using Benford's Law
<p style="text-align:justify;">This project aims at using Benford's law to detect DeepFake images by visualizing the Benford's Curve and evaluating the distribution difference between original Benford's Distribution and the Benford's Distribution of suspected GAN image. The Benford's Curve gives a visual analysis while the test statistic gives a numerical analysis of the image.
The following experimentations have been conducted :
<ul style="margin-top : 0px;padding-top : 0px;">
        <li>Setup a GAN network to generate images</li>
        <li>Analyze different transform functions for Benford's law and choose the best one</li>
        <li>Analyze generated and real images using Benford's law</li>
        <li>Find deviation of image using Deviance tests - KS test, Chi-square test and Euclidean Distance test</li>
        <li>Find a deepfake to analyze it using deviance test</li>
     </ul>
</p>

<p>Published Paper : https://www.irjet.net/archives/V8/i10/IRJET-V8I10113.pdf</p>
## Running the project
<p>
Clone the repository and execute <i>main.py.ipynb</i> on a Jupyter Notebook Platform (Or any platform that supports Python Noteboooks).
</p>
