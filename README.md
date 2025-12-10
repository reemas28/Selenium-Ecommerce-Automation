# Flipkart Automation Bot 🛒

## 📌 Project Overview
This is a Python-based automation tool built with **Selenium WebDriver**. It mimics a real user's journey on Flipkart.com, handling complex workflows including product search, tab switching, and applying "Exchange Offers" for mobile devices.

## 🛠 Skills Demonstrated
* **Advanced Selenium:** Handling multiple windows/tabs (`window_handles`).
* **JavaScript Injection:** Using `execute_script` to interact with difficult UI elements.
* **Explicit Waits:** Implementing `WebDriverWait` to ensure script stability against dynamic page loads.
* **DOM Manipulation:** Locating elements via XPATH and ID.

## ⚙️ Workflow Automations
| Step | Action | Logic Used |
| :--- | :--- | :--- |
| 1 | **Search** | Locates search bar, inputs "Pixel 10 Pro", and submits. |
| 2 | **Product Selection** | Identifies specific model and handles the "New Tab" opening. |
| 3 | **Pincode Check** | Automates availability check for specific region codes. |
| 4 | **Exchange Logic** | Selects "Buy with Exchange" and automates the old device selection (Motorola Edge 50). |
| 5 | **Add to Cart** | Finalizes the flow by adding the item to the cart. |

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/ReemasFury/Selenium-Ecommerce-Automation.git](https://github.com/ReemasFury/Selenium-Ecommerce-Automation.git)
    ```
2.  Install Selenium:
    ```bash
    pip install selenium
    ```
3.  Run the bot:
    ```bash
    python Flipkart_automation.py
    ```

## ⚠️ Note
This script is for **educational purposes**. It uses `chromedriver` (assumed to be in system PATH).
