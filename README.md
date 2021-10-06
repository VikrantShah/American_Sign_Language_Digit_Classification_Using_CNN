# American_Sign_Language_Digit_Classification_Using_CNN

![American Digit Classification](https://github.com/VikrantShah/American_Sign_Language_Digit_Classification_Using_CNN/blob/main/american_sign_digit.png)

Conversing with people having a hearing disability is a major challenge. Deaf and Mute people use hand gesture sign language to communicate, hence normal people face problems in recognizing their language by signs made. Hence there is a need for systems that recognize the different signs and conveys the information to normal people.

Sign language is a visual language. It mainly consists of 3 major components:

1. Fingerspelling: Spell out words character by character, and word level association which involves hand gestures that convey the word meaning. The static Image Dataset is used for this purpose.

2. World-level sign vocabulary: The entire gesture of words or alphabets is recognized through video classification. (Dynamic Input / Video Classification)

3. Non-manual features: Facial expressions, tongue, mouth, body positions

## Splitting the Dataset
This dataset is divided into 70:30:0 ratio (70% for Training, 30% for Validation, and 0% for Testing), using the [split-folders](https://pypi.org/project/split-folders/) package.
<br>
The code for splitting the dataset can be found [here](https://github.com/VikrantShah/Python_Programs/blob/main/Splitting_train_validation_test.py).

C201023C201024
