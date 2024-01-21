# React Number Type

![npm](https://img.shields.io/npm/v/react-number-type)
![GitHub](https://img.shields.io/github/license/your-username/react-number-type)
![GitHub issues](https://img.shields.io/github/issues/your-username/react-number-type)

A React component for handling number types with ease.

Welcome to React Number Type, your go-to solution for painless handling of number types in React applications! 🚀 This versatile component is loaded with powerful features to simplify your development experience.

### Key Features

1. **Smart Number Representation:** Say goodbye to language barriers! React Number Type excels at seamlessly replacing numbers in any language with easy-to-read English characters. Your users will effortlessly engage with numeric data, regardless of their language preferences.

2. **Mobile-Friendly Magic:** Enhance your mobile user experience effortlessly! React Number Type is engineered to showcase the number and telephone keyboards by default on mobile devices. No more frustrating toggling between keyboard layouts—just smooth, intuitive interactions.


## Installation

Install the package using npm:

```bash
npm install react-number-type
```

or using yarn:

```bash
yarn add react-number-type
```

## Usage

Import the `NumberType` component and use it in your React application.
```jsx
import React from 'react';
import NumberType from 'react-number-type';

const MyComponent = () => {
  return (
    <div>
      <h1>React Number Type Example</h1>
      <NumberType
        onChange={(newValue) => console.log('New Value:', newValue)}
        // Add any additional props as needed
      />
    </div>
  );
};

export default MyComponent;
```
## Props
- Additional props: You can pass any additional props that the underlying input element supports.
