```cpp




while (true){                                   
    if (MEMORY[KBD] !=0){                       
        if (MEMORY[0] == MEMORY[KBD])           
            {
            MEMORY[16] = -1;                    
            }
        else if (MEMORY[1] == MEMORY[KBD])      
            {
            MEMORY[16] = 0;                     
            }
        else{
            continue;                           
        }

    MEMORY[17] = 16384;                          

    while (MEMORY[17]<24576)
    {
        MEMORY[MEMORY[17]] == MEMORY[16];
        MEMORY[17]++;
    }
        
    }
}



