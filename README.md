## ⚡ Mini-Batch Gradient Descent

![Mini-Batch Path](Image1.png)

Mini-Batch Gradient Descent is a **hybrid between Batch and Stochastic Gradient Descent**.  

Instead of using the entire dataset like Batch GD, or just one sample like SGD, it updates the model using **a small batch of samples at a time**.  

This combines the **stability of Batch GD** with the **speed of SGD**, making it very popular in real-world machine learning.

---

## 🧠 In Simple Words  
Think of the loss function like a **bowl** again.  

- Mini-Batch GD looks at **a handful of points** on the bowl at each step.  
- This makes the path **smoother than SGD**, but **faster than Batch GD**.  
- It reduces the zig-zag noise of SGD while still allowing the model to move quickly.  
- Mini-Batches also make it easier to **parallelize computations** on GPUs, which is why it is widely used in deep learning.

---

## ✅ Key Points
- Updates parameters **per small batch** of samples  
- Combines speed of SGD with stability of Batch GD  
- Less noisy than SGD but faster than full-batch updates  
- Works well for **large datasets** and is GPU-friendly
