- 👋 Hi, I’m @namdeoviral
- 👀 I’m interested in 
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- import streamlit as st

def main():
    st.title("Gear Box - Co-Own Your Camera Dream")

    st.write("Welcome to Gear Box, India's revolutionary camera ownership platform!")
    st.write("Explore premium camera equipment, form co-ownership groups, and unleash your creativity.")

    st.sidebar.title("Menu")
    app_mode = st.sidebar.selectbox("Choose an option", ["Home", "Catalog", "Co-Ownership", "Community"])

    if app_mode == "Home":
        display_home_page()
    elif app_mode == "Catalog":
        display_catalog_page()
    elif app_mode == "Co-Ownership":
        display_co_ownership_page()
    elif app_mode == "Community":
        display_community_page()

def display_home_page():
    st.write("This is the home page. Discover what Gear Box has to offer!")

def display_catalog_page():
    st.write("Browse through our extensive catalog of premium camera equipment.")

def display_co_ownership_page():
    st.write("Form co-ownership groups and share the cost of your dream camera gear.")

def display_community_page():
    st.write("Join a vibrant community of passionate creatives. Collaborate, share knowledge, and inspire each other.")

if name == "__main__":
    main()

<!---
namdeoviral/namdeoviral is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
