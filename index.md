
## Adversarial Robustness Benchmarks

Comparing adversarial defences has become a daunting task, with many defences reporting robustness improvements in spite of the fact that [they can easily be broken](https://arxiv.org/abs/2002.08347).


This page gathers benchmarks for defences that either stood the test of time or proved effective.

The list is subject to continuous change and some defences may be removed as they are broken.
Contributions are welcomed.

We exclude certified defences because they can only provide certificates for the training data set.

Also, the neural network architecture may vary between different papers. 
The table is meant as an overview, to provide guidance for researchers and practitioners when navigating through defenses.
It should be taken with a grain of salt. 
The table's interpretation is in the hands of the beholder.

<table>
  <tr>
    <td rowspan="2">Title</td> <td rowspan="2">Acronym</td> <td rowspan="2">Eps.</td> <td colspan="2">CIFAR-10</td> <td colspan="2">CIFAR-100</td> <td rowspan="2">Impact on Training</td> <td rowspan="2">Notes</td>  <td rowspan="2">Link</td>       
  </tr>
  <tr>
   <td>Clean Acc. </td> <td> Attack / Acc. </td> <td>Clean Acc. </td> <td> Attack / Acc. </td> 
  </tr>  

  <tr>
   <td>Adversarial Training for Free!</td> <td> - </td> <td> 8/255 </td>  <td> 85.96%  </td> <td>  PGD-20 / 46.82% </td> <td>   62.13% </td> <td> PGD-20 25.88% </td> <td> Medium  </td> <td> -  </td> <td> https://arxiv.org/abs/1904.12843 </td>
  </tr>
  
   <tr>
    <td>Fast is better than free: Revisiting adversarial training</td> <td> - </td> <td> 8/255 </td>  <td> 83.81%  </td> <td>  PGD-20 / 46.06% </td> <td>   -  </td> <td> - </td> <td> Medium  </td> <td> -  </td> <td> https://arxiv.org/abs/2001.03994 </td>
  </tr> 
  
  <tr>
    <td>Towards Deep Learning Models Resistant to Adversarial Attacks</td> <td> PGD-7 </td> <td> 8/255 </td>  <td> 87.25%  </td> <td>  PGD-20 / 45.84% </td> <td> 59.87% </td> <td> PGD-20 22.76% </td> <td> High </td> <td> - </td> <td> https://arxiv.org/abs/1706.06083  </td> 
  </tr>
  
</table>
