# ListOfSimulationsForFiniteTemperature

# List of simulations has been performed for the estimation of thermodynamic properties at a finite temperature for many linear rotors systems

List of simulations by using Path Integral Ground State Monte Carlo for the estimation of Renyi entropy for N number of rotors placed in a linear chain. The interaction potential is modelled by dipole - dipole interactions. The following parameters has been used for all simulations -
 ```
Rotational B constant = 20.561 wavenumber
R    = 10.05 Angstrom
		
# of Blocks = 150000
# of Pass   = 200
```

:one: Simulations for the **Entropy vs beta** 

   - At **tau  = 0.005 Kelvin^(-1)**
  
   _The list of beads P is_
    
   ```
   P    = [5, 9, 13, 17, 21, 25, 29, 33, 37, 41] 
   ```		
		
   - [x] N = 2, g = [1.0, 2.0, 4.0, 6.0, 8.0] :+1: **In Graham**
    
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.005Kinv-Blocks20000-Passes100-System2HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~
    
   Analysis complete: Skipped data first 0, 10000, 15000

   - [x] N = 8, g = [1.0, 1.5, 2.0]           :+1: **In Graham**
    
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.005Kinv-Blocks20000-Passes100-System8HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~

   Analysis complete: Skipped data first 0, 10000, 15000

   - [x] N = 16,g = [1.0, 1.3]                :+1: **In Graham** 
    
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.005Kinv-Blocks20000-Passes100-System16HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~

   Analysis complete: Skipped data first 0, 10000, 15000

   - At **tau  = 0.02 Kelvin^(-1)**
  
   _The list of beads P is_
    
   ```
   P    = [5, 7, 9, 11, 13, 15, 17, 19, 21] 
   ```		

   - [x] N = 16,g = [1.0, 1.3] :+1:         **In Graham** 
    
   ~/scratch/tapas/test-ratio-trick/ENT-Ratio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.02Kinv-Blocks20000-Passes100-System16HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~
    
   Analysis complete: Skipped data first 0, 10000, 15000
    
   - [x] N = 32,g = [1.0, 1.1] :+1:         **In Graham** 
    
   ~/scratch/tapas/test-ratio-trick/ENT-Ratio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.02Kinv-Blocks20000-Passes100-System32HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~
    
   Analysis complete: Skipped data first 0, 10000, 15000
                     
   - At **tau  = 0.04 Kelvin^(-1)**
  
   _The list of beads P is_
    
   ```
   P    = [5, 7, 9, 11, 13, 15, 17, 19, 21] 
   ```		

   - [x] N = 32,g = [1.0, 1.1] :+1:         **In Graham** 
                     
   ~/scratch/tapas/test-ratio-trick/ENT-Ratio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor1.0-tau0.04Kinv-Blocks20000-Passes100-System32HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~
    
   Analysis complete: Skipped data first 0, 10000, 15000
  
