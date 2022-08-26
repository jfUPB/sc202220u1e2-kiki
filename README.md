```cpp




while (true){
    if (??? !=0){
        if (MEMORY[0] ???? ){

            value = -1;
            
            ???MEMORY[0] = MEMORY[0] - 1;
            ???MEMORY[MEMORY[0]] = 0x0000;
        }

        else if (MEMORY[1] ??? ){

             value = 0;
            ???MEMORY[MEMORY[1]] = 0xFFFF;
            ???MEMORY[1] = MEMORY[1] + 1;

        }
        else{
            continue;
        }
        
        // DRAW
        MEMORY[16] = 16384;
        
        //LOOP
        ???
        
    }
}



