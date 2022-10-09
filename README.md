# Kalman-Filtering-on-Lie-Groups

This is a documentation of my project titled "Kalman Filtering on Lie Groups". We initially look at an implementation of a simple Kalman Filter in the context of Euclidean Spaces, and then look at expanding it to Lie Groups, which has applications in diverse fields in control. The overarching benefit of doing so is that the traditional Kalman Filter Algorithm needs linearization in situations when we have non-linear system dynamics. On the other hand, the Kalman Filter needs no such approximations. In situations with complex dynamics, when large errors are being propagated, the Kalman Filter on Lie Groups is expected to perform better.

The code file titled "Kalman Filtering on Lie Groups" presents the implementation of an observer (simplified version of a filter) design on smooth manifolds for determining the orientation rotating ground robot fixed at a point in space. The parameters can be varied and the results can be compared to determine the best possible choice for an optimal filter design.
