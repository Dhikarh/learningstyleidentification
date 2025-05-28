<h2 data-pm-slice="1 2 []">
    <span>Project Title: Feature Reduction and Visualization for Learning Style Classification</span>
</h2>
<p>
    <span>This repository contains Python scripts and notebooks for dimensionality reduction, feature correlation analysis, model evaluation, and visualization in the context of student learning style classification based on the Felder-Silverman Learning Style Model (FSLSM).</span>
</p>
<h3>
    <span>Contents</span>
</h3>
<ul data-spread="false">
    <li>
        <span><strong>Feature Generation and Labeling</strong>: Synthetic dataset creation and random labeling for experimentation.</span>
    </li>
    <li>
        <span><strong>Feature Selection and Correlation Analysis</strong>: Selection of 18 key features and their correlation heatmaps.</span>
    </li>
    <li>
        <span><strong>Dimensionality Reduction</strong>:</span>
        <ul data-spread="false">
            <li>
                <span>PCA (Principal Component Analysis) for feature compression.</span>
            </li>
            <li>
                <span>t-SNE (t-distributed Stochastic Neighbor Embedding) for visualization.</span>
            </li>
        </ul>
    </li>
    <li>
        <span><strong>Model Evaluation</strong>: Comparison of classification models based on accuracy, precision, recall, and F1-score.</span>
    </li>
    <li>
        <span><strong>Visualization</strong>:</span>
        <ul data-spread="false">
            <li>
                <span>Class distribution pre- and post-dimension reduction.</span>
            </li>
            <li>
                <span>Confusion matrices for top-performing models.</span>
            </li>
            <li>
                <span>Scree plot and heatmaps.</span>
            </li>
        </ul>
    </li>
</ul>
<h3>
    <span>Directory Structure</span>
</h3>
<pre><code class="language-plaintext">├── feature_extraction.py           # PCA, t-SNE, and SVD analysis
├── visualization.py                # All plots and graphs
├── evaluation.py                   # Model metrics and confusion matrix
├── data_synthesis.py               # Synthetic data generation
├── figures/                        # Output visualizations
├── tables/                         # Evaluation and feature analysis tables
└── README.md                       # This file</code></pre>
<h3>
    <span>Getting Started</span>
</h3>
<h4>
    <span>Prerequisites</span>
</h4>
<ul data-spread="false">
    <li>
        <span>Python 3.7+</span>
    </li>
    <li>
        <span>numpy</span>
    </li>
    <li>
        <span>pandas</span>
    </li>
    <li>
        <span>matplotlib</span>
    </li>
    <li>
        <span>seaborn</span>
    </li>
    <li>
        <span>scikit-learn</span>
    </li>
</ul>
<p>
    <span>Install dependencies:</span>
</p>
<pre><code class="language-plaintext">pip install -r requirements.txt</code></pre>
<h4>
<span>Running the Scripts</span>
</h4>
<p>
<span>To perform PCA and visualize results:</span>
</p>
<pre><code class="language-plaintext">python feature_extraction.py</code></pre>
<p>
<span>To generate visualizations (heatmaps, scatter plots):</span>
</p>
<pre><code class="language-plaintext">python visualization.py</code></pre>
<p>
<span>To run model evaluation and print accuracy scores:</span>
</p>
<pre><code class="language-plaintext">python evaluation.py</code></pre>
<h3>
<span>Highlights</span>
</h3>
<ul data-spread="false">
    <li>
<span><strong>Dimensionality Reduction</strong>: From 44 features down to 18 using PCA and correlation thresholds.</span>
    </li>
    <li>
<span><strong>Model Accuracy</strong>: Models were trained and tested pre- and post-reduction, with top accuracy reaching 91.3%.</span>
    </li>
    <li>
<span><strong>Visual Insights</strong>: High-quality t-SNE and PCA plots for interpretability of class clusters.</span>
    </li>
</ul>
<h3>
<span>Example Outputs</span>
</h3>
<ul data-spread="false">
    <li>
<span>Scree Plot for PCA</span>
    </li>
    <li>
<span>t-SNE 2D Scatter Plot showing 4-class distribution</span>
    </li>
    <li>
<span>Heatmaps of selected and original features</span>
    </li>
    <li>
<span>Table summarizing accuracy and feature counts</span>
    </li>
</ul>
<h3>
<span>Repository DOI</span>
</h3>
<p>
<span>This project and dataset are available at Zenodo: <strong>DOI</strong>: </span><a disabled="true"><span>10.5281/zenodo.15531930</span></a>
</p>
<h3>
<span>References</span>
</h3>
<ul data-spread="false">
    <li>
<span>Felder-Silverman Learning Style Model (FSLSM)</span>
    </li>
    <li>
<span>scikit-learn documentation</span>
    </li>
</ul>
<h3>
<span>License</span>
</h3>
<p>
<span>This project is licensed under the MIT License. See the LICENSE file for details.</span>
</p>
<h3>
<span>Citation</span>
</h3>
<p>
<span>If you use this project in your research, please cite:</span>
</p>
<blockquote>
    <p>
<span>Andhika RH, "Multiclass Learning Style Classification via Dimensionality Reduction and Ensemble Techniques", 2025.</span>
    </p>
</blockquote>
