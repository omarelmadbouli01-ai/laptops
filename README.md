Egyptian Laptop Market Dataset
This dataset contains a collection of laptops available for purchase from various online retailers in Egypt, compiled in August 2025. It includes detailed hardware specifications, pricing in Egyptian Pounds (EGP), seller information, and direct links to the product pages.

This data was compiled to provide a snapshot of the laptop market in Egypt, allowing for analysis of pricing, brand popularity, and feature distribution.

📂 File Description
Laptops.csv: A comma-separated values file containing the core dataset.

📖 Data Dictionary
The dataset contains the following columns:

Column                Type          Description                                                                                      Example
brand                 String        The manufacturer of the laptop.                                                                  HP
model                 String        The specific model name or number of the laptop.                                                 Omen 16-AE0075CL
price_egp             String        The price of the laptop in Egyptian Pounds (EGP). Formatted with commas.                         "79,999"
cpu                   String        The model of the central processing unit (CPU).                                                  Intel Core i7 14700HX
cpu_cores             Integer       The total number of cores in the CPU.                                                            20
cpu_max_speed         Float         The maximum boost clock speed of the CPU in Gigahertz (GHz).                                     5.5
cpu_score             String        A performance benchmark score for the CPU (likely from a source like PassMark).                  "37,275"
gpu                   String        The model of the graphics processing unit (GPU).                                                 NVIDIA GeForce RTX 4070
vram                  Integer       The amount of dedicated video RAM for the GPU in Gigabytes (GB).                                 8
ram                   Integer       The amount of system memory (RAM) in Gigabytes (GB).                                             16
hard_capacity         String        The storage capacity of the primary hard drive (SSD or HDD).                                     1TB
display_size          Float         The diagonal size of the screen in inches.                                                       16.1
refresh_rates         String        The maximum refresh rate of the display in Hertz (Hz).                                           144Hz
resolution            String        The screen resolution in pixels (Width x Height).                                                1920x1080
warranty              Boolean       Indicates if a warranty is included (1 for Yes, 0 for No).                                       1
warranty_duration     Integer       The duration of the warranty in years.                                                           1
windows_11            Boolean       Indicates if Windows 11 is pre-installed (1 for Yes, 0 for No).                                  1
seller                String        The name of the online retailer selling the laptop.                                              EGYPTLAPTOP
link_to_product       String        A direct URL to the product's sales page.                                                        https://egyptlaptop.com/...


💡 Potential Use Cases
Market Analysis: Analyze the distribution of laptop brands, specs, and prices in the Egyptian market.

Price Comparison: Build a tool to compare laptop prices across different sellers.

Data Visualization: Create charts to visualize the relationship between price and specifications (e.g., Price vs. CPU Score, RAM vs. Price).

Predictive Modeling: Train a machine learning model to predict laptop prices based on their hardware specifications.

⚠️ Disclaimer
The data, especially pricing and availability, reflects the state at the time of collection. Prices and product links may have changed since then.

📄 License
Consider adding an open-source license to your repository to let others know how they can use your data. The Creative Commons Zero v1.0 Universal (CC0 1.0) is a good choice for public datasets.
