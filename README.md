# Tomato-Leaf-Disease-Detection

 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄:
Our project aimed to enhance the accuracy of tomato leaf disease detection by leveraging deep learning techniques. We started with a dataset of 10,000 images sourced from Kaggle. Through meticulous preprocessing, including background blackout/masking and extensive data augmentation, we expanded our dataset to 26,500 images.

 𝗗𝗮𝘁𝗮 𝗣𝗿𝗲𝗽𝗿𝗼𝗰𝗲𝘀𝘀𝗶𝗻𝗴:

𝗕𝗮𝗰𝗸𝗴𝗿𝗼𝘂𝗻𝗱 𝗕𝗹𝗮𝗰𝗸𝗼𝘂𝘁/𝗠𝗮𝘀𝗸𝗶𝗻𝗴: We applied background blackout techniques to isolate the leaves from the images, ensuring that our models focused on the relevant features.

𝗗𝗮𝘁𝗮 𝗔𝘂𝗴𝗺𝗲𝗻𝘁𝗮𝘁𝗶𝗼𝗻: We performed extensive data augmentation to create variations of the images, which helped simulate different conditions and improve model generalization.


𝗞𝗲𝘆 𝗛𝗶𝗴𝗵𝗹𝗶𝗴𝗵𝘁𝘀:

𝗗𝗮𝘁𝗮𝘀𝗲𝘁 𝗗𝗲𝘁𝗮𝗶𝗹𝘀: Our augmented dataset of 26,500 images provided a robust foundation for training and validating our models.

𝗠𝗼𝗱𝗲𝗹𝘀 𝗘𝗺𝗽𝗹𝗼𝘆𝗲𝗱: We explored various architectures to find the most effective model for disease detection:

𝗖𝘂𝘀𝘁𝗼𝗺 𝗖𝗡𝗡 𝗠𝗼𝗱𝗲𝗹: Our tailored CNN model achieved remarkable results with 96% accuracy during training and 92% accuracy during validation.

𝗩𝗚𝗚𝟭𝟲: This established architecture delivered solid performance with 75% training accuracy and 77% validation accuracy.

𝗗𝗲𝗻𝘀𝗲𝗡𝗲𝘁: Demonstrated consistent results with 76% training accuracy and 80% validation accuracy.

𝗠𝗼𝗯𝗶𝗹𝗲𝗡𝗲𝘁 (𝗧𝗲𝗮𝗰𝗵𝗮𝗯𝗹𝗲 𝗠𝗮𝗰𝗵𝗶𝗻𝗲): MobileNet excelled with 97% training accuracy and 95% validation accuracy, proving to be the most efficient and accurate for deployment on mobile and edge devices.

📊 𝗖𝗼𝗻𝗰𝗹𝘂𝘀𝗶𝗼𝗻:
Our custom CNN model performed exceptionally well, but MobileNet stood out as the top performer due to its superior accuracy and efficiency. This makes it a prime candidate for real-world applications, especially on resource-constrained devices.
