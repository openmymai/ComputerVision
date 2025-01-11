## Computer Vision
Computer vision is the art of teaching a computer to see.
For example, it could involve building a model to classify whether a photo is of a cat or a dog (binary classification).
- Or whether a photo is of a cat, dog or chicken (multi-class classification).
- Or identifying where a car appears in a video frame (object detection).
- Or figuring out where different objects in an image can be separated (panoptic segmentation).

### Where does computer vision get used?
- If you use a smartphone, you've already used computer vision.
- Camera and photo apps use computer vision to enhance and sort images.
- Modern cars use computer vision to avoid other cars and stay within lane lines.
- Manufacturers use computer vision to identify defects in various products.
- Security cameras use computer vision to detect potential intruders.
- In essence, anything that can be described in a visual sense can be a potential computer vision problem.

#### PyTorch Workflow we've been learning in the past couple of sections to computer vision.

![image](https://github.com/user-attachments/assets/a9fe6cef-dd05-45aa-adf9-50a43397af12)


| Topic                                             | Contents                                                                                                                                                    |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0\. Computer vision libraries in PyTorch          | PyTorch has a bunch of built-in helpful computer vision libraries, let's check them out.                                                                    |
| 1\. Load data                                     | To practice computer vision, we'll start with some images of different pieces of clothing from FashionMNIST.                                                |
| 2\. Prepare data                                  | We've got some images, let's load them in with a PyTorch DataLoader so we can use them with our training loop.                                              |
| 3\. Model 0: Building a baseline model            | Here we'll create a multi-class classification model to learn patterns in the data, we'll also choose a loss function, optimizer and build a training loop. |
| 4\. Making predictions and evaluating model 0     | Let's make some predictions with our baseline model and evaluate them.                                                                                      |
| 5\. Setup device agnostic code for future models  | It's best practice to write device-agnostic code, so let's set it up.                                                                                       |
| 6\. Model 1: Adding non-linearity                 | Experimenting is a large part of machine learning, let's try and improve upon our baseline model by adding non-linear layers.                               |
| 7\. Model 2: Convolutional Neural Network (CNN)   | Time to get computer vision specific and introduce the powerful convolutional neural network architecture.                                                  |
| 8\. Comparing our models                          | We've built three different models, let's compare them.                                                                                                     |
| 9\. Evaluating our best model                     | Let's make some predictions on random images and evaluate our best model.                                                                                   |
| 10\. Making a confusion matrix                    | A confusion matrix is a great way to evaluate a classification model, let's see how we can make one.                                                        |
| 11\. Saving and loading the best performing model | Since we might want to use our model for later, let's save it and make sure it loads back in correctly.                                                     |

Reference: [ZTM](https://www.learnpytorch.io/03_pytorch_computer_vision/)
I'm a fan of ZTM 🎉💡
