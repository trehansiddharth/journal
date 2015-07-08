# journal
This repository contains writeups of potentially useful ideas I've had so that I don't forget them. The process of writing down the ideas also helps me to catch bugs and formalize my thoughts better.

Contents
========

|Title | Abstract|
-------|---------
Accurately and Efficiently Identifying Centers of Circular Symmetry in Images | In cases such as the detection of circles at any scale in an image, it is important to be able to quantify the degree of circular symmetry about a point and use it to identify centers of high degree of circular symmetry in an image. This writeup describes a good metric for quantifying amount of circular symmetry and an efficient algorithm for finding the degree of rotational symmetry about every point in an N × M image at once in O(NM lg NM) time using gradient and cross-correlation.
