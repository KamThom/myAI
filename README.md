**Dormibot: Resident Assistant Support AI**

### **1. Objectives and Topic of Dormibot**
Dormibot is an AI-powered assistant designed to support Resident Assistants (RAs) in their duties by providing quick access to policies, procedures, and contact information. The chatbot aims to:
- Provide instant answers to RA-related questions.
- Link directly to relevant procedural documents.
- Assist in conflict resolution, key checkouts, and emergency protocols.
- Maintain an empathetic, supportive tone in interactions.

### **2. Data Sources and Curation**
Dormibot pulls its knowledge from a curated set of publicly available Google Docs provided by the university’s housing department. These documents contain:
- RA policies and procedures.
- Contact lists for emergency and administrative services.
- Training materials and guidelines.
- Incident response protocols.

To ensure relevant and accurate responses, Dormibot utilizes Retrieval-Augmented Generation (RAG). The chatbot retrieves relevant document excerpts based on user queries and integrates them into its responses, improving precision and reducing hallucinations.

### **3. Features and Tools**
- **Retrieval-Augmented Generation (RAG):** Fetches relevant text from RA policy documents to answer queries.
- **Empathetic Response System:** Dormibot maintains a warm, supportive, and understanding tone.
- **Hostile Message Handling:** If an RA is frustrated or upset, Dormibot de-escalates the situation with patient and constructive responses.
- **UI Enhancements:**
  - Favicon updated to a lantern icon to reflect the theme of guidance.
  - AI logo redesigned to match branding.
  - Custom fonts applied to improve readability and aesthetic appeal.
- **Customizable System Prompts:** The AI adapts its responses based on the context and nature of user interactions.

### **4. Code Modifications**
Dormibot was built upon the myAI codebase but has undergone significant changes, including:
- **Updated Default Response Messages:**
  - New friendly and engaging introductory message.
  - Redesigned fallback message for when Dormibot cannot retrieve an answer.
- **Overhauled UI.ts:**
  - Updated colors, fonts, and branding.
  - Adjusted spacing and element positioning for better usability.
- **Rewritten Prompts.ts:**
  - New system messages tailored for RA-specific needs.
  - Specialized prompts for handling questions, conflicts, and support inquiries.
- **Updated AI Identity:**
  - Dormibot is now known as "Sean," reinforcing its approachable personality.
- **Enhanced Search Logic:**
  - Improved how document excerpts are retrieved and ranked for relevance.

### **5. Custom Prompting Strategy**
Dormibot’s responses are guided by carefully designed system prompts, ensuring:
- **Precision:** AI provides direct and relevant information from RA policies.
- **Empathy:** Responses maintain warmth, humor, and supportiveness.
- **Guidance-Oriented Approach:** The AI directs users to specific documents via clickable links.
- **Error Handling:** If no relevant data is found, Dormibot acknowledges the limitation and suggests alternatives.

### **6. Access and Deployment**
Dormibot is currently deployed at [Dormibot Vercel](https://dormibot.vercel.app/).
The full source code is available at [GitHub Repository](INSERT_GITHUB_LINK_HERE).

### **7. Future Improvements**
- Implementing better search ranking for multi-document queries.
- Adding voice-to-text capabilities for mobile accessibility.
- Expanding knowledge sources beyond Google Docs.
- Enhancing response personalization based on RA experience levels.

---

This document serves as the technical overview of Dormibot, detailing its development, capabilities, and areas for future growth.

