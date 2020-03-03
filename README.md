from sympy import *

def compute_prob(nTrials, numObserved):

    prob = (factorial(nTrials)/(factorial(numObserved)*factorial(nTrials-numObserved)))*0.5**(numObserved)*0.5**(nTrials-numObserved)
    
    return prob # print the probability
