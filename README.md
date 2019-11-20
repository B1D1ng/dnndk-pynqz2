<!--
 * @Author: Sauron Wu
 * @GitHub: wutianze
 * @Email: 1369130123qq@gmail.com
 * @Date: 2019-08-27 10:48:42
 * @LastEditors: Sauron Wu
 * @LastEditTime: 2019-11-20 17:51:56
 * @Description: 
 -->
<table>
<tr>
  <td colspan="4" align="center"><img src="./images/xilinx-logo.png" width="30%"/><h1>Edge AI Tutorials</h1>
  </td>
</tr>
<tr>
<td colspan="4" align="center"><h1>Zynq 7000 DPU TRD</h1>
</td>
</tr>
</table>  

# dnndk3.0-pynqz2
- ## In this tutorial you will learn:
  1. How to use caffe model resnet50 to classify pictures using pynq-z2.
  2. How to use tensorflow model mnist to recognize hand-writing number using pynq-z2.
  3. How to train and use yolov3 in pynq-z2.
  4. How to use DNNDK-v3.0 to optimize the trained models.
  5. How to use dpu in pynq-z2 to accelerate inference.
- ## First download all the files to your pc.
- ## The files are organized as followed:
  > mnist_tf
  >> mnist_host  
  >> mnist_pynqz2  
  >> mnist-handwriting-guide.md  
  >>
  > resnet50_caffe  
  >> resnet50_host  
  >> resnet50_pynqz2  
  >> resnet50_pynqz2_guide.md

  The mnist_tf contains the mnist model trained by tensorflow and you can read the mnist-handwriting-guide.md to learn. The resnet50_caffe contains the resnet50 model trained by caffe and you can read the resnet50_pynqz2_guide.md to learn.  
- ## Preparation
  Before you start, you should read build-host-dnndk.md & build-pynqz2-system.md first to set your environment and do some preparation.
