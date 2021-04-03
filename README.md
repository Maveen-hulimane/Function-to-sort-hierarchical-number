# Function-to-sort-hierarchical-number

This is a function which takes list of shuffled hierarchical numbers (string) and then return sorted hierarchical numbers in ascending order

test case:
     1. input:['1.2.3','1','1.4.2','1.0.0','1.1.0','1.1.1']
        outut:['1', '1.0.0', '1.1.0', '1.1.1', '1.2.3', '1.4.2']
            
     2. input:["1.1.2", "1.0", "1.3.3", "1.0.12", "1.0.2",'01.02.05']
        output:['1.0', '1.0.2', '1.0.12', '1.1.2', '01.02.05', '1.3.3']
            
     3. input:['1.1.1','0.0','11.2','0','11','2.0.0','2.0','2','4.5.1','1.2.3','1.2.1','1.3.2','2.0.1']
        output:['0', '0.0', '1.1.1', '1.2.1', '1.2.3', '1.3.2', '2', '2.0', '2.0.0', '2.0.1', '4.5.1', '11', '11.2']
    
