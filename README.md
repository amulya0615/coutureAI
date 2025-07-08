# CoutureAl: Clothing Image Generator Using Stable Diffusion Pipeline
CoutureAI is a fashion-tech application designed to transform personalized clothing descriptions into realistic visual designs using state-of-the-art generative AI. Powered by the Stable Diffusion pipeline, CoutureAI empowers users to experiment with their creativity in fashion by generating high-quality outfit images from natural language inputs.

## Model and Dataset Used
- Stable Diffusion: https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5
- Dataset: https://huggingface.co/datasets/Marqo/deepfashion-inshop

## Demo Video

## Working Screens

![Uploading Screenshot (754).png…]()
![Uploading Screenshot (755).png…]()
![Uploading Screenshot (756).png…]()






## Features

- **User-Friendly Interface**: Built using Streamlit, the application offers an intuitive platform for users to enter detailed clothing descriptions.
- **Natural Language to Fashion Design**: Allows users to generate custom clothing visuals simply by describing them in everyday language.
- **Image Generation**: Utilizes the Stable Diffusion v1.5 model for high-quality, photorealistic image outputs based on user-defined styles.
- **Customization**: Users can specify attributes such as color, fabric, cut, accessories, and other design elements for personalized outputs.
- **Dataset Integration**: Based on the [DeepFashion In-Shop dataset](https://huggingface.co/datasets/Marqo/deepfashion-inshop), ensuring model output reflects current fashion trends.
- **Product Recommendations**: After image generation, the application fetches and recommends real-world products using Google Shopping based on the user’s prompt.


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

1. Launch the app in your browser.
2. Enter a detailed clothing description (e.g., "a denim jacket with floral embroidery and silver buttons").
3. Click "Generate" to see your design.
4. Review the image and view product suggestions.
5. Modify and iterate as needed.

## 🧑‍💻 Contributors

- Amulya 
- Duguru Meghana

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
