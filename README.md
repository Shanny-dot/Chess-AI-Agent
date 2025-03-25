# Chess-AI-Agent

## Features

### Multi-Agent Architecture
- **Agent White**: An OpenAI-powered strategic decision-maker focused on long-term planning.
- **Agent Black**: An OpenAI-powered tactical opponent excelling in sharp, precise moves.
- **Board Proxy**: A dedicated validation agent ensuring move legality and maintaining the game state.

### Safety & Validation
- Robust move verification to enforce chess rules.
- Prevention of illegal moves for fair gameplay.
- Real-time monitoring of the board state.
- Secure control over game progression.

### Strategic Gameplay
- AI-driven evaluation of board positions.
- Deep tactical analysis for competitive play.
- Dynamic strategy adaptation based on the game’s flow.
- Full implementation of standard chess rules.

## How to Get Started

1. **Clone the GitHub Repository**  
   ```bash
   git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
   cd ai_agent_tutorials/ai_chess_game
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Get Your OpenAI API Key**  
   - Sign up for an [OpenAI account](https://openai.com) (or your preferred LLM provider).  
   - Obtain your API key and configure it for use in the app.

4. **Run the Streamlit App**  
   ```bash
   streamlit run ai_chess_agent.py
   ```
