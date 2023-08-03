---
layout: page
title: DeepCSF
description: Contrast Sensitivity Function (CSF) in deep networks
img: assets/img/deepcsf/csf.png
importance: 1
category: vision
---

The contrast sensitivity function (CSF) is a fundamental signature of the visual system that has 
been measured extensively in several species. It is defined by the visibility threshold for 
sinusoidal gratings at all spatial frequencies. Here, we investigated the CSF in deep neural 
networks using the same 2AFC contrast detection paradigm as in human psychophysics.


# Results
1. [ImageNet](#imagenet)
   * [ResNet](#resnet)
     * [ResNet50](#resnet50)
     * [Wide-ResNet](#wide-resnet)
     * [ResNeXt](#resnext)
   * [ViT](#vit)
     * [ViT-B32](#vit-b32)
     * [ViT-L32](#vit-l32)
   * [VGG](#vgg)
   * [ConvNeXt](#convnext)
   * [RegNet](#regnet)
   * [Classification](#classification)
   * [Linear SVM](#linear-svm)
2. [Without Pretrained Weights](#without-pretrained-weights)
3. [Taskonomy](#taskonomy)
4. [MS COCO](#ms-coco)
5. [CLIP](#clip)
    * [ResNet50](#clip-rn50)
    * [ViT-B32](#clip-b32)


## ImageNet

### ResNet

#### ResNet18

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet18_i1.png" title="resnet18_i1" caption="resnet18_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### ResNet34

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet34_i1.png" title="resnet34_i1" caption="resnet34_i1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### ResNet50

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i0.png" title="resnet50_i0" caption="resnet50_i0" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i1.png" title="resnet50_i1" caption="resnet50_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i2.png" title="resnet50_i2" caption="resnet50_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i3.png" title="resnet50_i3" caption="resnet50_i3" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i4.png" title="resnet50_i4" caption="resnet50_i4" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i5.png" title="resnet50_i5" caption="resnet50_i5" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i6.png" title="resnet50_i6" caption="resnet50_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i7.png" title="resnet50_i7" caption="resnet50_i7" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i8.png" title="resnet50_i8" caption="resnet50_i8" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet50_i9.png" title="resnet50_i9" caption="resnet50_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### ResNet101

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet101_i1.png" title="resnet101_i1" caption="resnet101_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### ResNet152

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnet152_i1.png" title="resnet152_i1" caption="resnet152_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### ResNeXt

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnext50_32x4d_i1.png" title="resnext50_32x4d_i1" caption="resnext50_32x4d_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/resnext101_32x8d_i1.png" title="resnext101_32x8d_i1" caption="resnext101_32x8d_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### Wide-ResNet

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/wide_resnet50_2_i1.png" title="wide_resnet50_2_i1" caption="wide_resnet50_2_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/wide_resnet101_2_i1.png" title="wide_resnet101_2_i1" caption="wide_resnet101_2_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

### ViT

#### ViT-B32

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i0.png" title="vit_b_32_i0" caption="vit_b_32_i0" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i1.png" title="vit_b_32_i1" caption="vit_b_32_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i2.png" title="vit_b_32_i2" caption="vit_b_32_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i3.png" title="vit_b_32_i3" caption="vit_b_32_i3" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i4.png" title="vit_b_32_i4" caption="vit_b_32_i4" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i5.png" title="vit_b_32_i5" caption="vit_b_32_i5" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i6.png" title="vit_b_32_i6" caption="vit_b_32_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i7.png" title="vit_b_32_i7" caption="vit_b_32_i7" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i8.png" title="vit_b_32_i8" caption="vit_b_32_i8" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_b_32_i9.png" title="vit_b_32_i9" caption="vit_b_32_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### ViT-L32

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i0.png" title="vit_l_32_i0" caption="vit_l_32_i0" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i1.png" title="vit_l_32_i1" caption="vit_l_32_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i2.png" title="vit_l_32_i2" caption="vit_l_32_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i3.png" title="vit_l_32_i3" caption="vit_l_32_i3" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i4.png" title="vit_l_32_i4" caption="vit_l_32_i4" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i5.png" title="vit_l_32_i5" caption="vit_l_32_i5" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i6.png" title="vit_l_32_i6" caption="vit_l_32_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i7.png" title="vit_l_32_i7" caption="vit_l_32_i7" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i8.png" title="vit_l_32_i8" caption="vit_l_32_i8" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vit_l_32_i9.png" title="vit_l_32_i9" caption="vit_l_32_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

### ConvNeXt

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i0.png" title="convnext_tiny_i0" caption="convnext_tiny_i0" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i1.png" title="convnext_tiny_i1" caption="convnext_tiny_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i2.png" title="convnext_tiny_i2" caption="convnext_tiny_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i3.png" title="convnext_tiny_i3" caption="convnext_tiny_i3" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i4.png" title="convnext_tiny_i4" caption="convnext_tiny_i4" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i5.png" title="convnext_tiny_i5" caption="convnext_tiny_i5" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i6.png" title="convnext_tiny_i6" caption="convnext_tiny_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i7.png" title="convnext_tiny_i7" caption="convnext_tiny_i7" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i8.png" title="convnext_tiny_i8" caption="convnext_tiny_i8" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/convnext_tiny_i9.png" title="convnext_tiny_i9" caption="convnext_tiny_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

### RegNet

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i0.png" title="regnet_x_1_6gf_i0" caption="regnet_x_1_6gf_i0" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i1.png" title="regnet_x_1_6gf_i1" caption="regnet_x_1_6gf_i1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i2.png" title="regnet_x_1_6gf_i2" caption="regnet_x_1_6gf_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i3.png" title="regnet_x_1_6gf_i3" caption="regnet_x_1_6gf_i3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i4.png" title="regnet_x_1_6gf_i4" caption="regnet_x_1_6gf_i4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i5.png" title="regnet_x_1_6gf_i5" caption="regnet_x_1_6gf_i5" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i6.png" title="regnet_x_1_6gf_i6" caption="regnet_x_1_6gf_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i7.png" title="regnet_x_1_6gf_i7" caption="regnet_x_1_6gf_i7" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i8.png" title="regnet_x_1_6gf_i8" caption="regnet_x_1_6gf_i8" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/regnet_x_1_6gf_i9.png" title="regnet_x_1_6gf_i9" caption="regnet_x_1_6gf_i9" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### VGG

#### VGG16-BN

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i0.png" title="vgg16_bn_i0" caption="vgg16_bn_i0" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i1.png" title="vgg16_bn_i1" caption="vgg16_bn_i1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i2.png" title="vgg16_bn_i2" caption="vgg16_bn_i2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i3.png" title="vgg16_bn_i3" caption="vgg16_bn_i3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i4.png" title="vgg16_bn_i4" caption="vgg16_bn_i4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i5.png" title="vgg16_bn_i5" caption="vgg16_bn_i5" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i6.png" title="vgg16_bn_i6" caption="vgg16_bn_i6" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i7.png" title="vgg16_bn_i7" caption="vgg16_bn_i7" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i8.png" title="vgg16_bn_i8" caption="vgg16_bn_i8" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_bn_i9.png" title="vgg16_bn_i9" caption="vgg16_bn_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

#### VGG16

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i0.png" title="vgg16_i0" caption="vgg16_i0" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i1.png" title="vgg16_i1" caption="vgg16_i1" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i2.png" title="vgg16_i2" caption="vgg16_i2" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i3.png" title="vgg16_i3" caption="vgg16_i3" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i4.png" title="vgg16_i4" caption="vgg16_i4" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i5.png" title="vgg16_i5" caption="vgg16_i5" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i6.png" title="vgg16_i6" caption="vgg16_i6" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i7.png" title="vgg16_i7" caption="vgg16_i7" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i8.png" title="vgg16_i8" caption="vgg16_i8" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/imagenet/all_layers/vgg16_i9.png" title="vgg16_i9" caption="vgg16_i9" class="img-fluid rounded z-depth-1" %}	
    </div>
</div>

### Classification

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/alexnet_i1.png" title="alexnet_i1" caption="alexnet_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/convnext_base_i1.png" title="convnext_base_i1" caption="convnext_base_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/convnext_large_i1.png" title="convnext_large_i1" caption="convnext_large_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/convnext_small_i1.png" title="convnext_small_i1" caption="convnext_small_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/densenet121_i1.png" title="densenet121_i1" caption="densenet121_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/densenet161_i1.png" title="densenet161_i1" caption="densenet161_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/densenet169_i1.png" title="densenet169_i1" caption="densenet169_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/densenet201_i1.png" title="densenet201_i1" caption="densenet201_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b0_i1.png" title="efficientnet_b0_i1" caption="efficientnet_b0_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b1_i1.png" title="efficientnet_b1_i1" caption="efficientnet_b1_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b2_i1.png" title="efficientnet_b2_i1" caption="efficientnet_b2_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b3_i1.png" title="efficientnet_b3_i1" caption="efficientnet_b3_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b4_i1.png" title="efficientnet_b4_i1" caption="efficientnet_b4_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b5_i1.png" title="efficientnet_b5_i1" caption="efficientnet_b5_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b6_i1.png" title="efficientnet_b6_i1" caption="efficientnet_b6_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/efficientnet_b7_i1.png" title="efficientnet_b7_i1" caption="efficientnet_b7_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/googlenet_i1.png" title="googlenet_i1" caption="googlenet_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/inception_v3_i1.png" title="inception_v3_i1" caption="inception_v3_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/mnasnet0_5_i1.png" title="mnasnet0_5_i1" caption="mnasnet0_5_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/mnasnet1_0_i1.png" title="mnasnet1_0_i1" caption="mnasnet1_0_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/mobilenet_v2_i1.png" title="mobilenet_v2_i1" caption="mobilenet_v2_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/mobilenet_v3_large_i1.png" title="mobilenet_v3_large_i1" caption="mobilenet_v3_large_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/mobilenet_v3_small_i1.png" title="mobilenet_v3_small_i1" caption="mobilenet_v3_small_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_16gf_i1.png" title="regnet_x_16gf_i1" caption="regnet_x_16gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_32gf_i1.png" title="regnet_x_32gf_i1" caption="regnet_x_32gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_3_2gf_i1.png" title="regnet_x_3_2gf_i1" caption="regnet_x_3_2gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_400mf_i1.png" title="regnet_x_400mf_i1" caption="regnet_x_400mf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_800mf_i1.png" title="regnet_x_800mf_i1" caption="regnet_x_800mf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_x_8gf_i1.png" title="regnet_x_8gf_i1" caption="regnet_x_8gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_16gf_i1.png" title="regnet_y_16gf_i1" caption="regnet_y_16gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_1_6gf_i1.png" title="regnet_y_1_6gf_i1" caption="regnet_y_1_6gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_32gf_i1.png" title="regnet_y_32gf_i1" caption="regnet_y_32gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_3_2gf_i1.png" title="regnet_y_3_2gf_i1" caption="regnet_y_3_2gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_400mf_i1.png" title="regnet_y_400mf_i1" caption="regnet_y_400mf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_800mf_i1.png" title="regnet_y_800mf_i1" caption="regnet_y_800mf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/regnet_y_8gf_i1.png" title="regnet_y_8gf_i1" caption="regnet_y_8gf_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/shufflenet_v2_x0_5_i1.png" title="shufflenet_v2_x0_5_i1" caption="shufflenet_v2_x0_5_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/shufflenet_v2_x1_0_i1.png" title="shufflenet_v2_x1_0_i1" caption="shufflenet_v2_x1_0_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/squeezenet1_0_i1.png" title="squeezenet1_0_i1" caption="squeezenet1_0_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/squeezenet1_1_i1.png" title="squeezenet1_1_i1" caption="squeezenet1_1_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg11_bn_i1.png" title="vgg11_bn_i1" caption="vgg11_bn_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg11_i1.png" title="vgg11_i1" caption="vgg11_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg13_bn_i1.png" title="vgg13_bn_i1" caption="vgg13_bn_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg13_i1.png" title="vgg13_i1" caption="vgg13_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg19_bn_i1.png" title="vgg19_bn_i1" caption="vgg19_bn_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vgg19_i1.png" title="vgg19_i1" caption="vgg19_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vit_b_16_i1.png" title="vit_b_16_i1" caption="vit_b_16_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/imagenet/fc/vit_l_16_i1.png" title="vit_l_16_i1" caption="vit_l_16_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

## Linear-SVM

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i0.png" title="resnet50_i0" caption="resnet50_i0" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i1.png" title="resnet50_i1" caption="resnet50_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i2.png" title="resnet50_i2" caption="resnet50_i2" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i3.png" title="resnet50_i3" caption="resnet50_i3" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i4.png" title="resnet50_i4" caption="resnet50_i4" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/lin_svm/resnet50_i5.png" title="resnet50_i5" caption="resnet50_i5" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

## Without-pretrained-weights

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i0.png" title="resnet50_random_weights_i0" caption="resnet50_random_weights_i0" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i1.png" title="resnet50_random_weights_i1" caption="resnet50_random_weights_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i2.png" title="resnet50_random_weights_i2" caption="resnet50_random_weights_i2" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i3.png" title="resnet50_random_weights_i3" caption="resnet50_random_weights_i3" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i4.png" title="resnet50_random_weights_i4" caption="resnet50_random_weights_i4" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i5.png" title="resnet50_random_weights_i5" caption="resnet50_random_weights_i5" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i6.png" title="resnet50_random_weights_i6" caption="resnet50_random_weights_i6" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i7.png" title="resnet50_random_weights_i7" caption="resnet50_random_weights_i7" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i8.png" title="resnet50_random_weights_i8" caption="resnet50_random_weights_i8" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/random/resnet50_random_weights_i9.png" title="resnet50_random_weights_i9" caption="resnet50_random_weights_i9" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

## Taskonomy

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/autoencoding.png" title="autoencoding" caption="autoencoding" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/class_object.png" title="class_object" caption="class_object" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/class_scene.png" title="class_scene" caption="class_scene" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/curvature.png" title="curvature" caption="curvature" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/denoising.png" title="denoising" caption="denoising" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/depth_euclidean.png" title="depth_euclidean" caption="depth_euclidean" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/depth_zbuffer.png" title="depth_zbuffer" caption="depth_zbuffer" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/edge_occlusion.png" title="edge_occlusion" caption="edge_occlusion" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/edge_texture.png" title="edge_texture" caption="edge_texture" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/egomotion.png" title="egomotion" caption="egomotion" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/fixated_pose.png" title="fixated_pose" caption="fixated_pose" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/inpainting.png" title="inpainting" caption="inpainting" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/jigsaw.png" title="jigsaw" caption="jigsaw" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/keypoints2d.png" title="keypoints2d" caption="keypoints2d" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/keypoints3d.png" title="keypoints3d" caption="keypoints3d" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/nonfixated_pose.png" title="nonfixated_pose" caption="nonfixated_pose" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/normal.png" title="normal" caption="normal" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/point_matching.png" title="point_matching" caption="point_matching" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/reshading.png" title="reshading" caption="reshading" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/room_layout.png" title="room_layout" caption="room_layout" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/segment_semantic.png" title="segment_semantic" caption="segment_semantic" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/segment_unsup25d.png" title="segment_unsup25d" caption="segment_unsup25d" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/segment_unsup2d.png" title="segment_unsup2d" caption="segment_unsup2d" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/taskonomy/vanishing_point.png" title="vanishing_point" caption="vanishing_point" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

## MS COCO

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/coco/deeplabv3_resnet101.png" title="deeplabv3_resnet101" caption="deeplabv3_resnet101" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/coco/deeplabv3_resnet50.png" title="deeplabv3_resnet50" caption="deeplabv3_resnet50" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/coco/fcn_resnet101.png" title="fcn_resnet101" caption="fcn_resnet101" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/coco/fcn_resnet50.png" title="fcn_resnet50" caption="fcn_resnet50" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

## CLIP

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B16_i1.png" title="B16_i1" caption="B16_i1" class="img-fluid rounded z-depth-1" %}
	</div>
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/L14_i1.png" title="L14_i1" caption="L14_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deepcsf/clip/RN101_i1.png" title="RN101_i1" caption="RN101_i1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### CLIP-B32

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i0.png" title="B32_i0" caption="B32_i0" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i1.png" title="B32_i1" caption="B32_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i2.png" title="B32_i2" caption="B32_i2" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i3.png" title="B32_i3" caption="B32_i3" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i4.png" title="B32_i4" caption="B32_i4" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i5.png" title="B32_i5" caption="B32_i5" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i6.png" title="B32_i6" caption="B32_i6" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i7.png" title="B32_i7" caption="B32_i7" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i8.png" title="B32_i8" caption="B32_i8" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/B32_i9.png" title="B32_i9" caption="B32_i9" class="img-fluid rounded z-depth-1" %}
	</div>
</div>

### CLIP-RN50

<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i0.png" title="RN50_i0" caption="RN50_i0" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i1.png" title="RN50_i1" caption="RN50_i1" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i2.png" title="RN50_i2" caption="RN50_i2" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i3.png" title="RN50_i3" caption="RN50_i3" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i4.png" title="RN50_i4" caption="RN50_i4" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i5.png" title="RN50_i5" caption="RN50_i5" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i6.png" title="RN50_i6" caption="RN50_i6" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i7.png" title="RN50_i7" caption="RN50_i7" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i8.png" title="RN50_i8" caption="RN50_i8" class="img-fluid rounded z-depth-1" %}
	</div>
</div>
<div class="row">
	<div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/deepcsf/clip/RN50_i9.png" title="RN50_i9" caption="RN50_i9" class="img-fluid rounded z-depth-1" %}
	</div>
</div>