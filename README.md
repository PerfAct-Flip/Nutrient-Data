# Nutrient Data Repository

This repository contains JSON data files with detailed nutrient information for various food items, including energy, protein, fat, carbohydrates, and other key nutritional values per 100g. Each food item also includes relevant tags to categorize the type of food.

## Data Structure

Each entry in the data follows this structure:

```json
{
    "id": "food-item-id",
    "name": "Food Item Name",
    "nutrition-per-100g": {
        "energy": 1560,
        "protein": 12.3,
        "fat": 9.9,
        "saturated-fat": 2.8,
        "carbohydrate": 51.7,
        "sugars": 19.7,
        "dietary-fibre": 13,
        "sodium": 6
    },
    "tags": ["tag1", "tag2"]
}
