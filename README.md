Error message:
```
& : File E:\self_learning\Pytorch\pytorch_app\my_flask_app\Scripts\Activate.ps1 cannot be loaded        
because running scripts is disabled on this system. For more information, see about_Execution_Policies  
at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:3
+ & e:/self_learning/Pytorch/pytorch_app/my_flask_app/Scripts/Activate. ...
+   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
    
```
To activate virtual environment in VS code: 

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass 
```

Jupyter Notebook keep connecting to kernel in VS code? 
Deactive your virtual environment and run following commands:

```
python -m pip install 'traitlets==4.3.3' --force-reinstall
```
