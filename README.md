# LangGraph CampusX AI Projects

Welcome to the **LangGraph CampusX AI Projects** repository!  
This repo contains hands-on projects, experiments, and code samples for building advanced AI workflows using [LangGraph](https://github.com/langchain-ai/langgraph) and related LLM technologies.  
It is designed for learners and developers interested in exploring LLMs, prompt chaining, agent workflows, and practical graph-based AI applications.

---

## 📂 Project Structure

- **fundamental/**:
  - [`0_test_installation.ipynb`](fundamental/0_test_installation.ipynb): Quick test to verify LangGraph installation and environment setup.
  - [`1_bmi_workflow.ipynb`](fundamental/1_bmi_workflow.ipynb): Example workflow for calculating BMI using LangGraph nodes and edges.
  - [`2_simple_llm_workflow.ipynb`](fundamental/2_simple_llm_workflow.ipynb): Demonstrates a basic LLM workflow using LangGraph.
  - [`3_prompt_chaining_workflow.ipynb`](fundamental/3_prompt_chaining_workflow.ipynb): Shows how to chain prompts and process outputs in a graph structure.
  - [`4_batsman_parallel_workflow.ipynb`](fundamental/4_batsman_parallel_workflow.ipynb): Parallel computation of cricket statistics (strike rate, boundary %, etc.).
  - [`5_parallel_llm_workflow.ipynb`](fundamental/5_parallel_llm_workflow.ipynb): Parallel evaluation of essay components using Google Gemini.
  - [`6_quadratic_equation_conditional_workflow.ipynb`](fundamental/6_quadratic_equation_conditional_workflow.ipynb): Conditional branching in LangGraph based on the discriminant of a quadratic equation.
  - [`7_review_reply_conditional_workflow.ipynb`](fundamental/7_review_reply_conditional_workflow.ipynb): Sentiment-based conditional workflow to generate AI responses to positive or negative product reviews.

---

## 🚀 Key Features

- **Graph-Based Workflows**: Build and visualize AI workflows as directed graphs.
- **Prompt Chaining**: Connect multiple prompt steps for complex reasoning.
- **LLM Integration**: Use OpenAI, Gemini, Anthropic, and more in graph nodes.
- **Agent Workflows**: Implement agent-based reasoning and tool use.
- **Modular Design**: Easily extend and modify workflows for experimentation.

---

## 🛠️ Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/chintamani-pala/Langchain-Learning.git
   cd Langchain-Learning
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Configure API keys**
   - Add your API keys for OpenAI, Gemini, Anthropic, etc. as needed in your environment or notebook cells.
   - **Required:** Set your `GOOGLE_API_KEY` for Google Gemini integration in this project.

---

## 📖 Example Projects

### Test Installation

- Run [`fundamental/0_test_installation.ipynb`](fundamental/0_test_installation.ipynb) to verify your environment and LangGraph setup.

### BMI Workflow

- [`fundamental/1_bmi_workflow.ipynb`](fundamental/1_bmi_workflow.ipynb) demonstrates a simple graph workflow for BMI calculation.

### Simple LLM Workflow

- [`fundamental/2_simple_llm_workflow.ipynb`](fundamental/2_simple_llm_workflow.ipynb) shows how to use LangGraph for basic LLM tasks.

### Prompt Chaining Workflow

- [`fundamental/3_prompt_chaining_workflow.ipynb`](fundamental/3_prompt_chaining_workflow.ipynb) illustrates chaining prompts and processing outputs in a graph.

### Batsman Parallel Workflow

- [`fundamental/4_batsman_parallel_workflow.ipynb`](fundamental/4_batsman_parallel_workflow.ipynb) demonstrates parallel computation in LangGraph by calculating multiple cricket statistics (strike rate, balls per boundary, boundary percentage) in parallel nodes and summarizing the results. Shows how to use partial state updates for parallel workflows.

### Parallel LLM Workflow

- [`fundamental/5_parallel_llm_workflow.ipynb`](fundamental/5_parallel_llm_workflow.ipynb) showcases a parallel evaluation of an essays using Google Gemini. Multiple aspects (language, analysis, clarity) are evaluated in parallel nodes, and results are aggregated and summarized. Demonstrates structured output and advanced graph design for LLM-based feedback.

### Quadratic Equation Conditional Workflow

- [`fundamental/6_quadratic_equation_conditional_workflow.ipynb`](fundamental/6_quadratic_equation_conditional_workflow.ipynb) evaluates a quadratic equation using conditional logic in LangGraph. Based on the discriminant, the graph follows different paths to output either real or imaginary root handling. Demonstrates use of branching and formatting in a mathematical context.

### Review Reply Conditional Workflow

- [`fundamental/7_review_reply_conditional_workflow.ipynb`](fundamental/7_review_reply_conditional_workflow.ipynb) processes product reviews and uses LLM sentiment classification to conditionally generate responses. Positive and negative reviews are handled with different node paths. Great example of combining logic and LLM outputs for automated customer support or feedback systems.

---

## 📚 Learning Goals

- Understand graph-based workflow design for AI applications.
- Learn prompt chaining and output processing.
- Integrate LLMs and external tools in graph nodes.
- Experiment with agent-based and multi-step reasoning.
- Build workflows that branch dynamically using conditions.
- Experiment with agent-based and multi-step reasoning.

---

## 🤝 Contributing

Pull requests, issues, and suggestions are welcome!  
Feel free to fork and adapt for your own AI experiments.

---

## 📄 License

This repository is for educational purposes.  
See [LICENSE](LICENSE) for details.

---

**Happy Learning!**
