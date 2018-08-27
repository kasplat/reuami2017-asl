# REU AMI ASL Project

Classifying sign language using machine learning and computer vision techniques.

## Getting Started

To view a sign in the database: 
Run the skelAton.py file. 

You will need to install matplotlib to make this work.
You can edit the file being displayed by changing the name in the program to any other file name inside the XML_ASL_Files database. 



For linguistic analysis:
Run python main.py to run the program. It will ask if you would like to use the stored database.
Generally the answer to this questions is yes.


### Prerequisites

This will be detailed in requirements.txt

```
pip install nltk
pip install matplotlib
```

## Prediction Technology

The prediction was done by loading several features into a python dictionary, then using a similarity feature on those features to all items in the database a few times per second to identify which signs are most likely to be nearby. This is then returned to the user using a tkinter application in Python. 

The recognition for this is done with a Kinect v1.

## Authors

* **Shareef Ali** - *Researcher* - [shareefalis](https://github.com/shareefalis)
* **Kesavan Kushalnagar** - *Researcher* - [kasplat](https://github.com/kasplat)
* **Abraham Glasser** - *Researcher* - [abrahplaya](https://github.com/abrahplaya)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
