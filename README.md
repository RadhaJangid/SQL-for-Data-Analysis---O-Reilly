# Window Functions - 
Window functions are very-2 similar to groupby.
# OVER Clause - it is working as groupby only but the difference is in outcome.
Over Clause basically ek window create karta hai data me. window can be called as group.
window function aapko row by row result return karta hai whereas groupby grouped result return karta jitne groups honge utane hi rows aapke paas aayenge whereas in window function what will happen is ki jitne aapke data me rows hai utane hi rows vapas aayenge but sath hi sath aapko result bhi mil jayega aapke agregate operation ka.
# Conclusion
window functions are basiaclly analytical functions, jo agregate operation perform karte hai on groups. 

# RANK DENCE_RANK, ROW_NUMBER 
RANK  is window function, partition me ranking deta hai.Jaise ki sare branches me students ko rank karna hai on the basis of their marks.

Defference between RANK & DENCE_RANK :-
maan lo ki two students ke marks same hai.
<div class="w3-container">
  <table class="w3-table-all w3-card-4">
    <tr>
      <th>MARKS</th>
      <th>RANK()</th>
      <th>DENCE_RANK()</th>
    </tr>
    <tr>
      <td>95</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td>95</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td>80</td>
      <td>3</td>
      <td>2</td>
    </tr>
  </table>
</div>

