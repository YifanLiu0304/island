---
title: Travel Stories
cms_exclude: true
type: landing

sections:
  - block: markdown
    content:
      title: Global Adventures
      subtitle: Exploring the world, one story at a time
      text: |
        {{< world-map >}}
    design:
      columns: '1'
      
  - block: collection
    content:
      title: Featured Stories
      subtitle: Latest travel experiences and city guides
      text: |
        Discover detailed guides, local insights, and personal adventures from around the globe.
      filters:
        folders:
          - travel
        featured_only: true
    design:
      columns: '2'
      view: card
      
  - block: collection
    content:
      title: Travel Series
      subtitle: Curated collections of travel experiences
      text: |
        ### Food & Drink
        Culinary adventures and local gastronomy discoveries
        
        ### Arts & Culture
        Museums, galleries, and cultural experiences
        
        ### Nature & Adventure
        Outdoor explorations and natural wonders
        
        ### Urban Exploration
        City guides and metropolitan discoveries
        
        ### Travel Tips
        Insider knowledge and practical advice
      filters:
        folders:
          - travel
        exclude_featured: true
    design:
      columns: '2'
      view: compact

  - block: markdown
    content:
      title: Travel Map
      subtitle: Where I've Been
      text: |
        ### Recent Destinations
        - **France** - Wine tasting in Bordeaux, exploring Paris
        - **Japan** - Cherry blossom season, traditional temples
        - **New Zealand** - Hiking through national parks
        
        ### Upcoming Adventures
        - **Italy** - Summer 2024
        - **Norway** - Northern Lights expedition
        - **Morocco** - Desert adventure
    design:
      columns: '2'
---

Welcome to my travel adventures! Click on the markers on the map to explore my journeys around the world. 