# AI-Based Interactive Story Creation Platform

This project is an AI-based interactive story creation platform that combines user photos and imagination to create personalized stories and visual representations.

## Key Features
1. **Photo Upload and Analysis**
   - Analyze user photos using AI models to generate textual descriptions.
   - Utilize these descriptions as prompts for story generation.

2. **Genre, Setting, Art Style, and Character Customization**
   - Genres: Choose from fairy tales, fantasy, sci-fi, mystery, and more.
   - Settings: Specify environments such as castles, forests, cities, or space.
   - Art Styles: Select styles like cartoon, watercolor, pixel art, and more.
   - Characters: Freely set names, traits, age, gender, and other details.

3. **Story Idea Input and Length Adjustment**
   - Input your own ideas or provide specific settings.
   - Choose between short stories and longer narratives.

4. **AI-Based Story and Image Generation**
   - Automatically generate tailored stories using ChatGPT (LLM).
   - Create story illustrations using tools like Stable Diffusion or DALL·E.
   - Refine results with regeneration features.

5. **Export and Share Results (In Progress)**
   - Export completed stories and images as PDF or Word files.
   - Share results via platforms like KakaoTalk or Twitter.

---

## Installation and Execution

### Prerequisites
- Requires Python 3.8 or later.
- An OpenAI API key is necessary for operation.

### Execution

#### Recommended: Use Google Colab
- The program is best executed on Google Colab for ease of use.
- To run on Colab:
  1. Open the project notebook file in Colab.
  2. Set up your API key.
  3. Execute the cells sequentially.

#### Running Locally (VSCode or Jupyter Notebook)
- To run locally, install required packages using the `requirements.txt` file:
  ```bash
  pip install -r requirements.txt
  ```
- Then, run the project in Jupyter Notebook or VSCode.

1. Open the project file in Jupyter Notebook.
2. Set your API key. Example:

```python
openai_api_key = "Enter your OpenAI API key here"
```

3. Execute the cells sequentially to launch the interface.

---

## Usage

### Step 1: Choose Genre
- Select your preferred genre from the provided list.

### Step 2: Choose Settings
- Specify the background settings for the story.

### Step 3: Select Art Style
- Choose the visual style for generated images.

### Step 4: Customize Characters
- Input or randomly generate the protagonist’s name, gender, age, and traits.

### Step 5: Input Story Idea
- Provide a story idea or skip this step.

### Step 6: Choose Story Length
- Select between short and standard story lengths.

### Step 7: Generate Story and Images
- Upload a photo to let the AI create a story and corresponding images.
- Regenerate results as needed for better outcomes.

### Step 8: Export and Share
- Export the generated story and images as PDF or Word files, or share via platforms like KakaoTalk or Twitter.

---

## Contributing
If you would like to contribute to this project, please submit bug reports and feedback via the Issues tab or send a Pull Request (PR).

---

## License
This project is distributed under the [MIT License](LICENSE).