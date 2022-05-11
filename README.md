# Explain
Input validation for react.   
Use formik, yup, mui.   
Formik's sample. (https://formik.org/docs/examples/with-material-ui)   
But not working.

# Solved Example Problem
1. Modify import mui path.   
```
import Button from '@mui/material/Button';
import TextField from '@mui/material/TextField';
```

2. Add onBlur method. Because not working 'formik.touched'.
```
onBlur={formik.handleBlur}
```




