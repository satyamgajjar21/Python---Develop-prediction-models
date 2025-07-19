<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
  </a>
</p>

# Model Development

**Estimated time needed:** 30 minutes

## Objectives

After completing this lab you will be able to:

- Develop prediction models

In this section, we will develop several models that will predict the price of the car using the variables or features. This is just an estimate but should give us an objective idea of how much the car should cost.

### Some questions we want to ask in this module:

- Do I know if the dealer is offering fair value for my trade-in?
- Do I know if I put a fair value on my car?

In data analytics, we often use **Model Development** to help us predict future observations from the data we have.

A model will help us understand the exact relationship between different variables and how these variables are used to predict the result.

---

## Setup

Install and import libraries:

```python
import piplite
await piplite.install('seaborn')
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
