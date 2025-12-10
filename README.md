# 🟦 Water Tank – Trapping Rain Water Visualizer

## Frontend Assignment | Vanilla JavaScript + HTML + CSS + SVG
## Author: Sudharsan M S

## 📌 Problem Statement

Given an array of non-negative integers where each element represents the height of a block, compute how much water is trapped between the blocks after raining.

### We must build:
  ✔ A Frontend Web Application using Vanilla JavaScript + HTML + CSS
  
  ✔ A visual representation of the blocks and trapped water using SVG
  
  ✔ Show the total trapped water units

#### 🧪 Example

#### Input:

[0,4,0,0,0,6,0,6,4,0]


#### Output:

18 units of trapped water

### 🚀 Features of This Solution

  ✔ 100% Vanilla JS (no libraries/frameworks)
  
  ✔ SVG-based block and water visualization

  ✔ Smooth animated water fill
  
  ✔ Two-pointer efficient algorithm (O(n) time, O(1) space)
  
  ✔ Input validation
  
  ✔ Tooltip on hover (index, height, water stored)
  
  ✔ Download SVG as file
  
  ✔ Example & Random array generator
  
  ✔ Fully responsive layout

### 🛠️ Tech Stack

    HTML5
    
    CSS3 (Flexbox + modern UI styling)
    
    Vanilla JavaScript
    
    SVG for visualization


#### Note: The entire project is built inside a single index.html file for easy review.

### 🧠 Algorithm Used – Two Pointer (Optimal)

This solution uses the classic two-pointer approach:

#### Steps:

Maintain two pointers: left and right.

Track leftMax and rightMax.

Move the pointer with smaller height.

#### For every index:

Water trapped = min(leftMax, rightMax) - height[i]


### 📸 Visualization

    The app generates an SVG diagram where:
    
    Black bars = Block heights
    
    Blue bars = Trapped water
    
    Water fills with animation

### Hovering shows:

    index | block height | water units

### ▶️ How to Run This Project
#### Method 1 – Local (Recommended)

  Download the repository as ZIP
  
  Open index.html in any browser (Chrome recommended)
  
  That’s it — no installation required

#### Method 2 – GitHub Pages

  Go to Settings → Pages
  
  Enable GitHub Pages for the main branch
  
  The app becomes publicly viewable online


### ⭐ Why This Solution Stands Out

    Clean, understandable code
    
    Strong UI presentation
    
    Production-ready visualization
    
    Interviewer-friendly readme
    
    No dependencies
    
    Accurate algorithm
