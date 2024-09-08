# Linear_Regression

<div>
  <p>
    > mouse.data <- data.frame(weight=c(0.9,1.8,2.4,3.5,3.9,4.4,5.1,5.6,6.3),size=c(1.4,2.6,1.0,3.7,5.5,3.2,3.0,4.9,6.3))
      <br>
    > mouse.data
      <br>
    </p>
      </div>
<div> 
<img width="110" alt="Screenshot 2024-09-08 at 3 33 55 PM" src="https://github.com/user-attachments/assets/15dd1ed8-3651-4b01-8452-71f7ed7e284b">
</div>
      <p>
    > plot(mouse.data$weight,mouse.data$size)
      <br>
      </p>
<div> 

<img width="759" alt="Screenshot 2024-09-08 at 3 34 16 PM" src="https://github.com/user-attachments/assets/b1a6cd89-e17f-4962-a4a6-0eadb0bef66c">
</div>

<div> 
<p>
    > mouse.regression <- lm(size ~weight, data=mouse.data)
      <br>
    > summary(mouse.regression)
      <br>
    </p>
     <img width="471" alt="Screenshot 2024-09-08 at 3 34 33 PM" src="https://github.com/user-attachments/assets/1ca736e0-653f-4f41-a24e-a0455d176287">
</div> 
      <p>
    > abline(mouse.regression,col='red')
  </p>

<div> 
<img width="764" alt="Screenshot 2024-09-08 at 3 34 46 PM" src="https://github.com/user-attachments/assets/d9d9f6f9-0159-449c-8d1f-955253c10102">
</div>

