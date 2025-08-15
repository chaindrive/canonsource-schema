# canonsource-schema
JSON Schema that drives the canonsource standard

## Overview

The Canon Source Schema provides a standardized JSON Schema for representing canonical story structures, fictional universes, and narrative works. It enables consistent documentation and validation of complex storytelling elements including characters, places, temporal relationships, and episodic content.

## Example

For a working example, see:
https://github.com/canonsource/canon-hansel-and-gretel

## Purpose

Canon Source addresses the need for a unified approach to documenting fictional works and their canonical elements. Whether you're working with classic literature, modern franchises, or original creative works, this schema provides a structured framework for:

- **Canonical Documentation**: Systematically record characters, places, events, and facts within fictional universes
- **Temporal Modeling**: Handle complex time relationships with multiple date formats and cross-references
- **Perspective Management**: Support multiple narrative viewpoints and their validity periods
- **Episodic Organization**: Structure stories into series and episodes with detailed event tracking
- **Thematic Categorization**: Organize facts into thematic compendia for comprehensive knowledge management
- **Branching canonogy**: Using git, fandoms can fork canon works, request modifications to official canon or branch histories entirely

## Key Features

### Characters
Define characters with roles, aliases, and lifecycle events (birth, death, activation, deactivation) with temporal references.

### Places
Document locations with creation/destruction timelines and descriptive information.

### Compendia
Organize thematic collections of facts with validity periods. Individual facts can have their own temporal constraints for fine-grained control.

### Series & Episodes
Structure narratives into episodic content with events, facts, and perspective management.

### Temporal Flexibility
Support multiple date formats and translations between different temporal systems (in-universe vs. real-world dates).

### Perspective System
Enable multiple narrative viewpoints with defined validity periods for complex storytelling.

## Schema Structure

The schema requires the following core elements:
- `name`: The canonical work's title
- `authors`: List of creators/authors
- `published`: Publication year
- `characters`: Character definitions with roles and lifecycle
- `perspectives`: Narrative viewpoints with validity periods
- `places`: Location definitions with temporal context
- `compendia`: Thematic fact collections
- `series`: Episodic story organization

## Use Cases

- **Literary Analysis**: Document classic works like fairy tales, novels, or mythology
- **Franchise Management**: Maintain canonical information for ongoing series
- **Creative Development**: Plan and track fictional universe consistency
- **Academic Research**: Standardize narrative structure analysis
- **Interactive Media**: Provide structured data for games, apps, or educational tools

## Validation

All canon.json files following this schema can be automatically validated for structural correctness and completeness, ensuring consistency across different implementations and use cases.

## Utilizing Git To Alter Timelines

One of the most powerful aspects of the Canon Source approach is leveraging Git's distributed version control capabilities to enable collaborative and alternative canonical development. By treating canonical works as structured data under version control, fandoms and creative communities can engage with source material in unprecedented ways.

### Forking Canon

Just as developers fork code repositories, fans and creators can fork canonical works to:

- **Fix Inconsistencies**: Address plot holes, character contradictions, or timeline issues in the original work
- **Alternative Outcomes**: Explore "what if" scenarios by branching at key story moments
- **Character Development**: Expand on underdeveloped characters or relationships
- **Cultural Updates**: Modernize outdated elements while preserving core narrative structure
- **Accessibility Improvements**: Add missing representation or address problematic content

### Collaborative Canon Development

Git's collaboration features enable:

- **Pull Requests**: Propose changes to official canon through structured submissions
- **Issue Tracking**: Document canonical problems and track their resolution
- **Branching Strategies**: Maintain multiple timeline variants simultaneously
- **Merge Conflicts**: Explicitly handle contradictory canonical elements
- **Release Tags**: Mark significant canonical milestones and stable versions

### Canonical Governance

Different projects can adopt various governance models:

- **Authoritative Canon**: Original creators maintain merge authority
- **Community Canon**: Democratic voting on proposed changes
- **Multiverse Canon**: Multiple official branches for different interpretations
- **Living Canon**: Continuous evolution through community contributions

### Timeline Management

The schema's temporal features work synergistically with Git:

- **Temporal Branches**: Create alternate timelines as Git branches
- **Retroactive Changes**: Use Git history to track canonical retcons
- **Perspective Merging**: Combine different narrative viewpoints across forks
- **Date Conflicts**: Resolve temporal inconsistencies through structured merge processes

### Examples of Canon Forking

- **Fixing Character Deaths**: Fork at the moment before a beloved character dies, create an alternative survival timeline
- **Relationship Development**: Branch to explore relationships that were underdeveloped in the original
- **Social Justice Updates**: Update problematic elements while preserving narrative structure
- **Expanded Universe**: Add new characters, places, and events that complement the original
- **Cultural Adaptations**: Adapt works for different cultural contexts while maintaining core themes

This approach transforms passive consumption of media into active, collaborative world-building where every fan can contribute to the canonical discourse while maintaining respect for original works through proper attribution and version control.
