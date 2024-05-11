# PRIORITY_ENCODER
![image](https://github.com/RESMIRNAIR/PRIORITY_ENCODER/assets/154305926/016b3b20-1d4d-48fd-9012-a2c725b822db)
# Truth Table
![image](https://github.com/RESMIRNAIR/PRIORITY_ENCODER/assets/154305926/3da43bab-6ee6-456f-858f-4553d3623f8c)
# PROGRAM
```
module encoder(d,a,b,c);
input [7:0]d;
output a,b,c;
or(a,d[4],d[5],d[6],d[7]);
or(b,d[2],d[3],d[6],d[7]);
or(c,d[1],d[3],d[5],d[7]);
endmodule
```
# OUTPUT
![image](https://github.com/Vijayananthperumal22/PRIORITY_ENCODER/assets/107705127/55f2f725-1d70-4de9-8506-5fac605aa56f)
