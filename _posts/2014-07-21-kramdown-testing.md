---
layout: post
category: testing
tagline: Kramdown testing post
tags: 
  - testing
  - LaTex
  - Kramdown
published: true
---

{% include JB/setup %}

This post tests some features of Kramdown.

## Testing

Here is some math in LaTex:

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

-------------------

Here's a table:

|Name|Date|Count|
|:-|:-|-:|
|Peridotite|2003-12-01|6|
|Anorthosite|2001-07-14|8|
|Andesite|1986-08-24|17|
|Dunite|2003-09-11|2|
|===
|Sum||33|

-------------------

Here's a definition list:

BC
: Biochemistry

HAEM
: Haematology

RAD
: Radiology
: MRI

ONC
: Oncology
: Histopathology

-------------------

Here's an unordered list:

 * COBOL
 * FORTRAN
 * C
 * BASIC
 * SMALLTALK
 * HASKELL
 * EIFFEL
 * F#

-------------------

Example Worklight code comment:

~~~
WL.Logger.error("token");
WL.Logger.error(encryptedToken);
~~~

-------------------

Including and image is easy:

![Worklight](/images/icon.png)  

-------------------
