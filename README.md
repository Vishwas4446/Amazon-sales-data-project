# Project Background

Amazon is an American Tech Multi-National Company whose business interests include E-commerce, where they buy and store the inventory, and take care of everything from shipping and pricing to customer service and returns.

The dataset was taken from Kaggle, it consists of data of over a 1,000 products listed on Amazon. This project thoroughly analyses and synthesizes this data to uncover some insights that will tell us about the various categories and the products sold under them on the website.

An interactive Tableau Dashboard can be accessed and downloaded [here]([https://example.com](https://public.tableau.com/views/Amazonsalesdata_17327845008120/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)).

---

## Data Structure & Initial Checks

**Source**: Kaggle.  
**Format**: CSV to Excel file.  
**Size**: 1389 rows × 12 columns.

### Attributes:

- `product_id`: Unique identifier for products.
- `product_name`: Name of the product.
- `category`: High-level product categorization (e.g., Car & Motorbike, Computers & Accessories).
- `sub_category`: Specific categorization within the category.
- `fixed_discounted_price`: Discounted price of the product.
- `Fixed_actual_price`: Original price of the product.
- `discount_percentage`: Calculated discount percentage.
- `rating`: Product rating (possibly on a 5-point scale).
- `rating_count`: Number of user ratings.
- `user_id`: IDs of users who reviewed the product.
- `user_name`: Names of users who reviewed the product.
- `review_id`: IDs of reviews.

---

### Sample Data Snapshot

| product_id   | product_name                        | category           | sub_category            | fixed_discounted_price | Fixed_actual_price | discount_percentage | rating | rating_count |
|--------------|-------------------------------------|--------------------|-------------------------|-------------------------|-------------------|--------------------|--------|--------------|
| B0912WJ87V   | Reffair AX30 Portable Air Purifier  | Car & Motorbike    | Car Accessories         | 2339.0                 | 4000.0            | 42%                | 3.8    | 1118         |
| B097C564GC   | RTS Mini USB C Adapter             | Computers & Accessories | Accessories & Peripherals | 294.0                  | 4999.0            | 94%                | 4.3    | 4426         |
| B094DQWV9B   | Kanget Type C Female to USB A Male Charger | Computers & Accessories | Accessories & Peripherals | 149.0                 | 399.0             | 63%                | 4.0    | 1540         |

---

## Executive Summary

The dataset provides insights into product categories, their popularity, customer satisfaction, and pricing trends in the marketplace. It analyzes data for both main categories and subcategories, including metrics such as the number of products, average ratings, and mean discount percentages.

---

## Key Insights

### 1. Product Popularity

#### a. Main Categories:
- The top three main categories are **Electronics**, **Computers & Accessories**, and **Home & Kitchen**, accounting for the majority of the products.
- Categories such as **Office Products**, **Musical Instruments**, **Health & Personal Care**, and others have a significantly lower number of products, indicating niche or low-demand markets.

#### b. Subcategories:
- USB Cables, Smartwatches, and Smartphones dominate the subcategory rankings, showcasing high customer demand.
- A diverse range of subcategories, such as kitchen appliances, home electronics, and personal accessories, reflects varying customer preferences and needs.

---

### 2. Customer Ratings

#### a. Top Categories by Rating:
- **Office Products**, **Toys & Games**, and **Home Improvement** have the highest average ratings, indicating strong customer satisfaction.
- Categories like **Car & Motorbike** and **Musical Instruments** scored below 4.0, suggesting room for improvement.

#### b. Customer Trends:
- Popular categories like **Computers & Accessories** and **Electronics** also maintain high ratings, reflecting their reliability and customer satisfaction.

---

### 3. Pricing Trends

#### a. Main Categories:
- Categories with high discounts include **Home Improvement** (57.5%), **Computers & Accessories** (53.9%), and **Electronics** (50.8%), highlighting their price-sensitive nature.
- **Toys & Games** (0% discount) stands out as a high-demand category where discounts are unnecessary for sales.

#### b. Subcategories:
- Subcategories like **Adapters** (80.3%), **Basic Cases** (70.7%), and **Bluetooth Speakers** (48.5%) have high discount percentages, suggesting intense competition.
- Conversely, **Basic and Battery Chargers** have minimal discounts, indicating stable demand.

---

### 4. Market Opportunities

#### Emerging Focus Areas:
- Categories like **Home Improvement**, despite high ratings and discounts, present opportunities for growth and innovation.
- The low number of products in categories like **Health & Personal Care** and **Musical Instruments** indicates untapped potential for market expansion.

#### Diversification Potential:
- Retailers could expand offerings in trending subcategories such as **Smart Televisions**, **Mixer Grinders**, and **Water Heaters** to cater to growing customer needs.

---

## Recommendations

1. **Enhance Product Offerings**:
   - Focus on expanding inventory in high-demand categories like **Electronics** and **Home & Kitchen**, while exploring growth opportunities in niche areas such as **Health & Personal Care**.

2. **Optimize Pricing Strategies**:
   - Utilize dynamic pricing and targeted discounts for price-sensitive categories like **Adapters** and **Bluetooth Speakers** while maintaining premium pricing for high-demand subcategories with minimal discount needs.

3. **Improve Customer Satisfaction**:
   - Address lower-rated categories like **Car & Motorbike** by improving product quality and customer service to build trust and loyalty.

4. **Leverage Marketing Insights**:
   - Highlight the high ratings of categories like **Office Products** and **Toys & Games** in promotional campaigns to reinforce customer trust.
