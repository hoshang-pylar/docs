# Learn Section - Content Plan

## Section Structure Overview

```
Learn/
├── Making Connections/
├── Creating Data Views/
├── Building MCP Tools/
├── Publishing Tools to Agents/
└── Evals/
```

---

## 1. Making Connections

**Purpose**: Guide users through connecting their data sources to Pylar

### Proposed Files:

1. **`overview.mdx`** - Introduction to connections
   - What are connections in Pylar
   - Why connections matter
   - Supported data sources overview
   - Connection security overview

2. **`supported-data-sources.mdx`** - Complete list with details
   - BigQuery
   - Snowflake
   - PostgreSQL
   - MySQL
   - Redshift
   - AlloyDB
   - Databricks
   - Others
   - Feature comparison matrix

3. **`connecting-bigquery.mdx`** - Step-by-step BigQuery connection
   - Prerequisites
   - Getting credentials
   - Connection steps
   - Testing connection
   - Common issues

4. **`connecting-snowflake.mdx`** - Step-by-step Snowflake connection
   - Prerequisites
   - Getting credentials
   - Connection steps
   - Testing connection
   - Common issues

5. **`connecting-postgresql.mdx`** - Step-by-step PostgreSQL connection
   - Prerequisites
   - Getting credentials
   - Connection steps
   - Testing connection
   - Common issues

6. **`connection-security.mdx`** - Security best practices
   - Credential management
   - Encryption
   - Network security
   - Access controls
   - Best practices

7. **`managing-connections.mdx`** - Managing existing connections
   - Viewing connections
   - Editing connections
   - Testing connections
   - Removing connections
   - Connection health monitoring

8. **`troubleshooting-connections.mdx`** - Common issues and solutions
   - Connection timeout errors
   - Authentication failures
   - Network issues
   - Permission errors
   - Debugging tips

---

## 2. Creating Data Views

**Purpose**: Deep dive into creating and managing data views

### Proposed Files:

1. **`overview.mdx`** - Introduction to data views
   - What are data views
   - Views vs raw database access
   - How views work in Pylar
   - View organization in projects

2. **`sql-ide-basics.mdx`** - SQL IDE introduction
   - Navigating the SQL IDE
   - Interface overview
   - Data source selection
   - Query editor features
   - Running queries

3. **`writing-your-first-view.mdx`** - Getting started tutorial
   - Step-by-step first view
   - Basic SELECT queries
   - Saving views
   - Naming conventions
   - Adding descriptions

4. **`cross-database-joins.mdx`** - Advanced joining
   - What are cross-database joins
   - When to use them
   - Syntax and examples
   - Performance considerations
   - Best practices

5. **`view-best-practices.mdx`** - Best practices guide
   - Naming conventions
   - Query optimization
   - Security considerations
   - Documentation
   - Performance tips
   - Common patterns

---

## 3. Building MCP Tools

**Purpose**: Guide to creating and configuring MCP tools

### Proposed Files:

1. **`overview.mdx`** - Introduction to MCP tools
   - What are MCP tools
   - Tools vs views
   - Why multiple tools per view
   - Tool lifecycle

2. **`creating-tools-with-ai.mdx`** - AI-powered tool creation
   - How AI tool creation works
   - Writing effective prompts
   - Example prompts
   - Reviewing AI-generated tools
   - Refining AI suggestions
   - Best practices for AI prompts

3. **`creating-tools-manually.mdx`** - Manual tool configuration
   - When to create manually
   - Tool configuration options
   - Setting parameters
   - Tool descriptions
   - Response formatting
   - Advanced configuration

4. **`tool-parameters.mdx`** - Parameter configuration
   - Understanding parameters
   - Parameter types
   - Required vs optional
   - Default values
   - Parameter validation
   - Examples

5. **`multiple-tools-per-view.mdx`** - Creating multiple tools
   - Why create multiple tools
   - Use cases
   - Organizing multiple tools
   - Tool naming conventions
   - Best practices

6. **`testing-your-tools.mdx`** - Testing guide
   - How to test tools
   - Testing different scenarios
   - Interpreting test results
   - Debugging failed tests
   - Test data considerations

7. **`tool-best-practices.mdx`** - Best practices
   - Naming conventions
   - Descriptions and documentation
   - Parameter design
   - Error handling
   - Performance optimization
   - Common patterns

---

## 4. Publishing Tools to Agents

**Purpose**: Guide to deploying and connecting tools to agent builders

### Proposed Files:

1. **`overview.mdx`** - Publishing introduction
   - What is publishing
   - Link and token explained
   - Publishing workflow
   - Update behavior

2. **`publishing-your-project.mdx`** - Publishing process
   - When to publish
   - Publishing steps
   - Understanding the publish output
   - Link and token security
   - Best practices

3. **`getting-your-credentials.mdx`** - Link and token details
   - What is the MCP server link
   - What is the header token
   - How to use them
   - Security considerations
   - Token management

4. **`connecting-claude-desktop.mdx`** - Claude Desktop setup
   - Prerequisites
   - Step-by-step connection
   - Configuration details
   - Verifying connection
   - Troubleshooting

5. **`connecting-cursor.mdx`** - Cursor setup
   - Prerequisites
   - Step-by-step connection
   - Configuration details
   - Verifying connection
   - Troubleshooting

6. **`connecting-windsurf.mdx`** - Windsurf setup
   - Prerequisites
   - Step-by-step connection
   - Configuration details
   - Verifying connection
   - Troubleshooting

