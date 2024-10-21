### Author: Aman Sharma | Software Developer

Welcome to the **React Button and Counter Hook** package! This package provides a customizable button component and a simple, easy-to-use counter hook. It aims to help developers quickly implement reusable UI components and state management hooks in their React applications.

## Features

- `### Customizable Button Component`: A button component with default styles that can be easily customized.
- `### Counter Hook`: A `useCounter` hook that provides increment and decrement functions to manage numerical state.

This package is ideal for anyone looking to speed up their development process by using pre-built UI elements and logic in their React applications.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)

- [Button Component](#button-component)
- [useCounter Hook](#usecounter-hook)

3. [API Documentation](#api-documentation)

- [Button Component](#button)
- [useCounter Hook](#usecounter)

4. [Contributing](#contributing)
5. [License](#license)

## Installation

You can easily add this package to your project via npm or yarn.

### npm

`npm install half_engineer `

### yarn

`yarn add half_engineer`

## Usage

### Button Component

The `Button` component is a customizable button element that accepts child elements (usually text or icons) and an optional `onClick` handler.

#### Example:

`import React from "react";
import { Button } from "your-package-name";

const App = () => {
return (

<div>
<Button onClick={() => alert("Button clicked!")}>
Click Me
</Button>
</div>
);
};

export default App;`

### useCounter Hook

The `useCounter` hook provides a simple state management utility for counters. It returns the current count, along with functions to increment and decrement the value.

#### Example:

`import React from "react";
import { useCounter } from "your-package-name";

const CounterComponent = () => {
const { count, increment, decrement } = useCounter();

return (

<div>
<p>Counter: {count}</p>
<button onClick={increment}>+</button>
<button onClick={decrement}>-</button>
</div>
);
};

export default CounterComponent;`

## API Documentation

### Button

#### Props

Prop

Type

Description

children

`ReactNode`

The content (text, icons) to display inside the button.

onClick

`() => void`

An optional click handler function.

The `Button` component can be styled via inline styles or external CSS, making it highly customizable.

### useCounter

The `useCounter` hook provides basic counter logic with two key methods: `increment` and `decrement`.

#### Return Object

Property

Type

Description

count

`number`

The current value of the counter.

increment

`() => void`

Increases the counter value by 1.

decrement

`() => void`

Decreases the counter value by 1.

This hook is perfect for managing count-based logic, such as quantity controls, likes, or any numeric state tracking.

## Contributing

Contributions are welcome! If you want to improve or add features to this package, feel free to open an issue or submit a pull request on the [GitHub repository](#).

When contributing, please:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/my-new-feature`).
3.  Commit your changes (`git commit -m 'Add new feature'`).
4.  Push to the branch (`git push origin feature/my-new-feature`).
5.  Create a pull request.### Author: Aman Sharma | Software Developer

Welcome to the **React Button and Counter Hook** package! This package provides a customizable button component and a simple, easy-to-use counter hook. It aims to help developers quickly implement reusable UI components and state management hooks in their React applications.

## Features

- `### Customizable Button Component`: A button component with default styles that can be easily customized.
- `### Counter Hook`: A `useCounter` hook that provides increment and decrement functions to manage numerical state.

This package is ideal for anyone looking to speed up their development process by using pre-built UI elements and logic in their React applications.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)

- [Button Component](#button-component)
- [useCounter Hook](#usecounter-hook)

3. [API Documentation](#api-documentation)

- [Button Component](#button)
- [useCounter Hook](#usecounter)

4. [Contributing](#contributing)
5. [License](#license)

## Installation

You can easily add this package to your project via npm or yarn.

### npm

`npm install half_engineer`

### yarn

`yarn add half_engineer`

## Usage

### Button Component

The `Button` component is a customizable button element that accepts child elements (usually text or icons) and an optional `onClick` handler.

#### Example:

`import React from "react";
import { Button } from "your-package-name";

const App = () => {
return (

<div>
<Button onClick={() => alert("Button clicked!")}>
Click Me
</Button>
</div>
);
};

export default App;`

### useCounter Hook

The `useCounter` hook provides a simple state management utility for counters. It returns the current count, along with functions to increment and decrement the value.

#### Example:

`import React from "react";
import { useCounter } from "your-package-name";

const CounterComponent = () => {
const { count, increment, decrement } = useCounter();

return (

<div>
<p>Counter: {count}</p>
<button onClick={increment}>+</button>
<button onClick={decrement}>-</button>
</div>
);
};

export default CounterComponent;`

## API Documentation

### Button

#### Props

Prop

Type

Description

children

`ReactNode`

The content (text, icons) to display inside the button.

onClick

`() => void`

An optional click handler function.

The `Button` component can be styled via inline styles or external CSS, making it highly customizable.

### useCounter

The `useCounter` hook provides basic counter logic with two key methods: `increment` and `decrement`.

#### Return Object

Property

Type

Description

count

`number`

The current value of the counter.

increment

`() => void`

Increases the counter value by 1.

decrement

`() => void`

Decreases the counter value by 1.

This hook is perfect for managing count-based logic, such as quantity controls, likes, or any numeric state tracking.

## Contributing

Contributions are welcome! If you want to improve or add features to this package, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/half-1999/npm-packages.git).

When contributing, please:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/my-new-feature`).
3.  Commit your changes (`git commit -m 'Add new feature'`).
4.  Push to the branch (`git push origin feature/my-new-feature`).
5.  Create a pull request.
