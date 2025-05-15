# Portfolio Web Application

A modern, responsive portfolio website built with Flask, showcasing your skills, projects, and professional experience.

## Features

- Responsive design that works on all devices
- Modern UI with smooth animations
- Multiple sections (Home, About, Projects, Contact)
- Easy to customize and extend

## Setup Instructions

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
portfolio/
├── app.py              # Main Flask application
├── requirements.txt    # Project dependencies
├── static/            # Static files
│   ├── css/          # CSS stylesheets
│   ├── js/           # JavaScript files
│   └── images/       # Image assets
└── templates/         # HTML templates
    ├── base.html     # Base template
    └── index.html    # Home page
```

## Customization

- Edit the templates in the `templates/` directory to modify the content
- Update the styles in `static/css/style.css` to change the appearance
- Add your own images to `static/images/`
- Modify the routes in `app.py` to add new pages or functionality.

## License

This project is open source and available under the MIT License. # MyPortfolio
