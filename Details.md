### Resnet-18 architecture

## Training on base dataset
    While training on base dataset, where the face is present in formats of pp size photos, resnet-18 started to overfit from around 45th epochs during 100 epochs training, and the validation loss and accuracy didn't improve much.

## Training on Augmented dataset
    The base dataset is then augmented such that each class contains 30 samples, then resnet is trained with 64 batch size for 10 epochs, both validation and training accuracy increased alongside. But during inference, it couldn't classify properly.

## Training on Cropped dataset
    The augmented data is resampled to 500 class and resnet is trained for classification, but alas, problems of overfitting and bad inference performance.