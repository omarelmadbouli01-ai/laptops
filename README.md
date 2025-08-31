Egyptian Laptop Market Dataset
This dataset contains a collection of laptops available for purchase from various online retailers in Egypt, compiled in August 2025. It includes detailed hardware specifications, pricing in Egyptian Pounds (EGP), seller information, and direct links to the product pages.

This data was compiled to provide a snapshot of the laptop market in Egypt, allowing for analysis of pricing, brand popularity, and feature distribution.

📂 File Description
Laptops.csv: A comma-separated values file containing the core dataset.

📖 Data Dictionary
The dataset contains the following columns:

| Column Name            | Type    | Description                                                          | Example                       |
| ---------------------- | ------- | -------------------------------------------------------------------- | ----------------------------- |
| **brand**              | String  | The manufacturer of the laptop.                                      | `HP`                          |
| **model**              | String  | The specific model name or number of the laptop.                     | `Omen 16-AE0075CL`            |
| **price\_egp**         | String  | Price of the laptop in Egyptian Pounds (EGP), formatted with commas. | `79,999`                      |
| **cpu**                | String  | Model of the central processing unit (CPU).                          | `Intel Core i7 14700HX`       |
| **cpu\_cores**         | Integer | Total number of cores in the CPU.                                    | `20`                          |
| **cpu\_max\_speed**    | Float   | Maximum boost clock speed of the CPU in Gigahertz (GHz).             | `5.5`                         |
| **cpu\_score**         | String  | Performance benchmark score for the CPU (e.g., PassMark).            | `37,275`                      |
| **gpu**                | String  | Model of the graphics processing unit (GPU).                         | `NVIDIA GeForce RTX 4070`     |
| **vram**               | Integer | Amount of dedicated video RAM for the GPU in Gigabytes (GB).         | `8`                           |
| **ram**                | Integer | Amount of system memory (RAM) in Gigabytes (GB).                     | `16`                          |
| **hard\_capacity**     | String  | Storage capacity of the primary drive (SSD or HDD).                  | `1TB`                         |
| **display\_size**      | Float   | Screen size in inches (diagonal).                                    | `16.1`                        |
| **refresh\_rates**     | String  | Maximum display refresh rate in Hertz (Hz).                          | `144Hz`                       |
| **resolution**         | String  | Screen resolution (Width × Height).                                  | `1920x1080`                   |
| **warranty**           | Boolean | Warranty availability (`1` = Yes, `0` = No).                         | `1`                           |
| **warranty\_duration** | Integer | Warranty duration in years.                                          | `1`                           |
| **windows\_11**        | Boolean | Indicates if Windows 11 is pre-installed (`1` = Yes, `0` = No).      | `1`                           |
| **seller**             | String  | Online retailer selling the laptop.                                  | `EGYPTLAPTOP`                 |
| **link\_to\_product**  | String  | Direct URL to the product’s sales page.                              | `https://egyptlaptop.com/...` |

💡 Potential Use Cases
Market Analysis: Analyze the distribution of laptop brands, specs, and prices in the Egyptian market.

Price Comparison: Build a tool to compare laptop prices across different sellers.

Data Visualization: Create charts to visualize the relationship between price and specifications (e.g., Price vs. CPU Score, RAM vs. Price).

Predictive Modeling: Train a machine learning model to predict laptop prices based on their hardware specifications.

⚠️ Disclaimer
The data, especially pricing and availability, reflects the state at the time of collection. Prices and product links may have changed since then.

📄 License
Consider adding an open-source license to your repository to let others know how they can use your data. The Creative Commons Zero v1.0 Universal (CC0 1.0) is a good choice for public datasets.
