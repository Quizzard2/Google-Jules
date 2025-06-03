# Create a Minds - AI Translation Tool

This project is a web-based AI-powered translation tool developed by Create a Minds. It allows users to translate text between over 100 languages instantly.

## Features

*   **Instant Text Translation:** Quickly translate text by typing or pasting it into the input area.
*   **Multi-Language Support:** Supports translation between 100+ languages.
*   **Language Auto-Detection:** Can automatically detect the source language.
*   **Swap Languages:** Easily swap the source and target languages with a single click.
*   **User-Friendly Interface:** Sleek, modern, and mobile-friendly design for ease of use.
*   **Free to Use:** The tool is free for personal, educational, and professional use.

## Technologies Used

*   **HTML:** Structures the web page.
*   **CSS:** Styles the appearance of the tool, ensuring a responsive and modern look.
*   **JavaScript:** Powers the interactive elements, including:
    *   Populating language selection dropdowns.
    *   Handling user input and API calls for translation.
    *   Implementing the language swap functionality.
    *   Updating the copyright year dynamically.
*   **Google Translate API (via `translate.googleapis.com`):** Used for performing the actual text translations.

## File Structure

*   `translation.html`: The main HTML file containing the structure, styling, and client-side logic for the translation tool.
*   `README.md`: This file, providing an overview of the project.

## Getting Started

To use the tool, simply open the `translation.html` file in a web browser.
No special installation or backend setup is required as it's a client-side application that utilizes a public translation API.

## How to Use

1.  Open `translation.html` in your browser.
2.  Enter the text you want to translate in the left text area ("Enter text to translate...").
3.  If needed, select the source language from the dropdown. "Detect Language" is selected by default.
4.  Select your desired target language from the right dropdown.
5.  The translated text will appear in the right text area ("Translation will appear here...") automatically.
6.  Click the "↔" button to swap the source and target languages and texts.

## Content Section

The page includes an "About This Tool" section, which is an editable textarea. This section currently describes the tool's capabilities:
"Our AI-powered translation tool, part of the Prompt Minds suite, supports over 100 languages with high accuracy. Features include:
- Instant text translation
- Language auto-detection
- Sleek, modern, mobile-friendly interface
- Free to use for all your translation needs

Simply enter your text, select your desired languages, and get instant, reliable translations. Perfect for personal, educational, and professional use!"

## Customization

*   **Languages:** The list of languages in the dropdowns can be extended or modified by editing the `languages` array in the JavaScript section of `translation.html`.
*   **Styling:** The appearance can be customized by modifying the CSS rules within the `<style>` tags in `translation.html`.
*   **About Content:** The content in the "About This Tool" section can be directly edited in the `textarea` with the class `editable-content` within `translation.html`.

## Contributing

Contributions to improve this tool are welcome. You can contribute by:
*   Reporting bugs or issues.
*   Suggesting new features or enhancements.
*   Improving the existing code or styling.

(Standard contribution guidelines like forking the repository, creating a new branch, making changes, and submitting a pull request would apply if this were a version-controlled project.)

## License

This project does not currently have a specified license. Please assume all rights are reserved by Create a Minds. If you wish to use or distribute this code, please contact Create a Minds for permission.
---

*This README was generated based on an analysis of the `translation.html` file.*
