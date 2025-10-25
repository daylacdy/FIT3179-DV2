以下是您提供的中文文本的英文翻译：

# Malaysia Inbound Tourism Data Visualization

Interactive visualization dashboard for Malaysia's 2024 inbound tourism data.

## Runtime Requirements

  - Python 3.x (No additional Python libraries required)

## Dependency Notes

This project uses Python's built-in `http.server` module, so no dependency packages need to be installed via `pip`. All visualization libraries (Vega, Vega-Lite, Vega-Embed) are automatically loaded in the browser via CDN.

An empty `requirements.txt` file is included for reference.

## Running Steps

1.  Navigate to the project directory:

<!-- end list -->

```bash
cd malaysia-tourism-visualization
```

2.  Start the HTTP server:

<!-- end list -->

```bash
python3 -m http.server 8000
```

3.  Open your browser and visit:

<!-- end list -->

```
http://localhost:8000/index.html
```

## Project Structure

```
malaysia-tourism-visualization/
├── index.html
├── style.css
├── data/
└── README.md
```
