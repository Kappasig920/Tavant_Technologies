# URL Template

Use this template when adding new URLs to the repository.

## JSON Format for urls.json

```json
{
  "title": "Descriptive Title of the Resource",
  "url": "https://example.com/resource",
  "description": "A clear, concise description of what this resource contains and why it's relevant. Be specific about the value it provides.",
  "indexed_in_notebooklm": true,
  "relevance": "high",
  "tags": ["tag1", "tag2", "tag3"]
}
```

## Field Descriptions

### Required Fields

- **title**: A clear, descriptive name for the resource (String)
- **url**: The complete URL to the resource (String, must be valid URL)
- **description**: Brief summary of the resource content and relevance (String, 1-2 sentences)
- **indexed_in_notebooklm**: Whether this URL has been indexed in NotebookLM (Boolean: true/false)
- **relevance**: Priority level of this resource (String: "high", "medium", or "low")
- **tags**: Array of keywords for categorization (Array of strings)

## Relevance Guidelines

- **high**: Critical information for interview preparation or core company understanding
- **medium**: Important but supplementary information
- **low**: Background or reference material

## Tag Suggestions

Common tags to use:
- `company` - General company information
- `culture` - Company culture and values
- `technical` - Technical content and documentation
- `products` - Product and service information
- `blog` - Blog posts and articles
- `careers` - Career-related content
- `industry` - Industry-specific information
- `interview` - Interview preparation resources
- `solutions` - Solution offerings
- `innovation` - Innovation and R&D content

## Categories

Add your URL to one of these categories in `urls.json`:
- `company_information` - Company overview, mission, values, history
- `technical_resources` - Technical documentation, blogs, architecture
- `industry_insights` - Industry trends, domain expertise, solutions
- `interview_preparation` - Interview-specific resources

## Example Entry

```json
{
  "title": "Tavant AI/ML Capabilities",
  "url": "https://www.tavant.com/ai-ml-solutions",
  "description": "Overview of Tavant's artificial intelligence and machine learning solutions for various industries including predictive analytics and automation",
  "indexed_in_notebooklm": true,
  "relevance": "high",
  "tags": ["technical", "ai", "ml", "solutions", "innovation"]
}
```

## Steps to Add a New URL

1. Open `urls.json` in your editor
2. Locate the appropriate category section
3. Add your new URL entry following the template above
4. Ensure proper JSON syntax (commas, brackets, quotes)
5. Validate the JSON format
6. Commit your changes with a descriptive message
7. If the URL is indexed in NotebookLM, verify the indexing is complete

## Validation Checklist

Before committing your new URL entry:
- [ ] Title is clear and descriptive
- [ ] URL is valid and accessible
- [ ] Description provides meaningful context
- [ ] NotebookLM indexing status is accurate
- [ ] Relevance level is appropriate
- [ ] Tags are relevant and follow conventions
- [ ] JSON syntax is correct
- [ ] Entry is in the right category

## Tips

- Keep descriptions concise but informative
- Use consistent terminology across entries
- Verify URLs are accessible before adding
- Add multiple tags to improve discoverability
- Update `last_updated` field in metadata section
- Consider the interview preparation context when assessing relevance
