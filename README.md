# shopify-graphql-product-fetcher

It script that takes input product names and fetches the appropriate products that match the name and list down the variants sorting by price.

## Setup Instructions

1. **Copy Environment Variables:**

   - Duplicate `.env.example` and rename it to `.env`.
   - Replace values with your orignal Shopify store URL, admin token, and API version.

   Example `.env` file:

   ```dotenv
   # Replace values with your orignal Shopify store URL, admin token, and API version

		STORE_URL=https://your-shopify-store-url.myshopify.com
		ADMIN_TOKEN=your_shopify_admin_token_here
		API_VERSION=yyyy-mm


   ```

2. **Install Dependencies:**

   ```bash
   npm install

   ```

3. **Run the Script:**
   To fetch products from shopify based on a specific product name, use the following command:

   ```bash
   # Replace <product_name> with the name of the product you want to search for.
   node app.js --name <product_name>
   ```
# shopify-GQL
