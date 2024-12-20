# Tetris AI

## Introduction

This repository contains Python code to train an AI agent to play Tetris using Q learning.

<p align="center">
  <img src="demo/tetris.gif" width=600><br/>
  <i>Tetris AI Demo</i>
</p>

## How to Use

1. **Training the Model**  
   To train the AI model from scratch, run the following command:

   ```bash
   python train.py
   ```

2. **Testing the Model**  
   After training, you can test the performance of the trained model with:

   ```bash
   python test.py
   ```

## Pre-trained Models

You can find the pre-trained model files in the `trained_models/tetris` directory. These models can be used directly for testing without the need for training.

## File Structure

- `train.py`: Script to train the AI agent.
- `test.py`: Script to test the trained AI model.
- `trained_models/tetris`: Folder containing the pre-trained models.
- `demo/tetris.gif`: GIF showing the Tetris game in action.
