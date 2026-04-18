
# Tall Building Preliminary Sizing Streamlit App

This is a web version of the preliminary sizing tool for reinforced-concrete tall buildings.

## Features
- square and triangular conceptual plans
- central core walls
- distributed perimeter walls
- stronger corner columns
- directional column dimensions for rectangular plans
- graphical plan output
- stiffness-based period estimation from `T = 2π√(M/K)`

## Run locally
```bash
pip install streamlit matplotlib
streamlit run streamlit_app.py
```

## Deploy
You can deploy this on:
- Streamlit Community Cloud
- Hugging Face Spaces
- Render

## Important
This is a preliminary sizing tool only. It is not a final structural design program.
