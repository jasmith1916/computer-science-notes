#machinelearning #tensor 

# Tensor Operations

Tensors can have operations done to them just as numbers have +, -, /, and *

To do an in place operation in pytorch, add a trailing _ after the method name. For example if there are two tensors named x and y, y.add_(x) would add x and y together and change the values of y to x + y

### Element Wise Operations
The +,-,*, and / operations do element wise operations on each tensor. Each tensor must be the same size to be added or subtracted together and it will output a tensor of the same shape. In pytorch, using the + operator and doing torch.add() do the same thing. Element wise operations just multiply the elements of corresponding tensors and *DO NOT* do matrix multiplication or anything of the sort.

### Slicing Operations
Slicing can obtain different parts of the tensor. To slice a tensor, use [] notation. For example x[:, 0] would get all the rows but only the first column. You can also get one element with [index1,index2,...,indexn]