# Generic Jeopardy Frontend

A dynamic, customizable Jeopardy game frontend built with vanilla HTML, CSS, and JavaScript.

## Features

- Interactive Jeopardy game board
- Customizable question categories and answers
- Responsive design for desktop and tablet
- Easy to extend with new question sets

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3 (optional, for local server)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/ramdesh/generic-jeopardy-frontend.git
cd generic-jeopardy-frontend
```

2. Customize your questions by editing `questions.json`

3. Open `index.html` in your browser or run a local server:
```bash
npm start
# or
python3 -m http.server 8000
```

Visit `http://localhost:8000` in your browser.

## Usage

### Customizing Questions

Edit `questions.json` to add your own categories and questions. The format is:

```json
{
  "Category Name": {
    "100": {
      "question": "Question text here?",
      "answer": "Answer text here"
    },
    "200": { ... },
    ...
  }
}
```

## Deployment

### GitHub Pages

This project is configured to deploy automatically to GitHub Pages.

1. Ensure your repository is public
2. Go to Settings → Pages
3. Set the source to `main` branch
4. Your site will be available at `https://your-username.github.io/generic-jeopardy-frontend`

### Local Deployment

For local hosting or deployment to other platforms:

1. Copy all files to your web server
2. Ensure `index.html`, `questions.json`, and this README are included
3. Serve the files over HTTP/HTTPS

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Feel free to fork this repository and submit pull requests with improvements!
