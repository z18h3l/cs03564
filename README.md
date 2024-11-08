java c
ELEN 4810 Midterm Exam 
1.  Systems in Time and Frequency. Consider the following causal system.  Note that here, the operation Dk  denotes a delay by k samples:

Please answer the following questions: 
(a) Is the overall system stable?  (Why or why not)
(b) Is the overall system linear?  (Why or why not)
(c) Is the overall system time invariant?  (Why or why not)
(d) What is the frequency response HB (ejw ) of the subsystem in box B?
(e) Consider an input of the form. x[n] = ejw0 n.  For what choice or choices of ω0   (in the principal interval —π < ω0 ≤ π) is the output y[n] = 0 for all n?
2.  Sampling. A continuous-time signal xc (t) has Fourier transform.
Xc (jΩ)  =  δ(Ω - Ω0 ) + δ(Ω + Ω0 ) + δ(Ω - 1.5Ω0 ) + δ(Ω - 1.5Ω0 ) 
depicted below: 

We sample the signal with period T and sampling frequency Ωs  = 2π/T to produce a discrete time signal x[n], with discrete-time Fourier transform. X(ejw ). Xc (jΩ) is a superposition of four Dirac δ measures. For any choice of T > 0, X(ejw ) is also a superposition of Dirac δ measures.
Consider the following sampling frequencies:
(i) Ωs  = 4Ω0
(ii) Ωs  = 2.25Ω0
(iii) Ωs  = 1.25Ω0
For each of these sampling frequencies, please answer the following questions:
a. How  many  Dirac δ measures  does X(ejw ) contain  within  the  principal  interval -π < ω ≤ π? 
b. Would an ideal D/C converter with period T = 2π/Ωs correctly reconstruct xc (t) from the samples x[n]?
If you’d like, you can use the  extra graphs  of Xc   below  to  help  construct  and explain your answer.

3.  Convolution via the Discrete Fourier Transform. Consider three nonnegative, real-valued signals x, y and z. 代 写ELEN 4810 Midterm Exam 2021Statistics
代做程序编程语言These signals are nonzero on the following intervals:
x[n] > 0 0 ≤ n < 20, x[n] = 0 else 
y[n] > 0 5 ≤ n < 25, y[n] = 0 else 
z[n] > 0 10 ≤ n < 30, z[n] = 0 else
We wish to compute the convolution x * y * z of these three signals.
Please answer the following questions: 
Part (a) For what values of n is the convolution x * y * z[n] nonzero?
Part (b) Suppose we set w[n] = DFTL-1 {DFTL {x}DFTL {y}DFTL {z}} [n]. For what choices of L is w[n] = x * y * z[n] for all n?Part (c) Suppose we are allowed to reorder the entries of w to reproduce the nonzero entries of x * y * z. Can we reduce L compared to your answer to Part (b)?  If so, what is the smallest possible L?
4. An Ideal Low-Pass Filter. Consider an ideal lowpass ﬁlter, with frequency response

and impulse response hlp [n].
(a) Is the system causal? Briefly explain.
(b) Is the system stable? Briefly explain.
Suppose we create a new system with impulse response h[n] = w[n]hlp [n] and

Here, N1  and N2  are integers, and N1  ≤ N2 . Let H(ejw ) denote the frequency response of the new system.
(c) For what (if any) values of N1  and N2  is the new system causal? Briefly explain.
(d) For what (if any) values of N1  and N2  is the new system stable? Briefly explain.
5. Upsampling and Downsampling. Consider the following system:

Here,

The ﬁlters F1  and F2  satisfy  jFi (ejw )j > 0 for all ω .
Part 1. For what choices of the ﬁlters H3   and H4  is the overall system linear time  invariant (LTI)?
Part 2. With your choices of H3  and H4  in Part 1, what is the overall frequency response H (ejw ) of the system?






         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
