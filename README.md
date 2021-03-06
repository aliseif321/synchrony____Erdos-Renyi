# Measuring quantify the level of synchrony in a large population of neurons with in an Erdos-Renyi network.

In these programs, we created an Erdos-Renyi network for 100 neurons with a probability of connecting 0.3. then We performed these neurons with a Huxkin Huxley model with an external current of 2 µA/cm^2 for 2,500 milliseconds and stored the voltage for the last 500 milliseconds. Then, to better understand the production Erdos-Renyi network, we drew   how neurons connect to each other in the network in three dimensions and binary. And after calculating the spike train, we calculated the synchronization rate.

### For measure the level of synchrony we must pass 5 steps.


Step number  | work done | language used | outputs
:-------------: | :-------------: | :-------------: | :-------------:
first step  | Making an Erdos-Renyi network with Hodgkin-Huxley model | C++| temp.txt - datas.txt - bineryprint.txt
second step  |3D visualization of Erdos-Renyi Network | python| 3D Network.html
Third step  | plotting how neurons connect to each other in the network in a binary way | python| Binary.html
fourth step  | Calculating the spike train and draw the raster plot | MATLAB| train.png - spike_Phi_I.txt
fifth step  | Calculating the overall synchronization of the network | C++| level of synchrony



* ## first step

  * You can change the number of neurons, Possibility of connection, Finaltime for run, External Current and length steps of Runge-Kutta 4th Order Method
    * In these programs, we use ~100~ neurons with a probability of connecting ~0.3~ and external current of ~2 µA/cm^2~ for ~2,500~ milliseconds wih length steps ~0.01~
  * You receive three outputs
    * temp.txt
    * datas.txt
    * bineryprint.txt

* ## second step
  * You receive 3D visualization of Erdos-Renyi Network


<p align="center">
 <img src="https://github.com/aliseif321/synchrony____Erdos-Renyi/blob/main/step%202/Untitled.png?raw=true" >
 </p>


 
* ## Third step
  * You receive binary pic of Erdos-Renyi Network


<p align="center">
 <img src="https://github.com/aliseif321/synchrony____Erdos-Renyi/blob/main/step%203/Untitled1.png?raw=true" >
 </p>



* ## fourth step
  * You receive tow outputs
    * spike_Phi_I.txt
    * train.png 
 

<p align="center">
 <img src="https://github.com/aliseif321/synchrony____Erdos-Renyi/blob/main/step%204/train.png?raw=true" >
 </p>

 
* ## fifth step
  * The output of this program gives us level of synchrony
  

<p align="center">
 <img src="https://github.com/aliseif321/synchrony____Erdos-Renyi/blob/main/step%205/Untitled2.png?raw=true" >
 </p>


## References

[1] Emergence of global synchronization in directed excitatory networks of type I neurons (Abolfazl Ziaeemehr1, Mina Zarei & Aida Sheshbolouki

    DOI: 10.1038/s41598-020-60205-0
    
[2] Dynamic range in small-world networks of Hodgkin–Huxley neurons with chemical synapses C.A.S. Batista a, R.L. Viana a, S.R. Lopes a, A.M. Batista

    DOI: 10.1016/j.physa.2014.05.069
