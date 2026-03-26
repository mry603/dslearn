# Numpy & Project
## Technical Stack:
* Languages: Python
* Libraries: NumPy, Matplotlib, Scikit-image, IPython


## Vector: create, math functions, slicing, views and copies, sorting

### Project: Historical Temperature Analysis with NumPy
* Utilized NumPy to perform vectorized data transformations and statistical analysis, including seasonal slicing and proximity-based search algorithms to identify climate trends within large datasets.
* Concepts: Statistical Modeling, Algorithmic Optimization
     

## Plotting: matplotlib, function plot, bar plot, scatter plot, function of pi, e, log, sin, con
### Project: Predictive Climate Modeling and Seasonal Trend Analysis
* implemented a trigonometric model to approximate multi-decade seasonal temperature trends, utilizing NumPy for vectorized calculations and Matplotlib to perform residual analysis and evaluate model accuracy.
* Concepts: Trigonometric Modeling, Residual Analysis, Statistical Profiling, Vectorization
* Detailed Points:
    * Feature Engineering & Transformation: Standardized historical climate datasets by implementing vectorized unit conversions ($F \to C$) and calculating key statistical descriptors (mean, amplitude, and extremas).
    * Trigonometric Modeling: Developed a periodic cosine function to simulate the 12-month temperature cycle, effectively modeling the seasonality of New York’s record lows.
    * Error Analysis & Residual Visualization: Quantified model performance by calculating the absolute differences between empirical data and theoretical approximations, visualizing these residuals via bar plots to identify seasonal variances.
    * Continuous Data Synthesis: Used np.linspace to generate high-resolution continuous data points, allowing for the visualization of smooth theoretical climate curves against discrete monthly observations.
     

## Randomness: generator, create random vector, function of shuffle, choice, normal dist, unique

### project: Fundamental Linear Regression and Stochastic Modeling
* Engineered a from-scratch linear regression model using NumPy to implement least-squares optimization formulas, while performing residual analysis on stochastic data to evaluate the limits of predictive modeling
* Concepts: Linear Regression, Stochastic Processes, Least-Squares Optimization, Vectorization
* Detailed Points:
     * Synthetic Data Generation: Leveraged numpy.random to simulate controlled datasets of 100 independent variables ($x$) and dependent variables ($y$), establishing a baseline for statistical testing.
     * Statistical Profiling: Conducted exploratory data analysis (EDA) by calculating population means and standard deviations to validate the distribution of randomly generated features.
     * Algorithmic Model Implementation: Manually programmed the slope ($a$) and intercept ($b$) coefficients using the least-squares method, utilizing NumPy’s vectorized sum and mean functions for computational efficiency.
     * Predictive Inference & Visualization: Developed a deployment-ready prediction function to estimate outcomes for unseen data points and utilized Matplotlib scatter plots to visualize the relationship between training samples and the regression line.
     * Model Evaluation: Critically assessed the "boring" behavior of models trained on purely random data, identifying that the model correctly converges to the mean ($0.5$) when no true correlation exists.

## Metrics: create, get value, boolean metrics, attributes, newaxis, reshape,flattern

### Project: Multi-Dimensional Climate Data Analysis
* Leveraged NumPy for multi-dimensional data transformation and axis-based statistical modeling, including automated error correction and boolean-driven environmental threshold analysis
* Concepts: Data Cleaning, Descriptive Statistics, Boolean Indexing, Multi-dimensional Slicing 
* Detailed point:
     * Matrix-Based Data Wrangling: Transformed raw seasonal temperature lists into optimized 2D NumPy arrays, enabling efficient vectorized operations across record high, mean, and low temperature datasets.
     * Data Integrity & Preprocessing: Executed precise data-entry corrections via matrix indexing and validated dataset consistency through shape and size verification.
     * Advanced Feature Reshaping: Engineered a data reshaping pipeline to perform rolling average calculations over consecutive monthly periods, enhancing the granularity of seasonal trend analysis.
     * Multivariate Statistical Profiling: Computed row-wise descriptive statistics (max, min, mean) to contrast record-breaking extremes against daily averages.
     * Conditional Querying & Boolean Masking: Designed logical filters to identify specific climatic conditions, such as sub-zero record highs or months exceeding defined temperature benchmarks.

