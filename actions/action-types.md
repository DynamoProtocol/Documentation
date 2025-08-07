# 📊 Action Types

Dynamo AI offers three main categories of actions, each optimized for specific types of tasks. Understanding these categories will help you choose the right tool for your needs.

## Data Analysis Actions

### Overview

Transform raw data into meaningful insights using advanced statistical analysis and machine learning techniques.

### Supported Data Formats

- **CSV Files** - Comma-separated values (most common)
- **JSON Data** - Structured object notation
- **TSV Files** - Tab-separated values
- **Excel Files** - .xlsx format (converted to CSV)
- **Plain Text** - Structured text data

### Analysis Capabilities

#### 📈 **Statistical Analysis**

**What it does**: Calculates descriptive and inferential statistics
**Outputs**:

- Summary statistics (mean, median, mode, standard deviation)
- Distribution analysis and histograms
- Correlation matrices and relationships
- Confidence intervals and significance tests

**Example Use Cases**:

- Sales performance analysis
- Customer satisfaction surveys
- A/B testing results
- Financial data assessment

#### 📊 **Trend Analysis**

**What it does**: Identifies patterns and trends over time
**Outputs**:

- Time series analysis and forecasting
- Seasonal pattern identification
- Growth rate calculations
- Trend line visualizations

**Example Use Cases**:

- Website traffic analysis
- Revenue growth tracking
- Inventory level monitoring
- User engagement trends

#### 🔍 **Correlation Analysis**

**What it does**: Finds relationships between different variables
**Outputs**:

- Correlation coefficients and strength
- Scatter plot relationships
- Multivariate analysis results
- Causation vs correlation insights

**Example Use Cases**:

- Marketing attribution analysis
- Product feature impact assessment
- Customer behavior correlations
- Performance metric relationships

#### 🎯 **Segmentation Analysis**

**What it does**: Groups data points based on similarities
**Outputs**:

- Customer segments and profiles
- Product categorizations
- Behavioral groupings
- Demographic clusters

**Example Use Cases**:

- Customer persona development
- Market segmentation studies
- Product recommendation groups
- Risk assessment categories

#### ⚠️ **Anomaly Detection**

**What it does**: Identifies unusual patterns or outliers
**Outputs**:

- Outlier identification and scoring
- Anomaly explanations and context
- Normal vs abnormal pattern analysis
- Alert thresholds and recommendations

**Example Use Cases**:

- Fraud detection in transactions
- Quality control in manufacturing
- Network security monitoring
- Performance issue identification

### Input Requirements

```yaml
Required Fields:
  - Data file or structured text
  - Analysis type selection
  
Optional Fields:
  - Target columns for analysis
  - Grouping variables
  - Time period specifications
  - Confidence level settings
```

### Sample Output Structure

```json
{
  "summary": "Analysis of 1,000 customer records",
  "insights": [
    "Average customer age is 34.2 years",
    "Strong correlation (0.78) between age and spending",
    "Three distinct customer segments identified"
  ],
  "visualizations": [
    {
      "type": "histogram",
      "title": "Age Distribution",
      "description": "Customer age ranges from 18-65"
    }
  ],
  "recommendations": [
    "Target marketing to 25-40 age group",
    "Develop premium products for high spenders"
  ]
}
```

---

## Document Processing Actions

### Overview

Extract information, transform formats, and analyze content from text documents using natural language processing.

### Supported Document Types

- **Plain Text** - .txt files and direct text input
- **Markdown** - .md files with formatting
- **HTML** - Web content and formatted documents
- **PDF Text** - Extracted text from PDF documents
- **Word Documents** - .docx files (text extraction)

### Processing Capabilities

#### 📄 **Text Summarization**

**What it does**: Condenses long documents to essential points
**Outputs**:

- Executive summaries (25-50% of original length)
- Key point extraction and bullet lists
- Chapter/section summaries
- Abstract generation for research papers

**Configuration Options**:

- Summary length (short/medium/long)
- Focus areas (main points/conclusions/methodology)
- Output format (paragraph/bullets/structured)

#### 🔍 **Information Extraction**

**What it does**: Pulls specific data points from unstructured text
**Outputs**:

- Named entities (people, places, organizations)
- Dates, numbers, and financial figures
- Contact information and addresses
- Product names and specifications

**Extraction Types**:

- Contact details from business documents
- Financial figures from reports
- Technical specifications from manuals
- Research findings from papers

#### 🔄 **Format Conversion**

**What it does**: Transforms documents between different formats
**Outputs**:

- Markdown to HTML conversion
- Plain text to structured data
- Document standardization
- Template application

**Supported Conversions**:

- Text → Markdown → HTML
- Unstructured → Structured data
- Long form → Summary formats
- Technical → Plain language

#### 💭 **Content Analysis**

**What it does**: Analyzes themes, sentiment, and document properties
**Outputs**:

- Sentiment analysis (positive/negative/neutral)
- Topic identification and themes
- Readability scoring and recommendations
- Language style and tone analysis

**Analysis Features**:

- Emotional tone assessment
- Complexity level evaluation
- Key theme identification
- Writing style analysis

#### 🏷️ **Document Classification**

**What it does**: Categorizes documents based on content
**Outputs**:

- Document type identification
- Topic classification
- Intent recognition
- Priority level assignment

**Classification Types**:

- Business document types (invoice, contract, report)
- Content categories (technical, marketing, legal)
- Urgency levels (high/medium/low priority)
- Department routing recommendations

