# Forex Trading Bot Using NEAT Algorithm

## Project Overview

This project demonstrates the development of an innovative Forex trading bot powered by the NeuroEvolution of Augmenting Topologies (NEAT) algorithm, a cutting-edge reinforcement learning approach. By creating a custom trading environment and incorporating sophisticated trading features, this project showcases the ability to train, evaluate, and deploy a trading bot capable of robust performance in the dynamic Forex market. The bot is rigorously validated and executed in a demo trading setting, highlighting its potential for real-world financial applications.

## Motivation

The Forex market, with its high volatility and complexity, presents a unique challenge for automated trading systems. This project aims to leverage the NEAT algorithm’s ability to evolve neural network topologies, enabling the development of a trading bot that adapts to market conditions. By combining reinforcement learning with advanced trading strategies, the project seeks to create a scalable solution for automated trading with a focus on generalization and risk management.

## Methodology

### Custom Trading Environment
A bespoke OpenAI Gym-style environment was developed to simulate Forex trading for backtesting and training purposes. This environment replicates real-world market dynamics, allowing the NEAT algorithm to learn and optimize trading strategies in a controlled yet realistic setting. The environment supports key trading functionalities, ensuring the bot can interact with market data effectively.

### Feature Engineering
The trading bot incorporates a rich set of features to inform its decision-making process, including:
- **Williams %R**: A momentum indicator to identify overbought or oversold conditions.
- **Average True Range (ATR)**: A volatility measure to guide position sizing and risk management.
- **Session Timing Logic**: Accounts for market session volatility to optimize trade timing.
- **Partial Take Profits and Dynamic Trailing Stop-Loss**: Enhances profitability while managing risk dynamically.

These features enable the bot to make informed trading decisions tailored to the nuances of the Forex market.

### Training with NEAT
The NEAT algorithm was employed to train multiple trading strategies within the custom environment. NEAT’s unique ability to evolve both the weights and structure of neural networks allowed for the discovery of highly adaptive trading strategies. The training process involved evaluating numerous bot configurations, with the best-performing bot selected based on its fitness score, balancing profitability and stability.

### Validation and Generalization
To ensure the bot’s robustness, it was validated on unseen market data to assess its generalization to new conditions. The validation focused on achieving a fair win rate while maintaining low drawdown, critical metrics for a reliable trading system. This step confirmed the bot’s ability to perform consistently beyond the training dataset.

### Demo Execution
The validated bot was deployed in a demo trading environment using the MetaTrader API, allowing for real-time testing in a simulated market setting. This phase demonstrated the bot’s practical applicability and readiness for further development toward live trading scenarios.

## Key Achievements
- **Custom Environment Development**: Built a tailored OpenAI Gym-style environment for realistic Forex trading simulations, enabling effective training and backtesting.
- **Advanced Strategy Integration**: Incorporated sophisticated features like Williams %R, ATR, and dynamic trailing stop-loss to create a versatile and adaptive trading bot.
- **Robust Validation and Deployment**: Achieved a balanced win rate with low drawdown on unseen data and successfully executed the bot in a demo trading environment via the MetaTrader API.

## Applications
This project lays the groundwork for scalable, AI-driven trading solutions in the Forex market. The bot’s ability to generalize across unseen data makes it a promising candidate for further refinement and potential live trading applications. The methodologies developed here can also be adapted to other financial markets or reinforcement learning tasks, showcasing their versatility.

## Future Enhancements
To further elevate the project, future work could include:
- Incorporating additional technical indicators to enhance strategy robustness.
- Optimizing the NEAT algorithm’s hyperparameters for faster convergence and improved performance.
- Transitioning the bot to live trading with enhanced risk management protocols.

## Conclusion
This project exemplifies the power of reinforcement learning and the NEAT algorithm in tackling complex financial challenges. By developing a custom trading environment, integrating advanced features, and rigorously validating the bot’s performance, it demonstrates a sophisticated approach to automated Forex trading. The successful demo execution via the MetaTrader API underscores the project’s potential to contribute to the future of algorithmic trading.

## Contact
For inquiries, feedback, or collaboration opportunities, please reach out via [insert contact information or portfolio link]. Contributions to enhance the project are warmly welcomed!