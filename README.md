# MLP-regressor
Experimenting with different architectures of MLP to predict students score  

#### best model architecture:  
MLP_tanh_scaled(
  (layers): Sequential(  
    (0): Linear(in_features=41, out_features=64, bias=True)  
    (1): ScaledTanh()  
    (2): Dropout(p=0.1, inplace=False)  
    (3): Linear(in_features=64, out_features=128, bias=True)  
    (4): ScaledTanh()  
    (5): Dropout(p=0.1, inplace=False)  
    (6): Linear(in_features=128, out_features=256, bias=True)  
    (7): ScaledTanh()  
    (8): Dropout(p=0.1, inplace=False)  
    (9): Linear(in_features=256, out_features=1, bias=True)  
  )  
)  
#### reached final result:   
Mean Squared Error: 0.013751178  
Mean Absolute Error: 0.07862977  
R2 Score: 0.7525845078135946  



