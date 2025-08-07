 In today's world when humans are hit by the pandemic COVID-19, the governments and organizations concerned with human health around the globe have made it compulsory for people to wear masks whenever they are in a public place. But as we all know, wearing a
 mask gets suffocating after sometime and people tend to remove the
 mask which is dangerous for health as without a face mask it is very
 easy to catch the infection. Hence there arises the need to monitor
 people in public places, if they are wearing a mask or not and if they
 aren't  wearing a mask they are to be penalized by authority.
 
 As the name suggests this model will be able to classify images into
 two categories, i.e., with mask and without mask. It is a binary
 Classification problem.

 The dataset used for building the model was compiled from different sources
 by Balaji Srinivasan,
 https://github.com/balajisrinivas/Face-Mask-Detection/tree/master/dataset
 
 The dataset consists of two folders, one containing images with mask
 and other with no mask.
 ● With mask: 1915 images
 ● Without mask: 1918 images
 
 For image Classification we need to perform convolution which
 requires a large number of complex multiplications to be performed.
 Performing Multiplication is a costly operation and consumes a lot of
 memory. As a result the created model has a bigger size and slower
 processing, hence not optimal for embedded devices.
 
 To overcome these limitations we use the Mobilenet Architecture. It
 eliminates the need for a large number of complex multiplications. The
 process of convolution is divided into two parts, Depth Wise
 Convolution and PointWise Convolution. Using this we are able to
 reduce the number of multiplications which reduces the size and
 processing required. The size of MobileNet on disk is about 17MB
 only and it has 4.2 million parameters.
