# Konvolusi
CNN - Convolutional neural network

![](https://miro.medium.com/max/2510/1*XbuW8WuRrAY5pC4t-9DZAQ.jpeg)

Lihat slide -> 
- [Penjelasan Pengenalan CNN](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-what-are-convolutional-neural-networks)
- [Penjelasan Lengkap CNN](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-module-2)

Beberapa tahapan dalam membangun model CNN disini adalah sebagai berikut:  
- feature extraction layer  
### Step 1: Convolution  
Proses konvolusi memanfaatkan apa yang disebut sebagai filter. Seperti layaknya gambar, filter memiliki ukuran tinggi, lebar, dan tebal tertentu. Filter ini diinisialisasi dengan nilai tertentu (random atau menggunakan teknik tertentu seperti Glorot), dan nilai dari filter inilah yang menjadi parameter yang akan di-update dalam proses learning.

berikut proses layer conv
![](https://miro.medium.com/max/5966/1*SqbSiJxN9lDhyhWNuEZSdw.jpeg)

Dengan menggeser (convolve) filter di setiap kemungkinan posisi filter pada gambar, dihasilkan sebuah activation map.  
![](https://miro.medium.com/max/960/1*bx3kWA2cKm14OrNP1M-6gw.gif)

lihat slide presentasi berikut untuk lebih jelas -> 
- [Penjelasan Convolution](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-step-1-convolution-operation)
- [Penjelasan ReLu](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-step-1b-relu-layer)

### Step 2: Pooling  
untuk mereduksi input secara spasial (mengurangi jumlah parameter) dengan operasi down-sampling. Umumnya, metode pooling yang digunakan adalah max pooling atau mengambil nilai terbesar dari bagian tersebut. Namun terdapat metode pooling lain yang dapat digunakan seperti average pooling atau L2-norm pooling.

Lihat slide presentasi berikut untuk lebih jelas -> [Penjelasan Pooling](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-step-2-pooling)

![](https://qph.fs.quoracdn.net/main-qimg-cf2833a40f946faf04163bc28517959c)
![](https://qph.fs.quoracdn.net/main-qimg-3a8a3a78734fed3301ed3546634b871a.webp)

### Step 3: Flattening  
![](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/73_blog_image_1.png)

Lihat slide berikut untuk lebih jelas -> [Penjelasan Flattening](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-step-3-flattening)

### Step 4: Full Connection  
![](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/74_blog_image_1.png)

Lihat slide berikut untuk lebih jelas -> [Penjelasan Full Connection Layer](https://www.slideshare.net/KirillEremenko/deep-learning-az-convolutional-neural-networks-cnn-step-4-full-connection)

# Model
![](https://miro.medium.com/max/2510/1*hkUuCxTIivfgpMq9K_gpsA.jpeg)


# Tutorial
- https://medium.com/@samuelsena/pengenalan-deep-learning-part-7-convolutional-neural-network-cnn-b003b477dc94
- https://medium.com/@nadhifasofia/1-convolutional-neural-network-convolutional-neural-network-merupakan-salah-satu-metode-machine-28189e17335b
- https://medium.com/nodeflux/mengenal-convolutional-neural-network-8bd207ad4a8d
- http://machinelearning.mipa.ugm.ac.id/tag/convolutional_neural_network/
- https://www.youtube.com/watch?v=umGJ30-15_A
- https://www.youtube.com/watch?v=WvoLTXIjBYU
- http://machinelearning.mipa.ugm.ac.id/tag/convolutional_neural_network/
- https://jhui.github.io/2017/03/16/CNN-Convolutional-neural-network/
- http://cs231n.github.io/convolutional-networks/

# CNN for Stock Prediction
- https://www.youtube.com/watch?v=IscG_bAeEic
- https://www.youtube.com/watch?v=nMkqWxMjWzg


