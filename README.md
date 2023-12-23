### Note-Taking Assistant - Project Overview

<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <!-- Placeholder for a simple notebook icon -->
  <rect width="150" height="150" fill="#f2f2f2" />
  <path d="M15 20h120v100h-120z" fill="#ffffff" />
  <rect x="15" y="20" width="120" height="100" stroke="#000000" stroke-width="2" fill="none" />
  <rect x="20" y="30" width="110" height="80" fill="#ffffff" />
  <line x1="20" y1="50" x2="130" y2="50" stroke="#000000" stroke-width="2" />
  <line x1="20" y1="70" x2="130" y2="70" stroke="#000000" stroke-width="2" />
  <line x1="20" y1="90" x2="130" y2="90" stroke="#000000" stroke-width="2" />
</svg>

**Developed and Maintained by AI & Robotics Society, MTA**

#### Objective
The Note-Taking Assistant project aims to simplify the note-taking process for both professors and students through two integrated modules:
#### Vision
To revolutionize the note-taking process for educators and students, creating a seamless and efficient experience.
#### Module 1: Image and Text Processing (Codename: LensNotes)
- **Functionality:**
    - Takes images as input and converts them to Markdown and potentially LaTeX.
    - Utilizes OpenAPI to summarize the entire document or page, with a preference for the entire page.
- **Workflow:**
    - Periodic image capture facilitates image-to-text conversion.
    - Generates a comprehensive summary of processed notes towards the end of the lecture.

#### Module 2: Voice-to-Text Analysis (Codename: EchoLex)
- **Functionality:**
    - Converts spoken words to text.
    - Identifies frequently mentioned words and promotes them in a hierarchy.
    - Provides definitions for these words from reliable sources (e.g., Wikipedia via API).
- **Workflow:**
    - Analyzes the professor's voice, creating a hierarchy of frequently spoken words.
    - Provides definitions, serving as a supplement to Module 1 for highlighting crucial information.

#### Language of Implementation
**Python** will be the primary language used for all Modules in the project.
#### How to Contribute
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit: `git commit -m "Description of your changes."`.
4. Push to your branch: `git push origin feature-name`.
5. Open a pull request and describe your changes.

If your contribution is accepted, you will be added to the contribution list.
#### **Contributors / Credits**

The AI & Robotics Society would like to acknowledge and express gratitude to the following contributors for their valuable contributions to this project:

- Faycal Kilali

## License
This project is licensed under the [GNU General Public License (GPL)](https://github.com/faycalki/note-taking-assistant/blob/main/LICENSE). See the [LICENSE](https://github.com/faycalki/note-taking-assistant/blob/main/LICENSE) file for details.

## [](https://github.com/faycalki/note-taking-assistant#disclaimer)Disclaimer
This project is provided "as is" without warranty of any kind, express or implied. Use this software at your own risk. The authors and contributors of this project are not responsible for any damages or liabilities associated with the use, modification, or distribution of this software.