### Input Requirements

```yaml
Required Fields:
  - Document text or file upload
  - Processing type selection
  
Optional Fields:
  - Specific extraction targets
  - Output format preferences
  - Analysis focus areas
  - Language specifications
```

### Sample Output Structure

```json
{
  "document_info": {
    "word_count": 2500,
    "estimated_reading_time": "10 minutes",
    "complexity_score": "college level"
  },
  "summary": "Comprehensive analysis of market trends...",
  "extracted_data": {
    "key_figures": ["$2.5M revenue", "15% growth"],
    "important_dates": ["Q4 2024", "January 2025"],
    "action_items": ["Increase marketing budget", "Hire 3 developers"]
  },
  "sentiment": {
    "overall": "positive",
    "confidence": 0.85,
    "key_themes": ["growth", "opportunity", "expansion"]
  }
}
```

---

## Content Generation Actions

### Overview

Create original written content tailored to your specifications using advanced language models and content optimization techniques.

### Content Types

- **Blog Posts** - SEO-optimized articles and posts
- **Social Media** - Platform-specific content and captions
- **Technical Writing** - Documentation, guides, and manuals
- **Marketing Copy** - Sales pages, emails, and advertisements
- **Academic Writing** - Essays, reports, and research summaries

### Generation Capabilities

#### 📝 **Blog Post Generation**

**What it does**: Creates complete, SEO-optimized blog articles
**Outputs**:

- Full articles with headlines and structure
- SEO meta descriptions and titles
- Internal linking suggestions
- Call-to-action recommendations

**Customization Options**:

- Article length (500-3000 words)
- Target audience specification
- SEO keyword integration
- Tone and style preferences

#### 📱 **Social Media Content**

**What it does**: Generates platform-specific social content
**Outputs**:

- Platform-optimized posts (Twitter, LinkedIn, Facebook)
- Engaging captions and descriptions
- Hashtag recommendations
- Content series and campaigns

**Platform Specializations**:

- Twitter threads and viral content
- LinkedIn professional posts
- Instagram captions and stories
- Facebook engagement posts

#### 📚 **Technical Documentation**

**What it does**: Creates clear, structured technical content
**Outputs**:

- API documentation and guides
- User manuals and tutorials
- Process documentation
- Knowledge base articles

**Documentation Types**:

- Step-by-step tutorials
- Reference documentation
- Troubleshooting guides
- Getting started materials

#### 📧 **Marketing Copy**

**What it does**: Generates persuasive marketing content
**Outputs**:

- Sales page copy and headlines
- Email marketing campaigns
- Product descriptions
- Advertisement copy

**Copy Types**:

- Landing page headlines and body
- Email subject lines and content
- Product feature descriptions
- Call-to-action text

#### 🎓 **Academic Writing**

**What it does**: Creates structured academic and research content
**Outputs**:

- Research paper outlines and summaries
- Essay structures and arguments
- Literature review sections
- Thesis statements and conclusions

**Academic Features**:

- Citation format recommendations
- Argument structure guidance
- Research methodology outlines
- Academic tone and style

### Input Requirements

```yaml
Required Fields:
  - Content type selection
  - Topic or subject matter
  - Target audience description
  
Optional Fields:
  - Desired length and format
  - Tone and style preferences
  - SEO keywords and focus
  - Brand voice guidelines
  - Specific requirements or constraints
```

### Sample Output Structure

```json
{
  "content": {
    "title": "10 Essential Tips for Remote Work Productivity",
    "meta_description": "Discover proven strategies to boost productivity while working from home. Expert tips for focus, time management, and work-life balance.",
    "word_count": 1250,
    "reading_time": "5 minutes"
  },
  "structure": {
    "introduction": "Hook and problem statement",
    "main_sections": ["Setup", "Time Management", "Communication", "Wellness"],
    "conclusion": "Summary and call-to-action"
  },
  "seo_elements": {
    "primary_keyword": "remote work productivity",
    "secondary_keywords": ["work from home", "productivity tips"],
    "suggested_tags": ["productivity", "remote-work", "work-life-balance"]
  },
  "content_body": "Full article text with proper formatting..."
}
```

---

## Choosing the Right Action Type

### Decision Framework

#### For Data-Related Tasks

**Choose Data Analysis when you have**:

- Numerical data in spreadsheets
- Survey responses to analyze
- Performance metrics to evaluate
- Trends to identify over time

#### For Text-Related Tasks

**Choose Document Processing when you have**:

- Long documents to summarize
- Unstructured text needing organization
- Information to extract from documents
- Content requiring format conversion

#### For Creation Tasks

**Choose Content Generation when you need**:

- Original written content
- Marketing or sales copy
- Blog posts or articles
- Social media content

### Combination Strategies

Many projects benefit from combining action types:

1. **Research → Analysis → Content**
   - Document Processing to extract insights
   - Data Analysis to find patterns
   - Content Generation to create reports

2. **Data → Insights → Marketing**
   - Data Analysis to understand customers
   - Document Processing to analyze feedback
   - Content Generation to create targeted copy

3. **Content → Analysis → Optimization**
   - Content Generation for initial drafts
   - Document Processing for analysis
   - Iteration based on insights

{% hint style="success" %}
**Selection Tip**: Start with the type of input you have (data/documents/ideas) rather than the output you want. This will guide you to the most appropriate action type.
{% endhint %}

---

**Next**: Learn [How to Use Actions](how-to-use.md) with step-by-step execution instructions.
