# Customer-Segmentation-Business-Insights-Online-Retail
Customer segmentation project using clustering to identify distinct purchasing behaviour groups based on spending patterns, engagement metrics, and transaction characteristics for targeted business strategy development. 

## Basic Information of the Clusters

This section provides foundational information about the clusters, including their distribution, gender composition, and validation metrics. These observations serve as a precursor to the detailed cluster profiles described in the following section.

---

### Cluster Distribution

The dataset contains a total of **22,049 customers**, segmented into four distinct clusters based on behavioural and transactional characteristics.

- **Cluster 2:** 35.6% of total customers (largest segment)
- **Cluster 1:** 31.7% of total customers
- **Cluster 3:** 26.9% of total customers
- **Cluster 0:** 5.8% of total customers (smallest segment)

This distribution indicates that Clusters 1 and 2 together represent the majority of the customer base, while Cluster 0 represents a relatively niche group.

---

### Gender Distribution Across Clusters

The gender composition across all clusters is balanced, with nearly equal representation of male and female customers and a small proportion classified as "Other."

- **Cluster 0**
  - Female: 50.0%
  - Male: 48.1%
  - Other: 1.9%

- **Cluster 1**
  - Female: 51.5%
  - Male: 46.9%
  - Other: 1.6%

- **Cluster 2**
  - Female: 50.0%
  - Male: 48.5%
  - Other: 1.6%

- **Cluster 3**
  - Female: 49.7%
  - Male: 49.1%
  - Other: 1.2%

This balanced distribution suggests that gender is not a primary factor driving the clustering structure.

---

### Cluster Validation Using Decision Trees

Sensitivity and specificity were calculated using Decision Tree classification to evaluate the separability and reliability of the clusters. The results show strong performance across all clusters. Cluster 0 has a sensitivity of 0.84 and perfect specificity of 1.00, indicating it is clearly distinguishable from other clusters. Cluster 1 shows the highest sensitivity of 0.95 and specificity of 0.92, meaning it is highly identifiable with minimal misclassification. Cluster 2 has a sensitivity of 0.87 and very high specificity of 0.99, confirming strong separation. Cluster 3 also demonstrates robust performance, with a sensitivity of 0.91 and specificity of 0.96. Overall, the high sensitivity and specificity values indicate that the clusters are well-separated, internally consistent, and reliable. These metrics were obtained using Decision Trees as a post-clustering validation method to assess clustering accuracy.

# FINAL CLUSTER PROFILES AND BUSINESS RECOMMENDATIONS

## Cluster 0: High-Value Premium Buyers
These customers represent the most valuable segment, contributing the highest revenue per customer. They tend to purchase expensive products and buy in relatively higher quantities, indicating strong purchasing power and preference for premium offerings.

### Key Behaviour Insights:
- Extremely high average spend (₹8018), the highest among all clusters
- Very high unit price purchases (₹2636), indicating preference for premium products
- Higher purchase quantity (3.48 units on average)
- Moderate session duration (14.4 minutes), suggesting efficient decision-making
- Above-average pages viewed, showing focused but confident browsing

### Business Suggestions:
- Introduce loyalty programs and VIP memberships
- Offer exclusive premium deals and early product access
- Provide personalized recommendations and concierge-style services
- Focus on premium and high-margin product categories


## Cluster 1: Low-Spend Casual Browsers
This segment consists of customers who spend the least and purchase fewer items. They browse products but show lower conversion into high-value purchases, suggesting price sensitivity or exploratory behaviour.

### Key Behaviour Insights:
- Lowest average spend (₹519)
- Lowest quantity purchased (1.74 units)
- Low unit price purchases (₹333), indicating budget preferences
- Shorter session duration (13.1 minutes)
- Moderate browsing activity without strong purchase commitment

### Business Suggestions:
- Provide targeted discounts and entry-level offers
- Use conversion nudges like limited-time deals
- Offer affordable product bundles
- Use retargeting advertisements to increase conversions


## Cluster 2: Bulk Value Seekers
These customers purchase the highest quantities and are motivated by value and affordability. They respond well to discounts and tend to maximize quantity rather than spending on premium products.

### Key Behaviour Insights:
- Highest quantity purchased (4.34 units), highest among all clusters
- Moderate overall spend (₹1189)
- Low unit price purchases (₹291), indicating price sensitivity
- Moderate discount utilization (₹46)
- Average browsing and session duration

### Business Suggestions:
- Provide volume discounts and bundle pricing
- Offer wholesale-style pricing incentives
- Promote combo offers and bulk purchase deals
- Encourage cross-selling to increase overall order value


## Cluster 3: Older Selective Buyers
This segment consists of older customers who spend moderately and take more time during sessions, indicating careful and selective purchasing behaviour.

### Key Behaviour Insights:
- Oldest average age group (45.5 years)
- Moderate spending level (₹581)
- Moderate unit price purchases (₹324)
- Longest session duration (16.6 minutes), indicating careful evaluation
- Moderate quantity purchased (1.99 units)

### Business Suggestions:
- Focus on trust-building and product quality messaging
- Provide personalized recommendations
- Offer loyalty rewards and retention programs
- Promote reliable, practical, and high-quality products
