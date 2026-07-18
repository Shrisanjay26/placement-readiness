# Reflection

## Overview

This assignment helped me understand how dynamic forms can be generated using a JSON schema instead of hardcoding every input field.

## What I Learned

- JSON-driven UI development
- Dynamic component rendering
- Conditional rendering in React
- Schema-based validation
- Component-based architecture
- Big-O analysis for rendering and validation

## Challenges Faced

The biggest challenge was understanding how to represent the form entirely using JSON while keeping the application modular and scalable.

Another challenge was implementing conditional rendering, where certain fields appear only when specific conditions are met.

## Solution

I designed the application so that every form element is described in a JSON schema. The renderer reads the schema recursively and generates the required UI.

Validation rules and conditional logic are also stored in the schema, making the application flexible and easy to maintain.

## Improvements

If more time were available, I would implement:

- Multi-step forms
- API integration
- Dynamic schema editor
- Drag-and-drop form builder
- Better UI styling
