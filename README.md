# st-button
`st.button` display a button widget. 

## Demo app
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/st-button/)

## Code
Contents of the `streamlit_app.py` file:
```python
import streamlit as st

if st.button('Say hello'):
     st.write('Why hello there')
else:
     st.write('Goodbye')
```

## References
Read about [`st.button`](https://docs.streamlit.io/library/api-reference/widgets/st.button) in the Streamlit API Documentation.
