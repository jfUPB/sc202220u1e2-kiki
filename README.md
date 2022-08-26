MEMORY[16] = 16384;


while (true){
    if (kbd !=0){
        if (MEMORY[0] ){

            MEMORY[0] = MEMORY[0] - 1;
            MEMORY[MEMORY[0]] = 0x0000;
        }

        else if (MEMORY[1]){

            
            MEMORY[MEMORY[1]] = 0xFFFF;
            MEMORY[1] = MEMORY[1] + 1;

        }
    }
}