## Broadcasting:2D slicing, advanced indexing, matrix + vector

### Project: Monochromatic Image Processing & Spatial Data Analysis
* Engineered an efficient image manipulation engine using NumPy broadcasting and boolean indexing to perform pixel-level intensity transformations and automated spatial cropping on high-dimensional matrices
* Concepts: Digital Image Processing, Vectorization, Boolean Masking, Spatial Slicing
* Detailed point:
     * Spatial Data Representation: Modeled monochromatic images as $512 \times 512$ NumPy arrays, enabling the application of linear algebra and matrix calculus to visual data.
     * Vectorized Pixel Transformation: Optimized image inversion and intensity scaling by leveraging NumPy's broadcasting capabilities, replacing iterative loops with high-speed vectorized operations.
     * Intensity-Based Segmentation: Utilized boolean masking to isolate and modify specific pixel ranges, demonstrating a fundamental approach to data thresholding and noise filtering in spatial analysis.
     * Structural Data Engineering: Implemented precise matrix slicing and list-based indexing to perform centered cropping and targeted region-of-interest (ROI) modifications.
     * Exploratory Data Inspection: Conducted statistical audits of pixel intensity distributions (min/max analysis) to ensure data integrity and normalize inputs for visualization.


## Algebra: linalg, dot product, cross product, norm, determinant, inverse, solve, Eigenvalues, diagonal,orthogonal,upper triagular matrices, QR Decomposition, LinAlgError, lstsq
### Project: Computational Linear Algebra & Systems Modeling
* Developed a suite of linear algebra utilities using NumPy to perform high-dimensional vector analysis and matrix transformations, including the implementation of a linear system solver to model and balance complex chemical reaction equations
* Concepts: Linear Algebra, System of Equations, Matrix Theory, Vector Calculus, Stoichiometry Modeling
* Detailed point:
     * Vector Space Analysis: Engineered custom functions to evaluate spatial relationships between high-dimensional vectors, including orthogonality, parallelism, and angular distance calculations using dot and cross products.
     * Matrix Calculus & Transformations: Implemented advanced matrix operations—including inversion, transpositions, and matrix power calculations—to process multi-dimensional data structures efficiently.
     * Linear Systems Optimization: Utilized numpy.linalg to solve non-homogeneous systems of linear equations ($Ax = B$), determining the invertibility of matrices via determinant analysis.
    * Scientific Problem Solving: Applied linear regression principles and system solvers to a real-world chemistry use case, programmatically deriving stoichiometric coefficients to balance complex molecular equations.
     * Vectorized Computation: Leveraged NumPy’s low-level optimizations to replace iterative loops with high-performance vectorized matrix algebra, ensuring scalability for larger datasets.


### Project: image decomposition and functional approximation
* Implemented advanced matrix factorizations (QR decomposition) and polynomial curve fitting using NumPy's linear algebra submodule to approximate non-linear functions and perform structural data transformations.
* Concepts: Least Squares Optimization, QR Decomposition, Vandermonde Matrices, Polynomial Regression, Orthogonal Transformations
* Detailed point:
     * Polynomial Approximation & Regression: Engineered a second-degree polynomial model to approximate complex non-linear functions by constructing a Vandermonde matrix and solving for coefficients via the Least Squares method.
     * Matrix Factorization for Data Representation: Applied QR Decomposition to high-dimensional image data, effectively separating structural information into orthogonal ($Q$) and upper-triangular ($R$) components while maintaining data integrity.
     * Vector Space Modeling: Developed and validated custom rotation matrices and orthogonal transformations to manipulate spatial data orientations within a defined coordinate system.
     * Statistical Model Evaluation: Conducted comparative analysis between empirical data and theoretical approximations using Matplotlib for residual visualization and error assessment.
     * Vectorized System Solvers: Optimized the solution of overdetermined systems ($Ax = y$) using linalg.lstsq, ensuring efficient parameter estimation for high-resolution datasets.

