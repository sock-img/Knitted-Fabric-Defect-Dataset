The Knitted-Sock-Dataset is a specialized image dataset designed for defect detection on the surface of knitted socks. The data were collected from the quality inspection workshop of a hosiery manufacturing enterprise located in Zhejiang Province, China, and cover a diverse range of defect types that may occur during production due to fluctuations in raw material quality, equipment malfunctions, or human operational errors. The dataset includes knitted socks of various specifications.

To accurately capture defect details and closely reflect real-world inspection scenarios, each sock was mounted on a dedicated detection board during image acquisition, ensuring that the entire sock surface was included within the shooting and inspection range. Because the number of samples for certain defect categories in the raw data was insufficient, an improved CycleGAN-based method was employed to alleviate the issue of defect sample scarcity, expanding the dataset to a total of 2,075 images.

The constructed dataset comprises five representative defect categories: hole, snagging, flying, drop stitch, and stain. To ensure annotation accuracy and consistency, all images were manually labeled using the LabelImg tool, with each defect region outlined using a minimum bounding rectangle. A random sampling inspection was additionally conducted to further verify the reliability of the annotations.
Following standard machine learning practices, the dataset was divided into a training set (60%), validation set (20%), and test set (20%), making it suitable for developing, training, and evaluating defect detection algorithms.

In addition, our data set is too large for you to download directly, we provide you with the following two download methods.
You can download the dataset from Quark Netdisk. URL：https://pan.quark.cn/s/e56cec085f26. Extraction code: rJr7.
You can download the dataset from Baidu Netdisk. URL：https://pan.baidu.com/s/14QUWMDgqeJQqa7rRFCGBOg?pwd=6p5r. Extraction code: 6p5r.
If you have any problem, please contact me by email：1480582374@qq.com.
