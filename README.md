# Project-The-Dzhanibekov-Effect
This repo contains all the files of 'The-Dzhanibekov-Effect' project done by Aakarshika Singh,Dwara Nikhesh Babu, Y19, Mech UG, IIT Kanpur under the guidance of Prof. Ishan Sharma, Department of Mechanical Engineering, IIT Kanpur.
The project report is here - https://github.com/Aaka3021/Project-The-Dzhanibekov-Effect/blob/main/The_Dzhanibekov_Effect.pdf
de_numerical files are the only files not created by us (obtained from https://www.berkeley.edu).
To view an animation of The-Dzhanibekov-Effect, download this file - https://github.com/Aaka3021/Project-The-Dzhanibekov-Effect/blob/main/t-handle4.MP4 and view.


#Guide to run the files in Matlab:
Run de_analytical1_3.mlx with desired input to obtain the functions and plots for Angular Momentum and Angular Velocity.
This will also save the functions in analyticalsoln.mat file.
To obtain de_numerical solutions, first run de_numerical1.mlx to save ODEs in t_handle_ODEs.mat file.
Now run de_numerical2.mlx with desired input to obtain the function values and plots for Angular Momentum and Angular Velocity.
This will also save the function values in numericalsoln.mat file.
To combine plots of both analytical and numerical results as a way to validate our code, run validation.mlx .
This will make use of analyticalsoln.mat and numericalsoln.mat files.
Therefore, steps 1 and 2 should be done first with same input before running validation.mlx .
To obtain the animation, run de_analytical_2_1.mlx with desired input and then de_Model_1.mlx to create t-handle.avi which can be played in any videoplayer.
de_Model_1.mlx will make use of BFCS_E1E2E3.mat (created by de_analytical_2_1.mlx) to create t-handle.avi .
This takes a while because it creates 20fps animation bydefault. This can be changed by changing the value of dt (default is 0.05sec) in de_analytical_2_1.mlx, to obtain (1/dt)fps animation.
