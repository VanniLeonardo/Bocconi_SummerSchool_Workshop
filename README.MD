# 🤖 Robust Computer Vision Workshop - Bocconi Summer School 2025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VanniLeonardo/Bocconi_SummerSchool_Workshop/blob/main/workshop.ipynb)

---

## 📖 About this Project

This interactive workshop was created by **Vanni Leonardo**, representing alongside **Andrea Pettenon** and **Corrado Calamita** the **Bocconi AI & Neuroscience Student Association (BAINSA)**, for the **Bocconi University Summer School 2025**.

The goal of this session is to provide a fun, hands-on, and accessible introduction to fundamental concepts in Computer Vision. We'll go on a complete journey from training a simple model, discovering its limitations, and then using a technique called **Data Augmentation** to make it significantly more robust.

## 🚀 Workshop Outline

In this notebook, you will learn to:
1.  **Train a Simple Classifier:** Use the easy-to-use Teachable Machine to train a model that recognizes a few different people (you and your neighbours!).
2.  **Identify Model Weakness:** Test the model and see how easily it can be fooled by simple changes like noise and rotation. Simple training data isn't enough for the real world!
3.  **Implement Data Augmentation:** Programmatically create new, "harder" training data by adding random noise and rotations to your original images.
4.  **Retrain and Improve:** Use this new *augmented* dataset to retrain your model, making it "smarter" and more resilient.
5.  **Test in Real-Time:** Launch a live webcam feed directly within the notebook to see how your new, robust model performs compared to the original!

## ✅ Prerequisites

Before you can run the workshop notebook, you need to train your own model on Teachable Machine. It's fast, free, and requires no code!

1.  Go to **[Teachable Machine](https://teachablemachine.withgoogle.com/)** and start a new **Image Project**.
2.  Create **2 to 4 classes**. For example: `Me`, `Person to my Left`, `Person to my Right`.
3.  Using your webcam, record at least 100-200 image samples for each class. Make it balanced!
4.  Once you have your samples, click **Train Model**. Have a look at the advanced options and play around!
5.  After training is complete, click **Export Model**.
    *   Go to the **Tensorflow** tab and select the **Keras** format.
    *   Click **Download my model**. This will give you a `.zip` file.
6.  Now, go back to the "Train" section in Teachable Machine. For **each class**, click the three-dots menu (⋮) and select **Download samples**. This will download a `.zip` file for each of your classes.

You should now have:
*   One `converted_keras.zip` file containing your model.
*   Multiple sample `.zip` files (e.g., `Me.zip`, `Left_Person.zip`, etc.).

## 🛠️ Getting Started

1.  **Rename your model file:** Find the `converted_keras.zip` file you downloaded and rename it to **`model.zip`**.
2.  **Open the Notebook:** Click the "Open in Colab" badge at the top of this README.
3.  **Upload Your Files:** Run the first & second code cell in the notebook (Step 2). A file upload button will appear. Select your `model.zip` file AND all of your sample zip files at once.
4.  **Run the Workshop:** Follow the instructions and run the cells in order from top to bottom. Read the explanations in the text cells to understand what's happening at each stage.
5.  **Allow Webcam Access:** When you reach the final step (Step 8), your browser will ask for permission to use your camera. You must click **Allow** for the live demo to work. You might have to re-run this step twice.

## 📁 File Structure

The notebook expects the following files to be uploaded in Step 2:
```
- model.zip
- Class1-samples.zip
- Class2-samples.zip
- Class3-samples.zip
... (and so on for as many classes as you created)
```

## 👨‍💻 Author

**Vanni Leonardo**
- GitHub: [@VanniLeonardo](https://github.com/VanniLeonardo)
- LinkedIn: [Vanni Leonardo](https://www.linkedin.com/in/leonardo-vanni/)


## 🙏 Acknowledgments

A special thank you to **BAINSA** and **Bocconi University** for the opportunity to create and present this workshop for the 2025 Summer School.