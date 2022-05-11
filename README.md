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

# Reference
https://sig03.medium.com/formik-yup-mui-샘플-예제-동작-안-하는-부분-수정-43dafd55a919   
https://duckgugong.tistory.com/218



