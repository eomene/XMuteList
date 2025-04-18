# XMuteWords

A community-driven collection of word categories for muting on X (formerly Twitter). This repository contains JSON files with categorized words that users can use to filter out unwanted content from their X feed.

## Categories

The repository contains various categories of words that users might want to mute, including:
- Hate speech
- Politics
- Sports
- Entertainment
- Gaming
- Technology
- And more...

## How to Use

1. Download the JSON files from this repository
2. Use X's mute word feature to add these words to your mute list
3. Customize the lists according to your preferences

## Contributing

We welcome contributions to expand and improve the word lists! Here's how you can contribute:

### Adding New Words

1. Fork this repository
2. Choose the appropriate category JSON file
3. Add your words to the existing list
4. Submit a pull request

### Guidelines for Adding Words

- Keep words relevant to the category
- Use lowercase for consistency
- Add words that are commonly used in the context
- Avoid adding offensive or inappropriate words
- Consider adding variations of words (e.g., "football" and "soccer")
- Add words in alphabetical order

### Creating New Categories

If you want to add a new category:

1. Create a new JSON file with the category name (e.g., `sports.json`)
2. Follow the same structure as existing files
3. Add a brief description of the category in the file
4. Submit a pull request

## File Structure

Each category is stored in a separate JSON file with the following structure:

```json
{
  "category": "Category Name",
  "description": "Brief description of the category",
  "words": [
    "word1",
    "word2",
    "word3"
  ]
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. 