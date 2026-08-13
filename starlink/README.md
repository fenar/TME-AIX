# Starlink Internet Service Quality of Experience Predictions

Objective: Nomadic users, such as RV campers, often face challenges accessing the internet in remote locations. While mobile cellular radio access solutions may sometimes prove inadequate due to limited coverage or suboptimal price-to-performance ratios, satellite internet offers a compelling alternative.

With Starlink emerging as a robust option, providing improved coverage and connection speeds, its Quality of Experience (QoE) remains variable across different geographic locations. Factors such as altitude, the number of visible satellites, weather conditions, and potential obstructions affecting satellite line-of-sight significantly influence service quality.

To empower travelers with insights into Starlink's internet service quality at their destination, we have developed and trained a neural network transformer model. This model predicts QoE by analyzing key parameters, offering nomadic users a AI-Tool to anticipate and plan their connectivity needs effectively.<br>

**🎥 Demo Video**: [Watch on YouTube](https://youtu.be/RLj6Ju809jk) <br>

<div align="center">
    <img src="https://raw.githubusercontent.com/tme-osx/TME-AIX/refs/heads/RedHat-Special/starlink/images/starling-qoe-moods.png" width="640"/>
</div>

## Software Requirement

| Software      | Version |
|---------------|---------|
| Python        | 3.12    |

> Tested with Python 3.12 as the minimum version. Python 3.13 and later 3.x releases may work but have not been validated.

## Data
![Data Structure](https://raw.githubusercontent.com/tme-osx/TME-AIX/refs/heads/main/starlink/images/starlink-data.png)<br>
DataSet Location: https://huggingface.co/datasets/fenar/starlink
## API 
![Curl Test](https://raw.githubusercontent.com/tme-osx/TME-AIX/refs/heads/main/starlink/images/starlink-api.png)
## Web UI
![Interface](https://raw.githubusercontent.com/tme-osx/TME-AIX/refs/heads/main/starlink/images/starlink-main.png)<br>
