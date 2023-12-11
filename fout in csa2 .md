#FOUT IN CSA 2 (ADDERS)

er is een fout bij de overflow van de ripple carry adder (2de vraag). Je moet nog een xor-gate toevoegen waarbij een input de laatste carry out is van de laatste 1-bit adder en je moet de carry out van de 1 bit adder als tweede input gebruiken. De output van deze xor-gate is dan de juiste overflow (2's complement).
