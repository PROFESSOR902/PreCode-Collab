# PreCode-Collab
PreCode-Collab is on & is runging in [perchance.org](https://perchance.org/hub). URL for PreCode-Collab: https://perchance.org/precode-collab
Quick start to contribute. --> [CONTRIBUTING.md](https://github.com/PROFESSOR902/PreCode-Collab/blob/main/CONTRIBUTING.md)

# PreCode-Collab - Documentation  

## Overview  
Precode Collab is a collaborative platform for Perchance coders to work together on generators. Key features include:  

### Core Features  
- Chat System: Real-time communication tied to specific generators  
- Idea/Collab Board: Community voting/request system for feature and template development  
- GitHub Integration: Import projects from GitHub for collaboration  
- Code Compare Tool: Side-by-side generator code comparison  
- Search Engine: Find generators seeking collaboration  

## Feature Breakdown  

### Code Compare  
1. Manual Import:  
   - Visit generator URL → Copy code → Paste into two comparison windows:  
     - Window 1: Original generator  
     - Window 2: Comparison generator  
2. Future Upgrade: Automatic code fetching  

### Search Engine  
- How It Works:  
  - Searches generator titles/descriptions for #precodecollab  
  - Displays only matching generators actively seeking collaborators  

### Chat System  
- Flow:  
  1. User enters generator URL OR selects from search results  
  2. Redirects to dedicated chat room   
  3. Enables simultaneous:  
     - Code viewing  
     - Comparison  
     - Live discussion  

### Idea/Collab Board  (Implementation pending)
- Purpose: Community-driven development requests  
- Functionality:  
  - Users vote on desired topics (e.g., "More gaming-related generators")  
  - Identifies like-minded collaborators  
- Future: Implementation pending  

### GitHub Integration  (Implementation pending)
- Expansion: Allows importing projects from GitHub (beyond Perchance-native generators)  

## UI/UX Specifications  
- Header Bar: Navigation to search/code compare tools  
- Side Panel:  
  - Explains Precode Collab functionality  
  - Feedback collection for future modifications  
- Theme:  
  - Professional dark mode
  - Eye-friendly colors  
  - Readable fonts  

 
# PreCode-Collab - Feature Checklist  
*Last Updated: Mar/27/2026 11:23*

### ✅ Implemented Features  
- [x] Chat System  
  - [ ] Dedicated chat rooms per generator  (40% Completed)
  - [ ] Simultaneous code viewing + discussion  (40% Completed)

- [ ] Code Compare Tool  (80% Completed)
  - [x] Dual-window interface  
  - [x] Manual code pasting (URL → copy → paste)  

- [ ] Search Engine  (10% Completed) [:Working template:](https://perchance.org/mrfh3pqow0)
  - [ ] #precodecollab tag filtering  
  - [ ] Title/description search  

- [x] UI Framework  
  - [x] Dark theme  
  - [x] Header navigation  
  - [x] Explanatory side panel  

### Theme Specs  
- [x] Dark mode  
- [x] High-contrast fonts  
- [x] Professional aesthetics  

### 🚧 Future Features  
- [ ] Automatic Code Compare  
  - [ ] Direct URL fetching  

- [ ] Idea/Collab Board  
  - [ ] Topic voting system  
  - [ ] Community request tracking  

- [ ] GitHub Integration  
  - [ ] Cross-platform imports  
  - [ ] Repository syncing  


## GitHub Repository for PreCode-Collab PreCode-Collab, Tutorials and templates.

### PreCode-Collab
- [x] GitHub Repository for PreCode-Collab

### Tutorials and Templates
- [ ] Templates
- [ ] Tutorials
            
## Precode Collab - ToS Compliance Checklist  
**Before project is made public, these things have to be addressed ToS Requirements & Chat Room Access**

### ⚠️ Restricted Features  
- [ ] Automatic Import  
  - [ ] Must implement server-friendly caching  
  - [ ] Requires explicit rate limiting  

- [ ] Chat Room Access  
  - [ ] Generator links must remain unchanged  
  - [ ] Requires separate "Discuss" button (opt-in)  

### ToS Requirements  
- [ ] No generator link interception  
- [ ] No misleading UI flows  
- [ ] Clear distinction between chat/gen views  

### Mandatory Implementation  
- [ ] Rate limiting (max 10 reqs/minute)  
- [ ] Client-side caching for searches  
- [ ] Visible "Original Generator" link option
