## These are some examples of running and acquiring the connected components

### Note on Other implementations

We tried a lot of methonds to edit and train the Hamiltonian in order to give connected components, mostly by leveraging spanning trees and tweaking the "punishment" for the Hamiltonian. However, this worked really well for smaller graphs, but not nearly as well for bigger ones. On an average, it divided bigger graphs into multiple 2-3 node connected components, but we have certain ideas about fine tuning that we may implement in the future.
