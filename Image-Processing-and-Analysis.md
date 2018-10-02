# Image-Processing-and-Analysis-1

f=imread('yuanyuan.jpg');
% imshow(f);
%imwrite(f,'圆圆姐.jpg');
g=rgb2gray(f);%彩色转变成灰度图像
imshow(g);
h=imadjust(g,[ ],[ ],2);%反转，图片像素灰度值
imshow(h);
