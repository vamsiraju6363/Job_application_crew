<h1 align="center"> Job Application crewAI</h1>
<p align="center"><i>Your AI-powered assistant for automating job discovery and resume matching</i></p>

<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.11+-blue.svg" alt="Python 3.11+">
  </a>
  <a href="https://crewai.com/">
    <img src="https://img.shields.io/badge/Built%20with-CrewAI-blue.svg" alt="Built with CrewAI">
  </a>
</p>

---

## About the Project

`Job Application CrewAI` leverages intelligent agents to streamline your job hunt. With a combination of web scraping, semantic resume parsing, and CrewAI's agent collaboration framework, this tool helps identify the best job listings tailored to your profile.

### Use Case

- Automate job searching and ranking based on resume relevance.
- Save time manually browsing and comparing listings.
- Experiment with cutting-edge LLM and agent-based automation.

---

## Features

- Google job search integration via Serper.dev  
- Web scraping of job descriptions  
- Semantic resume-job matching  
- Modular CrewAI agent framework  
- Custom resume input via Markdown

---

##  Tech Stack

- **Python 3.11+**
- [CrewAI](https://docs.crewai.com/)
- [Serper.dev](https://serper.dev/)
- OpenAI LLMs
- Jupyter Notebooks

---

##  Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/vamsiraju6363/job-application-crew.git
cd job-application-crew
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Environment Variables

Add your API keys to your environment:

```bash
export SERPER_API_KEY="your-serper-api-key"
export OPENAI_API_KEY="your-openai-api-key"
```

### 4. Run the Notebook

```bash
jupyter notebook Job_application_crew.ipynb
```

---

##  Agent Workflow

1. **Search Agent**  
   Uses Serper.dev to identify job listings based on a user query.

2. **Scraper Agent**  
   Fetches and extracts job description content from URLs.

3. **Resume Reader Agent**  
   Loads resume content from a Markdown file.

4. **Matcher Agent**  
   Performs semantic comparison between job listings and your resume.

5. **Orchestrator Crew**  
   Coordinates agents to output a ranked list of matching job opportunities.

---

##  Resume Input Format

Create a file named `fake_resume.md` in the root folder with content like:

```markdown
## Vamsi Raju

### Skills
- Golang, Python, Kubernetes, Terraform, CI/CD

### Experience
- Software Engineer at ABC Inc (2021–2024)
  - Built distributed microservices in Golang.
  - Automated deployment with Kubernetes and Terraform.
```

---

##  Project Structure

```bash
.
├── Job_application_crew.ipynb       # Main notebook with all logic
├── fake_resume.md                   # Markdown resume used for matching
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
```

---

##  Future Enhancements

-  Email auto-apply feature  
-  Dashboard for match scoring  
-  Integration with LinkedIn and job APIs  
-  `.env` support for better credential management
  
---

<p align="center">
  Built with LLM agents using <a href="https://crewai.com/">CrewAI</a>
</p>
