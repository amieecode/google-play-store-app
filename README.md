# Google Play Store Apps 

This project explores a Google Play Store dataset to uncover the key factors that influence app success. The analysis focuses on user behavior, app performance metrics, and category-level insights to guide a better app development strategy.

## Project Objective
The goal is to answer:

- What drives an app’s success on the Play Store?

- How can companies improve their app offerings?

- What insights reveal user preferences and behaviors?

## Data Cleaning and Preparation

Major preprocessing steps:

- Remove duplicates and handle missing values.

- Convert Installs, Reviews, Size, and Price to numeric types.

- Standardize category and genre labels.

- Convert Last Updated to datetime.

- Create features such as update frequency and log-transformed installs.

The cleaned dataset is ready for analysis.

## Key Findings
### Average rating

- Mean app rating: 4.19

### Categories

- 33 unique categories.

- Most common categories: Games, Tools, Education, Entertainment.

### App size

- The majority of apps are below 100 MB.

- Smaller apps generally have a higher likelihood of being installed.

### Free vs paid

- Free apps: > 8,000

- Paid apps: < 1,000

### Content rating

- Most apps: Everyone, followed by Teen and Everyone 10+.

### Top installed apps

- Subway Surfers, Hangouts, Google, WhatsApp Messenger, Google News

### Highly rated apps

- 6,947 apps have a rating ≥ 4.0

### Reviews

- Free apps receive significantly more reviews than paid apps.

### Size by category

- Largest average sizes: Games, Family, Sports, Travel & Local

### Update activity

- 6,099 apps were updated in 2018.

## Advanced Insights

- **Installs vs Rating:** weak positive correlation — popularity ≠ guarantees a high rating.

- **Highest-rated categories:** Events, Education, Art & Design, Books & Reference, Personalization.

- **Price vs Rating:** best ratings for low-priced or free apps; ratings fall for mid-priced apps.

- **Genres with many 1M+ installs:** Tools, Action, Photography, Communication, Productivity.

- **Update frequency:** average gap between updates ≈ 6 months.

- **Most reviewed apps:** Facebook, WhatsApp Messenger, Instagram.

- **Sentiment patterns:** high-rated genres include Education and Tools; low-rated include Finance and some Tools/Business apps (often due to UX or ads).

- **Genre vs rating:** niche or specialized genres tend to have higher median ratings.

## Recommendations

- Focus product development on high-rating categories: Events, Education, Art & Design.

- Prioritize high-install categories for growth: Games, Tools, Communication.

- Keep apps lightweight (preferably < 30 MB).

- Prefer a free or low-cost model with optional in-app purchases.

- Release updates frequently (every 30–60 days) to fix bugs and improve UX.

- Target the Everyone content rating when possible for a broader reach.

- Reduce intrusive ads, improve onboarding, and fix crashes to boost ratings.

- Add social or sharing features to encourage engagement and retention.

- Continuously monitor analytics (installs, retention, crashes) and A/B test store listings.
