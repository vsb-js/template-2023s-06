# LAB 08 - React Hooks Part 1

## useState

### Task 1 - simple counter

1. Import the `Counter` component from file `components/Counter.js` to `App.js` and render it inside the main `<div>`
2. Add the `useState` hook in the `Counter` component to keep track of the internal count.
3. On click of the button the value of the internal counter should increment by 1.

### Task 2 - using current state

1. Add another button to the `Counter` component.
2. On click of this new button, the current count will double (multiply current value by 2)

FYI: You can comment out the `Counter` component in App.js once you finish it so it doesn't distract you in the following tasks.

### Task 3 - arrays in state

1. Import the `Lottery` component from file `components/Lottery.js` to `App.js` and render it inside the main `<div>`
2. Add the `useState` hook in the `Lottery` component to keep track of the lottery numbers.
3. On click of the button the next number should be added to the array.

### Task 4 - conditional rendering

State can be used for conditional rendering where we want to display different things based on the state.
We might have multiple state variables in one component.

1. Import the `WinningNumbers` component from file `components/WinningNumbers.js` into `components/Lottery.js`
2. Change the `Lottery` component in the following way:
   - if the count of numbers in the state is lower than 10, it displays the UI to roll next number (`<div>` with `className="TodaysNumbers"`)
   - if the count of numbers in the state is 10, it will display the `WinningNumbers` component, passing the current numbers as props

### BONUS - fixing mistakes

1. Inspect the `WinningNumbers` and `Numbers` components in `components/WinningNumbers.js`
2. The `Numbers` component should change colors based on the selected option in `WinningNumbers`
3. Find out why it is not working and fix it.
