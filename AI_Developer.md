## **Issue #1: Categorized Training Data**
**Title:** Implement categorized training data storage  

**User Story:**  
As an AI developer, I want training data to be organized into categories and subcategories so that I can efficiently manage and focus on specific areas of model training.  

**Purpose:**  
To enhance model learning efficiency by structuring training data into meaningful categories and subcategories, enabling better organization and retrieval.  

**Implementation Strategy:**  
- Define a list of categories and subcategories for training data.  
- Develop an automatic categorization algorithm.  
- Allow manual reclassification for incorrect categorizations.  
- Build an analytics dashboard to evaluate categorization effectiveness.  

**Priority:** High  

## **Sub-Issues:**

### **1. [UR-01.1] Define Categories for Training Questions**
- **Assumption:** A well-organized Q&A format helps learning by avoiding unintentional hints.  
- **Validation:** Conduct usability testing with developers to measure effectiveness. 

### **2. [UR-01.2] Implement Question Categorization UI**
- **Parent:** [UR-01] Categorized Training Questions  
- **Goal:** Allow users to assign categories.  
- **Approach:** Add dropdown and save logic.  
- **Tasks:**  
  - [ ] Create dropdown for category selection.  
  - [ ] Store category with question entry.  
  - [ ] Connect UI with backend API.  
  - [ ] Save category in database table.  
  - [ ] Validate category before saving.  
  - [ ] Load category options dynamically. 

  ### **3. [UR-01.3] Develop Automatic Categorization Algorithm**
- **Parent:** [UR-01] Categorized Training Questions  
- **Goal:** Automatically categorize training questions.  
- **Approach:** Train a machine learning model for classification.  
- **Tasks:**  
  - [ ] Collect and preprocess training data for categorization.  
  - [ ] Train a classification model using labeled data.  
  - [ ] Test the model’s accuracy and refine as needed.  
  - [ ] Integrate the model into the categorization workflow. 

  
