# ResumeGenius

ResumeGenius is an AI-powered resume enhancement tool that helps users improve their resumes by providing suggestions on content, structure, and wording. It also generates personalized cover letters and optimizes resumes for specific job descriptions.

## Features

- **AI-Powered Resume Suggestions**: Analyze resumes for clarity, relevance, and structure, and provide actionable improvement suggestions.
- **Job Description Matching**: Tailor resumes to match specific job descriptions by optimizing for keywords and required skills.
- **Cover Letter Generation**: Automatically generate cover letters based on the user's resume and a job description.
- **Version Control**: Save multiple versions of resumes and switch between them as needed.
- **Download Options**: Export enhanced resumes and cover letters as PDF, DOCX, or plain text.

## Setup Instructions

### Prerequisites
- Ruby (version 3.3.5 or higher)
- Rails (version 7.2.1 or higher)
- OpenAI API key

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/jamesboby897/resumegenius.git
   cd resumegenius
   ```
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Set up the database:
   ```bash
   rails db:create db:migrate
   ```
4. Add your OpenAI API key to the .env file:

    - Create a .env file in the root directory.
    - Add the following line to the .env file: ```env OPENAI_KEY=your-openai-api-key-here ```
5. Start the Rails server: ```bash rails s ```

6. Visit ```http://localhost:3000``` in your browser to access the application.

## To-Do (Pending Features)
  - User Authentication: Implement user sign-up, login, and authentication using Devise or similar.
  - Resume Upload and Parsing: Allow users to upload resumes as PDF or DOCX and parse the content.
  - AI Resume Suggestions: Integrate the OpenAI API to provide resume improvement suggestions.
  - Job Description Matching: Develop a feature that compares resumes with job descriptions and provides tailored       recommendations.
  - Cover Letter Generator: Add the ability to generate custom cover letters based on the user’s resume and job description.
  - User Dashboard: Create a dashboard where users can manage their resumes, cover letters, and view suggestions.
  - Analytics: Implement a system to track feedback and improve AI responses over time.
  - Version Control: Allow users to save and manage multiple resume versions.
  - Download Options: Enable exporting of resumes and cover letters in various formats.

## Contributing
Feel free to fork the repository and submit pull requests. For major changes, please open an issue to discuss your ideas.

## License
This project is licensed under the MIT License.






