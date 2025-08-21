
This is a guide to encoding and decoding the Trusted Genetic Module in the genome using the demo program for Windows.
 
File preparation:
1. If you want to encode Trusted Genetic Module, please refer to the file format of "encode.json" in the "datas" folder, in which "gene_id" is an ID of 14 characters in length, "gene" is the gene sequence to be encoded, and "payload" is the DNA sequence carrying digital information. 
2. If you want to decode Trusted Genetic Module, please refer to the file format of "decode.json" in the "datas" folder, where each "reads_id" corresponds to a "reads_seq".

program execution:
1. command: ............\TGM\Release_x64> .\GTPM_dGMS.exe ..\datas\GTPM-params.json
2. Parameters in "GTPM-params.json": "function"(Execution status: 0=off, 1=on). For example, to perform encoding, set the value after "ENCODE" to "1".
3. Encoding Result: after the "ENCODE" program is executed, the latest "gene_info.txt" and "encode_result.json" file appear in the "datas" folder; 
4. Decoding Result: after the "DECODE" program is executed,  the latest "decode_result.csv" file appears in the "datas" folder.

This software is licensed exclusively for academic research.
The use of this software for commercial purposes or non-profit applications is expressly prohibited.

