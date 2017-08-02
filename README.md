# Y-Shape NiDNA Device IV characteristics (Trial)
Basic Idea

In this work, we use Mathematica to simulate the current-voltage characteristics of a Y-shape Ni-DNA device, meaning there are three segments in the device and each segment consists of different numbers of Ni2+ and Ni3+ embedded inside the DNA helix. Different from the simple 2-terminal case, three terminal can be a very interesting case to study, as the change in one leg can indirectly affect the Ni2+/Ni3+ ratio and thus affect the I-V characteristic.

We use 3 coupled partial differential equations to solve for the numbers of Ni2+ and Ni3+ in terms of time. Once that is done, we can plot the I-V characteristic of each segment, eg. 1-2, 2-3, or 3-1.

Note that we include the diffusion parts in the coupled equations and the diffusion constant is approximated by the number we obtain from the literature (Ionic Diffusion Coefficients of Cs+, Pb2+,Sm3+,Ni2+, SeOz- and TcO, in Free Water Determined
from Conductivity Measurements, Journal of Nuclear Science and Technology, 33:12, 950-955)



