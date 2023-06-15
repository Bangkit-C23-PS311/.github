# SIBISA - Team Project

Team ID: C23-PS311

Team Members:
- (ML) M340DSX1314 – Paulus Lestyo Adhiatma – Universitas Sebelas Maret
- (ML) M182DSX1885 – Randi Maulana Putra – Universitas Indraprasta PGRI
- (CC) C121DKY4668 – Adilah Atikah Putri – UIN Sultan Syarif Kasim Riau 
- (CC) C121DKY4729 – Putri Zahwa – UIN Sultan Syarif Kasim Riau
- (MD) A150DKX4462 – Ilham Triputro Utomo – Universitas Bina Sarana Informatika
- (MD) A150DKX4459 – Aldo Wijaya Kusuma – Universitas Bina Sarana Informatika

## Themes
Education, Learning, and Personal Development

## Project Title: SIBISA
SIBI (Sistem Isyarat Bahasa Indonesia) is a sign language that has been designed and endorsed by the government as a learning standard in SLB schools and is recognized as an official sign language in Indonesia. However, the use of SIBI is still limited and not widespread in the community. Many Indonesians do not understand sign language, causing communication difficulties for deaf people when interacting with others. Learning SIBI offers numerous benefits for both deaf and hearing individuals, such as improving communication skills, expanding job opportunities, increasing social sensitivity, and acquiring knowledge and experience. Our project aims to develop an application that facilitates SIBI learning for both deaf and hearing users. The application includes examples of SIBI usage, and we have also developed a machine learning model to detect hand movements and provide feedback on the correctness of the user's sign language. This interactive approach enhances the learning experience for users.

## Machine Learning Learning Path

1. Open Google Colaboratory notebook
You can access our online [notebook](https://colab.research.google.com/drive/1aOfLQBI7nyxHDNOiY90w3JKodHmWO0b9?usp=sharing) that has been prepared. The model we created utilizes the Transfer Learning technique with MobileNetV2.
2. Dataset
The dataset we used was created by our team and can be found in the repositories [alphabets](https://github.com/Bangkit-C23-PS311/Data) and [word](https://github.com/Bangkit-C23-PS311/Dataset-kata)
3. Save model
After running all the program code, the model will be saved in the .h5 format. The model is then converted to .tflite format to be deployed in the mobile app.

### Featured Technologies
* [TensorFlow](https://www.tensorflow.org/): The core open source library to help you develop and train ML models. Get started quickly by running Colab notebooks directly in your browser.
* [TensorFlow Lite](https://www.tensorflow.org/lite): TensorFlow Lite is an open source deep learning framework for on-device inference.
* [Keras](https://keras.io/): Keras is a deep learning API written in Python, running on top of the machine learning platform TensorFlow.


## Android
### Steps To Clone Project
1. Pull the project from android  or download from this link https://github.com/Bangkit-C23-PS311/SIBISA-APP
2. Open It in Android studio wait until gradle done and launch it.

### Featured Technologies

* [Kotlin](kotlinlang.org): Why Kotlin. Modern, concise and safe programming language. Concise; Safe; Interoperable.
* [Retrofit](square.github.io): Retrofit is the class through which your API interfaces are turned into callable objects
* [CameraX](https://developer.android.com/training/camerax): CameraX is a Jetpack library, built to help make camera app development easier. easy-to-use API that works across the vast majority of Android devices
* [TensorFlow Lite](https://www.tensorflow.org/lite): TensorFlow Lite is an open source deep learning framework for on-device inference.

### Screen Shoot
![image](https://github.com/Bangkit-C23-PS311/.github/assets/51690314/d22a7ae8-9d95-4afb-a8dd-5ff32142c696)


## Cloud Computing Learning Path
### Steps To deploy laravel in Compute Engine, database in CloudSql, and storage in CloudStorage GCP
1. Set up a GCP project and enable the necessary APIs. This can be done through the GCP console.
2. Create a Compute Engine instance and install Laravel on it. You can choose a suitable virtual machine (VM) instance and install the required dependencies for Laravel.
3. Set up a Cloud SQL instance to create the database for your Laravel application. Configure the database connection in Laravel to connect to the Cloud SQL instance.
4. Create a Cloud Storage bucket to store and manage your application's files. Configure Laravel to use Cloud Storage for file uploads and storage.
5. Deploy the Laravel application on the Compute Engine instance. You can use tools like Git to clone your Laravel project onto the instance and configure the necessary web server settings.

### Featured Technologies
* [PHP](https://www.php.net/) PHP is a popular server-side scripting language used for web development. It is well-suited for building dynamic and interactive web applications.
* [Framework Laravel](https://laravel.com/)  Laravel is a powerful and elegant PHP framework that provides a rich set of features for web application development. It offers features like routing, view rendering, ORM (Object-Relational Mapping), and supports the MVC (Model-View-Controller) architectural pattern.
* [Google Cloud Platform (GCP)](https://cloud.google.com/gcp/)  GCP is a suite of cloud computing services offered by Google. It provides scalable and reliable infrastructure for hosting web applications, along with various services such as Compute Engine, Cloud SQL, and Cloud Storage that can be integrated into Laravel applications for deployment, database management, and file storage.

## Using the Image Classification feature
The SIBI application provides an image classification feature that allows users to train themselves in SIBI sign language using the front camera of their device. With this feature, users can capture their own hand movements and gestures while performing the SIBI sign language.

### Another Attachment
1. [Wireframe](https://whimsical.com/sibisa-13r3ttr9E5bzZRkcnY8kvk)
2. [UI](https://www.figma.com/file/EZIAgwFB884ajx4sapmYCW/SIBISA-UI?type=design&node-id=0-1)
3. [Database Design](https://drive.google.com/file/d/1z-l4pftJsL-6gPFo8MRKCSWHfH_SvhRX/view?usp=sharing)
4. [Cloud Architecture](https://drive.google.com/file/d/1RkoSGgp0WkhpS11xEiRhfSWYOUTaCX33/view)
