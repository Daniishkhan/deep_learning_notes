## Perceptrons

Perceptrons are building blocks of neural networks. They are simple decision makers.

### Basic Concept

A simple perceptron can be thought of as a judge in a cooking contest. Imagine they decide if a dish is good or bad based on three factors:
* Taste
* Presentation
* Creativity

The importance given to each factor is called weights:
* Taste (0.6)
* Presentation (0.7)
* Creativity (0.5)

The judge also has a minimum standard which is called threshold or bias, which must be met to classify a dish as good or not good.

### Example

Let's say the judge scores each factor as follows:
* Taste: 8
* Presentation: 9
* Creativity: 6

The final score would be calculated as:
```
final_score = (8 × 0.6) + (9 × 0.7) + (6 × 0.5)

if final_score > 5: dish is good
if final_score < 5: dish is not good
```

### Machine Learning Terms
* Inputs (taste, presentation, creativity) are called 'features'
* Weights define how important a feature is
* Threshold is called 'bias'
* Final output (yes/no) is called activation
