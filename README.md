# Fetch-Take-Home-Assesment

Overview: 

The project investigates the data that has been provided by the hiring team to gain knowledge about customer behavior, brand trends, and data inconsistencies. The dataset consists of three files:

1. USER_TAKEHOME.csv - User data (ID, created date, birth date, state, language, gender).
2. TRANSACTION_TAKEHOME.csv - Transaction data (purchase date, scan date, store name, user ID, barcode, final quantity and final sale columns).
3. PRODUCTS_TAKEHOME.csv - Product categories, manufacturers, brands, and barcodes.
   
Key Findings: 

Data Quality Issues:

1. High missing values in gender (5.9%), barcode (11.5%), and language (30.5%) columns.
2. 92% missing values for CATEGORY_4 column in product data, making it mostly unusable.
3. Data entries for final quantity and gender columns are inconsistent and must be cleaned.
   
Brand & Purchase Trends:

1. Top 5 brands read by users age 21+: Nerds Candy, Dove, Unknown Brand, Trident, and Sour Patch Kids.
2. Top brand in the Dips & Salsa category: Tostitos.
3. Most popular brands among active users 6+ months: CVS, Trident, Dove, Coors Light, and Unknown Brand.
   
Challenges & Next Steps: 

1. Cleaning and handling missing values (e.g., BARCODE, CATEGORY_4).
2. Standardizing gender labels and numeric values in transactions.
3. Investigating trends in user demographics vs. brand preference.
