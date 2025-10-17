# Differential Equations with MATLAB

Lesson: Practical user manuals for Differential Equations. These manuals represent a fourth-semester course in the analytical curriculum of the 
Civil Engineering program at the Faculty of Civil and Mechanical Engineering. The manual establishes the basic concepts and practices of first-order 
differential equations, based on a review of derivatives and integrals, using the mathematical language MATLAB.

-------------------------------------------------------------------------------------------------------------------------------------------

Differential Equations with MATLAB
"Ecuaciones Diferenciales con MATLAB".
                  Version 1.0
                  
-------------------------------------------------------------------------------------------------------------------------------------------
Theoretical Physics and the Cosmos Department

Signal Theory, Telematics and Communications Department

Andalusian Institute of Geophysics and Prevention of Seismic Disasters.

Granada University (Ugr), Granada, Spain
      
-------------------------------------------------------------------------------------------------------------------------------------------

    Author Docente: Ligdamis A. Gutiérrez PhD (1,2,3)
    Ambato, Ecuador 2015-2016

Institutions associated:

(1) Department of Theoretical Physics and Cosmos. Science Faculty. Avd. Fuentenueva s/n. University of Granada. 18071. Granada. Spain.

(2) Andalusian Institute of Geophysiscs. Campus de Cartuja. University of Granada. C/Profesor Clavera 12. 18071. Granada. Spain.

(3) Technical University of Ambato (UTA). Ambato, Ecuador.

WARNING: Do not modify or edit the documentation material without the author's permission.
   If you use this documentation, please indicate and reference the author and the institutions he represents.

  
-------------------------------------------------------------------------------------------------------------------------------------------

**Acknowledgment:**

We are grateful to the management of the Faculty of Civil and Mechanical Engineering of the Technical University of Ambato (UTA) - Ambato, Ecuador, 
for allowing the creation of this document by the author, as an integral part of the subject of Differential Equations within the analytical plan 
of the Civil Engineering Degree, for fourth-semester students, during the 2015 and 2016 academic years.
The Author, Teaching: Ligdamis A. Gutiérrez E., PhD.

-------------------------------------------------------------------------------------------------------------------------------------------

**Introduction:**

Dear User:

This file contains information related to Documentation for four modules on the topic:
 
Differential Equations with MATLAB.
"Ecuaciones Diferenciales con MATLAB".

Please read it carefully before starting work.

In the same way, it is recommended to review the contents of the manual attached to the documents, in order to become familiar with the different actions that can be carried 
out, through the elements of system management.

The codes and examples contained in the user manuals have been developed in MATLAB Software (Version 7a).
 
I) *** MATLAB LANGUAJE ****

Important Note:

To be able to use the scripts and GUIs (Graphical User Interfaces) presented in this manual, the user must have basic knowledge of the software used and be able to 
create and modify the script and GUI codes in order to adapt them and improve the calculation results in the proposed exercises on Differential Equations.

During the development of this course, the author designed and wrote a user manual for the MATLAB language to be used as a support tool and complement 
to the user manuals implemented here. This manual is intended to be used in learning and using the software, as well as in creating programs, scripts, 
and graphical user interfaces (GUIs) to be used in the examples and exercises proposed in this course.

These manuals will be published in a subsequent issue by the author.

The MATLAB languaje can be downloaded from the website:

https://es.mathworks.com/help/install/ug/install-products-with-internet-connection.html

This website can be used in different languages, for different versions of Matlab, on Windows, Linux and Mac operating systems.

It works on 32 and 64 Bit Systems (x86, win64), under Windows (7, 8, 10, 11).
This Software has been tested on Linux systems on Ubuntu 20 and the macOS for Mac System.
Additionally, should work without problems in other similar Linux systems like: Debian, Ret Hat, Fedora, SUSE, etc.


II) *** Examples and Exercises ****

Most of the examples and exercises, as well as the figures presented in the manuals, have been taken from the bibliography provided at the end of the manual. 
Many of them have been modified and adapted by the author to the purpose of this course, which is the Civil Engineering program.

The theoretical content offered in these manuals is a summary of the content taught during the course. 
This content is provided as theoretical content in various manuals taught during the academic course "Differential Equations" 
for the fourth semester of Civil Engineering.

This course focuses more on practical aspects, as a support and aid to the knowledge acquired during the course.

