# Design-_Verilog_Clk_generator_for_UART
Design  Systemverilog a Clock  Generator
  //tx_max = (System Clock Frequency) / (Baud Rate)   ////    Clk  T=tx_max -->  I/tx_max= Freq
/*

4800	50,000,000 / 4,800 ≈ 10416.67 → 10416	10416
9600	50,000,000 / 9,600 ≈ 5208.33 → 5208	5208
19200	50,000,000 / 19,200 ≈ 2604.17 → 2604	2604
38400	50,000,000 / 38,400 ≈ 1302.08 → 1302	1302
57600	50,000,000 / 57,600 ≈ 868.06 → 868	868
