Project Overview : 
- This is a lightweight, interactive Node.js Command Line Utility (CLI) designed for the quick and easy generation of QR code images.
- Instead of relying on third-party web services, this utility runs directly in your terminal, providing a fast and secure way to convert any URL into a scannable image file. The project performs two key functions upon receiving user input: it generates a high-quality QR code image and simultaneously logs the original URL for history and reference.

Key Features : 
- Interactive Input: Uses the inquirer package to cleanly prompt the user for the target URL.
- Image Output: Converts the input URL into a scannable PNG image file named qr_image.png.
- Persistent Logging: Automatically saves the original URL string to a text file named url.txt.
- Technology Stack: Built efficiently using Node.js, inquirer, and qr-image.

Getting Started : 

- Prerequisites : 
  You must have **Node.js** installed on your system to run this application.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL Here]
    cd url-to-qr-image-generator
    ```

2.  **Install Dependencies:**
    Install the necessary Node.js packages (`inquirer` and `qr-image`).
    Before running the code, you must install the required Node.js packages (`inquirer` and `qr-image`) specified in the `package.json` file. This creates the     necessary **`node_modules`** folder.
    ```bash
    npm install inquirer qr-image
    ```

### 💻 How to Run
Execute the main script from your terminal using the Node runtime:
```bash
node index.js
```

Example Output:
After a successful run, your project folder will contain two new files:
- qr_image.png: The generated QR code.
- url.txt: A record of the link you entered.

Technologies Used
- Node.js
- inquirer: For the interactive command line prompt.
- qr-image: For generating the QR code image data.
- fs (File System): For saving the output files to disk.
