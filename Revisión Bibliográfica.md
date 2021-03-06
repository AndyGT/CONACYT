#Revisión de Bibliografía 
1. Bijalwan,Vishwanath et al.  **KNN based Machine Learning Approach for Text and Document Mining**. 
International Journal of Database Theory and Application
    Vol.7, No.1 (2014), pp.61-70
    http://dx.doi.org/10.14257/ijdta.2014.7.1.06

    **Abstract(10)**
    Text Categorization (TC), also known as Text Classification, is the task of automatically classifying a set of text documents into different categories from a predefined set. If a document belongs to exactly one of the categories, it is a single-label classification task; otherwise, it is a multi-label classification task. TC uses several tools from Information Retrieval (IR) and Machine Learning (ML) and has received much attention in the last years from both researchers in the academia and industry developers. In this paper, we first categorize the documents using KNN based machine learning approach and then return the most relevant documents

2. Blessing,  Alexander y 
 Wen, Kai.
**Using Machine Learning for Identification of Art Paintings**, Technical Report (2010). Stanford University.

    **Abstract(5)**
    Machine learning applications have been suggested for
    many tasks. We have investigated the suitability of applying
    machine learning to the problem of art identification, which
    we believe to be a new, but promising field. Our approach
    focuses on classifying works of seven different artists, by
    using a multi-class SVM with state-of-the-art features. Our
    results indicate that machine learning has good potential to
    classify art works. We conclude this paper by analyzing our
    results.
    
1. Chen, Yixin y Wang, James. **Image Categorization by Learning and Reasoning with Regions**. Journal of Machine Learning Research 5 (2004) 913–939 
    
    **Abstract(27)**
    Designing computer programs to automatically categorize images using low-level features is a challenging
    research topic in computer vision. In this paper, we present a new learning technique, which
    extends Multiple-Instance Learning (MIL), and its application to the problem of region-based image
    categorization. Images are viewed as bags, each of which contains a number of instances
    corresponding to regions obtained from image segmentation. The standard MIL problem assumes
    that a bag is labeled positive if at least one of its instances is positive; otherwise, the bag is negative.
    In the proposed MIL framework, DD-SVM, a bag label is determined by some number of instances
    satisfying various properties. DD-SVM first learns a collection of instance prototypes according
    to a Diverse Density (DD) function. Each instance prototype represents a class of instances that is
    more likely to appear in bags with the specific label than in the other bags. A nonlinear mapping
    is then defined using the instance prototypes and maps every bag to a point in a new feature space,
    named the bag feature space. Finally, standard support vector machines are trained in the bag feature
    space. We provide experimental results on an image categorization problem and a drug activity
    prediction problem.
1. Jafarpour, Sina, et al. **Stylistic analysis of paintings using wavelets and machine learning**. En European Signal Processing Conference. 2009. p. 1220-1224.

    **ABSTRACT(5)**
    Wavelet transforms and machine learning tools can be used
    to assist art experts in the stylistic analysis of paintings. A
    dual-tree complex wavelet transform, Hidden Markov Tree
    modeling and Random Forest classifiers are used here for a
    stylistic analysis of Vincent van Gogh’s paintings with results
    on two stylometry challenges that concern “dating, resp. ex-
    tracting distinguishing features”.

1. Dimitrovski, Ivica, et al. **Fast and efficient visual codebook construction for multi-label annotation using predictive clustering trees.** Pattern Recognition Letters 38 (2014): 38-45.

    **Abstract(9)**The bag-of-visual-words approach to represent images is very popular in the image annotation community.
    A crucial part of this approach is the construction of visual codebook. The visual codebook is typically
    constructed by using a clustering algorithm (most often k-means) to cluster hundreds of thousands
    of local descriptors/key-points into several thousands of visual words. Given the large numbers of examples
    and clusters, the clustering algorithm is a bottleneck in the construction of bag-of-visual-words representations
    of images. To alleviate this bottleneck, we propose to construct the visual codebook by using
    predictive clustering trees (PCTs) for multi-label classification (MLC). Such a PCT is able to assign multiple
    labels to a given image, i.e., to completely annotate a given image. Given that PCTs (and decision trees in
    general) are unstable predictive models, we propose to use a random forest of PCTs for MLC to produce
    the overall visual codebook. Our hypothesis is that the PCTs for MLC can exploit the connections between
    the labels and thus produce a visual codebook with better discriminative power. We evaluate our
    approach on three relevant image databases. We compare the efficiency and the discriminative power
    of the proposed approach to the literature standard – k-means clustering. The results reveal that our
    approach is much more efficient in terms of computational time and produces a visual codebook with
    better discriminative power as compared to k-means clustering. The scalability of the proposed approach
    allows us to construct visual codebooks using more than usually local descriptors thus further increasing
    its discriminative power.
1. Duygulu, Pinar, et al. **Object recognition as machine translation: Learning a lexicon for a fixed image vocabulary.** Computer Vision—ECCV 2002. Springer Berlin Heidelberg, 2002. 97-112.

    **Abstract(16)** We describe a model of object recognition as machine translation.
    In this model, recognition is a process of annotating image regions
    with words. Firstly, images are segmented into regions, which are classified into region types using a variety of features. A mapping between
    region types and keywords supplied with the images, is then learned, using
    a method based around EM. This process is analogous with learning
    a lexicon from an aligned bitext. For the implementation we describe,
    these words are nouns taken from a large vocabulary. On a large test
    set, the method can predict numerous words with high accuracy. Simple
    methods identify words that cannot be predicted well. We show how to
    cluster words that individually are diÆcult to predict into clusters that
    can be predicted well | for example, we cannot predict the distinction
    between train and locomotive using the current set of features, but
    we can predict the underlying concept. The method is trained on a substantial
    collection of images. Extensive experimental results illustrate the
    strengths and weaknesses of the approach.

