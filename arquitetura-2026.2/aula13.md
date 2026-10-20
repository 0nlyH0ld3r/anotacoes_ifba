# Harvard e Von Neumann (Hardware)

- Harvard
    - Memória de dados e instruções
    - 2 barramentos para a CPU conversar com as memórias
        - Na verdade 6 barramentos:
            - 2 data bus
            - 2 address bus
            - 2 control bus

- Von Neumann
    - Memória de dados
    - Memória de instruções
    - 1 barramento para a CPU conversar com a memóra
        - Na verdade 3 barramentos:
            - 1 data bus
            - 1 address bus
            - 1 control bus


# RISC e CISC (Execução de Instruções)

- RISC -> Reduced Instruction Set Computer
    - Executa no memória CACHE (Registradores)
    - Arquitetura de Harvard
    - Mais rápida
    - Mais cara

- CISC -> Complex Instruction Set Computer
    - Executa na memória RAM
    - Arquitetura de Von Neumann
    - Gargalo de Von Neumann
        - Diferença entre a velocidade do barramento do processador
        e a velocidade do barramento da memória.
    - Mais lenta
    - Mais barata

# Processadores

- UC -> Barramentro Interno
    - Arbitrar o fluxo de dados entre as unidades (internas ou não)

- ULA -> Barramentro Externo
    - Realiza cálculos lógicos e aritméticos

- Registradores
    - PC -> Program Counter
        - Armazena a próxima instrução
    - RI -> Instruction Register
        - Armazena a instrução atual
    - Acumulador
        - Acumula valores em um endereço da memória (soma)
    - MAR -> Memory Adress Register
        - Registrador de Endereço da Memória
    - MBR -> Memory Buffer Register
        - Registrador de Buffer da memória

- Barramento -> Via de tráfego de dados, flags de controle e instruções
    - Data bus
        - Trafega dados da memória
    - Adress bus
        - Trafega endereços de memória
    - Control bus
        - Trafega flags de controle da UC

# Ciclo de fetch

- BUSCA -> DECODIFICA -> EXECUTA -> BUSCA -> DECODIFICA -> EXECUTA ...