:two: Simulations for the **Entropy vs tau** as well as **gFactor**
   
   - at **beta  = 0.2 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [5, 11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
     
   - [x] N = 2, g = [0.5+i*0.1 for i in range(76)] :+1:         **In Graham**     
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System2HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 10000, 15000
   
   - [x] N = 2, g = [9.0+i*1.0 for i in range(12)] :+1:         **In Graham**     
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System2HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 30000, 40000, 45000
   
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks100000-Passes100-System2HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis incomplete: Skipped data first 0
   
   - [x] N = 2, g = [9.0+i*1.0 for i in range(12)] :+1:         **In Graham**     
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System2HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 30000, 40000, 45000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
     
   - [x] N = 4, g = [0.5+i*0.1 for i in range(31)] :+1:         **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System4HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 10000, 15000
   
   - [x] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1:         **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System4HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 10000, 15000
   
   - [x] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1:         **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes200-System4HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 30000, 40000, 45000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 21, 31, 41, 51, 61]  
   ```
          
   - [x] N = 8, g = [0.5+i*0.1 for i in range(16)] :+1:         **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System8HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 10000, 15000
   
   - [ ] N = 8, g = [2.1+i*0.1 for i in range(10)] :+1:         **Running in Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System8HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis incomplete: Skipped data first 0, 10000, 15000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 21, 31, 41, 51, 61]  
   ```
     
   - [x] N = 16,g = [0.5+i*0.1 for i in range(11)] :+1:         **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System16HF-ParticleA*-e0vsbeads-SWAPTOUNSWAP~ 
     
   Analysis complete: Skipped data first 0, 10000, 15000
				
   _For N = 32, jobs has been submitted for_
     
   ```
   P    = [5, 11, 15, 21, 25, 31]  
   ```

   - [x] N = 32,g = [0.5+i*0.05 for i in range(15)] :+1: **In Graham**
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-beta0.2Kinv-Blocks20000-Passes100-System32HF-ParticleA1-e0vsbeads-SWAPTOUNSWAP~

   Analysis incomplete: Skipped data first 0, 10000, 15000
     
     
   - at **beta  = 0.25 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [11, 15, 21, 25, 31, 35, 41]    for N = 16 
   P    = [11, 15, 21, 25]                for N = 32
   ```
     
   - [x] N = 16,g = [0.5+i*0.1 for i in range(9)]  :+1:         **In Feynman**
   - [x] N = 32,g = [0.5+i*0.1 for i in range(7)]  :+1:         **In Feynman**
          

   - at **beta  = 0.32 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [5, 11, 21, 31, 41, 51, 61]   
   ```
     
   - [ ] N = 16, g = [0.5+i*0.1 for i in range(11)]  :+1:        **Resubmitted in Graham  for P = [31, 41, 51, 61]**
   
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-beta0.32Kinv-Blocks20000-Passes100-System16HF-ParticleA1-e0vsbeads-SWAPTOUNSWAP~ 
      
   ```
   P    = [5, 11, 15, 21, 25, 31]   
   ```
      
   - [ ] N = 32, g = [0.7+i*0.05 for i in range(11)]  :+1:         **Submitted in Graham**   
   
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-beta0.32Kinv-Blocks20000-Passes100-System32HF-ParticleA1-e0vsbeads-SWAPTOUNSWAP~ 
   
    Analysis incomplete: Skipped data first 0, 10000, 15000
          
