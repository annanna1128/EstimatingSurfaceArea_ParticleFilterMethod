# EstimatingSurfaceArea_ParticleFilterMethod
This code provides a method for estimation of surface area of flow paths in geothermal reservoirs based on "Particle Filter Method". 
The conept of estimation can be found in "A. Suzuki, Estimation of Fracture Surface Area based on Tracer and Temperature Histories, GRC Transaction, (2017).
We use the site: https://qiita.com/kenmatsu4/items/c5232b1499dfd00e877d as a reference for particle filter method.

Data needed to prepare:
  1. tracer concentration vs time
  2. temperature decline vs time
  
  
Workflow
1. Read data
2. Calclate flow rate and pore volume for each path using tracer data
3. Compare b/w temperature data and calculated result and optimize surface area
