# NutriScan
## Overview

NutriScan is an AI-based food nutrition analysis system that extracts nutritional information from food label images. It primarily uses OCR to read text from labels and applies a CNN model when OCR fails due to unclear or blurry images.

## Key Features

Food label text extraction using OCR

CNN-based product/brand identification (fallback)

Accurate nutrition details display

Simple and user-friendly interface

## Tech Stack

Frontend: Next.js, Tailwind CSS

Backend: Python

AI Models: OCR, CNN

Libraries: OpenCV, TensorFlow/Keras

Tools: VS Code

## How It Works

User uploads a food image

OCR extracts nutrition text

If OCR fails → CNN identifies product type

Nutrition details are displayed
