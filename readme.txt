sudo pip install tensorflow

from keras import backend as K
K.set_image_dim_ordering('th')

show hidden files
defaults write com.apple.finder AppleShowAllFiles YES
killall Finder

http://www.pyimagesearch.com/2016/08/10/imagenet-classification-with-python-and-keras/

to run
sudo python test_imagenet.py --image bear.png
THEANO_FLAGS=device=gpu,floatX=float32 python test.py --image bear.jpg

to change the permission of .theano file
sudo chmod -R 777 .theano
nano  ~/.bash_profile


AWS ec2 access

ssh -i Downloads/MyKeyPair4.pem ec2-user@ec2-35-165-219-243.us-west-2.compute.amazonaws.com

copy a folder from local to AWS EC2
scp -i ~/Downloads/MyKeyPair4.pem -r ~/Documents/keras_vgg_imagenet ec2-user@ec2-35-165-219-243.us-west-2.compute.amazonaws.com:~/data/



sliding window
https://stackoverflow.com/questions/41884001/keras-classification-object-detection



