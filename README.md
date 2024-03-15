# DBScan
DBSCAN Algorithm from scratch. With examples included and explanation of its complexity.
Given $n$ points to be clustered, the algorithm approximately takes $n^2 + \ln(n) \cdot \left(\ln{\left(\frac{n}{\ln(n)}\right)}\right)^{\ln{\left(\frac{n}{\ln(n)}\right)}}$ time, which for all practical purposes($*$) is $O(n^2)$.

$(*)$ For extremely large numbers like Graham's number, the second term(which is an exponential that grows faster than all polynomials) will be bigger then $n^2$, so the algorithm is actually $O\left(\ln(n) \cdot \left(\ln{\left(\frac{n}{\ln(n)}\right)}\right)^{\ln{\left(\frac{n}{\ln(n)}\right)}}\right)$

An explanation of this algorithm is on my YouTube video: [https://www.youtube.com/watch?v=PbU3JwRdAAw](youtube.com/watch?v=PbU3JwRdAAw)