-------------------------------------------------------------------------------------------------------------------------------------------
GENERAL CONTENT INDEX: Contents of each module
-------------------------------------------------------------------------------------------------------------------------------------------

**GENERAL OBJECTIVE:**

Generate practical knowledge based on positive-critical thinking and logical reasoning, aided by the use of 
specific mathematical analysis software such as Matlab, which is necessary for understanding this course on Differential Equations.


The main documents of the user manuals are designed and written in Spanish and are composed of three teaching units, which are detailed below.

a) Unit 1: Review of Limits, Derivatives and Integrals, Introduction to the Matlab language and its use with Differential Equations.
             (Repaso Límites, Derivadas e Integrales, Introducción al lenguaje Matlab y su uso con Ecuaciones Diferenciales).

b) Unit 2: Mathematical Models applied to Differential Equations, Basic Concepts of Differential Equations, Identification and Solution of First Order Differential Equations.
             (Modelos Matemáticos aplicados a Ecuaciones Diferenciales, Conceptos básicos de Ecuaciones Diferenciales, Identificación y Solución de Ecuaciones Diferenciales de Primer Orden).

c) Unit 3: Graphical and Numerical Methods for Solving Differential Equations, Taylor Series and Laplace and Fourier Transforms for Higher Order Differential Equations.
             (Métodos Gráficos y Numéricos de solución de Ecuaciones Diferenciales, Series de Taylor y Transformadas de Laplace y Fourier para Ecuaciones Diferenciales de orden superior).


The development, content, design, presentation and writing of these two user manuals by the author represent the teaching of a subject of a degree course 
of Differential Equations, aided by the use of the mathematical language software MATLAB Version 7a, taught to fourth semester students of the Civil Engineering degree, 
by the Technical University of Ambato (UTA), through the Faculty of Civil and Mechanical Engineering, in Ambato, Ecuador in two academic years 2015 and 2016.

NOTE: The two user manuals, which contain the three teaching units, include a detailed index to help users learn and improve their knowledge of both 
the language and the software used. Refer to the user manuals included in this document.

-------------------------------------------------------------------------------------------------------------------------------------------
MAIN OBJECTIVE OF MODULES DOCUMENTATION
-------------------------------------------------------------------------------------------------------------------------------------------

Through simple, intuitive, and easy-to-use explanations and examples, each unit represents the learning process for the subject "Differential Equations" 
and the software that provides mathematical analysis tools and models used in the proposed examples and exercises. This allows students to interact with 
the acquired knowledge and design new scripts or programs. It also includes GUIs that allow flexible management of the solution to most of the knowledge 
acquired about Differential Equations. It is very useful for those dedicated to understanding and learning Differential Equations and seeking to represent 
mathematical analysis and practical results in a much more useful way in the fields of civil engineering, education, etc.

The specific objectives and contents of each unit are as follows:

**a) Unit 1:**

Analyze preconditions and definitions to integrate them into the use of differential equations, know and manage the mathematical program Matlab and its 
use with derivatives, integrals and differential equations, and can develop programs in Matlab including 2D and 3D graphics, which applies in the following units.

**b) Unit 2:**

To understand the different applications of applied mathematical models as equations and the use of differential equations applied to mathematical models, as well as 
to understand and develop additional topics in the solution of first-order and first-degree differential equations: linear, exact, homogeneous, separable, and Bernoulli.

**c) Unit 3:**

Know and apply graphical and numerical methods to develop solutions to higher-order linear equations, homogeneous with constant coefficients, through the application 
of graphical methods such as isoclines, and numerical methods such as Euler and Runge-Kutta of 1st and 4th order, as well as the application to Taylor series 
and transforms such as Laplace and Fourier.

   
-------------------------------------------------------------------------------------------------------------------------------------------
INSTALLATION COMMENTS
-------------------------------------------------------------------------------------------------------------------------------------------

The user must have the knowledge to download and install the MATLAB software from the platform indicated above, in order to use, create and 
modify the various programs (scripr) and GUIs interfaces that need to be implemented.

-------------------------------------------------------------------------------------------------------------------------------------------

In the near future, in a new version or update of the current version (1.0), a new module containing several methods, functionalities, 
and more examples and exercises will be added.

** THEY WILL BE AVAILABLE FOR DOWNLOAD IN THE FUTURE **
Sincerely, Best Regards. Ligdamis A. Gutiérrez E. PhD.

-------------------------------------------------------------------------------------------------------------------------------------------
