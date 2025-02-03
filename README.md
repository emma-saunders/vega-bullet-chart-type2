# vega-bullet-chart-type2
https://stargate.swissre.com/workspace/module/edit/ri.workshop.main.module.ab3c30f4-5aee-44c7-9ade-52c151bc40ef
![image](https://github.com/user-attachments/assets/31d78eb7-e9d2-4b61-816e-f2ab63ca2c79)

## Features
- Responsive
- Tooltips show claims and revenue
- Pulls data from Foundry (must be added via Input data section) and updates in real time
- Dynamic loss ratio calculation based on values shown in chart, meaning loss ratio can never diverge from constituent parts
- Numbers shown in labels, removing the need for x axis
- Revenue hardcoded to highlight "danger zone" with red/green colouring. Can be removed:
  - Green is 0 - 80% of revenue
  - Amber is 80 - 100% revenue
  - Red is > 100% of revenue
- Claims data
  - Shown as grey overlay bar, clearly indicating if claims are in "danger zone"
  - Loss ratio shown in text at end of claims bar
