# tensornetwork-project-4--data-compression-with-quantum-fourier-transform-solved
**TO GET THIS SOLUTION VISIT:** [TensorNetwork Project 4- Data compression with quantum Fourier transform Solved](https://www.ankitcodinghub.com/product/tensornetwork-data-compression-with-quantum-fourier-transform-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126142&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;TensorNetwork Project 4- Data compression with quantum Fourier transform Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
The Fourier Transform is the cornerstone of frequency analysis and the fundamental step in many signal processing algorithms, from noise cancelling to audio and image compression. By working in the Fourier space, we can optimally approximate an input signal, for example, by cutting the frequencies that are not visible/audible by a human. This is the basic principle behind lossy image (JPEG) and audio (MPEG) compression, which gave us the ubiquitous jpg and mp3 codecs that we are so familiar with.

The best available (classical) implementation of the Fourier transform is the Fast Fourier Transform (FFT) algorithm. Despite being highly optimized, it scales as $O(Nlog_2N)$, where $N$ is the number of entries of the vector we are considering. Without loss of generality, we constraint ourselves in the case $N=2^n$, such that the FFT scaling can be expressed as $O(2^nn)$. Interestingly, the quantum version of the Fourier transform (QFT), presents an exponential speedup in the scaling $O(n^2)$, where we can now identify $n$ with the number of qubits. For this reason, the QFT is at the basis of many quantum algorithms, such as the celebrated Shor’s algorithm, over classical methods for the notoriously complex problem of number factorisation.

In this project we will tackle the compression of images using the standard JPEG compression codec. First, we will use the classical FFT algorithm and then, we will implement the QFT algorithm using matrix product operators on qmatchatea. While a speedup is not guaranteed when running the QFT on a classical machine, an advantage is achievable when processing sufficiently large signals, or by running the algorithm on a real quantum device.

drawing

Tasks

Implement the JPEG image compression algorithm using the FFT.

Write the quantum circuit, implement the QFT algorithm in qiskit.

Modify the application of the FFT in the JPEG algorithm with a QFT.

Apply the algorithm to different images and different scales. Compare the computational time and the scaling for the classical FFT and the

QFT.

[OPTIONAL] Repeat the analysis for the approximate QFT, studying the dependency of the results in the approximation factor.
