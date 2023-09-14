

## Datasets

### Mean square displacment data (`data/msd`)

The dataset in `data/msd` includes mean square displacment of atoms at different *P,T*s.
Each `.dat` file corresponds to one *P,T* point.
The nine columns in a `.dat` file corresponds to the MSD of Al(x,y,z), O(x,y,z), H(x,y,z) at every 1,000 timestep.

### Pair correlation function data (`data/rdf-300K`)

The dataset in `data/rdf-300K` includes the Pair correlation function data, i.e., $g(r)$, for different pressures at 300 K.
`rdf.dat` corresponds to total $g(r)$, and `rdf_p.dat` corresponds to partial $g(r)$. The columns are column ID, $r$, (`density[r]`, `cumulative_density[r]`)$_i$. [H-H, x-x, x-x, O-O, O-H]

### P-V compression curve data at 300 K (`data/eos-300K`)

The dataset in `data/eos-300K` includes the compression curve at 300 K. The results are for 1,024 atoms. The pressure unit is bar, and the volume unit is $\mathrm{\AA}^3$.