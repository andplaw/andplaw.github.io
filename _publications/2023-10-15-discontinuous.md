---
title: "Enhanced trapezoidal rule for discontinuous functions"
collection: publications
permalink: /publication/2023-10-15-discontinuous
date: 2023-10-15
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2023.112386'
---

In many applications, data to be integrated is available only in the form of function values at predetermined equispaced points. For smooth periodic functions, the trapezoidal rule gives very accurate approximations to the integral, but is only second order accurate in more commonly arising non-periodic cases. The Gregory approach for end corrections can improve the accuracy order to 9 before the onset of negative weights, and of rapidly increasing ill-conditioning. In recent work, this has been extended to accuracy orders around 20.

This present study focuses on the more general case when one or both end points of the integration interval do not coincide with any of the equispaced grid points. We show that accuracy orders up to around 10 can also then be achieved, with all quadrature weights still remaining non-negative. This method can be utilized for example when functions to be integrated feature discontinuities at locations that can be separately determined (at or in between the equispaced grid points).
