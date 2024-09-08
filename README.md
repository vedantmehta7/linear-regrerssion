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
<img width="114" alt="Screenshot 2024-09-08 at 3 55 19 PM" src="https://github.com/user-attachments/assets/0571e40c-8dfa-4ffd-a9f2-4b1d7182f650">
</div>
      <p>
    > plot(mouse.data$weight,mouse.data$size)
      <br>
      </p>
<div> 
<img width="757" alt="Screenshot 2024-09-08 at 3 55 50 PM" src="https://github.com/user-attachments/assets/ebce499a-93b4-487c-9ed1-b3402ab2cdf3">
</div>

<div> 
<p>
    > mouse.regression <- lm(size ~weight, data=mouse.data)
      <br>
    > summary(mouse.regression)
      <br>
    </p>
      <div>
        <img width="469" alt="Screenshot 2024-09-08 at 3 56 22 PM" src="https://github.com/user-attachments/assets/8c129d2f-233d-49d7-9c88-e463e3211c83">
      </div> 
      <p>
    > abline(mouse.regression,col='red')
  </p>
<div> 
  <img width="758" alt="Screenshot 2024-09-08 at 3 56 40 PM" src="https://github.com/user-attachments/assets/ef699b69-f1dd-4e2c-99a4-2a3df78f8eab">
</div>

