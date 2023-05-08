Download Link: https://assignmentchef.com/product/solved-quantum-physics-ex-1
<br>
Exercise 1: Setup

<ul>

 <li>Create a working directory.</li>

 <li>Open emacs and write your first program in FORTRAN(c) Submit a test job.</li>

</ul>

(d) Connect to the cluster spiro.fisica.unpd.it via ssh and repeat the execution

Exercise 2: Number precision

Integer and real numbers have a finite precision. Explore the limits of INTEGER and REAL in Fortran.

<ul>

 <li>Sum the numbers 2.000.000 and 1 with INTEGER*2 and INTEGER*4</li>

</ul>

√

<ul>

 <li>Sum the numbers <em>π </em> 10<sup>32 </sup>and 2 · 10<sup>21 </sup>in single and double precision.</li>

</ul>

Exercise 3: Test performance

Matrix matrix multiplication is many times the bottleneck of linear algebra computations.

<ul>

 <li>Write explicitely the matrix-matrix multiplication loop in two different orders.</li>

 <li>Use the Fortran intrinsic function.</li>

 <li>Increase the matrix size and use the Fortran Function CPUTIME to monitor the code performance.</li>

</ul>

Use the compiler different optimization flags and monitor the performances