:three: Simulations for the **Entropy vs tau** as well as **gFactor** for ``BROKEN PATH''   
   
   - at **beta  = 0.2 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
     
   - [x] N = 2, g = [0.5+i*0.1 for i in range(76)] :+1:         **In Graham**
   
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks20000-Passes100-System2HF-ParticleA1-e0vsbeads-BROKENPATH~ 
     
   Analysis complete: Skipped data first 0, 10000 and 15000
   
   - [x] N = 2, g = [9.0+i*1.0 for i in range(12)] :+1:         **In Graham**     
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System2HF-ParticleA1-e0vsbeads-BROKENPATH~ 
     
   Analysis incomplete: Skipped data first 0, 30000, 40000, 45000
   
   - [ ] N = 2, g = [21.0+i*1.0 for i in range(10)] :+1:         **Running in Graham for P = [61]**     
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System2HF-ParticleA*-e0vsbeads-BROKENPATH~ 
     
   Analysis complete: Skipped data first 0, 30000, 40000, 45000
   
   _The list of beads P is_
     
   ```
   P    = [11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
   
   - [x] N = 4, g = [0.5+i*0.1 for i in range(31)] :+1:         **In Graham**   
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System4HF-ParticleA2-e0vsbeads-BROKENPATH~ 
     
   Analysis complete: Skipped data first 0, 30000 and 40000
   
   - [x] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1:         **In Graham**   
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes100-System4HF-ParticleA2-e0vsbeads-BROKENPATH~ 
     
   Analysis complete: Skipped data first 0, 30000 and 40000
   
   - [x] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1:         **In Graham**   
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor*-beta0.2Kinv-Blocks50000-Passes200-System4HF-ParticleA2-e0vsbeads-BROKENPATH~ 
     
   Analysis complete: Skipped data first 0, 30000 and 40000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
     
   - [ ] N = 8, g = [0.5+i*0.1 for i in range(16)] :+1:         **Running in Graham for P = [35, 45, 55]**  
     
   ~/scratch/tapas/test-ratio-trick/ENT-RotDOFs-Rpt10.05Angstrom-gFactor1.0-beta0.2Kinv-Blocks50000-Passes100-System8HF-ParticleA4-e0vsbeads-BROKENPATH~ 
     
   Analysis incoplete: Skipped data first 0 and 30000
     			
			
:four: Simulations for the **Entropy vs tau** as well as **gFactor** for **No Ratio Trick** using **SWAP+UNSWAP grand ensemble**
   
   - at **beta  = 0.2 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [5, 11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
   - [x] N = 4, g = [0.5+i*0.1 for i in range(31)] :+1: **In Graham**
     
   ~/scratch/tapas/test-no-ratio-trick/ENT-NoRatio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor3.5-beta0.2Kinv-Blocks30000-Passes100-System4HF-ParticleA2-e0vsbeads-SWAPTOUNSWAPPIMC/~
     
   Analysis complete: Skipped data first 0, 20000
   
   - [x] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1: **In Graham**
     
   ~/scratch/tapas/test-no-ratio-trick/ENT-NoRatio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor3.5-beta0.2Kinv-Blocks30000-Passes100-System4HF-ParticleA2-e0vsbeads-SWAPTOUNSWAPPIMC/~
     
   Analysis complete: Skipped data first 0, 20000
   
   - [ ] N = 4, g = [3.5+i*0.25 for i in range(11)] :+1: **Running in Graham for P = [55, 61]**
     
   ~/scratch/tapas/test-no-ratio-trick/ENT-NoRatio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor3.5-beta0.2Kinv-Blocks50000-Passes200-System4HF-ParticleA2-e0vsbeads-SWAPTOUNSWAPPIMC/~
     
   Analysis incomplete: Skipped data first 0, 20000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 15, 21, 25, 31, 35, 41, 45, 51, 55, 61]  
   ```
     
   - [ ] N = 8, g = [0.5+i*0.1 for i in range(16)] :+1: **Running in Graham for P = [35, 45, 55]**
     
   ~/scratch/tapas/test-no-ratio-trick/ENT-NoRatio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor2.0-beta0.2Kinv-Blocks50000-Passes100-System8HF-ParticleA4-e0vsbeads-SWAPTOUNSWAPPIMC/~
     
   Analysis incomplete: Skipped data first 0, 30000
   
   _The list of beads P is_
     
   ```
   P    = [5, 11, 21, 31, 41, 51, 61]  
   ```
     
   - [x] N = 16, g = [0.5+i*0.1 for i in range(11)] :+1: **In Graham**
     
   ~/scratch/tapas/test-no-ratio-trick/ENT-NoRatio-Trick-RotDOFs-Rpt10.05Angstrom-gFactor1.5-beta0.2Kinv-Blocks80000-Passes100-System16HF-ParticleA8-e0vsbeads-SWAPTOUNSWAPPIMC/~
     
   Analysis is complete: Skipped data first 0, 40000
     
   - at **beta  = 0.32 Kelvin^(-1)**	

   _The list of beads P is_
     
   ```
   P    = [11, 15, 21, 25, 31, 35, 41]    for N = 16 
   P    = [11, 15, 21, 25]                for N = 32
   ```
     
   - [ ] N = 16,g = [0.5+i*0.1 for i in range(9)]               **Need to be run**
   - [ ] N = 32,g = [0.5+i*0.1 for i in range(7)]               **Need to be run**   

**N.B.: Here I have analyzed MoRiBs data by skipping some amount of data by using preskip values: 0, 10000, 15000. Finally, I have decided to finalize it for preskip 10000 for all computations.**
