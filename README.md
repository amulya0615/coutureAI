# CoutureAl: Clothing Image Generator Using Stable Diffusion Pipeline

CoutureAl is a cutting-edge application designed to empower users to visualize their unique clothing ideas through realistic image generation. By leveraging the Stable Diffusion pipeline, CoutureAl allows users to input detailed descriptions of their envisioned outfits and receive high-quality images that bring their fashion dreams to life.

## Model and Dataset Used
- Stable Diffusion: https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5
- Dataset: https://huggingface.co/datasets/Marqo/deepfashion-inshop

## Demo Video

## Working Screens
![Screenshot (756)](https://github.com/user-attachments/assets/4e9f1287-da4b-49ef-8063-68e78ff34e31)
![Screenshot (756)](https://github.com/user-attachments/assets/1217df03-a776-4b2e-9bab-18b2ec4e5867)
![Screenshot (755)](https://github.com/user-attachments/assets/a27cdbc8-1326-4542-ab9c-aecdf465266a)




## Features

- **User-Friendly Interface**: Built with Streamlit, the application provides an intuitive interface for users to enter clothing descriptions.
- **Image Generation**: Utilizes the Stable Diffusion model to generate realistic images based on user-defined clothing styles.
- **Customization**: Users can describe various aspects of clothing, including color, fabric, style, and additional features, to create personalized designs.
- **Product Recommendations**: Based on your prompts it'll fetch the products from the google shopping and recommends that products. 

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/amulya0615/coutureAI.git
   cd coutureal
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   streamlit run src/app.py
   ```

## Usage

1. Open the application in your web browser.
2. Enter a detailed description of the clothing item you wish to visualize.
3. Click on the "Generate" button to create an image of your custom design.
4. Review the generated image and make adjustments to your description as needed.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
