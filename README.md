Chest X-Ray Images (Pneumonia) is a quite popular dataset available on Kaggle. It stores pictures from 5863 X-Ray scans, divided into 2 categories (Pneumonia and Normal). Hundreds of notebooks were proposed classify these images, following various approaches. The one here proposed involves using data generators for the pre-processing and transfer learning to build the supervised learnig model.

Transfer learning allows brand new models to be built starting from a pre-trained model, basically changing the top and the bottom layers, if necessary. Many pre-built models exists, most popular are Inception, VGG and ResNet, and many of them are already included in Keras.