## Ndarrays: 3d array, slicing, strides
### Project: 3D Array Manipulation & RGB Color Engineering
* Developed a multi-dimensional image processing pipeline using NumPy to perform channel-wise color engineering and spatial slicing, enabling precise control over RGB intensity distributions and localized data transformations
* Concepts: Tensor Slicing, RGB Color Space, Data Clipping, Spatial Partitioning, Vectorized Transformations
* Detailed point:
     * 3D Tensor Manipulation: Modeled color images as tensors, applying advanced indexing and slicing to isolate and manipulate individual color channels (Red, Green, Blue).
     * Channel-Specific Feature Engineering: Implemented vectorized operations to adjust color saturation and intensity levels, including the development of logic to handle uint8 overflow during additive transformations.
     * Spatial Segmentation (Divide & Conquer): Utilized array slicing to partition high-resolution images into quadrants, applying independent mathematical models to each localized data subset.
     * Pixel Intensity Normalization: Applied boolean masking and conditional updates to clip and normalize pixel values, ensuring data integrity across large-scale numerical transformations.
     * Data Visualization & Audit: Leveraged Matplotlib to visually validate the results of matrix-based image modifications and audit the impact of channel-wise variance.

## Fourier Transforms: rfft, rfftfreq,irfft, rfft2,smooth signal, compress signal,play audio
### Project: Audio Signal Processing & Frequency-Domain Analysis
* Engineered an audio processing pipeline using NumPy’s FFT module to perform frequency-domain transformations, implementing threshold-based signal compression and low-pass filtering for noise reduction
* Concepts: Fast Fourier Transform (FFT), Signal Processing, Frequency Analysis, Data Compression, Noise Filtering
* Detailed point:
     * Frequency-Domain Modeling: Transformed discrete-time audio signals into their constituent frequencies using rfft, enabling the identification of dominant spectral components in complex musical chords
     * Signal Smoothing & Filtering: Developed a digital low-pass filter by programmatically truncating high-frequency components (above 950Hz) to reduce signal noise and regenerate smoothed audio via Inverse FFT (irfft)
     * Lossy Data Compression: Optimized storage efficiency by implementing a magnitude-thresholding algorithm that removed low-amplitude spectral noise, significantly reducing the number of non-zero data points without perceptible loss in audio quality
     * Spectral Visualization: Utilized Matplotlib to contrast time-domain waveforms with complex-valued frequency distributions (real and imaginary components), facilitating deep exploratory data analysis of acoustic patterns
     * Computational Efficiency: Leveraged NumPy’s vectorized logic to perform batch frequency manipulations, demonstrating a scalable approach to handling high-resolution time-series data

## Data save and load and library: txt,csv,npy, npz with label. And learn numba to fastern python
### Project: Housing Market Exploratory Data Analysis & Persistence
* Developed a data analysis pipeline using NumPy and Matplotlib to perform multi-dimensional statistical profiling and trend visualization on housing data, implementing customized feature selection and binary serialization for data persistence
* Concepts: Exploratory Data Analysis (EDA), Feature Selection, Data Persistence, Boolean Indexing, Descriptive Statistics
* Detailed point:
     *External Data Integration: Implemented robust data loading protocols to ingest large-scale CSV datasets into optimized NumPy arrays for high-performance computing.
     * Univariate & Bivariate Visualization: Leveraged Matplotlib to construct frequency histograms for architectural features (room counts) and price distributions, while using scatter plots to identify positive correlations between property size and market value.
     * Segmented Socio-Economic Analysis: Conducted comparative statistical audits between housing tiers (e.g., "cheap" vs. "average" priced homes), discovering significant disparities in town-wide crime rates based on property valuation.
     * Categorical Data Processing: Analyzed dummy variables to determine the geographical distribution of housing (e.g., river proximity), calculating population percentages via non-zero indexing.
     * Data Engineering & Optimization: Performed targeted feature extraction by isolating high-impact variables (Crime, River Access, Room Count, Price) and utilized .npy binary serialization to preserve data structures for future use.
