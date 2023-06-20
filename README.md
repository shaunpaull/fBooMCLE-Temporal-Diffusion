# fBooMCLE-Temporal-Diffusion
fBooMCLE Temporal Diffusion
This code includes a modified fBm function that takes a t parameter representing time. It uses this parameter to generate a time offset for each lattice symbol. The createLattice function now applies temporal diffusion by calling fBm with appropriate arguments and adjusting the time index accordingly. The encryption and decryption functions are also updated to handle the modified lattice structure.
