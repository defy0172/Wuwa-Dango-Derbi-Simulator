# Wuwa-Dango-Derbi-Simulator
A simple simulator of activity "Dango Derbi" in Wuthering Waves

鸣潮 - 小团快跑模拟器 | Wuthering Waves - Dango Derby Simulator

![alt text](https://img.shields.io/badge/python-3.8+-blue.svg)

![alt text](https://img.shields.io/badge/Tools-Jupyter%20Notebook-orange.svg)

![alt text](https://img.shields.io/badge/License-MIT-yellow.svg)

## 项目简介 | Introduction

本项目是对《鸣潮》限定活动「小团快跑」的数值模拟与可视化实现。通过 Python 开发，加入了基于蒙特卡洛算法的胜率统计功能。

This project is a high-fidelity numerical simulation and visualization of the "Dango Derby" limited-time event in Wuthering Waves.It also features a Monte Carlo-based win-rate analyzer.

## 核心特性 | Key Features

#### 面向对象设计 | OO Architecture

每个团子角色均为独立的类模块，具有极高的扩展性。

Each Dango character is an independent class module with high scalability.

#### 可视化交互 | Interactive UI

使用 Jupyter Widgets，支持实时勾选参赛阵容、观看分步动画。

Use Jupyter Widgets to support real-time selection of participating lineups and watching step-by-step animations.

#### 胜率统计分析 | Statistical Analysis

支持上万场模拟，量化不同角色技能对胜率的影响。

Support thousands of simulations to quantify the impact of different character skills on win rates.


## 快速开始 | Quick Start

#### 依赖环境 | Prerequisites

确保你的环境中安装了以下库：

Ensure you have the following libraries installed:

```python
pip install matplotlib ipywidgets ipython
```

#### 运行步骤 | Running the Simulator

克隆仓库 | Clone the repo:

```python
git clone https://github.com/YourUsername/Tuanzi-Flying-Chess.git
```

打开 Jupyter Notebook | open your Jupyter Notebook

```python
jupyter notebook Tuanzi_Simulator.ipynb
```

运行所有单元格，在交互界面选择团子并点击 "▶ 观看动画" 或 "📊 统计胜率"。
Run all cells, select characters in the UI, and click "Play Animation" or "Simulate Win Rate".(Note:Only the Chinese version is available for the time being.English Version will be added soon.)

#### 在线使用 | Use it Online


#### 后续扩展 | Extensibility

如果你想加入新的团子，只需继承 Tuanzi 类并重写 modify_steps 等钩子函数，然后在 AVAILABLE_TUANZIS 字典中注册即可。

To add a new Dango, simply inherit the Tuanzi class in Cell 5, override hooks like modify_steps, and register it in the AVAILABLE_TUANZIS dictionary.

## 开源协议 | License

本项目采用 MIT License 协议。

This project is licensed under the MIT License.


Disclaimer: This project is a fan-made simulation and is not affiliated with Kuro Games or Wuthering Waves.

``声明：本项目为粉丝制作，与库洛游戏或《鸣潮》官方无关。
