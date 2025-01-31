# Jargons

## Signatures

Think of signature as the important underlying properties of a path. Say I move my hand in the air from point A to point B, the important properties/signatures of that motion would be : start and end point, direction, etc...
Mathematically, signatures are apparently represented as iteraqted integrals shown below:-

![image](https://github.com/user-attachments/assets/86c6cbfa-c873-4d22-9735-23e2fdad2e31)

Signatures remove the need to describe the path at a micro level.

There is also a concept of truncated signatures. This means we only focus on properties of a certain order. (ex : I only care about how far my hand moved, not the orientation, tweists and turns, etc...). Formal definition below:-
![image](https://github.com/user-attachments/assets/262bbcd9-e6c0-4da2-a588-55c9a06e70bd)

Signatures are handy in giving approximations of a higher-order rough path/function.

## Reservoirs

I think of reservoirs as these black-box processors which process inputs and maps them to a higher-dimensional space. You could think of them as neuralk networks but the key difference is that these reservoirs are static and fixed
unlike trainable NNs. Reservoir is essentially the ground-truth which drives a particular system (ex : the exact function driving the time series).

The advantage of a reservoir is that since its not trained, its computationally efficient and easy to map to higher-order output space.

## Johnson-Lindenstrauss argument 

This is apparently the foundation of why dimensionality reduction works. It states "Any set of n points in high-dimensional space can be embedded into a much lower-dimensional space while
approximately preserving pairwise Euclidean distances, with high probability."
