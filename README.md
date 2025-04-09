<h1>Fingerprint Liveness Detection Using an Improved CNN</h1>

<h2>Overview</h2>
<p>This project implements the methods described in the paper titled <strong>"Fingerprint Liveness Detection using An Improved CNN with Image Scale Equalization."</strong> The aim of this project is to enhance fingerprint authentication systems by effectively detecting live fingerprints and preventing spoofing attacks. The proposed method utilizes an improved Deep Convolutional Neural Network (DCNN) that incorporates image scale equalization to preserve texture information and maintain image resolution.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#performance-evaluation">Performance Evaluation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>Fingerprint authentication systems are increasingly vulnerable to spoofing attacks, where unauthorized individuals use artificial replicas to impersonate legitimate users. This project addresses these vulnerabilities by implementing a fingerprint liveness detection (FLD) method that leverages deep learning techniques. The proposed DCNN model aims to improve the accuracy of fingerprint recognition by effectively distinguishing between live and fake fingerprints.</p>

<h2 id="features">Features</h2>
<ul>
    <li><strong>Improved Deep CNN Architecture:</strong> Utilizes advanced convolutional neural networks for better feature extraction.</li>
    <li><strong>Image Scale Equalization:</strong> Preserves important texture details and enhances image resolution.</li>
    <li><strong>Adaptive Learning Rate:</strong> Implements an adaptive learning rate to optimize training efficiency.</li>
    <li><strong>Performance Metrics:</strong> Employs confusion matrices as performance indicators for evaluating detection accuracy.</li>
</ul>

<h2 id="installation">Installation</h2>
<p>To set up the project, follow these steps:</p>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/peyman-dashtestani/Fingerprint-Liveness-Detection-Using-an-Improved-CNN.git
cd Fingerprint-Liveness-Detection-Using-an-Improved-CNN
        </code></pre>
    </li>
    <li>Install the required dependencies:
        <pre><code>pip install -r requirements.txt
        </code></pre>
    </li>
    <li>Ensure you have the necessary libraries installed for image processing and deep learning.</li>
</ol>

<h2 id="usage">Usage</h2>
<p>To run the fingerprint liveness detection model, use the following command:</p>
<pre><code>python main.py --input &lt;path_to_fingerprint_image&gt;
</code></pre>
<p>Replace &lt;path_to_fingerprint_image&gt; with the path to the fingerprint image you wish to analyze.</p>

<h2 id="performance-evaluation">Performance Evaluation</h2>
<p>The model's performance is evaluated using datasets such as LivDet 2011 and LivDet 2013. The results demonstrate that the proposed method outperforms traditional approaches in terms of accuracy and robustness against spoofing attacks.</p>

<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your improvements or bug fixes.</p>










