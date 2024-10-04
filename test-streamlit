import streamlit as st

# Set the title of the app
st.title("Welcome to My First Streamlit App!")

# Add input fields for user name and age
name = st.text_input("Enter your name:")
age = st.number_input("Enter your age:", min_value=0, max_value=100)

# Button to submit the form
if st.button("Submit"):
    if name and age:
        st.success(f"Hello {name}! You are {age} years old.")
    else:
        st.error("Please enter both your name and age.")
