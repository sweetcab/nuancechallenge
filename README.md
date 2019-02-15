# nuancechallenge

## Description
Consider a 100011-word file excerpt from the novel “A Tale of Two Cities” by Charles Dickens (A_tale_of_two_cities.100kwords.original.txt).
An obfuscated version where each instance of the words “a” and “the” have been replaced by the words “a” or “the” 
(A_tale_of_two_cities.100kwords.obfuscated.txt).
                                        
The task is to resolve the “a/the” ambiguity in the latter version as best as possible via a computer program. 
Note this program should not access any part of the novel “A Tale of Two Cities” to accomplish this; 
i.e. it cannot “train on” or “memorize” this particular novel.  You are otherwise free to use whatever approach you see fit.

## Models
RNNs are the models used in this task trained by tensorflow, please refer to the report for details.
