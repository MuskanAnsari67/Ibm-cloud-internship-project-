CAPSTONE PROJECT
Course Content  Simplification Agent


 


OUTLINE
◾	Problem Statement
◾	Proposed System/Solution
◾	System Development Approach
◾	Algorithm & Deployment
◾	Result
◾	Conclusion
◾	Future Scope
◾	References
 
PROBLEM STATEMENT
Problem Statement No.19 – Course Content Simplification Agent
The Challenge – Educational materials often vary in complexity and are not always accessible to learners with different levels of prior knowledge. Students may struggle to grasp key concepts due to jargon heavy or overly advanced explanations in faculty notes and textbooks. The challenge is to develop an Ai powered agent that can intelligently analyse academic content and reframe explanations based on theLearner’s current proficiency—ranging from beginner to expert. This would support more inclusive learning and personalized education delivery at scale.
 
PROPOSED SOLUTION
Objective:
To build an AI-based system that offers tailored career suggestions to students based on their academic background, skill set, interests, and work preferences.
  Input Details:
Qualification and current stream, Technical & soft skills, Areas of interest (e.g., creativity, design, data) Job preferences (remote, flexible, etc.
  Prompt Design Strategy
Carefully structured inputs are framed into natural-language prompts that guide the model to generate meaningful outputs.
Example prompt:
> “Suggest 3 career options for a student skilled in Python and Canvas, interested in design and data, and looking for flexible jobs.
Include reasoning, required skills, salary range, and future scope.’.
  Technology Stack:
Platform: IBM Watsonx.ai, Model: Granite-13b-instruct (No training needed, prompt-based),IBM Cloud Lite Plan used for deployment
 


  Working Process:
1.	User provides input via a web-based form or directly in Prompt Lab
2.	Prompt is dynamically generated
3.	Model processes the prompt and gives detailed career options
4.	Output is shown in a readable, structured format   Evaluation:
Responses were evaluated for clarity, accuracy, and relevance Tested across multiple profiles with consistent, logical suggestions   Result:
The system delivers smart, real-time career guidance in a conversational format. It acts like a digital counselor and provides reliable suggestions to students with minimal manual effort.
 
SYSTEM APPROACH
◾	The Career Advisor system is designed to run entirely on the cloud using IBM Watsonx, eliminating the need for high-end local hardware. Below are the key system requirements:
◾	A laptop or desktop with Windows 10/11, macOS, or Linux OS
◾	Minimum 4 GB RAM is sufficient, though 8 GB is recommended for smoother multitasking
◾	A modern multi-core processor (Intel i3 or above; i5/Ryzen 5 recommended)
◾	No software installation is required, as the project is browser-based
◾	A stable internet connection is essential, preferably 4G/5G or broadband Wi-Fi
◾	Any updated web browser such as Google Chrome, Firefox, or Microsoft Edge
◾	An IBM Cloud account (Lite plan) to access Watsonx.ai services
◾	Access to IBM Watsonx.ai Prompt Lab for creating and running prompts
◾	Optional tools for documentation or results export: Google Docs, Word, or Notepad
◾	This setup allows users to interact with the AI model directly through the browser, making the solution lightweight, scalable, and accessible on most standard machines.
 
ALGORITHM & DEPLOYMENT
◾	  Algorithm Used
◾	  Model Used:
◾	Granite-13B-Instruct – A Large Language Model (LLM) by IBM
◾	Hosted and accessed via IBM Watsonx.ai Prompt Lab
◾	  Working Principle:
◾	No training or dataset required
◾	Uses Prompt Engineering to guide the model response
◾	The model understands natural language and generates human-like career suggestions
◾	Based on: Skills , Educational background , Interests , Work preferences (e.g., remote/flexible jobs)-
◾	  Why Granite-13B?
◾	Fine-tuned for instruction-following tasks , Generates accurate and structured output , Designed for enterprise-grade AI applications
 


 	 
 

 	 
 

 

 
 
LAST STEP

 



◾	Steps:
◾	1. Create project on IBM Watsonx.ai
◾	2. Select Granite-13b-instruct model
◾	3. Design and test prompt in Prompt Lab
◾	4. Input user profile (skills, education, interests)
◾	5. Generate and display career suggestions---
◾	  Interface / Output:
◾	Real-time suggestions with:
◾	Career name Why it’s suitable , Required skills , Salary info , Future demand.
 
DEPLOYMENT
◾	  Platform Used:IBM Watsonx Prompt Lab (Cloud-based)Model runs directly on IBM Cloud – no need for local deployment---

 
RESULT
◾	The AI-powered Career Advisor successfully generated personalized career suggestions based on user inputs like skills, interests, and preferences. It provided suitable job roles, along with required skills, average salary, and future growth—helping students make informed career decisions instantly.



 
CONCLUSION

The Career Advisor system successfully uses generative AI to provide personalized and intelligent career guidance. By analyzing a student’s skills, interests, and goals, it recommends suitable job roles along with essential details like required skills, salary range, and growth scope.
This solution reduces the need for manual counselling and helps students explore future-ready career paths with clarity and confidence. Built on IBM Watsonx Granite, it offers quick, accurate, and meaningful suggestions — making it a smart step toward tech-driven career planning.
 
FUTURE SCOPE

◾	The Career Advisor system has significant potential for real-world enhancement:
◾	Multi-language Support: Can be extended to support regional languages for wider accessibility
◾	Integration with Job Portals: Real-time job matching based on AI suggestions
◾	Learning Path Recommendations: Suggest relevant courses, certifications, or skills to bridge career gaps
◾	Mobile App Development: Making the advisor accessible on the go
◾	Voice Assistant Integration: Enable voice-based career queries using NLP
◾	Institutional Use: Can be deployed in schools/colleges as a smart counselling tool
 
REFERENCES
◾	1. IBM Watsonx Prompt Lab Documentation –
https://www.ibm.com/products/watsonx
◾	2. IBM Granite Models Overview – https://www.ibm.com/blog/what-is-granite
◾	3.IBM Cloud Lite Plan – https://www.ibm.com/cloud/free
◾	4. AI Use Cases in Career Guidance – Research articles from IEEE Xplore &
Google Scholar
◾	5. Prompt Engineering for LLMs – OpenAI & Hugging Face Community Tutorials
◾	6. Stack Overflow, IBM Developer Community – For resolving Prompt Lab
technical queries.
# Ibm-cloud-internship-project-
IBM cloud internship project using artificial intelligence .
