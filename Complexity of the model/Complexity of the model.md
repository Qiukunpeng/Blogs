<!--
 * @Author: your name
 * @Date: 2021-01-21 20:33:33
 * @LastEditTime: 2021-01-21 20:52:10
 * @LastEditors: Please set LastEditors
 * @Description: This blog is about the complexity of the model.
 * @FilePath: \L1 & L2\Complexity of the model.md
-->
# Complexity
## What is Complexity?
1. **Complexity** can be divided into **Time Complexity** and **Space Complexity**.
- In the paper, the authors use **FLOPS** to indicate **Time Complexity**, which is the number of calculations.
- The same, the author use **Bytes** to indicate **Space Complexity**, which is the number of parameters in the model.
- They are all computed by the most terrible situation.
- These metrics are generally used to evaluate the performance of the model
- The **Punishment** in **Loss Function** only restricts **Space Complexity**.