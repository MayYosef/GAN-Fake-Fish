# GAN-ThisFishDoesNotExist
<h2>Generating non-real fish images through a GAN Architecture</h2>-

In this project I created fake images of fish, i.e. non-real fish using the GAN network.
 
 <img src="https://github.com/MayYosef/GAN-ThisFishDoesNotExist/blob/master/images/GAN1.jpeg" width="50%" />
 
The code above is the best architecture I've been able to get after various experiments.
 
The net is trained on  DataSet containing 4415 pictures of different fish,
the network is learning and finally knows how to ganerate a new and high quality fish that not found in this DataSet.
In the research, I tried to create different architectures and mentioned a few other points:
<ul>
  <li>Loss function</li>
  <li>Optimizers</li>
  <li>Deeper vs shallower network</li>
  <li>Label smoothing</li>
  <li>Decrease learning rate after a few epochs</li>
  <li>Batch Normalization</li>
  <li>Manually decay learning rate</li>
</ul>  


This architecture is largely based on DCGAN networks with changes I made.

<h3>Below are fake pictures of fishes that was output the net:</h3>

<img src="https://github.com/MayYosef/GAN-ThisFishDoesNotExist/blob/master/images/final_fishes.png" width="75%" />


