# Multi-Core Image Resizer with Performance Comparison

This repository provides a multi-core image resizing utility designed to efficiently process large batches of images. It includes performance comparison tools to evaluate different resizing strategies, making it ideal for benchmarking and optimizing image processing workflows.

## Features

- **Multi-Core Processing**: Utilizes multiple CPU cores to speed up image resizing operations.
- **Batch Image Resizing**: Resize many images in parallel for maximum throughput.
- **Performance Measurement**: Built-in tools for benchmarking and comparing different resizing algorithms or configurations.
- **Modular Design**: Separate modules for configuration, resizing utilities, and performance analysis.

## Directory Structure

- `config/` — Configuration files and settings for the resizing process.
- `main/` — Main application logic and entry point.
- `performance/` — Scripts and tools for measuring and comparing performance.
- `resize utils/` — Utility functions for image resizing operations.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yahya-Sabbagh/Multi-Core-Image-Resizer-with-Performance-Comparison.git
   cd Multi-Core-Image-Resizer-with-Performance-Comparison
   ```

2. **Install dependencies:**
   - Ensure you have Python 3.7+ and required packages (see `requirements.txt` if provided).
   - Install packages:
     ```bash
     pip install -r requirements.txt
     ```

## Usage

1. **Configure the resizing options:**
   - Edit files in the `config/` directory to set desired parameters (e.g., output size, number of cores).

2. **Run the main application:**
   ```bash
   python main/main.py
   ```

3. **Analyze performance:**
   - Use scripts in the `performance/` directory to benchmark and visualize speed or efficiency.

## Customization

- You can modify or extend the resizing algorithms in `resize utils/`.
- Adjust the number of cores and other batch parameters in the `config/` files.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve features, fix bugs, or add new resizing methods.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

SABBAGH Yahya