2. Polatkan, Gungor, et al. **Detection of forgery in paintings using supervised learning.** Image Processing (ICIP), 2009 16th IEEE International Conference on. IEEE, 2009.

    **Abstract(4)**This paper examines whether machine learning and image analysis
    tools can be used to assist art experts in the authentication of unknown
    or disputed paintings. Recent work on this topic [1] has presented
    some promising initial results. Our reexamination of some of
    these recently successful experiments shows that variations in image
    clarity in the experimental datasets were correlated with authenticity,
    and may have acted as a confounding factor, artificially improving
    the results. To determine the extent of this factor’s influence on previous
    results, we provide a new “ground truth” data set in which
    originals and copies are known and image acquisition conditions are
    uniform. Multiple previously-successful methods are found ineffective
    on this new confounding-factor-free dataset, but we demonstrate
    that supervised machine learning on features derived from Hidden-
    Markov-Tree-modeling of the paintings’ wavelet coefficients has the
    potential to distinguish copies from originals in the new dataset.
3. Schwenker, Friedhelm, and Edmondo Trentin. **Pattern classification and clustering: A review of partially supervised learning approaches.** Pattern Recognition Letters 37 (2014): 4-14.

    **Abstract(12)**The paper categorizes and reviews the state-of-the-art approaches to the partially supervised learning
    (PSL) task. Special emphasis is put on the fields of pattern recognition and clustering involving partially
    (or, weakly) labeled data sets. The major instances of PSL techniques are categorized into the following
    taxonomy: (i) active learning for training set design, where the learning algorithm has control over the
    training data; (ii) learning from fuzzy labels, whenever multiple and discordant human experts are
    involved in the (complex) data labeling process; (iii) semi-supervised learning (SSL) in pattern classification
    (further sorted out into: self-training, SSL with generative models, semi-supervised support vector
    machines; SSL with graphs); (iv) SSL in data clustering, using additional constraints to incorporate expert
    knowledge into the clustering process; (v) PSL in ensembles and learning by disagreement; (vi) PSL in
    artificial neural networks. In addition to providing the reader with the general background and categorization
    of the area, the paper aims at pointing out the main issues which are still open, motivating the ongoing
    investigations in PSL research.
4. Johnson, C. Richard, et al. **Image processing for artist identification.** Signal Processing Magazine, IEEE 25.4 (2008): 37-48.

    **Abstract(15)**
    A survey of the literature reveals that image processing tools aimed at supplementing the art historian's toolbox are currently in the earliest stages of development. To jump-start the development of such methods, the Van Gogh and Kroller-Muller museums in The Netherlands agreed to make a data set of 101 high-resolution gray-scale scans of paintings within their collections available to groups of image processing researchers from several different universities. This article describes the approaches to brushwork analysis and artist identification developed by three research groups, within the framework of this data set.

5. Sun, Liang, et al. **Support vector description of clusters for content-based image annotation.** Pattern Recognition 47.3 (2014): 1361-1374.

    **Abstarct(14)**Continual progress in the fields of computer vision and machine learning has provided opportunities to develop automatic tools for tagging images; this facilitates searching and retrieving. However, due to the complexity of real-world image systems, effective and efficient image annotation is still a challenging problem. In this paper, we present an annotation technique based on the use of image content and word correlations. Clusters of images with manually tagged words are used as training instances. Images within each cluster are modeled using a kernel method, in which the image vectors are mapped to a higher-dimensional space and the vectors identified as support vectors are used to describe the cluster. To measure the extent of the association between an image and a model described by support vectors, the distance from the image to the model is computed. A closer distance indicates a stronger association. Moreover, word-to-word correlations are also considered in the annotation framework. To tag an image, the system predicts the annotation words by using the distances from the image to the models and the word-to-word correlations in a unified probabilistic framework. Simulated experiments were conducted on three benchmark image data sets. The results demonstrate the performance of the proposed technique, and compare it to the performance of other recently reported techniques.
6. Uzair, Muhammad, et al. **Representation Learning with Deep Extreme Learning Machines for Efficient Image Set Classification.** arXiv preprint arXiv:1503.02445 (2015).

    **Abstract(10)** Efficient and accurate joint representation of a collection
    of images, that belong to the same class, is a major research
    challenge for practical image set classification. Existing
    methods either make prior assumptions about the data
    structure, or perform heavy computations to learn structure
    from the data itself. In this paper, we propose an efficient
    image set representation that does not make any prior assumptions
    about the structure of the underlying data. We
    learn the non-linear structure of image sets with Deep Extreme
    Learning Machines (DELM) that are very efficient
    and generalize well even on a limited number of training
    samples. Extensive experiments on a broad range of public
    datasets for image set classification (Honda/UCSD, CMU
    Mobo, YouTube Celebrities, Celebrity-1000, ETH-80) show
    that the proposed algorithm consistently outperforms stateof-
    the-art image set classification methods both in terms of
    speed and accuracy.


    



