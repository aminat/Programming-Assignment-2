Programming-Assignment-2
========================

makeVector &lt;- function(x = numeric()) {         m &lt;- NULL         set &lt;- function(y) {                 x &lt;&lt;- y                 m &lt;&lt;- NULL         }         get &lt;- function() x         setmean &lt;- function(mean) m &lt;&lt;- mean         getmean &lt;- function() m         list(set = set, get = get,              setmean = setmean,              getmean = getmean) }