7. **`connecting-custom-agents.mdx`** - Custom agent integration
   - MCP protocol overview
   - Integration steps
   - Code examples
   - Authentication
   - Best practices

8. **`managing-published-tools.mdx`** - Managing published projects
   - Viewing published status
   - Understanding updates
   - Revoking access
   - Re-publishing
   - Version management

9. **`updates-and-versioning.mdx`** - How updates work
   - Automatic updates
   - When changes reflect
   - Version control
   - Rolling back changes
   - Testing updates

---

## 5. Evals

**Purpose**: Guide to using Evals for monitoring and optimization

### Proposed Files:

1. **`overview.mdx`** - Introduction to Evals
   - What are Evals
   - Why use Evals
   - What you can learn
   - Accessing Evals

2. **`evals-dashboard.mdx`** - Dashboard overview
   - Navigating the dashboard
   - Key metrics overview
   - Time range selection
   - Filtering options
   - Exporting data

3. **`understanding-query-logs.mdx`** - Query log analysis
   - What are query logs
   - Reading logs
   - Log structure
   - Finding specific queries
   - Log analysis tips

4. **`analyzing-errors.mdx`** - Error analysis
   - Error types
   - Error frequency
   - Common errors
   - Error patterns
   - Fixing errors
   - Error prevention

5. **`understanding-query-shapes.mdx`** - Query shape analysis
   - What are query shapes
   - Common patterns
   - Performance implications
   - Optimization opportunities
   - Best practices

6. **`improving-views-with-evals.mdx`** - Using Evals to improve views
   - Identifying issues
   - Optimization opportunities
   - Security improvements
   - Performance tuning
   - Iterative refinement

7. **`improving-tools-with-evals.mdx`** - Using Evals to improve tools
   - Tool usage patterns
   - Parameter optimization
   - Description improvements
   - Error reduction
   - User experience enhancements

8. **`evals-best-practices.mdx`** - Best practices
   - Regular monitoring
   - Setting up alerts
   - Interpreting metrics
   - Actionable insights
   - Continuous improvement

---

## Navigation Structure

```json
{
  "group": "Learn",
  "pages": [
    {
      "group": "Making Connections",
      "pages": [
        "learn/making-connections/overview",
        "learn/making-connections/supported-data-sources",
        "learn/making-connections/connecting-bigquery",
        "learn/making-connections/connecting-snowflake",
        "learn/making-connections/connecting-postgresql",
        "learn/making-connections/connection-security",
        "learn/making-connections/managing-connections",
        "learn/making-connections/troubleshooting-connections"
      ]
    },
    {
      "group": "Creating Data Views",
      "pages": [
        "learn/creating-data-views/overview",
        "learn/creating-data-views/sql-ide-basics",
        "learn/creating-data-views/writing-your-first-view",
        "learn/creating-data-views/cross-database-joins",
        "learn/creating-data-views/view-best-practices"
      ]
    },
    {
      "group": "Building MCP Tools",
      "pages": [
        "learn/building-mcp-tools/overview",
        "learn/building-mcp-tools/creating-tools-with-ai",
        "learn/building-mcp-tools/creating-tools-manually",
        "learn/building-mcp-tools/tool-parameters",
        "learn/building-mcp-tools/multiple-tools-per-view",
        "learn/building-mcp-tools/testing-your-tools",
        "learn/building-mcp-tools/tool-best-practices"
      ]
    },
    {
      "group": "Publishing Tools to Agents",
      "pages": [
        "learn/publishing-tools/overview",
        "learn/publishing-tools/publishing-your-project",
        "learn/publishing-tools/getting-your-credentials",
        "learn/publishing-tools/connecting-claude-desktop",
        "learn/publishing-tools/connecting-cursor",
        "learn/publishing-tools/connecting-windsurf",
        "learn/publishing-tools/connecting-custom-agents",
        "learn/publishing-tools/managing-published-tools",
        "learn/publishing-tools/updates-and-versioning"
      ]
    },
    {
      "group": "Evals",
      "pages": [
        "learn/evals/overview",
        "learn/evals/evals-dashboard",
        "learn/evals/understanding-query-logs",
        "learn/evals/analyzing-errors",
        "learn/evals/understanding-query-shapes",
        "learn/evals/improving-views-with-evals",
        "learn/evals/improving-tools-with-evals",
        "learn/evals/evals-best-practices"
      ]
    }
  ]
}
```

---

## Content Priorities

### Phase 1 (Essential - Start Here):
1. Making Connections: overview, supported-data-sources, connecting-bigquery
2. Creating Data Views: overview, sql-ide-basics, writing-your-first-view
3. Building MCP Tools: overview, creating-tools-with-ai, testing-your-tools
4. Publishing Tools: overview, publishing-your-project, connecting-claude-desktop
5. Evals: overview, evals-dashboard, understanding-query-logs

### Phase 2 (Important):
- All connection guides for major databases
- Cross-database joins
- Creating tools manually
- Connecting to other agent builders
- Error analysis

### Phase 3 (Advanced):
- Advanced security
- Troubleshooting guides
- Best practices
- Custom agent integration
- Advanced evals analysis

---

## Notes

- Each section should have an overview page that sets context
- Pages should include practical examples and code snippets where relevant
- Include troubleshooting sections for common issues
- Cross-reference related pages where appropriate
- Use Mintlify components (Info, Tip, Warning, Check, Code blocks) consistently
- Include visual aids where helpful (screenshots, diagrams)

