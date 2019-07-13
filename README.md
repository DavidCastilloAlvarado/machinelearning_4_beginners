## Machinelearning_4_beginners
# Machine learning from Perceptron to Deep learning simple aplication
---
# PERCEPTRÓN
In this little work we create a perceptron model who can classify 
if you are able for go to a party, I know is straugforward, 
but this is a spotlight for the beginners, using this model 
they can create his own model or undestrand how a neural-network works.

### X_input = [X1, X2]
### Y_output = {-1,1}

---
# Algoritmo
#### Sea: Perceptron{{X^i,Y^i,i=1,…,n},T}
#### Se inicializan W y bias con valores en cero 
####   For t = 1,...,T then
####        For i = 1,...,n then
####             If 〖Y^i*(W〗_t*X^i+bias)≤0 then
####                  Update W_(t+1)←W_t+Y^i*X^i    
####                  Update bias ←bias+Y^i

